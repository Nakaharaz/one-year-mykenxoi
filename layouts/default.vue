<template>
  <div class="page-wrapper">
    <Preloader />
    <nuxt />
  </div>
</template>


<script>
  import Preloader from "~/components/Preloader.vue";
  export default {
    components: {
      Preloader
    },
    head(){
      return {
        title: "Mykenxoi | Uma linda história de amor❤"
      }
    }

  }
</script>
