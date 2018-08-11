<style>
    .paragraph{
        margin: 20px 200px;
    }
</style>
<template>
    <div>
        <img src="/images/carousel3.JPG" style="width:100%; height: 700px; object-fit: cover">
        <div style="text-align: center; margin: 20px;">
            <h5>Here at the PODI Organization for Dive Instruction (PODI), we pride ourselves on being a new and revolutionary
            certification agency for the 21st century.</h5>
            <p class="paragraph">
                We believe that the dive industry is ripe for change, with numerous other agencies becoming prevalent we
            want to create one certification agency that is able to provide diving to everyone while maintaining exacting standards.
            Many diving industries of the modern world are bogged down in liability and accountability, we believe that this limits a divers
            ability to explore the underwater world that we all enjoy so much. That is why we offer courses that will not be found anywhere else
            in the world, so that divers are able to do what they love underwater regardless of the arbitrary standards of others.
            </p>
            <p class="paragraph">
                Our courses and instructors are of a very high standard and are designed to provide all the information required
                to engage in any type of diving in existence, come and experience the PODI style of diving today!
            </p>
        </div>
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