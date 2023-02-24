<script setup>
import VLazyImage from "v-lazy-image";
</script>
<template>
    <!-- Third Div -->
    
    
    <div class="mt-12 mb-24">
        <!-- Grid Container -->
    
        <h2
            class="text-center text-4xl font-[Raleway] text-white underline decoration-yellow-500 decoration-2 underline-offset-8 mb-8">
            Boss Awards</h2>
    
        <div
            class="grid justify-items-center container mx-auto px-12 grid-cols-1 gap-4 md:grid md:grid-cols-2 md:gap-4 lg:grid lg:grid-cols-4 lg:gap-4">
    
            <!-- Grid Box 1 -->
            <div
                class="transform hover:scale-105 transition duration-500 ease-in-out  grid grid-cols-1 gap-4 drop-shadow-lg shadow-lg  rounded-lg">
    
                <!-- Svg icon -->
                <!-- Grid Box 1 -->
                <div class="mx-auto">
                    <v-lazy-image src="/award2020/M1.jpg" class="w-full bg-cover" alt="image" />
                </div>
    
            </div>
    
            <!-- Grid Box 2 -->
            <div
                class="transform hover:scale-105 transition duration-500 ease-in-out  grid grid-cols-1 gap-4 drop-shadow-lg shadow-lg  rounded-lg">
    
                <!-- Svg icon -->
                <!-- Grid Box 1 -->
                <div class="mx-auto">
                    <v-lazy-image src="/award2021/awards 3.png" class="w-full bg-cover" alt="image" />
                </div>
    
            </div>
    
            <!-- Grid Box 3 -->
            <div
                class="transform hover:scale-105 transition duration-500 ease-in-out  grid grid-cols-1 gap-4 drop-shadow-lg shadow-lg  rounded-lg">
    
                <!-- Svg icon -->
                <!-- Grid Box 1 -->
                <div class="mx-auto">
                    <v-lazy-image src="/award2021/captain Emmanuel uroegbulam.jpg" class="w-full bg-cover" alt="image" />
                </div>
    
            </div>
    
            <!-- Grid Box 4 -->
            <div
                class="transform hover:scale-105 transition duration-500 ease-in-out  grid grid-cols-1 gap-4 drop-shadow-lg shadow-lg  rounded-lg">
    
                <!-- Svg icon -->
                <!-- Grid Box 1 -->
                <div class="mx-auto">
                    <v-lazy-image src="/award2021/Sir. Obiefule Charles Chiebuka.jpg" class="w-full bg-cover" alt="image" />
                </div>
    
            </div>
    
            <!-- Grid Box 5 -->
            <div
                class="transform hover:scale-105 transition duration-500 ease-in-out  grid grid-cols-1 gap-4 drop-shadow-lg shadow-lg  rounded-lg">
    
                <!-- Svg icon -->
                <!-- Grid Box 1 -->
                <div class="mx-auto">
                    <v-lazy-image src="/award2020/M4.jpg" class="w-full bg-cover" alt="image" />
                </div>
    
            </div>
    
            <!-- Grid Box 6 -->
            <div
                class="transform hover:scale-105 transition duration-500 ease-in-out  grid grid-cols-1 gap-4 drop-shadow-lg shadow-lg  rounded-lg">
    
                <!-- Svg icon -->
                <!-- Grid Box 1 -->
                <div class="mx-auto">
                    <v-lazy-image src="/award2021/sunshine .jpg" class="w-full bg-cover" alt="image" />
                </div>
    
            </div>
    
            <!-- Grid Box 7 -->
            <div
                class="transform hover:scale-105 transition duration-500 ease-in-out  grid grid-cols-1 gap-4 drop-shadow-lg shadow-lg  rounded-lg">
    
                <!-- Svg icon -->
                <!-- Grid Box 1 -->
                <div class="mx-auto">
                    <v-lazy-image src="/award2020/M6.jpg" class="w-full bg-cover" alt="image" />
                </div>
    
            </div>
    
            <!-- Grid Box 8 -->
            <div
                class="transform hover:scale-105 transition duration-500 ease-in-out  grid grid-cols-1 gap-4 drop-shadow-lg shadow-lg  rounded-lg">
    
                <!-- Svg icon -->
                <!-- Grid Box 1 -->
                <div class="mx-auto">
                    <v-lazy-image src="/award2020/M2.jpg" class="w-full bg-cover" alt="image" />
                </div>
    
            </div>
    
    
        </div>
    
        <RouterLink class="flex justify-center items-center mt-6" to="/">
            <button class="py-3 px-4  bg-yellow-500 mt-4 rounded">
                View more
            </button>
        </RouterLink>
    </div>
</template>
<style scope>

/** iMAGE STYLE */

.v-lazy-image {
    filter: blur(10px);
    transition: filter 0.7s;
}

.v-lazy-image-loaded {
    filter: blur(0);
}

</style>