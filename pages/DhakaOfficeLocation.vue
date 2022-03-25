<template>
    <div class="pt-20">

        <!-- Navbar -->

        <div>
            <NavigationBar />
        </div>

        <!-- Dhaka Office Location Section -->

        <div>
            <DhakaOffice />
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
import DhakaOffice from "../components/AboutUsPage/DhakaOffice.vue";
import LetsTalkSection from "../components/LetsTalkSection.vue";
import NavigationBar from "../components/NavigationBar.vue";
import Footer from "../components/Footer.vue";

export default { components: { DhakaOffice, LetsTalkSection, NavigationBar, Footer } }



</script>