<template>

    <nav class="fixed top-0 w-full bg-gradient-to-r from-cyan-500 to-blue-500 py-3 z-30">
        <div class="flex items-center justify-between">

            <!-- Brand -->

            <div class=" w-auto h-auto mx-auto px-5">
                <img class=" w-14 h-auto mx-2 inline-block" src="../assets/masleap-header-logo.png" alt="">
                <h3 class="text-white text-xl self-center font-bold antialiased inline-block"> Masleap INC</h3>
            </div>

            <!-- Navigation Menu -->

            <div class="w-auto mx-auto px-5 hidden lg:flex">
                <ul class="inline-block text-white text-lg font-semibold w-auto">

                    <li class="inline-block mx-5 hover:scale-110 duration-300"><NuxtLink to="/">Home</NuxtLink></li>

                    <li class="inline-block mx-5 hover:scale-110 duration-300"><NuxtLink to="/Services">Services</NuxtLink></li>

                    <li class="inline-block mx-5 hover:scale-110 duration-300"><NuxtLink to="/AboutUs">About Us</NuxtLink></li>

                    <li class="inline-block mx-5 hover:scale-110 duration-300"><NuxtLink to="/OurWorks">Our Works</NuxtLink></li>

                    <li class="inline-block mx-5 hover:scale-110 duration-300"><NuxtLink to="/Careers">Careers</NuxtLink></li>
                </ul>
            </div>

            <div class="w-auto mx-auto inline-block px-5 lg:flex md:hidden sm:hidden">
                <NuxtLink to="/Contact">
                    <button class=" text-white text-xl rounded border-2 border-white hover:bg-white hover:text-cyan-500 duration-300 px-3 py-2 inline-block">Let's Talk</button>
                </NuxtLink>
                
            </div>

            <!-- Hamburger Button -->

            <div class="mx-5 hidden lg:hidden md:flex sm:flex" >
                <button :class="open ? ' rotate-180 duration-300' : 'duration-300'" class="mx-auto px-5" type="button" @click="toggle">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-auto w-10 stroke-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" />
                    </svg>
                </button>
            </div>

            
        </div>

        <!-- Mobile Menu -->

        <div :class="open ? 'block': 'hidden'" class="w-full mx-auto lg:hidden" >
        
            <ul class="bg-gradient-to-r from-cyan-500 to-blue-500 text-white text-center text-2xl font-semibold py-5">
                
                <li class="py-5 hover:translate-x-5 duration-300 block"> <NuxtLink to="/">Home</NuxtLink> </li>

                <li class="py-5 hover:translate-x-5 duration-300 block"> <NuxtLink to="/Services">Services</NuxtLink> </li>

                <li class="py-5 hover:translate-x-5 duration-300 block"> <NuxtLink to="/AboutUs">About Us</NuxtLink> </li>

                <li class="py-5 hover:translate-x-5 duration-300 block"> <NuxtLink to="/OurWorks">Our Works</NuxtLink> </li>

                <li class="py-5 hover:translate-x-5 duration-300 block"> <NuxtLink to="/Careers">Careers</NuxtLink> </li>

            </ul>

            <div class="w-full mx-auto block my-5">
                
                <NuxtLink to="/Contact">
                    <button class=" text-white text-xl mx-auto rounded border-2 border-white px-3 py-2 hover:bg-white hover:text-cyan-500 duration-300 block">Let's Talk</button>
                </NuxtLink>
                
            </div>
        
        </div>

        
    </nav>

</template>


<script>


    export default {

        
        name: "NavigationBar",
        // el: '#app',

        data() {
            return{

                open: false,

            }
            
        },

        methods: {
            toggle(){
                this.open = !this.open;
            }
        }
   

    }
    

</script>