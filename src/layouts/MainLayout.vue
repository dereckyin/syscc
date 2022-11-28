<template>
  <q-layout view="hHh lpR fFf">
    <div class="q-pa-none">
      <q-carousel
        animated
        v-model="slide"
        arrows
        navigation
        swipeable
        :autoplay="6000"
        infinite
        height="220px"
      >
        <q-carousel-slide
          :name="1"
          img-src="~assets/images/fotis-fotopoulos-SyvsTmuuZyM-unsplash.jpg"
        ></q-carousel-slide>
        <q-carousel-slide
          :name="2"
          img-src="~assets/images/kai-wenzel-06MHFfYv6YY-unsplash.jpg"
        ></q-carousel-slide>
        <q-carousel-slide
          :name="3"
          img-src="~assets/images/brett-jordan-LPZy4da9aRo-unsplash.jpg"
        ></q-carousel-slide>
        <q-carousel-slide
          :name="4"
          img-src="~assets/images/brett-jordan-OCfHTaB5THQ-unsplash.jpg"
        ></q-carousel-slide>
        <q-carousel-slide
          :name="5"
          img-src="~assets/images/markus-spiske-L29OcSbFbYo-unsplash.jpg"
        ></q-carousel-slide>
        <q-carousel-slide
          :name="6"
          img-src="~assets/images/szabo-viktor-qmvl6m4Tots-unsplash.jpg"
        ></q-carousel-slide>
        <q-carousel-slide
          :name="7"
          img-src="~assets/images/ed-hardie-xG02JzIBf7o-unsplash.jpg"
        ></q-carousel-slide>
      </q-carousel>
    </div>
    <q-page-container class="page-wrapper">
      <router-view />
    </q-page-container>

    <q-footer reveal elevated class="bg-black text-white">
      <q-toolbar>
        <q-toolbar-title>
          <div class="gt-sm h6 q-py-md" style="text-align: center">
            校園網路服務
          </div>
          <div class="gt-sm text-subtitle2 q-py-md" style="text-align: center">
            ※ 上述服務使用上如有任何問題，請與資訊網路組(分機
            7126～7129、7112)聯繫
          </div>

          <div class="lt-md text-subtitle1 q-py-xs" style="text-align: center">
            校園網路服務
          </div>
          <div class="lt-md text-subtitle2 q-py-xs" style="text-align: center">
            ※ 上述服務使用上如有任何問題<br />請與資訊網路組(分機
            7126～7129、7112)聯繫
          </div>
        </q-toolbar-title>
      </q-toolbar>
    </q-footer>
  </q-layout>
</template>

<script>
import { defineComponent, ref } from "vue";

export default defineComponent({
  name: "MainLayout",

  components: {},

  setup() {
    const leftDrawerOpen = ref(false);

    return {
      leftDrawerOpen,
      toggleLeftDrawer() {
        leftDrawerOpen.value = !leftDrawerOpen.value;
      },
      slide: ref(1),

      showActions: ref(false),
    };
  },
});
</script>
