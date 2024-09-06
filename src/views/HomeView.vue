<template>
  <div class="home">

    <div class="page-wrapper">
        <!-- Start of Header -->
        <!-- End of Header -->
        <!-- Start of Main -->
      <div class="main">
          <div class="container">
            <IntroWrapper/>
            <!-- End of Intro Wrapper -->
            <BoxWrapper/>
            <!-- End of Iocn Box Wrapper -->
            <MostPopularBrand/>
            <!-- End of Category Wrapper -->
            <DealsWrapper/>
            <!-- End of Deals Wrapper -->
            <TopWeeklyVendor/>
            <!-- End of Swiper Container -->
            <TrendingProducts/>
            <!-- Banner Product Wrapper -->
            <BannerWrapperOne/>
            <!-- End of Category Accessories -->
            <ConsumerElectric/>
            <!-- Banner Product Wrapper -->
            <HomeKitchen/>
            <!-- Banner Product Wrapper -->
          </div>
          <!-- End of Container -->
          <GreySection/>
        </div>
        <!-- End of Main -->
        <!-- Start of Footer -->
        <!-- End of Footer -->
    </div>
    <!-- End of Page-wrapper -->
    <!-- Start of Sticky Footer -->
    <!-- End of Sticky Footer -->
    <!-- Start of Scroll Top -->
    <a id="scroll-top" class="scroll-top" href="#top" title="Top" role="button"> <i class="w-icon-angle-up"></i> <svg version="1.1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 70 70"> <circle id="progress-indicator" fill="transparent" stroke="#000000" stroke-miterlimit="10" cx="35" cy="35" r="34" style="stroke-dasharray: 16.4198, 400;"></circle> </svg> </a>
    <!-- End of Scroll Top -->
    <!-- Start of Mobile Menu -->
    <MobilemenuWrapper/>
    <!-- End of Mobile Menu -->
    <!-- Start of Newsletter popup -->
    <NewsletterPopup/>
    <!-- End of Newsletter popup -->
    <!-- Start of Quick View -->
    <SingleProductPopup/>
    <!-- End of Quick view -->

  </div>
</template>

<script>
  import IntroWrapper from "@/components/home/IntroWrapper";
  import BoxWrapper from "@/components/home/BoxWrapper";
  import MostPopularBrand from "@/components/home/MostPopularBrand";
  import DealsWrapper from "@/components/home/DealsWrapper";
  import TopWeeklyVendor from "@/components/home/TopWeeklyVendor";
  import TrendingProducts from "@/components/home/TrendingProducts";
  import BannerWrapperOne from "@/components/home/BannerWrapperOne";
  import ConsumerElectric from "@/components/home/ConsumerElectric";
  import HomeKitchen from "@/components/home/HomeKitchen";
  import GreySection from "@/components/home/GreySection";
  import MobilemenuWrapper from "@/components/home/MobilemenuWrapper";
  import NewsletterPopup from "@/components/home/NewsletterPopup";
  import SingleProductPopup from "@/components/home/SingleProductPopup";
export default {
  name: 'HomeView',
  components: {IntroWrapper,BoxWrapper,MostPopularBrand,DealsWrapper,TopWeeklyVendor,TrendingProducts,
    BannerWrapperOne,ConsumerElectric,HomeKitchen,GreySection,MobilemenuWrapper,NewsletterPopup,SingleProductPopup}
}
</script>

<style>

</style>