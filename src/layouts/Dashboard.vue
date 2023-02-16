<template>
    <div class="bg-blue-400/50 flex text-white max-h-screen h-screen">
        <div class="w-64">
            <span class="font-semibold p-6 block opacity-90">Super Pica-Pau</span>

            <nav class="p-6">
                <h3 class="opacity-50 uppercase font-semibold tracking-widest mb-6 text-xs">Menu</h3>

                <div class="space-y-6">
                    <MenuItem :icon="HomeIcon"> Início </MenuItem>
                    <MenuItem :icon="HomeIcon"> Início </MenuItem>
                    <MenuItem :icon="HomeIcon"> Início </MenuItem>
                    <MenuItem :icon="HomeIcon"> Início </MenuItem>
                </div>
            </nav>
        </div>

        <div class="border-2 flex-1 border-red-500">Content</div>
</div>
</template>

<script lang="ts" setup>

import HomeIcon from "../components/icons/HomeIcon.vue";
import MenuItem from "./navs/MenuItem.vue";
</script>