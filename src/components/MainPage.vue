<template>
  <main>
    <SectionPage1 />
    <SectionPage2 />
    <SectionPage3 />
    <SectionPage4 />
    <SectionPage5 />
    <SectionPage6 />
  </main>
</template>

<script>
import SectionPage1 from '@/components/SectionPage1.vue';
import SectionPage2 from '@/components/SectionPage2.vue';
import SectionPage3 from '@/components/SectionPage3.vue';
import SectionPage4 from '@/components/SectionPage4.vue';
import SectionPage5 from '@/components/SectionPage5.vue';
import SectionPage6 from '@/components/SectionPage6.vue';

export default {
  name: 'MainPage',
  components: {
    SectionPage1,
    SectionPage2,
    SectionPage3,
    SectionPage4,
    SectionPage5,
    SectionPage6,
  },
};
</script>

<style scoped lang="scss">
</style>
