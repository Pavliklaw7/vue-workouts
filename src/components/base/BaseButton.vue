<template>
    <button @click="handleClick" :class="['base-button', variant, size]">
        <img v-if="isBackArrow" src="@/assets/icons/arrows/arrow-left.svg" alt="arrow left">
        <p class="base-button__title">
            {{ title }}
        </p>
        <img v-if="isNextArrow" src="@/assets/icons/arrows/arrow-right.svg" alt="arrow right">
    </button>
</template>

<script lang="ts">
import HomeProjects from '../home/HomeProjects.vue'
import { defineComponent } from 'vue';

export default defineComponent({
    props: {
        title: String,
        isBackArrow: Boolean,
        isNextArrow: Boolean,
        size: {
            type: String,
            default: 'md'
        },
        variant: {
            type: 'primary' || 'secoondary' || 'tertiary' || 'attention',
            default: 'primary'
        }
    },
    setup(props, ctx) {

        const handleClick = () => {
            console.log('props', props.title)
        }
        return {
            handleClick
        }
    },

})
</script>

<style lang="scss" scoped>
.base-button {
    padding: 16px 20px;
    border-radius: 6px;
    color: #2947A9;

    .primary {
        
    }
}
</style>