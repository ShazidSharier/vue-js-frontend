<template>
    <h2 class="title text-left appear-animate mb-5">Trending Products</h2>
    <div class="row banner-product-wrapper appear-animate mb-10">
        <div class="col-lg-9 mb-4 mb-lg-0">
            <div class="banner banner-fixed br-sm appear-animate">
                <figure>
                    <img src="assets/images/demos/demo3/banners/2.jpg" alt="banner" width="925" height="298"
                         style="background-color: #ECEDE8;" />
                </figure>
                <div class="banner-content y-50">
                    <h5 class="banner-subtitle text-primary font-weight-bold text-uppercase ls-25">Season
                        Lifestyle</h5>
                    <h3 class="banner-title font-weight-bold text-uppercase ls-25">
                        Wonderful Long Weekend<br><strong class="text-capitalize">Women's Style</strong>
                    </h3>
                    <a href="shop-banner-sidebar.html" class="btn btn-dark btn-outline btn-rounded">Shop Now</a>
                </div>
            </div>
            <div class="row swiper-theme mt-4" data-swiper-options="{
                              'spaceBetween': 20,
                              'slidesPerView': 2,
                              'breakpoints': {
                                  '576': {
                                      'slidesPerView': 3
                                  },
                                  '768': {
                                      'slidesPerView': 4
                                  }
                              }
                          }">
                <div class="swiper-wrapper row cols-md-4 cols-sm-3 cols-2">
                    <div class="swiper-slide product-wrap" v-for="(product, key) in products" :key="key">
                        <div class="product product-simple text-center">
                            <figure class="product-media">
                                <a href="">
                                    <img :src="product.image" class="image-height" alt="Product"
                                         width="330" height="338" />
                                    <img src="assets/images/demos/demo3/products/2-1-2.jpg" alt="Product"
                                         width="330" height="338" />
                                </a>
                                <div class="product-action-vertical">
                                    <a href="#" class="btn-product-icon btn-wishlist w-icon-heart"
                                       title="Add to wishlist"></a>
                                    <a href="#" class="btn-product-icon btn-compare w-icon-compare"
                                       title="Add to Compare"></a>
                                </div>
                                <div class="product-action">
                                    <a href="#" class="btn-product btn-quickview" title="Quick View">Quick
                                        View</a>
                                </div>
                            </figure>
                            <div class="product-details">
                                <h4 class="product-name"><a href="product-default.html">{{product.name}}</a>
                                </h4>
                                <div class="ratings-container">
                                    <div class="ratings-full">
                                        <span class="ratings" style="width: 100%;"></span>
                                        <span class="tooltiptext tooltip-top"></span>
                                    </div>
                                    <a href="product-default.html" class="rating-reviews">(3 reviews)</a>
                                </div>
                                <div class="product-pa-wrapper">
                                    <div class="product-price">
                                        <ins class="new-price">TK. {{product.selling_price}}</ins>
                                    </div>
                                    <div class="product-action">
                                        <a href="#"
                                           class="btn-cart btn-product btn btn-icon-right btn-link btn-underline">Add
                                            To Cart</a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="col-lg-3">
            <div class="widget widget-products widget-products-bordered h-100">
                <div class="widget-body br-sm pb-2 h-100">
                    <h4 class="title-sm title-underline font-weight-bolder ls-normal mb-2">Recommend</h4>
                    <div class="swiper">
                        <div class="swiper-container swiper-theme nav-top" data-swiper-options="{
                                          'slidesPerView': 1,
                                          'spaceBetween': 20,
                                          'breakpoints': {
                                              '576': {
                                                  'slidesPerView': 2
                                              },
                                              '992': {
                                                  'slidesPerView': 1
                                              }
                                          }
                                      }">
                            <div class="swiper-wrapper row cols-lg-1 cols-md-3">
                                <div class="swiper-slide product-widget-wrap">
                                    <div class="product product-widget bb-no">
                                        <figure class="product-media">
                                            <a href="product-default.html">
                                                <img src="assets/images/demos/demo3/products/3-1.jpg" alt="Product"
                                                     width="105" height="118" />
                                            </a>
                                        </figure>
                                        <div class="product-details">
                                            <h4 class="product-name">
                                                <a href="product-default.html">T-Shirt</a>
                                            </h4>
                                            <div class="ratings-container">
                                                <div class="ratings-full">
                                                    <span class="ratings" style="width: 80%;"></span>
                                                    <span class="tooltiptext tooltip-top"></span>
                                                </div>
                                            </div>
                                            <div class="product-price">
                                                <ins class="new-price">$20.00</ins>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="product product-widget bb-no">
                                        <figure class="product-media">
                                            <a href="product-default.html">
                                                <img src="assets/images/demos/demo3/products/3-2.jpg" alt="Product"
                                                     width="105" height="118" />
                                            </a>
                                        </figure>
                                        <div class="product-details">
                                            <h4 class="product-name">
                                                <a href="product-default.html">Best Pedestrian Bag</a>
                                            </h4>
                                            <div class="ratings-container">
                                                <div class="ratings-full">
                                                    <span class="ratings" style="width: 80%;"></span>
                                                    <span class="tooltiptext tooltip-top"></span>
                                                </div>
                                            </div>
                                            <div class="product-price">
                                                <ins class="new-price">$35.88</ins>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="product product-widget bb-no">
                                        <figure class="product-media">
                                            <a href="product-default.html">
                                                <img src="assets/images/demos/demo3/products/3-3.jpg" alt="Product"
                                                     width="105" height="118" />
                                            </a>
                                        </figure>
                                        <div class="product-details">
                                            <h4 class="product-name">
                                                <a href="product-default.html">Fashionable Original Coat</a>
                                            </h4>
                                            <div class="ratings-container">
                                                <div class="ratings-full">
                                                    <span class="ratings" style="width: 60%;"></span>
                                                    <span class="tooltiptext tooltip-top"></span>
                                                </div>
                                            </div>
                                            <div class="product-price">
                                                <ins class="new-price">$89.00</ins>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="product product-widget">
                                        <figure class="product-media">
                                            <a href="product-default.html">
                                                <img src="assets/images/demos/demo3/products/3-4.jpg" alt="Product"
                                                     width="105" height="118" />
                                            </a>
                                        </figure>
                                        <div class="product-details">
                                            <h4 class="product-name">
                                                <a href="product-default.html">Classic Hat</a>
                                            </h4>
                                            <div class="ratings-container">
                                                <div class="ratings-full">
                                                    <span class="ratings" style="width: 60%;"></span>
                                                    <span class="tooltiptext tooltip-top"></span>
                                                </div>
                                            </div>
                                            <div class="product-price">
                                                <ins class="new-price">$23.00</ins>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="swiper-slide product-widget-wrap">
                                    <div class="product product-widget bb-no">
                                        <figure class="product-media">
                                            <a href="product-default.html">
                                                <img src="assets/images/demos/demo3/products/3-5.jpg" alt="Product"
                                                     width="105" height="118" />
                                            </a>
                                        </figure>
                                        <div class="product-details">
                                            <h4 class="product-name">
                                                <a href="product-default.html">Smart Watch</a>
                                            </h4>
                                            <div class="ratings-container">
                                                <div class="ratings-full">
                                                    <span class="ratings" style="width: 100%;"></span>
                                                    <span class="tooltiptext tooltip-top"></span>
                                                </div>
                                            </div>
                                            <div class="product-price">
                                                <ins class="new-price">$230.95</ins>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="product product-widget bb-no">
                                        <figure class="product-media">
                                            <a href="product-default.html">
                                                <img src="assets/images/demos/demo3/products/3-6.jpg" alt="Product"
                                                     width="105" height="118" />
                                            </a>
                                        </figure>
                                        <div class="product-details">
                                            <h4 class="product-name">
                                                <a href="product-default.html">Women's Comforter</a>
                                            </h4>
                                            <div class="ratings-container">
                                                <div class="ratings-full">
                                                    <span class="ratings" style="width: 100%;"></span>
                                                    <span class="tooltiptext tooltip-top"></span>
                                                </div>
                                            </div>
                                            <div class="product-price">
                                                <ins class="new-price">$24.00</ins>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="product product-widget bb-no">
                                        <figure class="product-media">
                                            <a href="product-default.html">
                                                <img src="assets/images/demos/demo3/products/3-7.jpg" alt="Product"
                                                     width="105" height="118" />
                                            </a>
                                        </figure>
                                        <div class="product-details">
                                            <h4 class="product-name">
                                                <a href="product-default.html">Fashionable Leather Satchel</a>
                                            </h4>
                                            <div class="ratings-container">
                                                <div class="ratings-full">
                                                    <span class="ratings" style="width: 100%;"></span>
                                                    <span class="tooltiptext tooltip-top"></span>
                                                </div>
                                            </div>
                                            <div class="product-price">
                                                <ins class="new-price">$25.68</ins>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="product product-widget">
                                        <figure class="product-media">
                                            <a href="product-default.html">
                                                <img src="assets/images/demos/demo3/products/3-8.jpg" alt="Product"
                                                     width="105" height="118" />
                                            </a>
                                        </figure>
                                        <div class="product-details">
                                            <h4 class="product-name"><a href="product-default.html">Gold Watch</a>
                                            </h4>
                                            <div class="ratings-container">
                                                <div class="ratings-full">
                                                    <span class="ratings" style="width: 100%;"></span>
                                                    <span class="tooltiptext tooltip-top"></span>
                                                </div>
                                            </div>
                                            <div class="product-price">
                                                <ins class="new-price">$189.90</ins>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <button class="swiper-button-next"></button>
                            <button class="swiper-button-prev"></button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import axios from "axios";
    export default {
        name: "TrendingProducts",
        data() {
            return {
                products:[],
            }
        },
        created() {
            this.getAllProduct();
        },

        methods: {
            getAllProduct()
            {
                axios.get("http://localhost/ecom-final-11/public/api/get-all-trending-product").then((response) => {
                    //console.log(response.data);
                    this.products = response.data;
                });
            }
        }
    }
</script>

<style scoped>
.image-height
{
    height:250px;
}
</style>