<template>
  <div class="about">


<!-- Component Code -->
<div class="max-w-screen-xl mx-auto p-5 sm:p-10 md:p-10">
  
  <div class="border-b mb-5 flex justify-between text-xl">
    <div class="text-indigo-600 flex items-center pb-2 pr-2 border-b-2 border-indigo-600 uppercase">

      <a href="#" class="font-semibold inline-block" >Project</a>
    </div>
    <!-- <a href="#">See All</a> -->
  </div>
  
  <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-10">
 
    <!-- ////////////////////////11111///////////////////////////////// -->
    <div class="rounded overflow-hidden shadow-lg flex flex-col">
  <a href="#"><div class="relative">
    <img class="w-full" :src="src1" alt="Sunset in the mountains">
<div @click="openModal(1)" class="hover:bg-transparent transition duration-300 absolute bottom-0 top-0 right-0 left-0 bg-gray-900 opacity-25"></div>
    <a href="#!"><div class="text-xs absolute top-0 right-0 bg-indigo-600 px-4 py-2 text-white mt-3 mr-3 hover:bg-white hover:text-indigo-600 transition duration-500 ease-in-out">
    바로가기
    </div></a>
    </div></a>
  <div class="px-6 py-4 mb-auto">
    <a href="#" class="font-medium text-lg inline-block hover:text-indigo-600 transition duration-500 ease-in-out inline-block mb-2">TasteIt</a>
    <p class="text-gray-500 text-sm">
      Responsive Bootstrap 4 HTML5 Restaurant Website
    </p>
  </div>
  <div class="px-6 py-3 flex flex-row items-center justify-between bg-gray-100">
    
    <span href="#" class="py-1 text-xs font-regular text-gray-900 mr-1 flex flex-row items-center">
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#Bootstrap</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#Python</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#AWS</span>
    </span>
  
  </div>
</div>
    



    <!-- ////////////////////////2222222///////////////////////////////// -->
    <div class="rounded overflow-hidden shadow-lg flex flex-col">
  <a href="#"><div class="relative">
    <img class="w-full" :src="src2" alt="Sunset in the mountains">
<div @click="openModal(2)" class="hover:bg-transparent transition duration-300 absolute bottom-0 top-0 right-0 left-0 bg-gray-900 opacity-25"></div>
    <a href="#!"><div class="text-xs absolute top-0 right-0 bg-indigo-600 px-4 py-2 text-white mt-3 mr-3 hover:bg-white hover:text-indigo-600 transition duration-500 ease-in-out">
    바로가기
    </div></a>
    </div></a>
  <div class="px-6 py-4 mb-auto">
    <a href="#" class="font-medium text-lg inline-block hover:text-indigo-600 transition duration-500 ease-in-out inline-block mb-2">Eden</a>
    <p class="text-gray-500 text-sm">
      Bootstrap 4 HTML5 Responsive Magazine Website
    </p>
  </div>
  <div class="px-6 py-3 flex flex-row items-center justify-between bg-gray-100">
    
    <span href="#" class="py-1 text-xs font-regular text-gray-900 mr-1 flex flex-row items-center">
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#Bootstrap</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#Java</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#Spring</span>
    </span>
  
  </div>
</div>



    <!-- ////////////////////////333333///////////////////////////////// -->
    <div class="rounded overflow-hidden shadow-lg flex flex-col">
  <a href="#"><div class="relative">
    <img class="w-full" :src="src3" alt="Sunset in the mountains">
<div @click="openModal(3)" class="hover:bg-transparent transition duration-300 absolute bottom-0 top-0 right-0 left-0 bg-gray-900 opacity-25"></div>
    <a href="#!"><div class="text-xs absolute top-0 right-0 bg-indigo-600 px-4 py-2 text-white mt-3 mr-3 hover:bg-white hover:text-indigo-600 transition duration-500 ease-in-out">
    바로가기
    </div></a>
    </div></a>
  <div class="px-6 py-4 mb-auto">
    <a href="#" class="font-medium text-lg inline-block hover:text-indigo-600 transition duration-500 ease-in-out inline-block mb-2">eStore</a>
    <p class="text-gray-500 text-sm">
      Bootstrap 4 HTML5 eCommerce Website
    </p>
  </div>
  <div class="px-6 py-3 flex flex-row items-center justify-between bg-gray-100">
    
    <span href="#" class="py-1 text-xs font-regular text-gray-900 mr-1 flex flex-row items-center">
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#TailWind</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#PHP</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#MySql</span>
    </span>
  
  </div>
