<template>
  <div class="home">
    <HeaderShyna />
    <HeroSection />
    <ProductSection />
    <InstaShyana />
    <PatnerShyna />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from "@/components/HelloWorld.vue";
import HeaderShyna from "@/components/HeaderShyna.vue";
import HeroSection from "@/components/HeroSection.vue";
import ProductSection from "@/components/ProductSection.vue";
import InstaShyana from "@/components/InstaShyana.vue";
import PatnerShyna from "@/components/PatnerShyna.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    HeaderShyna,
    HeroSection,
    ProductSection,
    InstaShyana,
    PatnerShyna,
    Footer
  }
};
</script>
