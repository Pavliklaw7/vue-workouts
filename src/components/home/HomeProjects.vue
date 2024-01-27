<template>
    <div class="projects">
        <div class="container">                
            <h4 class="projects__title h4-title">Projects</h4>
            <div class="projects__container">
                <aside class="projects__sidebar">
                    <nav class="projects__nav nav">
                        <div class="nav__item body-l active body-l-bold">All</div>
                        <div class="nav__item body-l">Commercial</div>
                        <div class="nav__item body-l">Residential</div>
                        <div class="nav__item body-l">Other</div>
                    </nav>
                </aside>
                <div class="projects__inner combo-carusel">
                    <div class="combo-carusel__screen">
                        <div class="combo-carusel__item active">
                            <div class="combo-carusel__item-block">
                                <img src="@/assets/carusel/1.png" alt="" class="combo-carusel__item-img">
                                <div class="combo-carusel__item-caption">
                                    <p class="combo-carusel__item-title body-m-bold">Wildstone Infra Hotel</p>
                                    <p class="body1">2715 Ash Dr. San Jose, South Dakota</p>
                                </div>
                            </div>
                            <div class="combo-carusel__item-block">
                                <img src="@/assets/carusel/1.png" alt="" class="combo-carusel__item-img">
                                <div class="combo-carusel__item-caption">
                                    <p class="combo-carusel__item-title body-m-bold">Wildstone Infra Hotel</p>
                                    <p class="body1">2715 Ash Dr. San Jose, South Dakota</p>
                                </div>
                            </div>
                            <div class="combo-carusel__item-block">
                                <img src="@/assets/carusel/1.png" alt="" class="combo-carusel__item-img">
                                <div class="combo-carusel__item-caption">
                                    <p class="combo-carusel__item-title body-m-bold">Wildstone Infra Hotel</p>
                                    <p class="body1">2715 Ash Dr. San Jose, South Dakota</p>
                                </div>
                            </div>
                            <div class="combo-carusel__item-block">
                                <img src="@/assets/carusel/1.png" alt="" class="combo-carusel__item-img">
                                <div class="combo-carusel__item-caption">
                                    <p class="combo-carusel__item-title body-m-bold">Wildstone Infra Hotel</p>
                                    <p class="body1">2715 Ash Dr. San Jose, South Dakota</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="combo-carusel__controls">
                        <div class="combo-carusel__control">
                            <img src="@/assets/icons/arrows/arrow-left.svg" alt="arrow left">
                            Back
                        </div>
                        <div class="combo-carusel__dots">
                            <div class="combo-carusel__dot active"></div>
                            <div class="combo-carusel__dot"></div>
                            <div class="combo-carusel__dot"></div>
                            <div class="combo-carusel__dot"></div>
                            <div class="combo-carusel__dot"></div>
                        </div>
                        <div class="combo-carusel__control">
                            Next
                            <img src="@/assets/icons/arrows/arrow-right.svg" alt="arrow right">
                        </div>
                    </div>
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
.projects {
    padding: 88px 0 138px;
    &__title {
        margin-bottom: 40px;
    }
    &__container {
        display: flex;
        align-items: flex-start;
        justify-content: space-between;
    }

}

.nav {
    &__item {
        padding-left: 18px;
        color: #C2C7D6;
        border-left: 4px solid transparent;
        &:not(:last-child) {
            margin-bottom: 20px;
        }
        &.active {
            color: #2947A9;
            border-left: 4px solid #2947A9;
        }
    }

}

.combo-carusel {
    &__screen {

    }
    &__item {
        display: none;
        grid-template-columns: repeat(2, 384px);
        grid-template-rows: repeat(2, 331px);
        gap: 32px;
        &.active {
            display: grid;
        }
    }
    &__item-block {
        display: flex;
        flex-direction: column;
        img {
            flex-grow: 1;
            width: 100%;
        }
    }
    &__item-caption {
        padding: 18px 12px;
        background-color: #2947A9;
        color: #fff;
    }
    &__item-title {
        margin-bottom: 12px;
    }
    &__controls {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    &__dots {
        display: flex;
    }
    &__dot {
        width: 16px;
        height: 16px;
        margin-top: 32px;
        border-radius: 100%;
        background-color: #F6F8F7;

        &:not(:last-child) {
            margin-right: 16px;
        }
        &.active {
            background-color: #2947A9;
        }
    }
}
</style>