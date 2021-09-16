<template>
    <div>
        <div id="main-section" class="container section mt-3">
            <b-row>
                <b-col lg="5" class="d-flex flex-wrap">
                    <div class="w-100 align-self-center">
                        <h1 class="text-primary">Good Food Us<br>Good Mood</h1>
                        <p class="main-section__lg-description text-light">I would think that conserving our natural resources should be a conservative position: Not to waste food, and not to throw away a lot of the food that we buy.</p>
                        <b-row class="main-section__lg-button">
                            <b-col cols="12">
                                <b-btn variant="primary" class="mr-2">Daftar Sekarang</b-btn>
                                <b-btn variant="secondary" class="text-dark">About Us</b-btn>
                            </b-col>
                        </b-row>
                    </div>
                </b-col>
                <b-col lg="7">
                    <div class="main-section__hero d-flex justify-content-center">
                        <div class="main-section__hero__wrapper">
                            <img src="~/static/img/salad.png" alt="" class="img-fluid">
                        </div>
                        <div class="main-section__banner d-flex align-self-center justify-content-end">
                            <div class="main-section__banner__wrapper">
                                <div class="main-section__banner__main-img"><img src="~/static/img/salad.png" alt=""></div>
                                <div>
                                    <p>Green Salad Tomato</p>
                                    <p class="text-muted"><small>Tomato</small></p>
                                    <div class="main-section__banner__rate d-flex">
                                        <div>
                                            <img src="~/static/img/star.png" alt="">
                                        </div>
                                        <div>
                                            <img src="~/static/img/star.png" alt="">
                                        </div>
                                        <div>
                                            <img src="~/static/img/star.png" alt="">
                                        </div>
                                        <div>
                                            <img src="~/static/img/no-star.png" alt="">
                                        </div>
                                        <div>
                                            <img src="~/static/img/no-star.png" alt="">
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </b-col>

                <b-col class="main-section__md-description-col" cols="12">
                    <p class="text-light">I would think that conserving our natural resources should be a conservative position: Not to waste food, and not to throw away a lot of the food that we buy.</p>
                    <b-row>
                        <b-col cols="12">
                            <b-btn variant="primary" class="mr-2">Daftar Sekarang</b-btn>
                            <b-btn variant="secondary" class="text-dark">About Us</b-btn>
                        </b-col>
                    </b-row>
                </b-col>
            </b-row>
        </div>
        <div id="category-section" class="section py-5">
            <div class="section__title container mb-5">
                <h3>Browser Our Category</h3>
                <h3 class="text-primary">Receipt</h3>
            </div>
            <div id="receipts__carousel" class="section__content glide">
                <div class="glide__track" data-glide-el="track">
                    <ul class="glide__slides">
                        <li class="glide__slide">
                            <a href="#" class="glide__slide__wrapper glide__cupcake">
                                <img src="~/static/img/cupcake.png" alt="">
                                <h3>Cupcake</h3>
                                <p>22 items</p>
                            </a>
                        </li>
                        <li class="glide__slide">
                            <a href="#" class="glide__slide__wrapper glide__pizza">
                                <img src="~/static/img/pizza.png" alt="">
                                <h3>Pizza</h3>
                                <p>25 items</p>
                            </a>
                        </li>
                        <li class="glide__slide">
                            <a href="#" class="glide__slide__wrapper glide__kebab">
                                <img src="~/static/img/kebab.png" alt="">
                                <h3>Kebab</h3>
                                <p>22 items</p>
                            </a>
                        </li>
                        <li class="glide__slide">
                            <a href="#" class="glide__slide__wrapper glide__salmon">
                                <img src="~/static/img/salmon.png" alt="">
                                <h3>Salmon</h3>
                                <p>11 items</p>
                            </a>
                        </li>
                        <li class="glide__slide">
                            <a href="#" class="glide__slide__wrapper glide__doughnut">
                                <img src="~/static/img/doughnut.png" alt="">
                                <h3>Doughnut</h3>
                                <p>22 items</p>
                            </a>
                        </li>
                        <li class="glide__slide">
                            <a href="#" class="glide__slide__wrapper glide__cupcake">
                                <img src="~/static/img/salmon.png" alt="">
                                <h3>Fish</h3>
                                <p>33 items</p>
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="receipts__carousel__nav container mt-2">
                <div class="d-flex justify-content-end">
                    <a href="#" @click.prevent="receiptCarousel.go('<')" class="receipts__carousel__nav__prev">
                        <img src="~/static/img/prev-btn.png" alt="">
                    </a>
                    <a href="#" @click.prevent="receiptCarousel.go('>')" class="receipts__carousel__nav__next">
                        <img src="~/static/img/next-btn.png" alt="">
                    </a>
                </div>
            </div>
        </div>
        <div id="trending-section" class="section py-5">
            <div class="section__title container mb-5">
                <h3>Browser Our Trending</h3>
                <h3 class="text-primary">Receipt</h3>
            </div>
            <div class="container section__content">
                <b-row>
                    <b-col lg="3" md="6" cols="12">
                        <a href="#" class="trending-section__receipt trending-section__receipt--pizza">
                            <div class="trending-section__receipt__image"><img src="~/static/img/pizza-p.png" alt=""></div>
                            <h4>Pizza Paperoni</h4>
                            <p>Pizza</p>
                            <div class="trending-section__receipt__rate d-flex">
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/no-star.png" alt="">
                                </div>
                            </div>
                        </a>
                    </b-col>
                    <b-col lg="3" md="6" cols="12">
                        <a href="#" class="trending-section__receipt trending-section__receipt--pizza">
                            <div class="trending-section__receipt__image"><img src="~/static/img/pizza-p.png" alt=""></div>
                            <h4>Pizza Paperoni</h4>
                            <p>Pizza</p>
                            <div class="trending-section__receipt__rate d-flex">
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/no-star.png" alt="">
                                </div>
                            </div>
                        </a>
                    </b-col>
                    <b-col lg="3" md="6" cols="12">
                        <a href="#" class="trending-section__receipt trending-section__receipt--kebab">
                            <div class="trending-section__receipt__image"><img src="~/static/img/pizza-p.png" alt=""></div>
                            <h4>Doner Kebab</h4>
                            <p>Kebab</p>
                            <div class="trending-section__receipt__rate d-flex">
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/no-star.png" alt="">
                                </div>
                            </div>
                        </a>
                    </b-col>
                    <b-col lg="3" md="6" cols="12">
                        <a href="#" class="trending-section__receipt trending-section__receipt--salmon">
                            <div class="trending-section__receipt__image"><img src="~/static/img/pizza-p.png" alt=""></div>
                            <h4>Salmon Roll</h4>
                            <p>Salmon</p>
                            <div class="trending-section__receipt__rate d-flex">
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/no-star.png" alt="">
                                </div>
                            </div>
                        </a>
                    </b-col>
                    <b-col lg="3" md="6" cols="12">
                        <a href="#" class="trending-section__receipt trending-section__receipt--cupcake">
                            <div class="trending-section__receipt__image"><img src="~/static/img/pizza-p.png" alt=""></div>
                            <h4>Cupcake Choco</h4>
                            <p>Cupcake</p>
                            <div class="trending-section__receipt__rate d-flex">
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/no-star.png" alt="">
                                </div>
                            </div>
                        </a>
                    </b-col>
                    <b-col lg="3" md="6" cols="12">
                        <a href="#" class="trending-section__receipt trending-section__receipt--doughnut">
                            <div class="trending-section__receipt__image"><img src="~/static/img/pizza-p.png" alt=""></div>
                            <h4>Doughnut Milk</h4>
                            <p>Doughnut</p>
                            <div class="trending-section__receipt__rate d-flex">
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/no-star.png" alt="">
                                </div>
                            </div>
                        </a>
                    </b-col>
                    <b-col lg="3" md="6" cols="12">
                        <a href="#" class="trending-section__receipt trending-section__receipt--doughnut">
                            <div class="trending-section__receipt__image"><img src="~/static/img/pizza-p.png" alt=""></div>
                            <h4>Doughnut Unicorn</h4>
                            <p>Doughnut</p>
                            <div class="trending-section__receipt__rate d-flex">
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/no-star.png" alt="">
                                </div>
                            </div>
                        </a>
                    </b-col>
                    <b-col lg="3" md="6" cols="12">
                        <a href="#" class="trending-section__receipt trending-section__receipt--kebab">
                            <div class="trending-section__receipt__image"><img src="~/static/img/pizza-p.png" alt=""></div>
                            <h4>Kathi Kebab</h4>
                            <p>Kebab</p>
                            <div class="trending-section__receipt__rate d-flex">
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/star.png" alt="">
                                </div>
                                <div>
                                    <img src="~/static/img/no-star.png" alt="">
                                </div>
                            </div>
                        </a>
                    </b-col>
                </b-row>
                <div class="text-center mt-4">
                    <b-btn variant="primary" size="lg" class="px-4">All Receipt</b-btn>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import Glide from '@glidejs/glide'

export default {
    layout: 'homepage',
    data() {
        return {
            receiptCarousel: null
        }
    },
    mounted() {
        this.receiptCarousel = new Glide('#receipts__carousel', {
            type: 'carousel',
            perView: 5,
            bound: true,
            breakpoints: {
                1080: {
                    perView: 2
                }
            }
        }).mount()
    }
}
</script>
