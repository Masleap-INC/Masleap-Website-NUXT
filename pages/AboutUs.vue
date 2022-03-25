<template>
    <div class="pt-20">

        <!-- Navbar -->

        <div>
            <NavigationBar />
        </div>

        <!-- Heading Section -->

        <div>
            <AboutUsHeadingSection />
        </div>

        <!-- About us description Section -->

        <div>
            <AboutUsSection1 />
        </div>

        <!-- Our Office Heading -->

        <div>
            <OurOfficeHeading />
        </div>

        <!-- Maryland office Section -->

        <div>
            <MarylandOffice />
        </div>

        <!-- Dhaka Office Section -->

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
import NavigationBar from "../components/NavigationBar.vue";
import AboutUsHeadingSection from "../components/AboutUsPage/AboutUsHeadingSection.vue";
import AboutUsSection1 from "../components/AboutUsPage/AboutUsSection1.vue";
import OurOfficeHeading from "../components/AboutUsPage/OurOfficeHeading.vue";
import MarylandOffice from "../components/AboutUsPage/MarylandOffice.vue";
import DhakaOffice from "../components/AboutUsPage/DhakaOffice.vue";
import LetsTalkSection from "../components/LetsTalkSection.vue";
import Footer from "../components/Footer.vue";


export default {
    name: "AboutUs",
    components: { NavigationBar, AboutUsHeadingSection, AboutUsSection1, OurOfficeHeading, MarylandOffice, DhakaOffice, LetsTalkSection, Footer }
}

</script>