<template>

    <about class="h-56 bg-slate-400">
        <About/>
    </about>

    <content>
        <Content/>
    </content>

</template>

<script>
import About from "./About.vue";
import Content from "./Content.vue";
export default {
    components: { About, Content }
}
</script>

<style>
</style>