<script setup>

</script>

<template>
    <!-- nav container -->
    <nav class="mt-10 lg:w-[80%] w-[90%] m-auto">
        <!-- flex container for all item -->
         <div>
            <!-- flex container for logo/menu -->
             <div class="flex lg:justify-start items-center justify-between gap-10">
                <!-- logo -->
                  <img src="../assets/logo.svg" alt="" class="h-8 w-auto mr-10">
                 <!-- left menu -->
                  <button class="lg:hidden text-2xl text-gray-400">☰</button>
                  <div class="hidden lg:flex items-center gap-10 font-bold">
                    <a href="">Features</a>
                    <a href="">Pricing</a>
                    <a href="">Resources</a>
                  </div>
                  <!-- right menu -->
                  <div class="hidden ml-auto lg:flex items-center gap-10 font-bold">
                    <a href="">Login</a>
                    <a href="" class="bg-[#21c9ef] px-5 py-2 rounded-3xl text-white">Sign Up</a>
                  </div>
             </div>
         </div>
    </nav>

</template>

<style scoped>

</style>