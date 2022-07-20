<template>
    <div></div>
    <div></div>
    <div></div>
</template>

<script >
import { onMounted } from 'vue'
export default {
    name: 'app',
    setup() {
        onMounted(() => {
            console.log('mounted执行了');
        })
    }
}
</script>

<style>
</style>