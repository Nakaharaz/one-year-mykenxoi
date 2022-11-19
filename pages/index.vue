<template>
  <div>
    <Banner />
    <CallToAction />
    <CallToActionTwo />
    <Testimonial />
    <Brands />
    <Counter />
    <Screenshots />
    <Faq />
    <BlogHome />
    <Subscribe />
    <Footer />
  </div>
</template>
<script>
  import Banner from "~/components/Banner.vue";
  import CallToAction from "~/components/CallToAction.vue";
  import CallToActionTwo from "~/components/CallToActionTwo.vue";
  import Testimonial from "~/components/Testimonial.vue";
  import Brands from "~/components/Brands.vue";
  import Counter from "~/components/Counter.vue";
  import Screenshots from "~/components/Screenshots.vue";
  import Faq from "~/components/Faq.vue";
  import BlogHome from "~/components/BlogHome.vue";
  import Subscribe from "~/components/Subscribe.vue";
  import Footer from "~/components/Footer.vue";
  export default {
    components: {
      Banner,
      CallToAction,
      CallToActionTwo,
      Testimonial,
      Brands,
      Counter,
      Screenshots,
      Faq,
      BlogHome,
      Subscribe,
      Footer,

    }
  }
</script>
