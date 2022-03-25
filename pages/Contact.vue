<template>

    <div class="pt-20">

        <!-- Navbar -->

        <div>
            <NavigationBar />
        </div>

         <!-- Heading Section -->

        <div>
            <ContactUsHeadingSection />            
        </div>

        <!-- Contact Form Section -->

        <div>
            <ContactFormSection />
        </div>

        <!-- Footer -->

        <div>
            <Footer />
        </div>
    </div>

</template>

<script>
import NavigationBar from "../components/NavigationBar.vue";
import ContactUsHeadingSection from "../components/ContactPage/ContactUsHeadingSection.vue";
import ContactFormSection from "../components/ContactPage/ContactFormSection.vue";
import Footer from "../components/Footer.vue";


    export default {
    name: "Contact",
    components: { NavigationBar, ContactUsHeadingSection, ContactFormSection, Footer }
}

</script>