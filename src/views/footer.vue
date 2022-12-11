<script setup>
const year = new Date().getFullYear();
</script>

<template>
    <footer class="footer-area">
        <div class="container">
            <div class="footer-content">
                <div class="about-us">
                    <h6>About Us</h6>
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipisicing
                        elit, sed do eiusmod tempor incididunt ut labore dolore
                        magna aliqua.
                    </p>
                </div>
                <div class="news-letter">
                    <h6>Newsletter</h6>
                    <p>Stay update with our latest</p>
                    <div class="email">
                        <input type="email" placeholder="Enter Email" />
                        <button class="email-btn">
                            <svg
                                class="m-auto"
                                stroke="currentColor"
                                fill="currentColor"
                                stroke-width="0"
                                viewBox="0 0 448 512"
                                height="1.5em"
                                width="1.5em"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    d="M313.941 216H12c-6.627 0-12 5.373-12 12v56c0 6.627 5.373 12 12 12h301.941v46.059c0 21.382 25.851 32.09 40.971 16.971l86.059-86.059c9.373-9.373 9.373-24.569 0-33.941l-86.059-86.059c-15.119-15.119-40.971-4.411-40.971 16.971V216z"
                                ></path>
                            </svg>
                        </button>
                    </div>
                </div>
                <div class="ig-feed">
                    <h6 class="">Instragram Feed</h6>
                    <ul class="ig-img">
                        <li>
                            <img
                                src="https://preview.colorlib.com/theme/karma/img/i1.jpg.webp"
                                alt=""
                            />
                        </li>
                        <li>
                            <img
                                src="https://preview.colorlib.com/theme/karma/img/i2.jpg.webp"
                                alt=""
                            />
                        </li>
                        <li>
                            <img
                                src="https://preview.colorlib.com/theme/karma/img/i3.jpg.webp"
                                alt=""
                            />
                        </li>
                        <li>
                            <img
                                src="https://preview.colorlib.com/theme/karma/img/i4.jpg.webp"
                                alt=""
                            />
                        </li>
                        <li>
                            <img
                                src="https://preview.colorlib.com/theme/karma/img/i5.jpg.webp"
                                alt=""
                            />
                        </li>
                        <li>
                            <img
                                src="https://preview.colorlib.com/theme/karma/img/i6.jpg.webp"
                                alt=""
                            />
                        </li>
                        <li>
                            <img
                                src="https://preview.colorlib.com/theme/karma/img/i7.jpg.webp"
                                alt=""
                            />
                        </li>
                        <li>
                            <img
                                src="https://preview.colorlib.com/theme/karma/img/i8.jpg.webp"
                                alt=""
                            />
                        </li>
                    </ul>
                </div>
                <div class="contact">
                    <h6>Follow Us</h6>
                    <p>Let us be social</p>
                    <div class="social">
                        <div class="fackbook">
                            <svg
                                stroke="currentColor"
                                fill="currentColor"
                                stroke-width="0"
                                viewBox="0 0 320 512"
                                height="1.3em"
                                width="1.3em"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    d="M279.14 288l14.22-92.66h-88.91v-60.13c0-25.35 12.42-50.06 52.24-50.06h40.42V6.26S260.43 0 225.36 0c-73.22 0-121.08 44.38-121.08 124.72v70.62H22.89V288h81.39v224h100.17V288z"
                                ></path>
                            </svg>
                        </div>
                        <div class="twitter">
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
                                    d="M928 254.3c-30.6 13.2-63.9 22.7-98.2 26.4a170.1 170.1 0 0 0 75-94 336.64 336.64 0 0 1-108.2 41.2A170.1 170.1 0 0 0 672 174c-94.5 0-170.5 76.6-170.5 170.6 0 13.2 1.6 26.4 4.2 39.1-141.5-7.4-267.7-75-351.6-178.5a169.32 169.32 0 0 0-23.2 86.1c0 59.2 30.1 111.4 76 142.1a172 172 0 0 1-77.1-21.7v2.1c0 82.9 58.6 151.6 136.7 167.4a180.6 180.6 0 0 1-44.9 5.8c-11.1 0-21.6-1.1-32.2-2.6C211 652 273.9 701.1 348.8 702.7c-58.6 45.9-132 72.9-211.7 72.9-14.3 0-27.5-.5-41.2-2.1C171.5 822 261.2 850 357.8 850 671.4 850 843 590.2 843 364.7c0-7.4 0-14.8-.5-22.2 33.2-24.3 62.3-54.4 85.5-88.2z"
                                ></path>
                            </svg>
                        </div>
                        <div class="dribbble">
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
                                    d="M512 96C282.6 96 96 282.6 96 512s186.6 416 416 416 416-186.6 416-416S741.4 96 512 96zm275.1 191.8c49.5 60.5 79.5 137.5 80.2 221.4-11.7-2.5-129.2-26.3-247.4-11.4-2.5-6.1-5-12.2-7.6-18.3-7.4-17.3-15.3-34.6-23.6-51.5C720 374.3 779.6 298 787.1 287.8zM512 157.2c90.3 0 172.8 33.9 235.5 89.5-6.4 9.1-59.9 81-186.2 128.4-58.2-107-122.7-194.8-132.6-208 27.3-6.6 55.2-9.9 83.3-9.9zM360.9 191c9.4 12.8 72.9 100.9 131.7 205.5C326.4 440.6 180 440 164.1 439.8c23.1-110.3 97.4-201.9 196.8-248.8zM156.7 512.5c0-3.6.1-7.3.2-10.9 15.5.3 187.7 2.5 365.2-50.6 10.2 19.9 19.9 40.1 28.8 60.3-4.7 1.3-9.4 2.7-14 4.2C353.6 574.9 256.1 736.4 248 750.1c-56.7-63-91.3-146.3-91.3-237.6zM512 867.8c-82.2 0-157.9-28-218.1-75 6.4-13.1 78.3-152 278.7-221.9l2.3-.8c49.9 129.6 70.5 238.3 75.8 269.5A350.46 350.46 0 0 1 512 867.8zm198.5-60.7c-3.6-21.6-22.5-125.6-69-253.3C752.9 536 850.7 565.2 862.8 569c-15.8 98.8-72.5 184.2-152.3 238.1z"
                                ></path>
                            </svg>
                        </div>
                        <div class="behance">
                            <svg
                                stroke="currentColor"
                                fill="currentColor"
                                stroke-width="0"
                                viewBox="0 0 1024 1024"
                                height="2em"
                                width="2em"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    d="M634 294.3h199.5v48.4H634zM434.1 485.8c44.1-21.1 67.2-53.2 67.2-102.8 0-98.1-73-121.9-157.3-121.9H112v492.4h238.5c89.4 0 173.3-43 173.3-143 0-61.8-29.2-107.5-89.7-124.7zM220.2 345.1h101.5c39.1 0 74.2 10.9 74.2 56.3 0 41.8-27.3 58.6-66 58.6H220.2V345.1zm115.5 324.8H220.1V534.3H338c47.6 0 77.7 19.9 77.7 70.3 0 49.6-35.9 65.3-80 65.3zm575.8-89.5c0-105.5-61.7-193.4-173.3-193.4-108.5 0-182.3 81.7-182.3 188.8 0 111 69.9 187.2 182.3 187.2 85.1 0 140.2-38.3 166.7-120h-86.3c-9.4 30.5-47.6 46.5-77.3 46.5-57.4 0-87.4-33.6-87.4-90.7h256.9c.3-5.9.7-12.1.7-18.4zM653.9 537c3.1-46.9 34.4-76.2 81.2-76.2 49.2 0 73.8 28.9 78.1 76.2H653.9z"
                                ></path>
                            </svg>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer-dev">
                <p class="footer-text">
                    Copyright ©{{ year }}
                    All rights reserved | This template is made with
                    <span
                        ><svg
                            stroke="currentColor"
                            fill="currentColor"
                            stroke-width="0"
                            viewBox="0 0 1024 1024"
                            height="1.3em"
                            width="1.3em"
                            xmlns="http://www.w3.org/2000/svg"
                            class="inline-block text-amber-500"
                        >
                            <path
                                d="M923 283.6a260.04 260.04 0 0 0-56.9-82.8 264.4 264.4 0 0 0-84-55.5A265.34 265.34 0 0 0 679.7 125c-49.3 0-97.4 13.5-139.2 39-10 6.1-19.5 12.8-28.5 20.1-9-7.3-18.5-14-28.5-20.1-41.8-25.5-89.9-39-139.2-39-35.5 0-69.9 6.8-102.4 20.3-31.4 13-59.7 31.7-84 55.5a258.44 258.44 0 0 0-56.9 82.8c-13.9 32.3-21 66.6-21 101.9 0 33.3 6.8 68 20.3 103.3 11.3 29.5 27.5 60.1 48.2 91 32.8 48.9 77.9 99.9 133.9 151.6 92.8 85.7 184.7 144.9 188.6 147.3l23.7 15.2c10.5 6.7 24 6.7 34.5 0l23.7-15.2c3.9-2.5 95.7-61.6 188.6-147.3 56-51.7 101.1-102.7 133.9-151.6 20.7-30.9 37-61.5 48.2-91 13.5-35.3 20.3-70 20.3-103.3.1-35.3-7-69.6-20.9-101.9zM512 814.8S156 586.7 156 385.5C156 283.6 240.3 201 344.3 201c73.1 0 136.5 40.8 167.7 100.4C543.2 241.8 606.6 201 679.7 201c104 0 188.3 82.6 188.3 184.5 0 201.2-356 429.3-356 429.3z"
                            ></path></svg
                    ></span>
                    by
                    <a class="text-amber-500" href="https://colorlib.com" target="_blank">Colorlib</a>
                </p>
            </div>
        </div>
    </footer>
