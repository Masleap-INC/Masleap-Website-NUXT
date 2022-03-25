<template>
    <div class="pt-20">

        <!-- Navbar -->

        <div>
            <NavigationBar />
        </div>

        <!-- Dhaka Office Location Section -->

        <div>
            <MarylandOffice />
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
import LetsTalkSection from "../components/LetsTalkSection.vue";
import NavigationBar from "../components/NavigationBar.vue";
import Footer from "../components/Footer.vue";
import MarylandOffice from "../components/AboutUsPage/MarylandOffice.vue";

export default { components: { LetsTalkSection, NavigationBar, Footer, MarylandOffice } }



</script>