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

                        <span class=" grid grid-cols-3 w-1/2 mx-auto mt-5">
                            <div class="inline-block w-7 h-auto mx-auto"><img src="https://img.icons8.com/ios-glyphs/30/ffffff/facebook-f.png"/></div>
                            <div class="inline-block w-7 h-auto mx-auto"><img src="https://img.icons8.com/ios-glyphs/30/ffffff/twitter--v1.png"/></div>
                            <div class="inline-block w-7 h-auto mx-auto"><img src="https://img.icons8.com/ios-filled/50/ffffff/linkedin-2--v1.png"/></div>
                        </span>

                        <span class="block text-white mx-auto mt-5">contact@masleap.io</span>

                        <span class="block text-white mx-auto mt-2">+1 (301) 244-0147</span>
                    </h2>
                </div>

                <!-- Column 2 -->

                <div class="py-10 mx-auto">

                    <h2 class=" text-center text-lg text-white">

                        <span class="block text-3xl mb-10 font-semibold">Site Links</span>

                        <span class="block mt-5"><router-link to="/">Services</router-link></span>

                        <span class="block mt-5"><router-link to="/">About Us</router-link></span>

                        <span class="block mt-5"><router-link to="/">Our Works</router-link></span>

                        <span class="block mt-5"><router-link to="/">Careers</router-link></span>


                    </h2>

                </div>

                <!-- Column 3 -->

                <div class="py-10 mx-auto">

                    <h2 class=" text-center text-lg text-white">

                        <span class="block text-3xl mb-10 font-semibold">Locations</span>

                        <span class="block mt-5"><router-link to="/">Maryland</router-link></span>

                        <span class="block mt-5"><router-link to="/">Dhaka</router-link></span>

                    </h2>

                </div>

                <!-- Column 4 -->

                <div class="mx-auto py-10">

                    <h2 class="block mx-auto text-center text-white text-3xl mb-10 font-semibold">Get Our Newsletter</h2>
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
        name: "Footer",
    }

</script>