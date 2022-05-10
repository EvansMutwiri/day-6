<template>
    <div class=" bg-yellow-400 text-center text-white text-2xl relative m-8 overflow-hidden rounded-md">
            <h1 class="overline pt-10 text-4xl">Content</h1>

            <div class="grid grid-cols-3 gap-4 place-items-stretch h-screen p-10 text-black">
                <div class="bg-yellow-100 shadow-md rounded-sm"><TextContent content="Vue" /> <img v-bind:src="image" alt="" class="object-cover"></div>
                <div class="bg-yellow-100 shadow-md rounded-sm"><TextContent content="Django" /><img v-bind:src="image" alt="" class="object-cover"></div>
                <div class="bg-yellow-100 shadow-md rounded-sm"><TextContent content="C" /><img v-bind:src="image" alt="" class="object-cover"></div>
                <div class="bg-yellow-100 shadow-md rounded-sm"><TextContent content="html" /><img v-bind:src="image" alt="" class="object-cover"></div>
                <div class="bg-yellow-100 shadow-md rounded-sm"><TextContent content="Js" /><img v-bind:src="image" alt="" class="object-cover"></div>
                <div class="bg-yellow-100 shadow-md rounded-sm"><TextContent content="Spark" /><img v-bind:src="image" alt="" class="object-cover"></div>
            </div>
        </div>
</template>

<script setup>
import { ref } from "@vue/reactivity";
import TextContent from "./TextContent.vue";
// export default {
//     setup() {
//     },
//     components: { TextContent }
// }

let image = ref('https://picsum.photos/600')
</script>