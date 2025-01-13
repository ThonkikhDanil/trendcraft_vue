<script setup>
import { Link } from '@inertiajs/vue3';
</script>

<template>
    <div class="py-6">
        <div class="container flex justify-between mx-auto">
            <Link :href="route('home')" class="text-[2rem] font-semibold">
                <span class="text-black">TREND</span>
                <span class="text-[#eb3e32]">CRAFT</span>
            </Link>
            <form action="" class="flex">
                <input type="text" name="product_name" id="product_name" placeholder="Поиск"
                    class="border-2 border-solid border-[#e8e8e8] rounded-s-lg w-[450px] text-[14px]">
                <button type="submit" class="rounded-e-lg bg-[#eb3e32] flex items-center px-2 text-white hover:bg-[#333131]">Найти</button>
            </form>
            <div class="flex">
                <div class="pr-4">Желаемое</div>
                <div>Корзина</div>
            </div>
        </div>
    </div>
</template>
