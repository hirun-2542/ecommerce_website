<script setup></script>

<template>
    <section class="banner-area">
        <div class="container">
            <div class="banner-slider">
                <div class="banner-state">
                    <div class="banner-content">
                        <h1>Nike New <br />Collection!</h1>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipisicing
                            elit, sed do eiusmod tempor incididunt ut labore et
                            dolore magna aliqua. Ut enim ad minim veniam, quis
                            nostrud exercitation.
                        </p>
                        <div class="add-bag">
                            <svg
                                stroke="currentColor"
                                fill="currentColor"
                                stroke-width="0"
                                viewBox="0 0 1024 1024"
                                height="3em"
                                width="3em"
                                class="text-orange-400"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    d="M512 64C264.6 64 64 264.6 64 512s200.6 448 448 448 448-200.6 448-448S759.4 64 512 64zm192 472c0 4.4-3.6 8-8 8H544v152c0 4.4-3.6 8-8 8h-48c-4.4 0-8-3.6-8-8V544H328c-4.4 0-8-3.6-8-8v-48c0-4.4 3.6-8 8-8h152V328c0-4.4 3.6-8 8-8h48c4.4 0 8 3.6 8 8v152h152c4.4 0 8 3.6 8 8v48z"
                                ></path>
                            </svg>
                            <span
                                class="flex items-center text-black ml-4 font-semibold"
                                >ADD TO BACK</span
                            >
                        </div>
                    </div>
                    <div class="banner-images">
                        <img
                            src="https://preview.colorlib.com/theme/karma/img/banner/banner-img.png.webp"
                            alt=""
                        />
                    </div>
                </div>
                <!-- <div class="banner-state">
                    <div class="banner-content">
                        <h1>Nike New <br />Collection!</h1>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipisicing
                            elit, sed do eiusmod tempor incididunt ut labore et
                            dolore magna aliqua. Ut enim ad minim veniam, quis
                            nostrud exercitation.
                        </p>
                        <div class="add-bag">
                            <svg
                                stroke="currentColor"
                                fill="currentColor"
                                stroke-width="0"
                                viewBox="0 0 1024 1024"
                                height="3em"
                                width="3em"
                                class="text-orange-400"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    d="M512 64C264.6 64 64 264.6 64 512s200.6 448 448 448 448-200.6 448-448S759.4 64 512 64zm192 472c0 4.4-3.6 8-8 8H544v152c0 4.4-3.6 8-8 8h-48c-4.4 0-8-3.6-8-8V544H328c-4.4 0-8-3.6-8-8v-48c0-4.4 3.6-8 8-8h152V328c0-4.4 3.6-8 8-8h48c4.4 0 8 3.6 8 8v152h152c4.4 0 8 3.6 8 8v48z"
                                ></path>
                            </svg>
                            <span
                                class="flex items-center text-black ml-4 font-semibold"
                                >ADD TO BACK</span
                            >
                        </div>
                    </div>
                    <div class="banner-images">
                        <img
                            src="https://preview.colorlib.com/theme/karma/img/banner/banner-img.png.webp"
                            alt=""
                        />
                    </div>
                </div>
                <div class="banner-state">
                    <div class="banner-content">
                        <h1>Nike New <br />Collection!</h1>
                        <p>
                            Lorem ipsum dolor sit amet, consectetur adipisicing
                            elit, sed do eiusmod tempor incididunt ut labore et
                            dolore magna aliqua. Ut enim ad minim veniam, quis
                            nostrud exercitation.
                        </p>
                        <div class="add-bag">
                            <svg
                                stroke="currentColor"
                                fill="currentColor"
                                stroke-width="0"
                                viewBox="0 0 1024 1024"
                                height="3em"
                                width="3em"
                                class="text-orange-400"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    d="M512 64C264.6 64 64 264.6 64 512s200.6 448 448 448 448-200.6 448-448S759.4 64 512 64zm192 472c0 4.4-3.6 8-8 8H544v152c0 4.4-3.6 8-8 8h-48c-4.4 0-8-3.6-8-8V544H328c-4.4 0-8-3.6-8-8v-48c0-4.4 3.6-8 8-8h152V328c0-4.4 3.6-8 8-8h48c4.4 0 8 3.6 8 8v152h152c4.4 0 8 3.6 8 8v48z"
                                ></path>
                            </svg>
                            <span
                                class="flex items-center text-black ml-4 font-semibold"
                                >ADD TO BACK</span
                            >
                        </div>
                    </div>
                    <div class="banner-images">
                        <img
                            src="https://preview.colorlib.com/theme/karma/img/banner/banner-img.png.webp"
                            alt=""
                        />
                    </div>
                </div> -->
            </div>
        </div>
    </section>
</template>

<style scoped>
.banner-area {
    background: url("https://preview.colorlib.com/theme/karma/img/banner/banner-bg.jpg.webp")
        no-repeat center;
    background-size: cover;
    height: 731px;
    position: relative;
    display: flex;
}

.banner-slider {
    display: flex;
    position: relative;
    /* transform: translate3d(50px, 0px, 0px);
    transition: all 0s ease 0s; */
    width: 5580px;
}

.banner-state {
    display: flex;
    margin: 0 auto;
    justify-content: center;
    position: relative;
    width: 1400px;
}
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0 auto;
    width: 100%;
}

.banner-content {
    width: 40%;
    color: #777777;
    padding: 0 0 0 2rem;
}

.banner-content h1 {
    font-size: 4rem;
    color: #000;
    font-weight: 800;
    line-height: 1.2;
    margin-top: 0;
    margin-bottom: 2rem;
}

.banner-images {
    padding: 0 0 0 2rem;
}

.add-bag {
    margin-top: 2em;
    display: flex;
}
</style>
