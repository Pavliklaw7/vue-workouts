<script lang="ts">
import { defineComponent } from 'vue'

  export default defineComponent({

  })
</script>

<template>
  <div class="reputation">
    <div class="container">
        <div class="reputation__inner">
            <h4 class="reputation__title h4-title">
            Our Reputation
            </h4>
            <div class="reputation__list">
                <div class="reputation__item">
                    <img src="@/assets/icons/caller.svg" alt="call center" class="reputation__item-icon">
                    <p class="reputation__item-title subtitle">Best Services</p>
                    <p class="reputation__item-text caption2">Nullam senectus porttitor in eget. Eget rutrum leo interdum.</p>
                </div>
                <div class="reputation__item">
                    <img src="@/assets/icons/caller.svg" alt="call center" class="reputation__item-icon">
                    <p class="reputation__item-title subtitle">Best Services</p>
                    <p class="reputation__item-text caption2">Nullam senectus porttitor in eget. Eget rutrum leo interdum.</p>
                </div>
                <div class="reputation__item">
                    <img src="@/assets/icons/caller.svg" alt="call center" class="reputation__item-icon">
                    <p class="reputation__item-title subtitle">Best Services</p>
                    <p class="reputation__item-text caption2">Nullam senectus porttitor in eget. Eget rutrum leo interdum.</p>
                </div>
            </div>
        </div>
    </div>
  </div>
</template>

<style lang="scss">
.reputation {
    &__title {
        margin-bottom: 60px;
        text-align: center;
    }
    &__inner {
        padding: 60px 104px 84px;
    }
    &__list {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    &__item {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        max-width: 292px;
        padding: 20px;
        border: 1.4px solid #E0E3EB;
        border-radius: 4px;
    }
    &__item-icon {
        margin-bottom: 18px;
    }
    &__item-title {
        margin-bottom: 18px;
    }
    &__item-text {
        color: #858EAD;
    }

}
</style>