<template>
  
<!-- Section 1 -->
<section class="py-12 bg-purple-600 sm:py-16 md:py-20 lg:py-24 pb-28">
    <div class="max-w-6xl px-8 mx-auto lg:px-16">
        <h2 class="mb-2 text-2xl font-bold text-center text-white md:text-3xl lg:text-4xl">Frequently Asked Questions</h2>

        <div class="relative flex flex-col mt-8 mt-16 lg:flex-row">

            <!-- Left side of FAQs -->
            <div class="relative w-full space-y-3 lg:space-y-5 lg:w-1/2 lg:pr-4">
                <!-- Question 1 -->
                <div x-data="{ show: false }" class="relative px-6 py-2 overflow-hidden text-white bg-purple-700 rounded-lg select-none">
                    <h4 @click="show=!show" class="flex items-center justify-between py-4 text-base font-medium text-purple-100 cursor-pointer sm:text-lg hover:text-white">
                        <span>Where do I go to upgrade my account?</span>
                        <svg class="w-4 h-4 mr-1 transition-all duration-200 ease-out transform rotate-0" :class="{ '-rotate-180' : show }" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                    </h4>
                    <p class="px-1 pt-0 mt-1 text-purple-200 sm:text-lg py-7" x-transition:enter="transition-all ease-out duration-300" x-transition:enter-start="opacity-0 transform -translate-y-4" x-transition:enter-end="opacity-100 transform -translate-y-0" x-transition:leave="transition-all ease-out hidden duration-200" x-transition:leave-start="opacity-100 transform -translate-y-0" x-transition:leave-end="opacity-0 transform -translate-y-4" x-show="show" x-cloak="">You can upgrade your account by visiting The Pro Upgrade Page. You will also gain access to many other applications and sections of the site.</p>
                </div>

                <!-- Question 2 -->
                <div x-data="{ show: false }" class="relative px-6 py-2 overflow-hidden text-white bg-purple-700 rounded-lg select-none">
                    <h4 @click="show=!show" class="flex items-center justify-between py-4 text-base font-medium text-purple-100 cursor-pointer sm:text-lg hover:text-white">
                        <span>How do I use Tails in my project?</span>
                        <svg class="w-4 h-4 mr-1 transition-all duration-200 ease-out transform rotate-0" :class="{ '-rotate-180' : show }" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                    </h4>
                    <p class="px-1 pt-0 mt-1 text-purple-200 sm:text-lg py-7" x-transition:enter="transition-all ease-out duration-300" x-transition:enter-start="opacity-0 transform -translate-y-4" x-transition:enter-end="opacity-100 transform -translate-y-0" x-transition:leave="transition-all ease-out hidden duration-200" x-transition:leave-start="opacity-100 transform -translate-y-0" x-transition:leave-end="opacity-0 transform -translate-y-4" x-show="show" x-cloak="">Implementation in your project is very simple. You can use the exported page as a starting point, or you can copy and paste the HTML into your own page.</p>
                </div>

                <!-- Question 3 -->
                <div x-data="{ show: false }" class="relative px-6 py-2 overflow-hidden text-white bg-purple-700 rounded-lg select-none">
                    <h4 @click="show=!show" class="flex items-center justify-between py-4 text-base font-medium text-purple-100 cursor-pointer sm:text-lg hover:text-white">
                        <span>How long will I have access to Tails?</span>
                        <svg class="w-4 h-4 mr-1 transition-all duration-200 ease-out transform rotate-0" :class="{ '-rotate-180' : show }" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                    </h4>
                    <p class="px-1 pt-0 mt-1 text-purple-200 sm:text-lg py-7" x-transition:enter="transition-all ease-out duration-300" x-transition:enter-start="opacity-0 transform -translate-y-4" x-transition:enter-end="opacity-100 transform -translate-y-0" x-transition:leave="transition-all ease-out hidden duration-200" x-transition:leave-start="opacity-100 transform -translate-y-0" x-transition:leave-end="opacity-0 transform -translate-y-4" x-show="show" x-cloak="">You will have unlimited access to all your pre-built pages; however, if you want to be able to download and export your pages, you'll need a pro account. Paddle for processing payments.</p>
                </div>


                <!-- Question 4 -->
                <div x-data="{ show: false }" class="relative px-6 py-2 overflow-hidden text-white bg-purple-700 rounded-lg select-none">
                    <h4 @click="show=!show" class="flex items-center justify-between py-4 text-base font-medium text-purple-100 cursor-pointer sm:text-lg hover:text-white">
                        <span>What is the license on the pages?</span>
                        <svg class="w-4 h-4 mr-1 transition-all duration-200 ease-out transform rotate-0" :class="{ '-rotate-180' : show }" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                    </h4>
                    <p class="px-1 pt-0 mt-1 text-purple-200 sm:text-lg py-7" x-transition:enter="transition-all ease-out duration-300" x-transition:enter-start="opacity-0 transform -translate-y-4" x-transition:enter-end="opacity-100 transform -translate-y-0" x-transition:leave="transition-all ease-out hidden duration-200" x-transition:leave-start="opacity-100 transform -translate-y-0" x-transition:leave-end="opacity-0 transform -translate-y-4" x-show="show" x-cloak="">You have unlimited use to the templates used in Tails; however, you cannot re-use the templates to sell for others to use.</p>
                </div>
            </div>


            <!-- Right side of FAQs -->
            <div class="relative w-full mt-3 space-y-3 lg:mt-0 lg:space-y-5 lg:w-1/2 lg:pl-4">
                <!-- Question 1 -->
                <div x-data="{ show: false }" class="relative px-6 py-2 overflow-hidden text-white bg-purple-700 rounded-lg select-none">
                    <h4 @click="show=!show" class="flex items-center justify-between py-4 text-base font-medium text-purple-100 cursor-pointer sm:text-lg hover:text-white">
                        <span>How Many API Calls Do I Get?</span>
                        <svg class="w-4 h-4 mr-1 transition-all duration-200 ease-out transform rotate-0" :class="{ '-rotate-180' : show }" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                    </h4>
                    <p class="px-1 pt-0 mt-1 text-purple-200 sm:text-lg py-7" x-transition:enter="transition-all ease-out duration-300" x-transition:enter-start="opacity-0 transform -translate-y-4" x-transition:enter-end="opacity-100 transform -translate-y-0" x-transition:leave="transition-all ease-out hidden duration-200" x-transition:leave-start="opacity-100 transform -translate-y-0" x-transition:leave-end="opacity-0 transform -translate-y-4" x-show="show" x-cloak="">The free plan will give you 2,000 free API calls. At anytime, if you wish to <a href="#_" class="font-medium text-purple-100 underline">upgrade to a paid plan</a>, you can eaisily increase that amount.</p>
                </div>

                <!-- Question 2 -->
                <div x-data="{ show: false }" class="relative px-6 py-2 overflow-hidden text-white bg-purple-700 rounded-lg select-none">
                    <h4 @click="show=!show" class="flex items-center justify-between py-4 text-base font-medium text-purple-100 cursor-pointer sm:text-lg hover:text-white">
                        <span>Where Can I Learn More?</span>
                        <svg class="w-4 h-4 mr-1 transition-all duration-200 ease-out transform rotate-0" :class="{ '-rotate-180' : show }" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                    </h4>
                    <p class="px-1 pt-0 mt-1 text-purple-200 sm:text-lg py-7" x-transition:enter="transition-all ease-out duration-300" x-transition:enter-start="opacity-0 transform -translate-y-4" x-transition:enter-end="opacity-100 transform -translate-y-0" x-transition:leave="transition-all ease-out hidden duration-200" x-transition:leave-start="opacity-100 transform -translate-y-0" x-transition:leave-end="opacity-0 transform -translate-y-4" x-show="show" x-cloak="">You can learn more about using our API by visiting our <a href="#_" class="font-medium text-purple-100 underline">Academy page</a> which contains screencasts that will teach you the ins-and-outs of using the API. You may also visit the <a href="#_" class="font-medium text-purple-100 underline">developer docs</a> to learn more.</p>
                </div>

                <!-- Question 3 -->
                <div x-data="{ show: false }" class="relative px-6 py-2 overflow-hidden text-white bg-purple-700 rounded-lg select-none">
                    <h4 @click="show=!show" class="flex items-center justify-between py-4 text-base font-medium text-purple-100 cursor-pointer sm:text-lg hover:text-white">
                        <span>Do You Have Any SDK's?</span>
                        <svg class="w-4 h-4 mr-1 transition-all duration-200 ease-out transform rotate-0" :class="{ '-rotate-180' : show }" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                    </h4>
                    <p class="px-1 pt-0 mt-1 text-purple-200 sm:text-lg py-7" x-transition:enter="transition-all ease-out duration-300" x-transition:enter-start="opacity-0 transform -translate-y-4" x-transition:enter-end="opacity-100 transform -translate-y-0" x-transition:leave="transition-all ease-out hidden duration-200" x-transition:leave-start="opacity-100 transform -translate-y-0" x-transition:leave-end="opacity-0 transform -translate-y-4" x-show="show" x-cloak="">Absolutely, we have an SDK for most of the popular languages and frameworks. Be sure to visit our <a href="#_" class="font-medium text-purple-100 underline">list of SDK's</a> to learn how you can build on top of our service.</p>
                </div>


                <!-- Question 4 -->
                <div x-data="{ show: false }" class="relative px-6 py-2 overflow-hidden text-white bg-purple-700 rounded-lg select-none">
                    <h4 @click="show=!show" class="flex items-center justify-between py-4 text-base font-medium text-purple-100 cursor-pointer sm:text-lg hover:text-white">
                        <span>Can I Become an Affiliate?</span>
                        <svg class="w-4 h-4 mr-1 transition-all duration-200 ease-out transform rotate-0" :class="{ '-rotate-180' : show }" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                    </h4>
                    <p class="px-1 pt-0 mt-1 text-purple-200 sm:text-lg py-7" x-transition:enter="transition-all ease-out duration-300" x-transition:enter-start="opacity-0 transform -translate-y-4" x-transition:enter-end="opacity-100 transform -translate-y-0" x-transition:leave="transition-all ease-out hidden duration-200" x-transition:leave-start="opacity-100 transform -translate-y-0" x-transition:leave-end="opacity-0 transform -translate-y-4" x-show="show" x-cloak="">Yes. We are utilizing <a href="https://paddle.com" class="font-medium text-purple-100 underline">paddle</a>, which has a fully functional affiliate program. <a href="#_" class="font-medium text-purple-100 underline">Click here</a> to signup as an affiliate.</p>
                </div>
            </div>


        </div>

    </div>
</section>

</template>