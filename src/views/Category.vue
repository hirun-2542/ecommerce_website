<script setup></script>

<template>
    <section class="category-area">
        <div class="container">
            <div class="row justify-center">
                <div class="row col-lg-8">
                    <div class="col-lg-8">
                        <div class="single">
                            <div class="overlay"></div>
                            <img
                                src="https://preview.colorlib.com/theme/karma/img/category/c1.jpg.webp"
                                alt=""
                            />
                            <div class="deal-detail">
                                <h6 class="deal-title">Sneaker for Sports</h6>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="single">
                            <div class="overlay"></div>
                            <img
                                src="https://preview.colorlib.com/theme/karma/img/category/c2.jpg.webp"
                                alt=""
                            />
                            <div class="deal-detail">
                                <h6 class="deal-title">Sneaker for Sports</h6>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="single">
                            <div class="overlay"></div>
                            <img
                                src="https://preview.colorlib.com/theme/karma/img/category/c3.jpg.webp"
                                alt=""
                            />
                            <div class="deal-detail">
                                <h6 class="deal-title">Sneaker for Sports</h6>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-8">
                        <div class="single">
                            <div class="overlay"></div>
                            <img
                                src="https://preview.colorlib.com/theme/karma/img/category/c4.jpg.webp"
                                alt=""
                            />
                            <div class="deal-detail">
                                <h6 class="deal-title">Sneaker for Sports</h6>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4">
                    <div class="single">
                        <div class="overlay"></div>
                        <img
                            src="https://preview.colorlib.com/theme/karma/img/category/c5.jpg.webp"
                            alt=""
                        />
                        <div class="deal-detail">
                            <h6 class="deal-title">Sneaker for Sports</h6>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.row {
    display: flex;
    flex-wrap: wrap;
    margin-right: -15px;
    margin-left: -15px;
}
.category-area {
    display: block;
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

.col-lg-8 {
    flex: 0 0 66.666667%;
    max-width: 66.666667%;
    padding-right: 15px;
    padding-left: 15px;
}

.col-lg-4 {
    flex: 0 0 33.333333%;
    max-width: 33.333333%;
    padding-right: 15px;
    padding-left: 15px;
}

.single {
    position: relative;
    margin-bottom: 30px;
}

.single .deal-detail {
    position: absolute;
    left: 50%;
    top: 100%;
    display: inline-block;
    text-align: center;
    transform: translate(-50%, -50%);
    opacity: 0;
    visibility: hidden;
    transition: all 0.3s ease 0s;
}

.deal-title {
    font-size: 14px;
    font-weight: 500;
    color: #fff;
    text-transform: uppercase;
    line-height: 1.2;
}

.single .overlay {
    position: absolute;
    left: 0;
    top: 0;
    height: 100%;
    width: 100%;
    content: "";
    background: #000;
    opacity: 0;
    transition: all 0.3s ease 0s;
}

.single:hover .overlay {
    opacity: 0.5;
}

.single:hover .overlay ~ .deal-detail {
    visibility: visible;
    opacity: 1;
    top: 50%;
}
</style>
