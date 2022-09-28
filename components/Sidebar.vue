<template>
    <div class="hidden md:block mt-7">
      <!-- User Info -->
      <div class="flex items-center justify-between">
        <div class="flex items-center gap-3">
          <img class="h-14 w-14 rounded-full" src="https://media-exp1.licdn.com/dms/image/C5603AQHO62hb1kDaQA/profile-displayphoto-shrink_200_200/0/1649937984739?e=1669852800&v=beta&t=50QrTQ6rytNxl1qBQWm_9tCfsjdYfBXwPNhD4_jw9d4" alt="user profile">
          <div class="text-sm">
            <a href="#" class="text-sm flex flex-col text-white">sanket.khote</a>
            <p class=" text-gray-400">Sanket Khote</p>
  
          </div>
        </div>
        <div>
          <a href="#" class="text-sm text-blue-600">Switch</a>
        </div>
      </div>

      <!-- Suggest -->
      <div class="text-sm flex items-center justify-between pt-3">
        <p class="text-gray-400">Suggestions For You</p>
        <a class="text-white" href="#">See All</a>
      </div>
      

      <!-- <Suggest class="text-white" :status="follow" :username="sanket" /> -->
      <Suggest username="Letitia Russell" status="Follow" photo="https://randomuser.me/api/portraits/women/34.jpg"/>
      <Suggest username="Margie Burke" status="Follow" photo="https://randomuser.me/api/portraits/women/43.jpg"/>
      <Suggest username="Bruce Peck" status="Follow" photo="https://randomuser.me/api/portraits/men/41.jpg"/>
      <Suggest username="Stanley Jimenez" status="Follow" photo="https://randomuser.me/api/portraits/men/42.jpg"/>
      <Suggest username="Misty Bishop" status="Follow" photo="https://randomuser.me/api/portraits/women/45.jpg"/>

      <div class="text-gray-400 flex gap-1 text-xs pt-5">
        <a class="hover:underline " href="#">About</a>
        <a class="hover:underline " href="#">Helps</a>
        <a class="hover:underline " href="#">Press</a>
        <a class="hover:underline " href="#">API</a>
        <a class="hover:underline " href="#">Jobs</a>
        <a class="hover:underline " href="#">Privacy</a>
        <a class="hover:underline " href="#">Terms</a>
        <a class="hover:underline " href="#">Location</a>
    </div>
    <div class="text-gray-400 text-xs ">
        <a href="#">Language</a>
    </div>

    <div class="text-gray-400 text-xs pt-5">
        <p>© 2022 INSTAGRAM FROM META</p>
    </div>



    </div>
  </template>
  <script>
import Suggest from './Suggest.vue';
    export default {
    name: "sidebar",
    components: { Suggest,  }
}
    </script>
    