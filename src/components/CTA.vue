<script setup>
</script>

<template>

    <div class="relative bg-[#1c2d5c] h-64">
        <!-- Mobile -->
        <img src="../assets/bg-boost-mobile.svg" class="absolute inset-0 w-full h-full object-cover md:hidden">
        <!-- Tablet -->
        <img src="../assets/bg-shorten-desktop.svg"
            class="absolute inset-0 w-full h-full object-cover hidden md:block lg:hidden">
        <!-- Desktop -->
        <img src="../assets/bg-boost-desktop.svg" class="absolute inset-0 w-full h-full object-cover hidden lg:block">
        <!-- content -->
        <div class="relative z-10 flex flex-col items-center justify-center h-full text-white text-center">
            <h1 class="text-3xl font-bold">
                Boost your links today
            </h1>
            <button class="mt-5 bg-[#21c9ef] px-6 py-3 rounded-full">
                Get Started
            </button>
        </div>
    </div>

</template>

<style scoped></style>