</template>

<style scoped>
.footer-area {
    padding: 100px 0;
    background-color: #222222;
    color: white;
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

.footer-content {
    display: grid;
    grid-template-columns: 25% 33.33% 25% 16.67%;
    line-height: 24px;
    font-size: 14px;
    font-family: "Roboto", sans-serif;
    font-weight: 400;
    color: #777777;
}

.about-us,
.news-letter,
.ig-feed,
.contact {
    position: relative;
    width: 100%;
    min-height: 1px;
    padding-right: 15px;
    padding-left: 15px;
}

.footer-content h6 {
    font-size: 18px;
    font-family: "Roboto", sans-serif;
    color: white;
    font-weight: 700;
    margin-bottom: 25px;
}

.footer-content p {
    margin-bottom: 16px;
}

.email {
    display: flex;
}

.email input {
    border: none;
    width: 80% !important;
    font-weight: 300;
    background: #fff;
    color: #777;
    padding: 6px 12px 6px 20px;
    border-radius: 0;
    font-size: 14px;
}
.email-btn {
    color: white;
    width: 3em;
    background: linear-gradient(90deg, #ffba00 0%, #ff6c00 100%);
}

.ig-img {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 0.5em;
}

.social {
    display: flex;
    align-items: center;
}

.social svg {
    cursor: pointer;
    color: white;
    margin-right: 25px;
}

.social svg:hover {
    color: #fd7e14;
    transition: all 0.3s ease 0s;
}

.footer-dev {
    color: #777;
    padding-top: 80px;
    width: 100%;
    display: flex;
    justify-content: center;
}
</style>
