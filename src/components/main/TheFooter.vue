<template>
  <footer class="footer">
    <div class="container">
      <div class="footer__main">
        <div class="footer__contact">
          <div class="footer__contact-item">
            <span class="footer__contact-title body1">
              Address:
            </span>
            <span class="footer__contact-text body1">
              6391 Elgin St. Celina, Delaware 10299
            </span>
          </div>
          <div class="footer__contact-item">
            <span class="footer__contact-title body1">
              Phone:
            </span>
            <span class="footer__contact-text body1">
              +84 1102 2703            </span>
          </div>
          <div class="footer__contact-item">
            <span class="footer__contact-title body1">
              Email:
            </span>
            <span class="footer__contact-text body1">
              hello@thebox.com            </span>
          </div>
          <div class="footer__contact-logo">
            <img src="@/assets/logo-box.svg" alt="logo">
          </div>
        </div>
        <div class="footer__subscribe">
          <div class="footer__subscribe-block">
            <div class="footer__subscribe-title body1">
            Newsletter:
            </div>
            <form action="" class="footer__subscribe-form">
              <input type="text" class="footer__subscribe-input" placeholder="Your email here">
              <button class="footer__subscribe-button body-m-bold">
                Subscribe
              </button>
            </form>
          </div>
          <div class="footer__subscribe-block">
            <div class="footer__subscribe-title body1">
              Social:
            </div>
            <div class="footer__subscribe-social">
              <img src="@/assets/social/facebook.svg" alt="">
              <img src="@/assets/social/linkedin.svg" alt="">
              <img src="@/assets/social/twitter.svg" alt="">
            </div>
          </div>
          
        </div>
      </div>
    </div>
    <div class="footer__copy">
      <div class="container">
        <p class="footer__copy-text caption1">
          TheBox Company © 2022. All Rights Reserved
        </p>
      </div>
    </div>
  </footer>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({})
</script>

<style lang="scss">

.footer {
  &__main {
    display: flex;
    justify-content: space-between;
    padding: 85px 0 83px;
  }
  &__contact-item {
    margin-bottom: 32px;
  }
  &__contact-title,
  &__subscribe-title {
    display: inline-block;
    width: 91px;
    text-align: start;
    text-transform: uppercase;
    color: #2947A9;
  }
  &__copy {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    height: 70px;
    background-color: #2947A9;
  }
  &__copy-text {
    color: #fff;
  }
  &__subscribe-block:first-child {
    margin-bottom: 42px;
  }
  &__subscribe-title {
    margin-bottom: 20px;
  }
  &__subscribe-form {
    display: flex;
  }
  &__subscribe-input {
    padding: 10px 8px;
    border: 1px #E0E3EB solid;
    border-radius: 4px;
    &::placeholder {
      color: #A3AAC2
    }
  }
  &__subscribe-button {
    display: block;
    text-align: center;
    padding: 10px 23px;
    background-color: #F9995D;
    color: #fff;
    border: none;
  }
  &__subscribe-social {
    img {
      &:not(:last-child) {
        margin-right: 20px;
      }
    }
  }
}


</style>
