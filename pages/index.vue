<template>
  <div class="bg-bg h-screen">
  <Tutorial/>
  <Header/>
  <Main/>
  </div>
</template>

<script>
import Header from '../components/Header.vue';
import Story from '../components/Story.vue';
import Sidebar from '../components/Sidebar.vue';
import Main from '../components/Main.vue';
export default {
    name: "IndexPage",
    components: { Header, Story, Sidebar, Main }
}
</script>
