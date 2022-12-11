<script setup></script>

<template>
    <section class="feature-area">
        <div class="container">
            <div class="row-feature">
                <div class="feature-content">
                    <div class="feature-icon">
                        <img
                            src="https://preview.colorlib.com/theme/karma/img/features/f-icon1.png.webp"
                            alt=""
                        />
                    </div>
                    <h6>Free Delivery</h6>
                    <p>Free Shipping on all order</p>
                </div>
                <div class="feature-content">
                    <div class="feature-icon">
                        <img
                            src="https://preview.colorlib.com/theme/karma/img/features/f-icon2.png.webp"
                            alt=""
                        />
                    </div>
                    <h6>Return Policy</h6>
                    <p>Free Shipping on all order</p>
                </div>
                <div class="feature-content">
                    <div class="feature-icon">
                        <img
                            src="https://preview.colorlib.com/theme/karma/img/features/f-icon3.png.webp"
                            alt=""
                        />
                    </div>
                    <h6>24/7 Support</h6>
                    <p>Free Shipping on all order</p>
                </div>
                <div class="feature-content">
                    <div class="feature-icon">
                        <img
                            src="https://preview.colorlib.com/theme/karma/img/features/f-icon4.png.webp"
                            alt=""
                        />
                    </div>
                    <h6>Secure Payment</h6>
                    <p>Free Shipping on all order</p>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
section {
    padding: 100px 0;
}
.container {
    width: 100%;
    padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
}

.row-feature {
    display: flex;
    box-shadow: 0 10px 30px rgb(0 0 0 / 10%);
    padding: 40px 0;
}

@media (min-width: 1200px) {
    .container {
        max-width: 1140px;
    }
}

.feature-content {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 0 1rem;
    width: 25%;
    text-align: center;
    border-right: 1px solid #eeeeee;
}

.feature-content h6 {
    font-size: 16px;
    font-weight: 600;
}

.feature-content p {
    font-size: 14px;
    font-weight: 400;
    color: #777777;
}

.feature-icon {
    margin-bottom: 20px;
}
</style>
