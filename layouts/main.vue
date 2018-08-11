<style>
    .luxbar-menu-material-red,
    .luxbar-menu-material-red .dropdown ul {
        background-color: #c62828;
        color: #fff; }
    .luxbar-menu-material-red .active,
    .luxbar-menu-material-red .luxbar-item:hover {
        background-color: #e53935; }
    .luxbar-menu-material-red .luxbar-hamburger span,
    .luxbar-menu-material-red .luxbar-hamburger span::before,
    .luxbar-menu-material-red .luxbar-hamburger span::after {
        background-color: #fff; }
</style>
<template>
    <div>
        <header id="luxbar" class="luxbar-static">
            <input type="checkbox" class="luxbar-checkbox" id="luxbar-checkbox"/>
            <div class="luxbar-menu luxbar-menu-right luxbar-menu-material-red">
                <ul class="luxbar-navigation">
                    <li class="luxbar-header">
                        <a href="#" class="luxbar-brand">PODI</a>
                        <label class="luxbar-hamburger luxbar-hamburger-doublespin"
                               id="luxbar-hamburger" for="luxbar-checkbox"> <span></span> </label>
                    </li>
                    <li class="luxbar-item"><a href="/">Home</a></li>

                    <li class="luxbar-item"><a href="/whypodi">Why Dive PODI?</a></li>

                    <li class="luxbar-item"><a href="#">Learn to Dive</a></li>
                    <li class="luxbar-item dropdown"><a href="#">Specialties</a>
                        <ul>
                            <li class="luxbar-item" ><a href="#">Boat</a></li>
                            <li class="luxbar-item" ><a href="#">Cave</a></li>
                            <li class="luxbar-item" ><a href="#">Martian</a></li>
                            <li class="luxbar-item" ><a href="#">Motorcycle</a></li>
                            <li class="luxbar-item" ><a href="#">Nitrox</a></li>
                            <li class="luxbar-item" ><a href="#">Wreck</a></li>
                        </ul>
                    </li>
                    <li class="luxbar-item"><a href="#">PODI Pro</a></li>
                    <li class="luxbar-item"><a href="#">TechWreck</a></li>
                    <li class="luxbar-item"><a href="#">About Us</a></li>
                </ul>
            </div>
        </header>
        <nuxt/>
        <footer class="page-footer red darken-3">
            <div class="container">
                <div class="row">
                    <div class="col l6 s12">
                        <h5 class="white-text">Dive PODI Today!</h5>
                        <p class="grey-text text-lighten-4">Send us an email or contact your local PODI dive van today.
                        We will be happy to take you along to try diving the PODI way, the way of the future.</p>
                    </div>
                    <div class="col l4 offset-l2 s12">
                        <h5 class="white-text">What we offer:</h5>
                        <ul>
                            <li><a class="grey-text text-lighten-3" href="#!">Courses</a></li>
                            <li><a class="grey-text text-lighten-3" href="#!">PODI Pro</a></li>
                            <li><a class="grey-text text-lighten-3" href="#!">TechWreck</a></li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="footer-copyright red darken-4">
                <div class="container">
                    A project of the r/scuba discord server
                    <a class="grey-text text-lighten-4 right" href="https://discord.gg/U9cSfyp" target="_blank">Join Us Here</a>
                </div>
            </div>
        </footer>
    </div>
</template>