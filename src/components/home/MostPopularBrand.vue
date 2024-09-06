<template>
    <h2 class="title text-left pt-1 mb-5 appear-animate">Most Popular Brand</h2>
    <div class="swiper">
        <div class="swiper-container category-wrapper swiper-theme appear-animate" data-swiper-options="{
                          'spaceBetween': 20,
                          'slidesPerView': 2,
                          'breakpoints': {
                              '576': {
                                  'slidesPerView': 3
                              },
                              '768': {
                                  'slidesPerView': 4
                              },
                              '992': {
                                  'slidesPerView': 5
                              },
                              '1200': {
                                  'slidesPerView': 6
                              }
                          }
                      }">
            <div class="swiper-wrapper row cols-xl-6 cols-lg-5 cols-md-4 cols-sm-3 cols-2">
                <div class="swiper-slide category category-ellipse">
                    <figure class="category-media">
                        <a href="shop-banner-sidebar.html">
                            <img src="assets/images/demos/demo3/categories/4.jpg" alt="Categroy" width="190"
                                 height="190" style="background-color: #5C92C0;" />
                        </a>
                    </figure>
                    <div class="category-content">
                        <h4 class="category-name">
                            <a href="shop-banner-sidebar.html">Adidas</a>
                        </h4>
                    </div>
                </div>
                <div class="swiper-slide category category-ellipse">
                    <figure class="category-media">
                        <a href="shop-banner-sidebar.html">
                            <img src="assets/images/demos/demo3/categories/5.jpg" alt="Categroy" width="190"
                                 height="190" style="background-color: #9BC4CA;" />
                        </a>
                    </figure>
                    <div class="category-content">
                        <h4 class="category-name">
                            <a href="shop-banner-sidebar.html">Nike</a>
                        </h4>
                    </div>
                </div>
                <div class="swiper-slide category category-ellipse">
                    <figure class="category-media">
                        <a href="shop-banner-sidebar.html">
                            <img src="assets/images/demos/demo3/categories/6.jpg" alt="Categroy" width="190"
                                 height="190" style="background-color: #48555B;" />
                        </a>
                    </figure>
                    <div class="category-content">
                        <h4 class="category-name">
                            <a href="shop-banner-sidebar.html">Samsung</a>
                        </h4>
                    </div>
                </div>
                <div class="swiper-slide category category-ellipse">
                    <figure class="category-media">
                        <a href="shop-banner-sidebar.html">
                            <img src="assets/images/demos/demo3/categories/7.jpg" alt="Categroy" width="190"
                                 height="190" style="background-color: #D4E5EF;" />
                        </a>
                    </figure>
                    <div class="category-content">
                        <h4 class="category-name">
                            <a href="shop-banner-sidebar.html">Xbox</a>
                        </h4>
                    </div>
                </div>
                <div class="swiper-slide category category-ellipse">
                    <figure class="category-media">
                        <a href="shop-banner-sidebar.html">
                            <img src="assets/images/demos/demo3/categories/8.jpg" alt="Categroy" width="190"
                                 height="190" style="background-color: #6A7881;" />
                        </a>
                    </figure>
                    <div class="category-content">
                        <h4 class="category-name">
                            <a href="shop-banner-sidebar.html">Xiaomi</a>
                        </h4>
                    </div>
                </div>
                <div class="swiper-slide category category-ellipse">
                    <figure class="category-media">
                        <a href="shop-banner-sidebar.html">
                            <img src="assets/images/demos/demo3/categories/9.jpg" alt="Categroy" width="190"
                                 height="190" style="background-color: #E4E4E4;" />
                        </a>
                    </figure>
                    <div class="category-content">
                        <h4 class="category-name">
                            <a href="shop-banner-sidebar.html">Apple</a>
                        </h4>
                    </div>
                </div>
            </div>
            <div class="swiper-pagination"></div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "MostPopularBrand"
    }
</script>

<style scoped>

</style>