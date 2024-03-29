<template>
  
<!-- Section 1 -->
<section class="py-16 bg-white md:py-20 lg:py-24">
    <div class="max-w-5xl px-12 mx-auto xl:px-0">

        <h2 class="text-3xl font-black md:text-4xl lg:text-6xl xl:text-7xl">Frequently Asked Questions</h2>
        <p class="mt-4 text-xl font-thin text-gray-700 lg:text-2xl">Here are some of the most common frequently asked questions</p>

        <div class="relative mt-12 space-y-3">

            <!-- Question 1 -->
            <div x-data="{ show: false }" class="relative overflow-hidden border-b border-gray-100 select-none">
                <h4 @click="show=!show" class="flex items-center justify-between px-2 text-lg font-medium text-gray-700 cursor-pointer sm:text-xl md:text-2xl py-7 hover:text-gray-900">
                    <span>How Do I Integrate Your Service with My App?</span>
                    <svg class="w-6 h-6 mr-2 transition-all duration-200 ease-out transform rotate-0" :class="{ '-rotate-180' : show }" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                </h4>
                <p class="px-2 pt-0 -mt-2 text-gray-400 sm:text-lg py-7" x-transition:enter="transition-all ease-out duration-300" x-transition:enter-start="opacity-0 transform -translate-y-4" x-transition:enter-end="opacity-100 transform -translate-y-0" x-transition:leave="transition-all ease-in duration-300" x-transition:leave-start="opacity-100 transform -translate-y-0" x-transition:leave-end="opacity-0 transform -translate-y-4" x-show="show" x-cloak="">There are multiple ways you can integrate with your app. The most common way is to utilize our API. For instructions on all integrations, visit our integrations page here.</p>
            </div>

            <!-- Question 2 -->
            <div x-data="{ show: false }" class="relative overflow-hidden border-b border-gray-100 select-none">
                <h4 @click="show=!show" class="flex items-center justify-between px-2 text-lg font-medium text-gray-700 cursor-pointer sm:text-xl md:text-2xl py-7 hover:text-gray-900">
                    <span>How Many API Calls Do I Get For Free?</span>
                    <svg class="w-6 h-6 mr-2 transition-all duration-200 ease-out transform rotate-0" :class="{ '-rotate-180' : show }" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                </h4>
                <p class="px-2 pt-0 -mt-2 text-gray-400 sm:text-lg py-7" x-transition:enter="transition-all ease-out duration-300" x-transition:enter-start="opacity-0 transform -translate-y-4" x-transition:enter-end="opacity-100 transform -translate-y-0" x-transition:leave="transition-all ease-in duration-300" x-transition:leave-start="opacity-100 transform -translate-y-0" x-transition:leave-end="opacity-0 transform -translate-y-4" x-show="show" x-cloak="">The free plan will give you 2,000 free API calls. At anytime, if you wish to <a href="#_" class="font-medium text-purple-600 underline">upgrade to a paid plan</a>, you can eaisily increase that amount.</p>
            </div>

            <!-- Question 3 -->
            <div x-data="{ show: false }" class="relative overflow-hidden border-b border-gray-100 select-none">
                <h4 @click="show=!show" class="flex items-center justify-between px-2 text-lg font-medium text-gray-700 cursor-pointer sm:text-xl md:text-2xl py-7 hover:text-gray-900">
                    <span>Where Can I Learn More About The API?</span>
                    <svg class="w-6 h-6 mr-2 transition-all duration-200 ease-out transform rotate-0" :class="{ '-rotate-180' : show }" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                </h4>
                <p class="px-2 pt-0 -mt-2 text-gray-400 sm:text-lg py-7" x-transition:enter="transition-all ease-out duration-300" x-transition:enter-start="opacity-0 transform -translate-y-4" x-transition:enter-end="opacity-100 transform -translate-y-0" x-transition:leave="transition-all ease-in duration-300" x-transition:leave-start="opacity-100 transform -translate-y-0" x-transition:leave-end="opacity-0 transform -translate-y-4" x-show="show" x-cloak="">You can learn more about using our API by visiting our <a href="#_" class="font-medium text-purple-600 underline">Academy page</a> which contains screencasts that will teach you the ins-and-outs of using the API. You may also visit the <a href="#_" class="font-medium text-purple-600 underline">developer docs</a> to learn more.</p>
            </div>

            <!-- Question 4 -->
            <div x-data="{ show: false }" class="relative overflow-hidden border-b border-gray-100 select-none">
                <h4 @click="show=!show" class="flex items-center justify-between px-2 text-lg font-medium text-gray-700 cursor-pointer sm:text-xl md:text-2xl py-7 hover:text-gray-900">
                    <span>Do You Offer Any Developer SDK's?</span>
                    <svg class="w-6 h-6 mr-2 transition-all duration-200 ease-out transform rotate-0" :class="{ '-rotate-180' : show }" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                </h4>
                <p class="px-2 pt-0 -mt-2 text-gray-400 sm:text-lg py-7" x-transition:enter="transition-all ease-out duration-300" x-transition:enter-start="opacity-0 transform -translate-y-4" x-transition:enter-end="opacity-100 transform -translate-y-0" x-transition:leave="transition-all ease-in duration-300" x-transition:leave-start="opacity-100 transform -translate-y-0" x-transition:leave-end="opacity-0 transform -translate-y-4" x-show="show" x-cloak="">Absolutely, we have an SDK for most of the popular languages and frameworks. Be sure to visit our <a href="#_" class="font-medium text-purple-600 underline">list of SDK's</a> to learn how you can build on top of our service.</p>
            </div>

            <!-- Question 5 -->
            <div x-data="{ show: false }" class="relative overflow-hidden border-b border-gray-100 select-none">
                <h4 @click="show=!show" class="flex items-center justify-between px-2 text-lg font-medium text-gray-700 cursor-pointer sm:text-xl md:text-2xl py-7 hover:text-gray-900">
                    <span>Do You Have An Affiliate Program?</span>
                    <svg class="w-6 h-6 mr-2 transition-all duration-200 ease-out transform rotate-0" :class="{ '-rotate-180' : show }" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
                </h4>
                <p class="px-2 pt-0 -mt-2 text-gray-400 sm:text-lg py-7" x-transition:enter="transition-all ease-out duration-300" x-transition:enter-start="opacity-0 transform -translate-y-4" x-transition:enter-end="opacity-100 transform -translate-y-0" x-transition:leave="transition-all ease-in duration-300" x-transition:leave-start="opacity-100 transform -translate-y-0" x-transition:leave-end="opacity-0 transform -translate-y-4" x-show="show" x-cloak="">Yes. We are utilizing <a href="https://paddle.com" class="font-medium text-purple-600 underline">paddle</a>, which has a fully functional affiliate program. <a href="#_" class="font-medium text-purple-600 underline">Click here</a> to signup as an affiliate.</p>
            </div>

        </div>

    </div>
</section>

</template>