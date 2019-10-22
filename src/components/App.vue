<template>
<div>
   <Header/>
  <router-view/>
  <footer class="footer"> Footer</footer>
</div>
  
</template>

<script>

import Header from './element/Header.vue'

export default {
  name: 'App',
  components: {
    Header,
  }
}
</script>

<style lang="scss">

</style>