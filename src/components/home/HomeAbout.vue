<template>
    <div class="about">
        <div class="container">
            <div class="about__inner">
                <div class="about__img">
                    <img src="@/assets/about_img.png" alt="men">
                </div>
                <div class="about__block">
                    <div class="about__block-title h4-title">About us</div>
                    <p class="about__block-text body-m">For more than 30 years we have been delivering world-class construction and we’ve built many lasting relationships along the way.</p>
                    <br>
                    <p class="about__block-text body-m">We’ve matured into an industry leader and trusted resource for those seeking quality, innovation and reliability when building in the U.S.</p>
                    <BaseButton class="about__block-button body2" title="More on Our History"/>
                </div>
            </div>
 
        </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import BaseButton from '@/components/base/BaseButton.vue'

  export default defineComponent({
    components: {
        BaseButton
    }
  })
</script>

<style lang="scss" scoped>

.about {
    padding: 74px 0 202px;
    &__inner {
        position: relative;
    }

    &__img {
        width: 902px;
        height: 669px;
        img {
            height: 100%;
        }
    }
    &__block {
        position: absolute;
        top: 0;
        right: 0;
        bottom: 0;
        max-width: 488px;
        height: 523px;
        margin: auto;
        padding: 50px 40px 60px;
        background-color: #2947A9;
        color: #fff
    }
    &__block-title {
        margin-bottom: 37px;
    }
    &__block-button {
        margin-top: 74px;
    }
}
</style>
