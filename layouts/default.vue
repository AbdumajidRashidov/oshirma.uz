<script setup lang="ts">
import { Analytics } from '@vercel/analytics/nuxt';
</script>
<template>
    <Analytics />
    <div class="wrapper mx-auto text-gray-900 font-normal max-w-[1320px]">
        <!-- <ElementsVideoPopup /> -->
        <!-- <LayoutHeader1 /> -->
        <div>
            <slot />
        </div>
        <ElementsBackToTop />
        <!-- <LayoutFooter1 /> -->
    </div>
</template>
