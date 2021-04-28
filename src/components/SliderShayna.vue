<template>
    <section class="hero-section">
        <carousel class="hero-items" :autoplay="true" :items="1" :nav="false" :dots="true">
            <div class="single-hero-items p-0" style="background-image:url('img/hero-1.jpg');background-size:100%;background-repeat: no-repeat;">
                <div class="container py-5" >
                    <div class="row py-5">
                        <div class="col-lg-5 text-left">
                            <span>Bag,kids</span>
                            <h1>Black friday</h1>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
                                incididunt ut labore et dolore
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="single-hero-items p-0" style="background-image:url('img/hero-2.jpg');background-size:100%;background-repeat: no-repeat;" >
                <div class="container py-5" style="background:">
                    <div class="row py-5">
                        <div class="col-lg-5 text-left">
                            <span>Bag,kids</span>
                            <h1>Black friday</h1>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
                                incididunt ut labore et dolore
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>
        </carousel>
    </section>
</template>

<script>
import carousel from 'vue-owl-carousel'
export default {
    name: 'SliderShayna',
    components:{
        carousel,
    }
}
</script>


<style scoped>
    .single-hero-items{
        max-height: 500px
    }
</style>
