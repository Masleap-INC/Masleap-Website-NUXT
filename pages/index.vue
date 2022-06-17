<template>
  
  <div class="pt-20">

    <!-- Navbar -->

    <div>
      <NavigationBar />
    </div>

    <!-- Hero Section -->

    <div>
      <HeroSection />
    </div>

    <!-- Section 2 -->

    <div>
      <HomeSection2 />
    </div>

    <!-- Section 3 -->

    <div>
      <HomeSection3 />
    </div>

    <!-- Section 4 -->

    <div>
      <HomeSection4 />
    </div>

    <!-- Let's Talk Section -->

    <div>
      <LetsTalkSection />
    </div>

    <!-- Footer -->

    <div>
      <Footer />
    </div>



  </div>

</template>

<script>
import NavigationBar from "../components/NavigationBar.vue";
import HeroSection from "../components/HomePage/HeroSection.vue";
import HomeSection2 from "../components/HomePage/HomeSection2.vue";
import HomeSection3 from "../components/HomePage/HomeSection3.vue";
import HomeSection4 from "../components/HomePage/HomeSection4.vue";
import LetsTalkSection from "../components/LetsTalkSection.vue";
import Footer from "../components/Footer.vue";
export default {
    name: "IndexPage",
    components: { NavigationBar, HeroSection, HomeSection2, HomeSection3, HomeSection4, Footer, LetsTalkSection }
}
</script>
