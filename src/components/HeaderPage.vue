<template>
  <header>
    <nav class="navbar navbar-expand-lg container">
      <div class="container-fluid">
        <div class="logo_navbar p-1">
          <img
            src="@/assets/img/logo-200x34.png"
            alt="logo"
          >
        </div>
        <button
          class="navbar-toggler collapsed"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarText"
          aria-controls="navbarText"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon" />
        </button>
        <div
          id="navbarText"
          class="navbar-collapse collapse"
          style=""
        >
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a
                class="nav-link"
                aria-current="page"
                href="#"
              >Home</a>
            </li>
            <li class="nav-item">
              <a
                class="nav-link"
                href="#"
              >Services</a>
            </li>
            <li class="nav-item">
              <a
                class="nav-link"
                href="#"
              >About</a>
            </li>
            <li class="nav-item">
              <a
                class="nav-link"
                href="#"
              >Videos</a>
            </li>
            <li class="nav-item">
              <a
                class="nav-link"
                href="#"
              >Blog</a>
            </li>
            <li class="nav-item">
              <a
                class="nav-link"
                href="#"
              >Store <span class="news_info">new</span></a>
            </li>
            <li class="nav-item">
              <a
                class="nav-link btn btn-primary btn_header"
                href="#"
              > Schedule a workout</a>
            </li>
          </ul>
          <div class="icon">
            <i class="fa-solid fa-cart-shopping px-4" />
            <i class="fa-solid fa-magnifying-glass" />
          </div>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'HeaderPage',
};
</script>

<style scoped lang="scss">
header {
  background-color: rgb(0, 0, 0);
}

a,
i {
  color: rgb(124, 124, 124);
  &:hover {
    color: rgb(255, 255, 255);
  }
}

.btn_header{
  max-width: max-content;
  white-space: nowrap;
  color: rgb(255, 255, 255);
  padding: .5em 1em;
  border-radius: 10em;
  font-size: small;
}

.news_info {
  background: rgb(255, 255, 1);
  border-radius: 2px;
  padding: .2em .4em;
  font-size: small;
  color: black;
}

.logo_navbar:hover {
  transform: scale(1.1);
}
</style>
