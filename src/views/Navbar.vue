<script setup>
import $ from "jquery";

// var scroll = $('#scroll');
// scroll.on("scroll", function (e) {
//     if(this.scrollTop > 1){
//         scroll.addClass("scroll-bar");
//     }else {
//         scroll.removeClass("scroll-bar");
//     }
// })

$(document).ready(function () {
    $(window).scroll(function () {
        if ($(this).scrollTop() > 1) {
            $("#scroll").addClass("scroll-bar");
            $("#width").addClass("nav-width");
        } else {
            $("#scroll").removeClass("scroll-bar");
            $("#width").removeClass("nav-width");
        }
    });
});
</script>

<template>
    <nav id="scroll" class="main">
        <header id="width" class="header-nav">
            <div class="container">
                <img
                    src="https://preview.colorlib.com/theme/karma/img/logo.png.webp"
                    alt=""
                />
                <div class="navbar ml-auto">
                    <ul class="menu">
                        <li>HOME</li>
                        <li>SHOP</li>
                        <li>BLOG</li>
                        <li>PAGES</li>
                        <li>CONTACT</li>
                        <ul class="flex items-center">
                            <li>
                                <svg
                                    stroke="currentColor"
                                    fill="currentColor"
                                    stroke-width="0"
                                    viewBox="0 0 24 24"
                                    height="1.5em"
                                    width="1.5em"
                                    xmlns="http://www.w3.org/2000/svg"
                                >
                                    <path
                                        d="M5,22h14c1.103,0,2-0.897,2-2V9c0-0.553-0.447-1-1-1h-3V7c0-2.757-2.243-5-5-5S7,4.243,7,7v1H4C3.447,8,3,8.447,3,9v11 C3,21.103,3.897,22,5,22z M9,7c0-1.654,1.346-3,3-3s3,1.346,3,3v1H9V7z M5,10h2v2h2v-2h6v2h2v-2h2l0.002,10H5V10z"
                                    ></path>
                                </svg>
                            </li>
                            <li>
                                <svg
                                    stroke="currentColor"
                                    fill="currentColor"
                                    stroke-width="0"
                                    viewBox="0 0 1024 1024"
                                    height="1.5em"
                                    width="1.5em"
                                    xmlns="http://www.w3.org/2000/svg"
                                >
                                    <path
                                        d="M909.6 854.5L649.9 594.8C690.2 542.7 712 479 712 412c0-80.2-31.3-155.4-87.9-212.1-56.6-56.7-132-87.9-212.1-87.9s-155.5 31.3-212.1 87.9C143.2 256.5 112 331.8 112 412c0 80.1 31.3 155.5 87.9 212.1C256.5 680.8 331.8 712 412 712c67 0 130.6-21.8 182.7-62l259.7 259.6a8.2 8.2 0 0 0 11.6 0l43.6-43.5a8.2 8.2 0 0 0 0-11.6zM570.4 570.4C528 612.7 471.8 636 412 636s-116-23.3-158.4-65.6C211.3 528 188 471.8 188 412s23.3-116.1 65.6-158.4C296 211.3 352.2 188 412 188s116.1 23.2 158.4 65.6S636 352.2 636 412s-23.3 116.1-65.6 158.4z"
                                    ></path>
                                </svg>
                            </li>
                        </ul>
                    </ul>
                </div>
            </div>
        </header>
    </nav>
</template>

<style scoped>
.main {
    position: absolute;
    width: 100%;
    top: 40px;
    z-index: 999;
    transition: all 0.3s ease 0s;
}

img {
    vertical-align: middle;
    border-style: none;
}

.header-nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0 auto;
    max-width: 1200px;
    box-shadow: 0 10px 30px rgb(0 0 0 / 10%);
    background: #fff;
    transition: all 0.3s ease 0s;
}
.nav-width {
    max-width: 1800px !important;
}
.scroll-bar {
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    z-index: 999;
    transition: width 0.3s ease 0s;
}

.container {
    display: flex;
    align-items: center;
    line-height: 80px;
    margin-left: auto;
    margin-right: auto;
    padding: 0 15px;
    flex-wrap: nowrap;
    max-width: 1200px;
}

.menu {
    display: flex;
    list-style: none;
    margin: 0;
    padding: 0;
}

.menu li {
    margin-right: 45px;
    font-size: 12px;
    font-weight: 500;
    color: #000;
    padding: 10px 0;
}

.menu li:hover {
    color: #ff0000;
    cursor: pointer;
}
</style>
