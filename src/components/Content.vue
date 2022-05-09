<template>
    <div class=" bg-yellow-400 text-center text-white text-2xl relative m-8 overflow-hidden rounded-lg">
            <h1 class="overline pt-10 text-4xl">Content</h1>

            <div class="grid grid-cols-3 gap-4 place-items-stretch h-screen p-10 text-black">
                <div class="bg-yellow-100"><TextContent content="Vue" /></div>
                <div class="bg-yellow-100"><TextContent content="Django" /></div>
                <div class="bg-yellow-100"><TextContent content="C" /></div>
                <div class="bg-yellow-100"><TextContent content="html" /></div>
                <div class="bg-yellow-100"><TextContent content="Js" /></div>
                <div class="bg-yellow-100"><TextContent content="Spark" /></div>
            </div>
        </div>
</template>

<script>
import TextContent from "./TextContent.vue";
export default {
    setup() {
    },
    components: { TextContent }
}
</script>