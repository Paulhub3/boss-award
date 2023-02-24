<script setup>
import AwardSection from "../components/AwardSection.vue";
import ContactSection from "../components/ContactSection.vue";
import Sponsor from "../components/Sponsor.vue";
import VLazyImage from "v-lazy-image";
import { RouterLink } from 'vue-router'
</script>

<template>
  
  <!-- HOME LANDING PAGE DIV -->
  <div class="flex flex-col mx-auto  md:flex md:flex-row px-6 md::px-0 relative bg-black h-full lg:h-screen w-full">
  
    <!--BACKGROUND BLOB -->
    <span class="absolute w-full  animate-pulse opacity-75">
      <svg viewBox="0 0 800 500" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink" width="100%" id="blobSvg">
        <g transform="translate(261, -233)">
          <path class="blob"
            d="M416.5,301Q390,352,345.5,380Q301,408,245.5,421Q190,434,139,401Q88,368,48,309Q8,250,37.5,183.5Q67,117,131.5,101Q196,85,247,94.5Q298,104,351,121Q404,138,423.5,194Q443,250,416.5,301Z"
            fill="#cccc00"></path>
        </g>
      </svg>
    </span>
  
    <!--BACKGROUND BLOB Two -->
    <span class="absolute bottom-2 w-full animate-pulse opacity-30">
      <svg viewBox="0 0 800 500" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink" width="100%" id="blobSvg">
        <g transform="translate(-49, 209)">
          <path class="blob"
            d="M457.5,314.5Q427,379,368.5,407.5Q310,436,247.5,443.5Q185,451,136,409.5Q87,368,50,309Q13,250,31.5,177Q50,104,115,70Q180,36,247.5,43.5Q315,51,354.5,98.5Q394,146,441,198Q488,250,457.5,314.5Z"
            fill="#808080"></path>
        </g>
      </svg>
    </span>
  
    <!-- First Div -->
    <div
      class="my-auto md:my-0 lg:my-auto z-40 space-y-5 py-6 lg:py-0 md:flex md:flex-col md:justify-center md:items-center container lg:justify-start lg:items-start mx-auto lg:ml-20">
  
      <h1 class="text-4xl md:text-5xl text-white font-medium font-serif">
        Welcome To
      </h1>
  
  
      <h1 class="text-3xl md:text-5xl text-yellow-500 font-medium font-serif">
        Boss Award
      </h1>

    </div>
  
    <!-- Second Div -->
    <div class="relative h-64  mt-16 md:mt-12 md:ml-36 container lg:my-auto mx-auto">
  
      <!--Big Center Image size -->
      <div>
        <v-lazy-image src="/images/boss-aw3.jpeg" alt=""
          class="w-full  lg:w-9/12 object-contain  border-8 border-solid border-white rounded-md overflow-hidden  drop-shadow-lg shadow-lg absolute" />
      </div>
  
  
      <!--Top Right Image -->
      <div class="z-40  absolute -right-5 -top-24 md:right-2 lg:right-32 lg:-top-32">
        <v-lazy-image src="/images/boss-award2.jpg"
          class="w-28 md:w-36 lg:w-44  rounded-md object-contain  border-2 border-solid border-white  overflow-hidden  drop-shadow-lg shadow-lg"
          alt="" />
      </div>
  

  
      <!--Bottom Left Image -->
      <div class="z-40  absolute top-44 md:top-36 lg:top-56">
        <v-lazy-image src="/images/M9.jpg"
          class=" w-24 md:w-36 lg:w-44 object-contain rounded-md border-2 border-solid border-white  overflow-hidden  drop-shadow-lg shadow-lg"
          alt="" />
      </div>
  
    </div>
  
  </div>


  <!-- About Third Layout Section with two div's -->
  <div class="grid grid-cols-1 gap-7 md:grid md:grid-cols-2 md:gap-7 mt-24 w-11/12 drop-shadow-lg shadow-lg px-4 mx-auto">
  
    <!-- First Div Of Image -->
    <div class="md:mt-16">
      <v-lazy-image src="/images/boss-aw3.jpeg" alt="" class="w-full h-95" />
    </div>
  
    <!-- Second Div Of About -->
    <div class="space-y-4 py-6">
      <h2 class="text-2xl text-gray-200 font-sans font-medium text-justify">ABOUT/ HISTORY</h2>
  
      <p class="text-white font-sans text-justify">
        Government School is a close-knit educational community where children are received from their ages of innocence,
        treated with great love, respect and nurtured into young men and women of intellect, character and integrity. PS
        understands that the search for quality education has remained a great concern for our parents. Our parents are
        taking
        the extra mile to provide their children with an education that is rich in value and quality. Hence the need to
        have an
        educational institution that has the physical and human resources to provide standard and values-based education
        in a
        highly conducive learning environment is the focus of Government School. Government School embodies all the tenets
        of an
        international model school. It is situated at Government Avenue, Avu- Owerri West L.G.A., Imo State, Nigeria, in a
        very
      </p>

      <RouterLink to="/">
        <button class="py-3 px-4 bg-yellow-500 mt-4 rounded">
            Read more
        </button>
      </RouterLink>
    </div>
  
  
  </div>

    <!-- Third Div -->
  <div>
    <AwardSection />
  </div>

  <!-- Fourth Div -->
  <div>
    <ContactSection />
  </div>

  <!-- Fifth Div -->
  <div>
    <Sponsor />
  </div>
  
  
</template>

<style scoped>
/** HOME CAROUSEL */
.left-full {
  left: -100%;
}

.carousel-item {
  float: left;
  position: relative;
  display: block;
  width: 100%;
  height: 70vh;
  margin-right: -100%;
  backface-visibility: hidden;
}

.carousel-item.active {
  left: 0;
}

/** iMAGE STYLE */

.v-lazy-image {
    filter: blur(10px);
    transition: filter 0.7s;
}

.v-lazy-image-loaded {
    filter: blur(0);
}
</style>
