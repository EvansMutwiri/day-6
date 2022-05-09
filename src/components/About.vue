<template>
    <div class="flex m-8">
        <p class="h-28 text-left text-white w-1/6 px-10 py-8 md:py-10 md:w-1/2"><span class="text-green-400">{{ title = 'Vue Developer' }}</span>  dolor sit amet consectetur
            adipisicing elit. Quasi recusandae maiores impedit aliquam non sit, possimus accusamus excepturi facere
            pariatur similique, neque repellendus veniam placeat expedita voluptates voluptatibus quis at!</p>
        <p class="text-5xl m-8 relative w-5/6 px-6 py-8 md:py-10 md:w-1/2 text-left">About</p>
    </div>
</template>

<script setup>
    defineProps(['title']);

</script>