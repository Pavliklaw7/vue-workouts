<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({

})
</script>

<template>
    <div class="services">
        <div class="container">
            <h4 class="services__title h4-title">
                Services
            </h4>
            <div class="services__grid">
                <div class="services__item">
                    <img src="@/assets/services/construction.svg" alt="Construction" class="services__item-icon">
                    <span></span>
                    <p class="services__item-title body2">Construction</p>
                </div>
                <div class="services__item">
                    <img src="@/assets/services/renovation.svg" alt="Renovation" class="services__item-icon">
                    <span></span>
                    <p class="services__item-title body2">Renovation</p>
                </div>
                <div class="services__item">
                    <img src="@/assets/services/consultation.svg" alt="Consultation" class="services__item-icon">
                    <span></span>
                    <p class="services__item-title body2">Consultation</p>
                </div>
                <div class="services__item">
                    <img src="@/assets/services/repair-services.svg" alt="Repair Services" class="services__item-icon">
                    <span></span>
                    <p class="services__item-title body2">Repair Services</p>
                </div>
                <div class="services__item">
                    <img src="@/assets/services/architecture.svg" alt="Architecture" class="services__item-icon">
                    <span></span>
                    <p class="services__item-title body2">Architecture</p>
                </div>
                <div class="services__item">
                    <img src="@/assets/services/electric.svg" alt="Electric" class="services__item-icon">
                    <span></span>
                    <p class="services__item-title body2">Electric</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.services {
    background-color: #F6F8F7;
    padding: 44px 0 76px;
    &__title {
        text-align: center;
        margin-bottom: 36px;
    }
    &__grid {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-template-rows: repeat(2, auto);
        grid-gap: 48px 98px;
        padding: 0 104px;
    }

    &__item {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-between;
        width: 271px;
        height: 181px;
        padding: 38px;
        background-color: #fff;
        color: #000;

        &:nth-child(even) {
            background-color: #2947A9;
            color: #fff;
        }

        & > span {
            width: 60px;
            height: 2px;
            background-color: #E0E3EB;
        }
    }

}

</style>