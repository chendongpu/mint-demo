<template>
  <div id="app">
  	<div class="content-div">
  	<router-view/>
  	</div>
    <footer-bar class="footer"></footer-bar>
  </div>
</template>
<script>
  import Footer from './components/FooterBar.vue'
  export default {
    name: 'app',
    components: {
      'footer-bar': Footer
    },
    computed: {}
  }
</script>


