<style>
    .paragraph{
        margin: 20px 200px;
    }
</style>
<template>
    <div>
        <img src="/images/carousel4.JPG" style="width:100%; height: 700px; object-fit: cover">
        <div style="text-align: center; margin: 20px;">
            <h4><u>The specialty courses we offer:</u></h4>
            <ul style="list-style-type:circle">
                <li class="luxbar-item" ><a href="/courses/boat"><b>Boat</b> <br> Take your diving offshore with our revolutionary class that gives you the opportunity to sail the 7 seas.</a></li>
                <li class="luxbar-item" ><a href="/courses/cave"><b>Cave</b> <br> While most of the skills required for cave diving are covered in the PODI Water Course, this completes your knowledge and makes you ready for any subterranean adventure. </a></li>
                <li class="luxbar-item" ><a href="/courses/martian"><b>Martian</b> <br> Take your diving out of this world and explore the next new frontier.</a></li>
                <li class="luxbar-item" ><a href="/courses/motorcycle"><b>Motorcycle</b> <br> Get around much more efficiently underwater, combining the best underwater sport with the best form of land transportation.</a></li>
                <li class="luxbar-item" ><a href="/courses/nitrox">Nitrox</a></li>
                <li class="luxbar-item" ><a href="/courses/wreck">Wreck</a></li>
                <li class="luxbar-item" ><a href="/courses/trust">Trust</a></li>
                <li class="luxbar-item" ><a href="/courses/sick">Sick</a></li>
            </ul>
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