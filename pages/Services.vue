<template>
    <div class="pt-20">
        <!-- Navbar -->

        <div>
            <NavigationBar />
        </div>

        <!-- Heading -->

        <div>
            <ServicesHeadingSection />
        </div>

        <!-- Services -->

        <div>
            <ServiceSection1 />
        </div>

        <!-- Let's Talk -->

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
import ServicesHeadingSection from "../components/ServicesPage/ServicesHeadingSection.vue";
import ServiceSection1 from "../components/ServicesPage/ServiceSection1.vue";
import LetsTalkSection from "../components/LetsTalkSection.vue";
import Footer from "../components/Footer.vue";


export default {
    name: "Services",
    components: { NavigationBar, ServicesHeadingSection, ServiceSection1, LetsTalkSection, Footer }
}

</script>