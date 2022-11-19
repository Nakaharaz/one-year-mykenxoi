<template>
  <section class="app-shot-one" id="screenshots">
    <img src="/assets/images/background/app-shot-bg.png" alt="Awesome Image" class="app-shot-one__bg" />
    <div class="container-fluid">
      <div class="block-title text-center">
        <h2 class="block-title__title">Essas fotos <br> <span>lindas</span> <br> que amolecem o <br> coração de qualquer um.</h2><!-- /.block-title__title -->
      </div><!-- /.block-title -->
      <div class="app-shot-one__carousel owl-theme owl-carousel">
        <div class="item">
          <img src="/assets/images/slide/slide (1).jpeg" alt="">
        </div><!-- /.item -->
        <div class="item">
          <img src="/assets/images/slide/slide (2).jpeg" alt="">
        </div><!-- /.item -->
        <div class="item">
          <img src="/assets/images/slide/slide (3).jpeg" alt="">
        </div><!-- /.item -->
        <div class="item">
          <img src="/assets/images/slide/slide (4).jpeg" alt="">
        </div><!-- /.item -->
        <div class="item">
          <img src="/assets/images/slide/slide (5).jpeg" alt="">
        </div><!-- /.item -->
        <div class="item">
          <img src="/assets/images/slide/slide (6).jpeg" alt="">
        </div><!-- /.item -->
        <div class="item">
          <img src="/assets/images/slide/slide (7).jpeg" alt="">
        </div><!-- /.item -->
        <div class="item">
          <img src="/assets/images/slide/slide (8).jpeg" alt="">
        </div><!-- /.item -->
        <div class="item">
          <img src="/assets/images/slide/slide (9).jpeg" alt="">
        </div><!-- /.item -->
        <div class="item">
          <img src="/assets/images/slide/slide (10).jpeg" alt="">
        </div><!-- /.item -->
        <div class="item">
          <img src="/assets/images/slide/slide (11).jpeg" alt="">
        </div><!-- /.item -->
        <div class="item">
          <img src="/assets/images/slide/slide (12).jpeg" alt="">
        </div><!-- /.item -->
        <div class="item">
          <img src="/assets/images/slide/slide (13).jpeg" alt="">
        </div><!-- /.item -->
        <div class="item">
          <img src="/assets/images/slide/slide (14).jpeg" alt="">
        </div><!-- /.item -->
        <div class="item">
          <img src="/assets/images/slide/slide (15).jpeg" alt="">
        </div><!-- /.item -->
      </div><!-- /.app-shot-one__carousel owl-theme owl-carousel -->
    </div><!-- /.container-fluid -->
  </section>
</template>

<script>
    export default {
      name: "Screenshots",
      mounted() {

          if ($('.app-shot-one__carousel').length) {
            $('.app-shot-one__carousel').owlCarousel({
              loop: true,
              margin: 43,
              nav: false,
              dots: false,
              autoWidth: false,
              autoplay: true,
              smartSpeed: 700,
              autoplayTimeout: 5000,
              autoplayHoverPause: true,
              slideBy: 5,
              responsive: {
                0: {
                  items: 1
                },
                480: {
                  items: 2
                },
                600: {
                  items: 3
                },
                991: {
                  items: 4
                },
                1000: {
                  items: 5
                },
                1200: {
                  items: 5
                }
              }
            });
          }
      }
    }
</script>

<style scoped>

</style>
