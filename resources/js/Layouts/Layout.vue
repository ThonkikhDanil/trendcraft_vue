<script setup>
import HeaderTop from '@/Components/HeaderTop.vue';
import HeaderMiddle from '@/Components/HeaderMiddle.vue';
import HeaderBottom from '@/Components/HeaderBottom.vue';
</script>

<template>
    <HeaderTop />
    <HeaderMiddle />
    <HeaderBottom />
    <slot />
</template>
