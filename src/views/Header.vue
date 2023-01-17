<template>
    <!-- Header
    ============================================= -->
    <header id="header" class="full-header dark border-full-header header-size-custom bg-dark sticky-header" data-sticky-shrink="true" data-mobile-sticky="true">
        <div id="header-wrap">
            <div class="container">
                <div class="header-row">

                    <!-- Logo
                    ============================================= -->
                    <div id="logo">
                        <a href="index.html" class="standard-logo" data-dark-logo="frontend/assets/logo/logo-mit-light.svg"><img src="frontend/assets/logo/logo-mit-light.svg" alt="Canvas Logo"></a>
                        <a href="index.html" class="retina-logo" data-dark-logo="frontend/assets/logo/logo-mit-light.svg"><img src="frontend/assets/logo/logo-mit-light.svg" alt="Canvas Logo"></a>
                    </div><!-- #logo end -->

                    <div class="header-misc d-none d-sm-block">
                        <a href="register.html">
                            <button class="button button-circle fw-medium ms-0"> Register Now </button>
                        </a>
                    </div>

                    <div id="primary-menu-trigger">
                        <svg class="svg-trigger" viewBox="0 0 100 100"><path d="m 30,33 h 40 c 3.722839,0 7.5,3.126468 7.5,8.578427 0,5.451959 -2.727029,8.421573 -7.5,8.421573 h -20"></path><path d="m 30,50 h 40"></path><path d="m 70,67 h -40 c 0,0 -7.5,-0.802118 -7.5,-8.365747 0,-7.563629 7.5,-8.634253 7.5,-8.634253 h 20"></path></svg>
                    </div>

                    <!-- Primary Navigation
                    ============================================= -->
                    <nav class="primary-menu">

                        <ul class="one-page-menu menu-container" data-easing="easeInOutExpo" data-speed="1250" data-offset="70">
                            <li class="menu-item">
                                <RouterLink class="menu-link" to="/">Home</RouterLink>
                            </li>
                            <li class="menu-item d-none">
                                <a href="event.html" class="menu-link"><div>Event</div></a>
                            </li>
                            <li class="menu-item">
                                <a href="#" class="menu-link"><div>Speakers</div></a>
                                <ul class="sub-menu-container">
                                    <li class="menu-item">
                                        <RouterLink class="menu-link" to="/speaker">Conference Speakers</RouterLink>
                                    </li>
                                    <li class="menu-item">
                                        <RouterLink class="menu-link" to="/judges">Judges</RouterLink>
                                    </li>
                                    <li class="menu-item">
                                        <RouterLink class="menu-link" to="/mentor">Mentors</RouterLink>
                                    </li>
                                </ul>
                            </li>
                            <li class="menu-item">
                                <RouterLink class="menu-link" to="/sponsor">Sponsorship</RouterLink>
                            </li>
                            <li class="menu-item">
                                <RouterLink class="menu-link" to="/contact">Contact</RouterLink>
                            </li>
                            <li class="menu-item">
                                <RouterLink class="menu-link" to="/faq">FAQ</RouterLink>
                            </li>
                            <li class="menu-item d-block d-sm-none">
                                <RouterLink  to="/register">
                                    <button class="button button-circle fw-medium ms-0"> Register Now </button>
                                </RouterLink>
                            </li>
                        </ul>

                    </nav><!-- #primary-menu end -->

                </div>
            </div>
        </div>
        <div class="header-wrap-clone"></div>
    </header><!-- #header end -->
</template>

<script setup>
import { RouterLink } from 'vue-router'
</script>