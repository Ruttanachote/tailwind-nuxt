<template>

<!-- Section 1 -->
<section class="w-full bg-white" x-data="{ showMenu: false }">
    <nav class="box-border flex items-center justify-between w-full h-20 px-6 mx-auto my-0 leading-6 text-gray-800 max-w-7xl">
        <a href="#_" class="flex items-center font-medium text-gray-900 lg:w-auto title-font lg:items-center lg:justify-center md:mb-0">
            <span class="text-xl font-black leading-none text-gray-900 select-none">tails<span class="text-indigo-600">.</span></span>
        </a>
        <div class="relative flex list-none lg:block" :class="{'flex fixed': showMenu, 'hidden': !showMenu }">
            <ul class="fixed top-0 left-0 z-10 flex-wrap items-center w-full h-full p-0 mt-20 space-y-5 leading-6 text-gray-800 bg-white lg:space-x-5 lg:static lg:w-auto lg:flex lg:space-y-0 lg:mt-0">
                <li class="box-border w-full my-3 text-lg text-center lg:w-auto">
                    <a href="#_" class="text-indigo-600 no-underline bg-transparent cursor-pointer opacity-90 hover:opacity-100 hover:text-indigo-800 hover:no-underline focus-within:opacity-100 focus-within:no-underline">Product</a>
                </li>
                <li class="box-border w-full my-3 text-lg text-center lg:w-auto">
                    <a href="#_" class="text-indigo-600 no-underline bg-transparent cursor-pointer opacity-90 hover:opacity-100 hover:text-indigo-800 hover:no-underline focus-within:opacity-100 focus-within:no-underline">Features</a>
                </li>
                <li class="box-border w-full my-3 text-lg text-center lg:w-auto">
                    <a href="#_" class="text-indigo-600 no-underline bg-transparent cursor-pointer opacity-90 hover:opacity-100 hover:text-indigo-800 hover:no-underline focus-within:opacity-100 focus-within:no-underline">Support</a>
                </li>
                <li class="box-border w-full my-3 text-lg text-center lg:w-auto">
                    <a href="#_" class="text-indigo-600 no-underline bg-transparent cursor-pointer opacity-90 hover:opacity-100 hover:text-indigo-800 hover:no-underline focus-within:opacity-100 focus-within:no-underline">Pricing</a>
                </li>
                <li class="box-border w-full my-3 text-lg text-center lg:w-auto">
                    <a href="#_" target="_blank" class="inline-block px-6 py-3 text-sm font-normal leading-normal text-white no-underline align-middle bg-indigo-600 rounded-full cursor-pointer select-none lg:py-3 lg:px-8 hover:bg-indigo-700 hover:text-white focus-within:bg-indigo-700 focus-within:border-indigo-700">Try For Free </a>
                </li>
            </ul>
        </div>
        <div @click="showMenu = !showMenu" class="absolute right-0 flex flex-col items-center items-end justify-center w-10 h-10 mr-5 -mt-1 rounded-full cursor-pointer lg:hidden hover:bg-gray-100">
            <svg class="w-6 h-6 text-gray-700" x-show="!showMenu" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" viewBox="0 0 24 24" stroke="currentColor" x-cloak="">
                <path d="M4 6h16M4 12h16M4 18h16"></path>
            </svg>
            <svg class="w-6 h-6 text-gray-700" x-show="showMenu" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" x-cloak="">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
            </svg>
        </div>
    </nav>

    <div class="box-border flex-grow w-full px-10 pt-8 pb-12 mx-auto leading-6 text-gray-800 lg:pt-16 lg:pb-20 max-w-7xl">
        <div class="relative w-full px-0 mb-12 leading-6 text-left md:text-center lg:flex-grow-0 lg:flex-shrink-0">
            <h1 class="box-border mt-0 mb-4 text-3xl font-black text-gray-800 md:text-4xl lg:text-5xl xl:text-6xl">
                Super-Charge your
                <span class="font-black text-indigo-600">Business</span>.
            </h1>
            <p class="box-border mt-0 text-base font-normal text-gray-800 opacity-90 lg:text-xl xl:text-2xl">We're revolutioninzing the way people do business and we are perfecting it!</p>
            <div class="box-border text-left text-gray-800 md:text-center">
                <a class="inline-block px-6 py-3 mt-5 mb-5 text-base font-normal leading-normal text-white no-underline align-middle bg-indigo-600 rounded-full cursor-pointer select-none md:text-xl lg:py-3 lg:px-8 hover:bg-indigo-700 hover:text-white focus-within:bg-indigo-700 focus-within:border-indigo-700" href="#_"> Get Started </a>
            </div>
        </div>
        <div class="relative flex-grow-0 flex-shrink-0 w-full max-w-5xl p-0 mx-auto mt-12 overflow-hidden rounded-lg shadow-2xl lg:flex-grow-0 lg:flex-shrink-0">

            <img src="https://cdn.devdojo.com/images/november2020/mockup-page.png" class="box-border leading-6 text-gray-800 align-middle border-none">
        </div>
    </div>
</section>

</template>