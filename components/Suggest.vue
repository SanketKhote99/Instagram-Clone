<template>
    <div>
        <div class="flex items-center justify-between pt-3">
            <div class="flex items-center gap-3">
              <img class="h-8 w-8 rounded-full" src="https://media-exp1.licdn.com/dms/image/C5603AQHO62hb1kDaQA/profile-displayphoto-shrink_200_200/0/1649937984739?e=1669852800&v=beta&t=50QrTQ6rytNxl1qBQWm_9tCfsjdYfBXwPNhD4_jw9d4" alt="user profile">
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
    props: [ "username",  "status"],
  };
  </script>
  
  <style>
  </style>





   