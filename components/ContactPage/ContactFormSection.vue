<template>

    <section>

        <!-- Contact Form -->

        <div class="mx-auto px-5">

            <form class="lg:w-3/6 md:w-2/3 sm:w-5/6 mx-auto py-20" name="contact" action="/" method="POST" data-netlify="true">

                <input type="hidden" name="form-name" value="contact">

                <!-- Name Label & Input -->
                <div class="mx-auto my-5">
                    <div class="mb-5">
                        <label class=" font-semibold text-2xl" for="name">Name</label>
                    </div>

                    <div class="mx-auto">
                        <input class="w-full h-14 border-2 border-cyan-500 rounded-lg px-5 text-black" type="text" name="name" required>
                    </div>
                </div>

                <!-- Company Label & Input -->
                <div class="mx-auto my-5">
                    <div class="mb-5">
                        <label class=" font-semibold text-2xl" for="company">Company</label>
                    </div>

                    <div class="mx-auto">
                        <input class="w-full h-14 border-2 border-cyan-500 rounded-lg px-5 text-black" type="text" name="company">
                    </div>
                </div>

                <!-- Email Label & Input -->
                <div class="mx-auto my-5">
                    <div class="mb-5">
                        <label class=" font-semibold text-2xl" for="email">Email</label>
                    </div>

                    <div class="mx-auto">
                        <input class="w-full h-14 border-2 border-cyan-500 rounded-lg px-5 text-black" type="email" name="email" required>
                    </div>
                </div>

                <!-- Phone Label & Input -->
                <div class="mx-auto my-5">
                    <div class="mb-5">
                        <label class=" font-semibold text-2xl" for="phone">Phone</label>
                    </div>

                    <div class="mx-auto">
                        <input class="w-full h-14 border-2 border-cyan-500 rounded-lg px-5 text-black" type="number" name="phone" required>
                    </div>
                </div>

                <!-- Message Label & Input -->
                <div class="mx-auto my-5">
                    <div class="mb-5">
                        <label class=" font-semibold text-2xl" for="message">Tell us a little about your project</label>
                    </div>

                    <div class="mx-auto">
                        <textarea class="w-full h-32 border-2 border-cyan-500 rounded-lg px-5 text-black" name="message" required></textarea>
                    </div>
                </div>

                <!-- Submit Button -->

                <div class="my-5 w-fit mx-auto">

                    <button class=" border-2 border-cyan-500 text-cyan-500 text-xl font-semibold px-5 py-3 rounded-lg hover:bg-gradient-to-r from-cyan-500 to-blue-500 hover:text-white hover:ease-in duration-300" type="submit">Submit</button>

                </div>
                
            </form>

        </div>

    </section>

</template>