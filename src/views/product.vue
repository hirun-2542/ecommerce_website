<script setup>
import { ref } from "vue";

const products = [
    "https://preview.colorlib.com/theme/karma/img/product/p6.jpg.webp",
    "https://preview.colorlib.com/theme/karma/img/product/p8.jpg.webp",
    "https://preview.colorlib.com/theme/karma/img/product/p3.jpg.webp",
    "https://preview.colorlib.com/theme/karma/img/product/p5.jpg.webp",
    "https://preview.colorlib.com/theme/karma/img/product/p1.jpg.webp",
    "https://preview.colorlib.com/theme/karma/img/product/p2.jpg.webp",
    "https://preview.colorlib.com/theme/karma/img/product/p4.jpg.webp",
    "https://preview.colorlib.com/theme/karma/img/product/p7.jpg.webp",
];
</script>

<template>
    <section class="product-area">
        <div class="container">
            <header class="header-content">
                <div class="header-title">
                    <h1 class="text-4xl mb-2 font-bold text-black">
                        Coming Products
                    </h1>
                    <p class="leading-6">
                        Lorem ipsum dolor sit amet, consectetur adipisicing
                        elit, sed do eiusmod tempor incididunt ut labore et
                        dolore magna aliqua.
                    </p>
                </div>
            </header>
            <main class="product-content">
                <div
                    class="mb-10"
                    v-for="(product, index) in products"
                    :key="index"
                >
                    <img class="mb-5" :src="product" alt="" />
                    <div class="product-details">
                        <h6 class="mb-2">
                            addidas New Hammer sole for Sports person
                        </h6>
                        <div class="price flex">
                            <h6>$150.00</h6>
                            <h6 class="old-price">$210.00</h6>
                        </div>
                        <div class="prd-btn">
                            <div class="info">
                                <div class="icon">
                                    <svg
                                        class="text-white w-full"
                                        stroke="currentColor"
                                        fill="currentColor"
                                        stroke-width="0"
                                        viewBox="0 0 24 24"
                                        height="1.2em"
                                        width="1.2em"
                                        xmlns="http://www.w3.org/2000/svg"
                                    >
                                        <g>
                                            <path
                                                fill="none"
                                                d="M0 0h24v24H0z"
                                            ></path>
                                            <path
                                                d="M7 8V6a5 5 0 1 1 10 0v2h3a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1h3zm0 2H5v10h14V10h-2v2h-2v-2H9v2H7v-2zm2-2h6V6a3 3 0 0 0-6 0v2z"
                                            ></path>
                                        </g>
                                    </svg>
                                </div>
                                <div class="hover-text">add to bag</div>
                            </div>
                            <div class="info">
                                <div class="icon">
                                    <svg
                                        class="text-white w-full"
                                        stroke="currentColor"
                                        fill="currentColor"
                                        stroke-width="0"
                                        viewBox="0 0 1024 1024"
                                        height="1.2em"
                                        width="1.2em"
                                        xmlns="http://www.w3.org/2000/svg"
                                    >
                                        <path
                                            d="M923 283.6a260.04 260.04 0 0 0-56.9-82.8 264.4 264.4 0 0 0-84-55.5A265.34 265.34 0 0 0 679.7 125c-49.3 0-97.4 13.5-139.2 39-10 6.1-19.5 12.8-28.5 20.1-9-7.3-18.5-14-28.5-20.1-41.8-25.5-89.9-39-139.2-39-35.5 0-69.9 6.8-102.4 20.3-31.4 13-59.7 31.7-84 55.5a258.44 258.44 0 0 0-56.9 82.8c-13.9 32.3-21 66.6-21 101.9 0 33.3 6.8 68 20.3 103.3 11.3 29.5 27.5 60.1 48.2 91 32.8 48.9 77.9 99.9 133.9 151.6 92.8 85.7 184.7 144.9 188.6 147.3l23.7 15.2c10.5 6.7 24 6.7 34.5 0l23.7-15.2c3.9-2.5 95.7-61.6 188.6-147.3 56-51.7 101.1-102.7 133.9-151.6 20.7-30.9 37-61.5 48.2-91 13.5-35.3 20.3-70 20.3-103.3.1-35.3-7-69.6-20.9-101.9zM512 814.8S156 586.7 156 385.5C156 283.6 240.3 201 344.3 201c73.1 0 136.5 40.8 167.7 100.4C543.2 241.8 606.6 201 679.7 201c104 0 188.3 82.6 188.3 184.5 0 201.2-356 429.3-356 429.3z"
                                        ></path>
                                    </svg>
                                </div>
                                <div class="hover-text">Wishlist</div>
                            </div>
                            <div class="info">
                                <div class="icon">
                                    <svg
                                        class="text-white w-full"
                                        stroke="currentColor"
                                        fill="currentColor"
                                        stroke-width="0"
                                        viewBox="0 0 24 24"
                                        height="1.2em"
                                        width="1.2em"
                                        xmlns="http://www.w3.org/2000/svg"
                                    >
                                        <path
                                            d="M12 6v3l4-4-4-4v3c-4.42 0-8 3.58-8 8 0 1.57.46 3.03 1.24 4.26L6.7 14.8c-.45-.83-.7-1.79-.7-2.8 0-3.31 2.69-6 6-6zm6.76 1.74L17.3 9.2c.44.84.7 1.79.7 2.8 0 3.31-2.69 6-6 6v-3l-4 4 4 4v-3c4.42 0 8-3.58 8-8 0-1.57-.46-3.03-1.24-4.26z"
                                        ></path>
                                    </svg>
                                </div>
                                <div class="hover-text">Compare</div>
                            </div>
                            <div class="info">
                                <div class="icon">
                                    <svg
                                        class="text-white w-full"
                                        stroke="currentColor"
                                        fill="currentColor"
                                        stroke-width="0"
                                        viewBox="0 0 16 16"
                                        height="1.2em"
                                        width="1.2em"
                                        xmlns="http://www.w3.org/2000/svg"
                                    >
                                        <path
                                            fill-rule="evenodd"
                                            d="M6.5 8a.5.5 0 00-.5-.5H1.5a.5.5 0 000 1H6a.5.5 0 00.5-.5z"
                                            clip-rule="evenodd"
                                        ></path>
                                        <path
                                            fill-rule="evenodd"
                                            d="M3.854 5.646a.5.5 0 00-.708 0l-2 2a.5.5 0 000 .708l2 2a.5.5 0 00.708-.708L2.207 8l1.647-1.646a.5.5 0 000-.708zM9.5 8a.5.5 0 01.5-.5h4.5a.5.5 0 010 1H10a.5.5 0 01-.5-.5z"
                                            clip-rule="evenodd"
                                        ></path>
                                        <path
                                            fill-rule="evenodd"
                                            d="M12.146 5.646a.5.5 0 01.708 0l2 2a.5.5 0 010 .708l-2 2a.5.5 0 01-.708-.708L13.793 8l-1.647-1.646a.5.5 0 010-.708zM8 9.5a.5.5 0 00-.5.5v4.5a.5.5 0 001 0V10a.5.5 0 00-.5-.5z"
                                            clip-rule="evenodd"
                                        ></path>
                                        <path
                                            fill-rule="evenodd"
                                            d="M5.646 12.146a.5.5 0 000 .708l2 2a.5.5 0 00.708 0l2-2a.5.5 0 00-.708-.708L8 13.793l-1.646-1.647a.5.5 0 00-.708 0zM8 6.5a.5.5 0 01-.5-.5V1.5a.5.5 0 011 0V6a.5.5 0 01-.5.5z"
                                            clip-rule="evenodd"
                                        ></path>
                                        <path
                                            fill-rule="evenodd"
                                            d="M5.646 3.854a.5.5 0 010-.708l2-2a.5.5 0 01.708 0l2 2a.5.5 0 01-.708.708L8 2.207 6.354 3.854a.5.5 0 01-.708 0z"
                                            clip-rule="evenodd"
                                        ></path>
                                    </svg>
                                </div>
                                <div class="hover-text">View more</div>
                            </div>
                        </div>
                    </div>
                </div>
            </main>
        </div>
    </section>
