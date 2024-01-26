<template>
  <header class="header">
    <div class="header__container container">
      <img alt="Vue logo" class="header__logo" src="@/assets/logo-box.svg" width="163" height="47" />
      <nav class="header__nav nav">
        <RouterLink class="nav__link body1" to="/">Home</RouterLink>
        <RouterLink class="nav__link body1" to="/about">About</RouterLink>
        <RouterLink class="nav__link body1" to="/projects">Projects</RouterLink>
        <RouterLink class="nav__link body1" to="/services">Services</RouterLink>
        <RouterLink class="nav__link body2 hilight-secondaty" to="/contact-us">Contact Us</RouterLink>
      </nav>
    </div>
  </header>
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
