<template>
    <div class="projects">
        <div class="projects__container container">
            <aside class="projects__sidebar">
                <h4 class="projects__title">Projects</h4>
                <nav class="projects__nav nav">
                    <div class="nav__item active">All</div>
                    <div class="nav__item">Commercial</div>
                    <div class="nav__item">Residential</div>
                    <div class="nav__item">Other</div>
                </nav>
            </aside>
            <div class="projects__inner">
                Slider
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
}
</style>