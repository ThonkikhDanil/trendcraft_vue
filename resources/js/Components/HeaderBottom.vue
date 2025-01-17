<script setup>
import { Link } from '@inertiajs/vue3';
</script>

<template>
    <div class="bg-[#eb3e32]">
        <div class="container flex items-center justify-center mx-auto uppercase">
            <Link :href="route('home')" class="p-4">Главная</Link>
            <Link class="p-4">Отзывы</Link>
            <Link class="p-4">О нас</Link>
            <Link class="p-4">Магазин</Link>
            <Link class="p-4">Написать нам</Link>
        </div>
    </div>
</template>
