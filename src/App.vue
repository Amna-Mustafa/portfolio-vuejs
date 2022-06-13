<template>
  <div id="app">
    <v-app id="inspire">
      <v-main>
        <router-view></router-view>
      </v-main>
    </v-app>
    
  </div>
</template>


<script>
import Login from '@/views/auth/Login.vue'
import Dashboard from '@/views/Dashboard.vue'
import About from '@/views/About.vue'


  export default {
    name: 'app',
    components: {
      Dashboard,
      About
    }
  }
</script>

<style>

</style>
