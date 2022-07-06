<template>

    <div>

        <div class="lg:grid lg:grid-cols-3 lg:w-2/3 md:w-5/6 sm:w-5/6 mx-auto my-10">

            <!-- Column 1 -->

            <div class="lg:col-span-1 bg-gradient-to-r from-cyan-500 to-blue-500 w-full">

                <div class="w-fit mx-auto">
                    <h2 class="text-white lg:text-4xl md:text-3xl sm:text-2xl font-bold px-5 py-20">Contact us at your convenience so that demand meets productivity</h2>
                </div>


            </div>

            <!-- Column 2 -->

            <div class="bg-[url('~/assets/tech-bg-3.png')] bg-scroll bg-center bg-no-repeat h-full w-full lg:col-span-2 ">

                

                <div class="w-fit mx-auto py-32">

                     <NuxtLink to="/Contact">
                        <button class=" text-3xl text-white px-5 py-3 font-bold bg-gradient-to-r from-cyan-500 to-blue-500 rounded-xl hover:scale-125 duration-300">Book a free Call</button>
                    </NuxtLink>

                </div>                               

                

            </div>

        </div>

    </div>

</template>