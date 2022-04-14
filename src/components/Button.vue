<template>
        <button @click="onClick()" class="btn" :style="{background: color}" >{{text}}</button>
</template>
<script>
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'Button',
    props: {
        text: String,
        color: String,
    },
    methods: {
        onClick() {
            console.log('click')
        }
    }
}
</script>
<style lang="">
    
</style>