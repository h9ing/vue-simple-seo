<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  },
  metaInfo() {
      return { 
          title: "vue-simple-seo首頁",
          meta: [
              { name: 'description', content:  '我是首頁'},
              { property: 'og:title', content: "vue-simple-seo首頁"},
              { property: 'og:site_name', content: 'vue-simple-seo'},
              {property: 'og:type', content: 'website'}
          ]
      }
  }
}
</script>
