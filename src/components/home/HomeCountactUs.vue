<template>
  <div class="contact-us">
    <div class="container">
      <h4 class="contact-us__title">What can us do for you?</h4>
      <p class="contact__text">
        We are ready to work on a project of any complexity, whether it’s commercial or residential.
      </p>
      <form action="" class="contact-us__form form">
        <input type="text" class="form__input" />
        <input
          type="text"
          class="form__input"
        />
        <input type="text" class="form__input" />
        <input
          type="text"
          class="form__input"
        />
        <textarea name="" id="" cols="30" rows="10" class="form__textarea"></textarea>
        <div class="form__button">Submit</div>
      </form>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({})
</script>

<style lang="scss" scoped>
.contact-us {
  background-color: #f6f8f7;
  padding: 60px 0 61px;
}
</style>
