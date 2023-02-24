<script setup>
import VLazyImage from "v-lazy-image";

</script>

<template>

    <div class="mt-24 mb-12">

        <h2
            class="text-center text-2xl md:text-4xl font-[Raleway] text-white underline decoration-yellow-500 decoration-2 underline-offset-8 mb-8">
           Packaged & Sponsored by
        </h2>
        
        <div class="grid grid-cols-1 gap-7 md:grid md:grid-cols-2 md:gap-7 mt-24 w-11/12 drop-shadow-lg shadow-lg px-4 mx-auto">
        
            <!-- First Div Of Image -->
            <div class="md:mt-36 lg:mt-0">
                <v-lazy-image src="/images/_MG_7469.JPG" alt="" class="w-full" />
            </div>
        
            <!-- Second Div Of Text And paragraph -->
            <div class="space-y-12 md:space-y-24 py-6">
                
                <h2 class="text-2xl text-gray-300 font-sans font-medium md:text-justify">
                    VERIFIED ENTERTAINMENT BRANDS OF DJPAKY CHICAGOBOY
                </h2>

                <div class="grid grid-cols-3 gap-4">

                    <div>
                        <v-lazy-image src="/images/shoutdowncity.jpeg" alt="" class="w-full" />
                    </div>

                    <div>
                        <v-lazy-image src="/images/lagalaga.jpeg" alt="" class="w-full" />
                    </div>

                    <div>
                        <v-lazy-image src="/images/chicago.jpeg" alt="" class="w-full" />
                    </div>

                </div>
        
            </div>
        
        
        </div>
    </div>


</template>
<style scoped>
/** iMAGE STYLE */

.v-lazy-image {
    filter: blur(10px);
    transition: filter 0.7s;
}

.v-lazy-image-loaded {
    filter: blur(0);
}
</style>