<template>
    <div class=" w-auto  justify-center flex gap-10 sm:pt-10 bg-bg mt-12">
      <Post class="w-[468px]"/>
      <Sidebar class="w-[319px] hidden lg:block"/>
    </div>
  </template>
  <script>
import Story from './Story.vue';
import Post from './Post.vue';
    export default {
    name: "NuxtTutorial",
    components: { Story, Post }
}
    </script>
    