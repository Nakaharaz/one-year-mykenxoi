<template>
  <div>
    <Banner />
    <CallToActionTwo />
    <CallToAction />
    <Testimonial />
    <Counter />
    <Screenshots />
  </div>
</template>
<script>
  import Banner from "~/components/Banner.vue";
  import CallToAction from "~/components/CallToAction.vue";
  import CallToActionTwo from "~/components/CallToActionTwo.vue";
  import Testimonial from "~/components/Testimonial.vue";
  import Counter from "~/components/Counter.vue";
  import Screenshots from "~/components/Screenshots.vue";
  export default {
    components: {
      Banner,
      CallToAction,
      CallToActionTwo,
      Testimonial,
      Counter,
      Screenshots,

    }
  }
</script>