</div>



    <!-- ////////////////////////444444///////////////////////////////// -->
    <div class="rounded overflow-hidden shadow-lg flex flex-col">
  <a href="#"><div class="relative">
    <img class="w-full" :src="src4" alt="Sunset in the mountains">
<div @click="openModal(4)" class="hover:bg-transparent transition duration-300 absolute bottom-0 top-0 right-0 left-0 bg-gray-900 opacity-25"></div>
    <a href="#!"><div class="text-xs absolute top-0 right-0 bg-indigo-600 px-4 py-2 text-white mt-3 mr-3 hover:bg-white hover:text-indigo-600 transition duration-500 ease-in-out">
    바로가기
    </div></a>
    </div></a>
  <div class="px-6 py-4 mb-auto">
    <a href="#" class="font-medium text-lg inline-block hover:text-indigo-600 transition duration-500 ease-in-out inline-block mb-2">Klassy Cafe</a>
    <p class="text-gray-500 text-sm">
      Bootstrap 4 HTML5 Responsive Restaurant Website
    </p>
  </div>
  <div class="px-6 py-3 flex flex-row items-center justify-between bg-gray-100">
    
    <span href="#" class="py-1 text-xs font-regular text-gray-900 mr-1 flex flex-row items-center">
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#Tailwind</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#JavaScript</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#AWS</span>
    </span>
  
  </div>
</div>



    <!-- ////////////////////////555555///////////////////////////////// -->
    <div class="rounded overflow-hidden shadow-lg flex flex-col">
  <a href="#"><div class="relative">
    <img class="w-full" :src="src5" alt="Sunset in the mountains">
<div @click="openModal(5)" class="hover:bg-transparent transition duration-300 absolute bottom-0 top-0 right-0 left-0 bg-gray-900 opacity-25"></div>
    <a href="#!"><div class="text-xs absolute top-0 right-0 bg-indigo-600 px-4 py-2 text-white mt-3 mr-3 hover:bg-white hover:text-indigo-600 transition duration-500 ease-in-out">
    바로가기
    </div></a>
    </div></a>
  <div class="px-6 py-4 mb-auto">
    <a href="#" class="font-medium text-lg inline-block hover:text-indigo-600 transition duration-500 ease-in-out inline-block mb-2">Burger</a>
    <p class="text-gray-500 text-sm">
      Bootstrap 4 HTML5 Responsive Food Website
    </p>
  </div>
  <div class="px-6 py-3 flex flex-row items-center justify-between bg-gray-100">
    
    <span href="#" class="py-1 text-xs font-regular text-gray-900 mr-1 flex flex-row items-center">
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#Bootstrap</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#Vue.js</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#web application</span>
    </span>
  
  </div>
</div>



    <!-- ////////////////////////666666///////////////////////////////// -->
    <div class="rounded overflow-hidden shadow-lg flex flex-col">
  <a href="#"><div class="relative">
    <img class="w-full" :src="src6" alt="Sunset in the mountains">
<div @click="openModal(6)" class="hover:bg-transparent transition duration-300 absolute bottom-0 top-0 right-0 left-0 bg-gray-900 opacity-25"></div>
    <a href="#!"><div class="text-xs absolute top-0 right-0 bg-indigo-600 px-4 py-2 text-white mt-3 mr-3 hover:bg-white hover:text-indigo-600 transition duration-500 ease-in-out">
    바로가기
    </div></a>
    </div></a>
  <div class="px-6 py-4 mb-auto">
    <a href="#" class="font-medium text-lg inline-block hover:text-indigo-600 transition duration-500 ease-in-out inline-block mb-2">Ninom</a>
    <p class="text-gray-500 text-sm">
      Bootstrap 4 HTML5 e-Commerce Website Template
    </p>
  </div>
  <div class="px-6 py-3 flex flex-row items-center justify-between bg-gray-100">
    
    <span href="#" class="py-1 text-xs font-regular text-gray-900 mr-1 flex flex-row items-center">
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#Tailwind</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#React.js</span>
            <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 cursor-pointer">#responsive web</span>
    </span>
  
  </div>
