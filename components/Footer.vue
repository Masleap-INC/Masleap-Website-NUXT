<template>
    <section>

        <div class=" bg-gradient-to-r from-cyan-500 to-blue-500 bottom-0">

            <!-- Wave section -->

            <div class="w-full">
                <img src="../assets/White-Wave-PNG-footer.png" alt="">
            </div>

            <!-- Grid section -->


            <div class="lg:grid lg:grid-cols-4 md:grid md:grid-cols-2 pb-10 pt-10 mx-5">

                <!-- Column 1 -->

                <div class="lg:w-5/6 md:w-1/2 md:mx-auto mb-10">
                    <h2 class="justify-self-center text-center">
                        <span class="block w-2/3 mx-auto min-w-1/3 h-auto"><img class="w-32 h-auto mx-auto" src="../assets/masleap-footer-logo.png" alt=""></span>

                        <span class=" grid grid-cols-4 gap-5 w-40 mx-auto mt-5">
                            <div class="inline-block w-7 h-auto mx-auto hover:scale-125 duration-300"><a href="https://www.facebook.com/pages/category/Software-Company/105052835051779/"><img src="https://img.icons8.com/ios-glyphs/30/ffffff/facebook-f.png"/></a></div>
                            <div class="inline-block w-7 h-auto mx-auto hover:scale-125 duration-300"><a href=""><img src="https://img.icons8.com/ios-glyphs/30/ffffff/twitter--v1.png"/></a></div>
                            <div class="inline-block w-7 h-auto mx-auto hover:scale-125 duration-300"><a href="https://bd.linkedin.com/company/masleap-plc"><img src="https://img.icons8.com/ios-filled/50/ffffff/linkedin-2--v1.png"/></a></div>
                            <div class="inline-block w-7 h-auto mx-auto hover:scale-125 duration-300"><a href="https://github.com/Masleap-INC"><img src="https://img.icons8.com/ios-glyphs/30/ffffff/github.png"/></a></div>
                        </span>

                        <span class="block text-white mx-auto mt-5">contact@masleap.io</span>

                        <span class="block text-white mx-auto mt-2">+1 (301) 244-0147</span>
                    </h2>
                </div>

                <!-- Column 2 -->

                <div class="py-10 mx-auto">

                    <h2 class=" text-center text-lg text-white">

                        <span class="block text-3xl mb-10 font-semibold">SITE LINKS</span>

                        <span class="block mt-5 hover:underline"><NuxtLink to="/Services">SERVICES</NuxtLink></span>

                        <span class="block mt-5 hover:underline"><NuxtLink to="/AboutUs">ABOUT US</NuxtLink></span>

                        <span class="block mt-5 hover:underline"><NuxtLink to="/OurWorks">OUR WORKS</NuxtLink></span>

                        <!-- <span class="block mt-5"><NuxtLink to="/">CAREERS</NuxtLink></span> -->


                    </h2>

                </div>

                <!-- Column 3 -->

                <div class="py-10 mx-auto">

                    <h2 class=" text-center text-lg text-white">

                        <span class="block text-3xl mb-10 font-semibold">LOCATIONS</span>

                        <span class="block mt-5 hover:underline"><NuxtLink to="/MarylandOfficeLocation">MARYLAND</NuxtLink></span>

                        <span class="block mt-5 hover:underline"><NuxtLink to="/DhakaOfficeLocation">DHAKA</NuxtLink></span>

                    </h2>

                </div>

                <!-- Column 4 -->

                <div class="mx-auto py-10">

                    <h2 class="block mx-auto text-center text-white text-3xl mb-10 font-semibold">GET OUR NEWSLETTER</h2>
                    <form class="mx-auto " action="">

                        <input class="block w-full mx-auto bg-white p-2 rounded-lg text-left" placeholder="example@example.com" type="email">

                        <button class="block mx-auto border-2 border-white text-center text-white py-2 px-5 mt-5 rounded hover:bg-white hover:text-gray-800 hover:ease-in-out duration-700" type="submit">Sign Up</button>
                    </form>
                </div>
            </div>
        </div>

    </section>

</template>


<script>

    export default {
        name: "SiteFooter",
    }

</script>