<template>
  <footer class="footer">
    
  </footer>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({})
</script>

<style lang="scss">

.header {
  padding-top: 16px;
  padding-bottom: 16px;
  &__container {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
}

.logo {
  display: block;
}

.nav {
  font-size: 12px;

  &__link {
    font-family: 'Work sans';
    font-size: 18px;
    text-decoration: none;

    &:not(:last-child) {
        margin-right: 50px;
    }
  }
}
</style>