</div>



  </div> 
  <!-- grid -->
</div>



<!-- modal -->

   <ModalView v-if="this.isModalViewed" @close-modal="isModalViewed = false">
     <Coment1 v-if="this.modal_num == 1"></Coment1>
     <Coment2 v-if="this.modal_num == 2"></Coment2>
     <Coment3 v-if="this.modal_num == 3"></Coment3>
     <Coment4 v-if="this.modal_num == 4"></Coment4>
     <Coment5 v-if="this.modal_num == 5"></Coment5>
     <Coment6 v-if="this.modal_num == 6"></Coment6>
   </ModalView> 









  </div>
</template>

<script>

import ModalView from '@/components/ModalView.vue';
import Coment1 from '@/components/coment1.vue';
import Coment2 from '@/components/coment2.vue';
import Coment3 from '@/components/coment3.vue';
import Coment4 from '@/components/coment4.vue';
import Coment5 from '@/components/coment5.vue';
import Coment6 from '@/components/coment6.vue';


export default {

  name: 'about',

  components: {

    ModalView,
    Coment1,
    Coment2,
    Coment3,
    Coment4,
    Coment5,
    Coment6,


   
  },
  data(){
    return{
      isModalViewed: false,
      modal_num: 0,
    
      src1: require("@/assets/1.png"),
      src2: require("@/assets/2.png"),
      src3: require("@/assets/3.png"),
      src4: require("@/assets/4.png"),
      src5: require("@/assets/5.png"),
      src6: require("@/assets/6.png"),
      
      

    }
  },
  methods: {
    openModal(num){
      this.isModalViewed = true;
      this.modal_num = num;
      
    }
  }
}
</script>

<style scoped>
body{
            margin: 0;
        }


        @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap");

body {
  font-family: "Poppins", sans-serif !important;
}





  
  /**
   * The different sections
   */
  .section {
    position: relative;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
        -ms-flex-flow: column nowrap;
            flex-flow: column nowrap;
    -webkit-box-align: stretch;
        -ms-flex-align: stretch;
            align-items: stretch;
    min-height: 60vh;
    width: 100%;
    -ms-flex-line-pack: center;
        align-content: center;
    padding: 20vh 50px 20vh 75px;
  }
  
  .section svg {
    position: absolute;
    top: -50px;
    left: 0;
    right: 0;
    width: 100%;
    height: 50px;
  }
  
  .section svg.bottom {
    bottom: 0;
    top: auto;
    fill: grey;
  }
  
  .section .section__inner {
    height: 100%;
    max-width: 800px;
    margin: auto auto auto 0;
  }
  
  .section.section--hello {
    background-color: #FDEF52;
    color: #181818;
  }
  
  .section.section--intro {
    background-color: white;
    color: #555;
  }
  
  .section.section--about {
    background-color: #de5f5f;
    color: white;
  }
  
  .section.section--about svg {
    fill: #de5f5f;
  }
  
  .section.section--clients {
    background-color: #343436;
    color: white;
  }
  
  .section.section--clients svg {
    fill: #343436;
  }
  
  .section.section--portfolio {
    background-color: orange;
    color: white;
  }
  
  .section.section--portfolio svg {
    top: -20px;
    fill: orange;
  }
  
  .section.section--portfolio svg.bottom {
    top: auto;
    bottom: -50px;
  }
  
  .section.section--portfolio1 {
    background-color: #3A99D8;
    color: white;
  }
  
  .section.section--portfolio1 svg {
    top: -50px;
    fill: #3A99D8;
  }
  
  .section.section--pepperhill svg {
    top: -50px;
    fill: #3A99D8;
  }
  
  .section.section--contact svg {
    fill: white;
  }




</style>