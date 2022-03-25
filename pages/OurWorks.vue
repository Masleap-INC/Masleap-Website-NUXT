<template>
    <div class="pt-20">

        <!-- Navbar -->

        <div>
            <NavigationBar />
        </div>

        <!-- Heading Section -->

        <div>
            <OurWorksHeadingSection />
        </div>

        <!-- Our Works Section -->

        <div>
            <OurWorksSection />
        </div>

        <!-- Let's talk Section  -->

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
import Footer from "../components/Footer.vue";
import OurWorksHeadingSection from "../components/OurWorksPage/OurWorksHeadingSection.vue";
import OurWorksSection from "../components/OurWorksPage/OurWorksSection.vue";
import LetsTalkSection from "../components/LetsTalkSection.vue";


export default {
    name: "Our-Works",
    components: { NavigationBar, Footer, OurWorksHeadingSection, OurWorksSection, LetsTalkSection }
}

</script>