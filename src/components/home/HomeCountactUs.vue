<template>
  <div class="contact-us">
    <div class="contact-us__container">
      <h4 class="contact-us__title h4-title">What can us do for you?</h4>
      <p class="contact-us__text body-m">
        We are ready to work on a project of any complexity, whether it’s commercial or residential.
      </p>
      <form action="" class="contact-us__form form">
        <div class="form__inner">
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
        </div>
        <div class="form__error">
          * indicates a required field
        </div>
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
  &__container {
    width: min(592px, 95%);
    margin: 0 auto;
  }
  &__title {
    text-align: center;
    margin-bottom: 20px;
  }
  &__text {
    margin-bottom: 38px;
    text-align: center;
  }
}
.form {

  &__inner {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: 41px 41px 162;
    gap: 20px 32px;
  }
  &__textarea {
    grid-column: span 2;
  }
  &__input,
  &__textarea {
    padding: 10px 8px;
    border: 1px #E0E3EB solid;
    border-radius: 4px;
    &::placeholder {
      color: #A3AAC2
    }
  }

  &__button {
    display: block;
    width: 90%;
    max-width: 271px;
    margin: 28px auto 0;
    text-align: center;
    padding: 18px 0;
    background-color: #2947A9;
    color: #fff;
  }
}
</style>
