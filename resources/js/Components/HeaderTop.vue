<script setup>
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
import { faUser } from '@fortawesome/free-solid-svg-icons';
</script>

<template>
    <div class="bg-[#f4f4f4] py-2">
        <div class="container flex justify-between mx-auto">
            <div>Еженедельные скидки только у нас!</div>
            <div>
                <FontAwesomeIcon :icon="faUser" class="text-[#eb3e32] mr-3" />
                Войти
            </div>
        </div>
    </div>
</template>
