<script>
//SWIPER COMPONENT
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

import "swiper/css/navigation";
import "swiper/css/pagination";

//import "./style.css";

// import required modules
import { Navigation, Pagination, Mousewheel, Keyboard } from "swiper";

export default {
    components: {
        Swiper,
        SwiperSlide,
},
    setup() {
        return {
            modules: [Navigation, Pagination, Mousewheel, Keyboard],
    };
},
};

</script>

<template>
    <section class="section is-info is-medium academics">
        <h1 class="title">Academics</h1>
        <div class="tile is-ancestor">
            <swiper
                :cssMode="true"
                :navigation="true"
                :pagination="true"
                :mousewheel="true"
                :keyboard="true"
                :modules="modules"
                class="mySwiper hero-body section is-medium tile is-9"
                >
                <swiper-slide><img class="brainimage js-modal-trigger" src="/images/Brain.jpg" alt="Mindmap of the brain" data-target="modal-js-example" @click="showModal = true"></swiper-slide>
                <swiper-slide>Slide 2</swiper-slide>
                <swiper-slide>Slide 3</swiper-slide>
            </swiper>
        </div>
    </section>

</template>

<style>
.academics {
    background-color: #549E54;
}

.swiper {
    width: 100%;
    height: 100%;
}

.swiper-slide {
    text-align: center;
    font-size: 18px;

  /* Center slide text vertically */
    display: -webkit-box;
    display: -ms-flexbox;
    display: -webkit-flex;
    display: flex;
    -webkit-box-pack: center;
    -ms-flex-pack: center;
    -webkit-justify-content: center;
    justify-content: center;
    -webkit-box-align: center;
    -ms-flex-align: center;
    -webkit-align-items: center;
    align-items: center;
}

.swiper-slide img {
    display: block;
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.brainimage {
    border-radius: 8px;
}

:root {
    --swiper-theme-color: #393939;
}
</style>