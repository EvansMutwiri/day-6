<template>
    {{ props.content }}
</template>

<script>
export default {
    props: ['content'],
    setup(props) {
        console.log(props.content)
        
        return {
            props
        }
    }
}
</script>

<style>
</style>