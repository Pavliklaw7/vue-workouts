<script lang="ts">
import { RouterView } from 'vue-router'
import TheHeader from '@/components/main/TheHeader.vue'
import TheFooter from '@/components/main/TheFooter.vue'

export default {
  components: {
    TheHeader,
    TheFooter
  }
}
</script>

<template>
  <TheHeader/>
  <RouterView />
  <TheFooter/>
</template>

<style scoped lang="scss">

</style>
