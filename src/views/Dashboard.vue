<template>
<div id="app">
    <SideBar />
    <router-view></router-view>
</div>
  
</template>


<script>
import SideBar from '@/components/SideBar.vue'
  export default {
    name: 'app',
    components: {
      SideBar
    }
  }
</script>

<style>

</style>
