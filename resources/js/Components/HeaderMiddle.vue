<script setup>
import { Link } from '@inertiajs/vue3';
</script>

<template>
    <div class="py-6">
        <div class="container flex items-center justify-between mx-auto">
            <Link :href="route('home')" class="text-[2rem] font-semibold">
                <span class="text-black">TREND</span>
                <span class="text-[#eb3e32]">CRAFT</span>
            </Link>
            <form action="" class="flex">
                <input type="text" name="product_name" id="product_name" placeholder="Поиск"
                    class="border-2 border-solid border-[#e8e8e8] rounded-s-lg w-[450px] text-[14px] border-r-0">
                <button type="submit" class="rounded-e-lg bg-[#eb3e32] flex items-center px-2 text-white hover:bg-[#333131] w-[65px] justify-center">
                    <i class="fi fi-rr-search" />
                </button>
            </form>
            <div class="flex">
                <i class="pr-4 text-2xl fi fi-rr-heart" />
                <i class="text-2xl fi fi-rr-shopping-bag" />
            </div>
        </div>
    </div>
</template>
