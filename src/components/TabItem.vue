<script setup>
import { inject } from 'vue'

const props = defineProps({
    title: String
})

const selectedTitle = inject('selectedTitle')
</script>

<template>
    <div class="tabs__content" v-show="selectedTitle === title">
        <slot />
    </div>
</template>