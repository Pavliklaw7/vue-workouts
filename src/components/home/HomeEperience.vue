<template>
    <div class="experience">
        <div class="container">
            <div class="experience__inner">
                <div class="experience__img">
                    <img src="@/assets/experience_img.png" alt="Happy Clients, Projects Completed, Projects Completed, Years in Business">
                </div>
                <div class="experience__block">
                    <h2 class="experience__title h2-title-bold">
                        30 Years Experience
                    </h2>
                    <p class="experience__text body-m">
                        Our company has been the leading provided construction services to clients throughout the USA since 1988.
                    </p>
                    <button class="experience__button body2">
                        Contact Us
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
.experience {
    &__inner {
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 103px 0 57px;
    }
    &__img {
        width: 641px;
        img {
            width: 100%;
        }
    }
    &__block {
        width: 359px;
    }
    &__title {
        margin-bottom: 40px;
        color: #2947A9
    }
    &__text {
        margin-bottom: 67px;
    }
    &__button {
        border-radius: 2px;
        color: #fff;
    }
}

</style>