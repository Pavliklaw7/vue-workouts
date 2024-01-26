<template>
  <main class="home">
    <HomeIntro class="home__intro"/>
    <HomeReputation class="home__reputation"/>
    <HomeAbout />
    <HomeServices/>
    <HomeEperience/>
    <HomeConsultation class="home__consultation"/>
    <HomeProjects/>
    <HomeCountactUs/>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HomeIntro from '@/components/home/HomeIntro.vue'
import HomeReputation from '@/components/home/HomeReputation.vue';
import HomeAbout from '@/components/home/HomeAbout.vue';
import HomeServices from '@/components/home/HomeServices.vue';
import HomeEperience from '@/components/home/HomeEperience.vue'
import HomeConsultation from '@/components/home/HomeConsultation.vue';
import HomeProjects from '@/components/home/HomeProjects.vue';
import HomeCountactUs from '@/components/home/HomeCountactUs.vue';

export default defineComponent({
  components: {
    HomeIntro,
    HomeReputation,
    HomeAbout,
    HomeServices,
    HomeEperience,
    HomeConsultation,
    HomeProjects,
    HomeCountactUs,
  }
})
</script>

<style lang="scss">
.home {
  &__intro,
  &__consultation {
    position: relative;
  }
  &__consultation {
    height: 300px;
  }
}
</style>

