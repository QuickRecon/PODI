<style>
    .paragraph{
        margin: 20px 200px;
    }
</style>
<template>
    <div>
        <img src="/images/carousel5.JPG" style="width:100%; height: 700px; object-fit: cover">
        <div style="text-align: center; margin: 20px;">
            <h4><u>Our Philosophy</u></h4>
            <p class="paragraph">At PODI we prioritize the diver above the team and the art of diving over all else.
                It's our belief that one should always aim to have a minimal rig with as few failure points as possible.
             In the water we always aim to allow divers to perform any diving that they wish, we attempt to rebel
            against the ideas of "forbidden knowledge" that permeates the diving industry. If you want to perform a dive
             we think that you should be able to.
            <p class="paragraph">Independence is one of the cornerstones of our approach to both diving and teaching,
            we want all divers to be able to independently do whatever they want to in the underwater world that we
            love so much. This is why we aim for a minimalist configuration in all of our divers, by reducing failure
            points we diminish the chances of an issue ever occurring, meaning our divers are less reliant on buddy
            diving and more capable of executing their own dives.</p>

            <p class="paragraph">We also place a large value on freedom for divers. This is why we choose to offer
                courses not available anywhere else, because we want to give divers the skills and opportunities to do
             whatever they want, be it reef diving in the tropics to extreme underwater motor sports, we want to provide
             you with the ability to do what you want.</p>

            <h4><u>Our Instruction</u></h4>
            <p class="paragraph"> Our instructors are hand picked in order to ensure that they reflect the PODI values
             and are able to give divers proper instruction across all areas of our course. We require all instructors
             to be certified in all of our current course offerings, this allows them to provide a synergetic and
             integrated experience for divers who are DIP (Doing It PODI). This also guarantees that an instructor will
             be able to work with students to achieve every PODI qualification, without being bounced between a number
             of different specialists.</p>
            <p class="paragraph"> Our fully qualified instructors are able to guarantee that anyone will be able to
             pass our courses, PODI instructors are fully certified to get anyone to tick the boxes required to meet
             the standards of certification. Ensuring that our philosophy of freedom is not just limited to PODI divers,
             but to everyone, diver or non-diver, who wants to join us. We also aim to ensure that anyone is able to
             achieve the level of diving they want in a time effective manner, with our "no-to-pro" programs we are
             able to turn even someone who has never even touched a regulator before into a PODI instructor in only a
             fortnight.</p>
            <p class="paragraph">
                Through our vast network of PODI dive vans, scattered all over the world, except for Australia of course
                , we provide all instruction necessary. At PODI, we don't believe in the archaic model of giving dive
                vans a star rating out of 5. We believe it is unfair to those dive vans who are less equipped; so
                therefore we grant stars equally to all vans regardless of their level of competence.
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