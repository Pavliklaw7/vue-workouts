<template>
    <div class="consultation">
        <img class="consultation__img" src="@/assets/bg/bg_consultation.png" alt="consultation">
        <div class="consultation__container">
            <div class="container">
                <div class="consultation__inner">
                    <div>
                        <h4 class="consultation__title h4-title">
                            Free consultation with exceptional quality
                        </h4>
                        <p class="consultation__text">
                            Just one call away: +84 1102 2703
                        </p>
                    </div>
                    <button class="consultation__button">
                        Get your consultation
                    </button>
                </div>
            </div>
        </div>
    </div>
</template>

<script lang="ts">
import  { defineComponent } from 'vue';

export default defineComponent({
    
})
</script>

<style lang="scss" scoped>
.consultation {
    &__img {
        width: 100%;
        height: 300px;
        object-fit: cover;
    }
    &__container {
        position: absolute;
        top: 0;
        left: 0;
        bottom: 0;
        right: 0;
        margin: auto;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    &__inner {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    &__title {
        color: #fff;
        margin-bottom: 30px;
    }
    &__text {
        color: #fff
    }
}

</style>