</template>

<style scoped>
.product-area {
    padding-top: 70px;
    padding-bottom: 100px;
}
.container {
    width: 100%;
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
}
@media (min-width: 1200px) {
    .container {
        max-width: 1140px;
    }
}

.header-content {
    text-align: center;
    margin-bottom: 50px;
    display: flex;
    justify-content: center;
}

.header-title {
    max-width: 50%;
    font-size: 14px;
    color: #777777;
}

.product-content {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 15px;
}

.product-details h6 {
    font-size: 16px;
    text-transform: uppercase;
    font-weight: 700;
    line-height: 1.2;
    color: #222222;
}

.price h6 {
    font-size: 14px;
    padding-right: 15px;
    margin-bottom: 10px;
}

.old-price {
    text-decoration: line-through;
    color: #cccccc !important;
}

.prd-btn {
    display: flex;
    margin-top: 20px;
}

.prd-btn .info {
    position: relative;
    display: inline-block;
    width: 35px;
    transition: all 0.3s ease 0s;
}

.info .icon {
    background: #828bb2;
    border-radius: 50%;
    width: 30px;
    height: 30px;
    margin-right: 10px;
    display: flex;
    align-items: center;
}

.info .hover-text {
    position: absolute;
    width: 100px;
    top: 20%;
    font-size: 12px;
    font-weight: 700;
    color: #222222;
    text-transform: uppercase;
    opacity: 0;
    visibility: hidden;
    /* margin-bottom: 16px; */
}

.prd-btn .info:hover .icon {
    background: linear-gradient(90deg, #ffba00 0%, #ff6c00 100%);
}
.prd-btn .info:hover {
    width: 120px;
}

.prd-btn .info:hover .icon + .hover-text {
    opacity: 1;
    visibility: visible;
    left: 30%;
    transition: all 0.1s ease;
}
</style>
