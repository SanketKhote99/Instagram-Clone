<template>
    <div>
        <div class="flex items-center justify-between pt-3">
            <div class="flex items-center gap-3">
              <img class="h-8 w-8 rounded-full" :src="photo" alt="user profile">
              <div class="text-sm">
                <a href="#" class="text-sm flex flex-col text-white">{{username}}</a>
                <p class="text-gray-400 text-xs">New to instagram</p>

              </div>
            </div>
            <div>
              <a href="#" class="text-sm text-blue-600">{{ status }}</a>
            </div>
          </div>
    </div>
</template>
  <script>
  export default {
    props: [ "username",  "status","photo"],
  };
  </script>
  
  <style>
  </style>





   