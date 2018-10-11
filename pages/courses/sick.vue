<style>
</style>
<template>
    <div>
        <img src="/images/carousel7.JPG" style="width:100%; height: 700px; object-fit: cover">
    </div>
</template>

<script>
    export default {
        layout: 'main',
        data () {
            return {
                title: 'Dive PODI'
            }
        },
        head () {
            return {
                title: this.title,
                meta: [
                ]
            }
        }
    }
</script>