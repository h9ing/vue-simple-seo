<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<script>
export default {  
  metaInfo() {
      return { 
          title: "vue-simple-seo About",
          meta: [
              { name: 'description', content:  '我是About'},
              { property: 'og:title', content: "vue-simple-seo About"},
              { property: 'og:site_name', content: 'vue-simple-seo'},
              {property: 'og:type', content: 'website'}
          ]
      }
  }
}
</script>