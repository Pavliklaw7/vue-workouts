<script lang="ts">
import { defineComponent } from 'vue'

  export default defineComponent({

  })
</script>

<template>
  <div class="intro">
    <img src="@/assets/bg/bg_intro.png" alt="" class="intro__bg">
    <div class="intro__container">
      <div class="container">
        <h1 class="intro__title h1-title">
        Building things is our mission.
      </h1>
      </div>

      <div class="intro__slider">
        <div class="slider">
          <div class="slider__block">
            <div class="slider__item active">
              <p class="slider__title h5-title">Feature Projects 1</p>
              <p class="slider__text caption1">The National University of Architecture</p>
            </div>
            <div class="slider__item">
              <p class="slider__title h5-title">Feature Projects 2</p>
              <p class="slider__text caption1">The National University of Architecture</p>
            </div>
            <div class="slider__item">
              <p class="slider__title h5-title">Feature Projects 3</p>
              <p class="slider__text caption1">The National University of Architecture</p>
            </div>
          </div>
          <div class="slider__controls">
            <div class="slider__control">
              <img src="@/assets/icons/arrows/arrow-left.svg" alt="arrow left">
              Back
            </div>
            <div class="slider__control">
              Next
              <img src="@/assets/icons/arrows/arrow-right.svg" alt="arrow right">
            </div>
          </div>
        </div>
      </div>
    </div>
    
  </div>
</template>



<style lang="scss">
.intro {
  &__bg {
    object-fit: cover;
    width: 100%;
    max-height: 646px;
  }
  &__container {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
  }

  &__title {
    max-width: 556px;
    margin-bottom: 40px;
    color: #fff;
    text-align: center;
  }
  &__text {
    text-align: center;
    color: #fff;
  }
  &__slider {
    height: 190px; // to remove
    margin-left: auto;
  }
}

.slider {
  &__block {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 416px;
    height: 150px;
    background-color: #3559C7;
    color: #fff;
  }
  &__item {
    display: none;

    &.active {
      display: block;
    }
  }

  &__title {
    margin-bottom: 20px;
    text-align: center;

  }
  &__text {
    text-align: center;

  }
  &__controls {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 0 1px
    }
  &__control {
    display: flex;
    align-items: center;
    justify-content: center;
    padding-top: 10px;
    padding-bottom: 10px;
    background-color: #000;
    color: #fff;
    & > img {
      margin-left: 10px;
      margin-right: 10px;
    }
  }
}
</style>