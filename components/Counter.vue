<template>
  <section class="fact-one">
    <div class="container">
      <div class="block-title text-center">
        <h2 class="block-title__title">Somos <span>FODAS</span>!</h2><!-- /.block-title__title -->
      </div><!-- /.block-title -->
      <div class="row">
        <div class="col-lg-3 col-md-6 col-sm-12 wow fadeInUp" data-wow-duration="1500ms">
          <div class="fact-one__single">
            <div class="fact-one__inner">
              <h3 class="fact-one__count counter">365</h3><!-- /.fact-one__count counter -->
              <p class="fact-one__text">Dias juntos</p><!-- /.fact-one__text -->
            </div><!-- /.fact-one__inner -->
          </div><!-- /.fact-one__single -->
        </div><!-- /.col-lg-3 col-md-6 col-sm-12 -->
        <div class="col-lg-3 col-md-6 col-sm-12 wow fadeInUp" data-wow-duration="1500ms">
          <div class="fact-one__single">
            <div class="fact-one__inner">
              <h3 class="fact-one__count counter">77777</h3><!-- /.fact-one__count counter -->
              <p class="fact-one__text" style="text-align: center; font-size: 10px;">Coisas que o Enzo faria pra ver a Myk feliz</p><!-- /.fact-one__text -->
            </div><!-- /.fact-one__inner -->
          </div><!-- /.fact-one__single -->
        </div><!-- /.col-lg-3 col-md-6 col-sm-12 -->
        <div class="col-lg-3 col-md-6 col-sm-12 wow fadeInUp" data-wow-duration="1500ms">
          <div class="fact-one__single">
            <div class="fact-one__inner">
              <h3 class="fact-one__count counter">2000</h3><!-- /.fact-one__count counter -->
              <p class="fact-one__text">Fotos juntos</p><!-- /.fact-one__text -->
            </div><!-- /.fact-one__inner -->
          </div><!-- /.fact-one__single -->
        </div><!-- /.col-lg-3 col-md-6 col-sm-12 -->
        <div class="col-lg-3 col-md-6 col-sm-12 wow fadeInUp" data-wow-duration="1500ms">
          <div class="fact-one__single">
            <div class="fact-one__inner">
              <h3 class="fact-one__count counter">1</h3><!-- /.fact-one__count counter -->
              <p class="fact-one__text">Ano!</p><!-- /.fact-one__text -->
            </div><!-- /.fact-one__inner -->
          </div><!-- /.fact-one__single -->
        </div><!-- /.col-lg-3 col-md-6 col-sm-12 -->
      </div><!-- /.row -->
    </div><!-- /.container -->
  </section>
</template>

<script>
    export default {
      name: "Counter",
      mounted() {
        if ($('.counter').length) {
          $('.counter').counterUp({
            delay: 10,
            time: 3000
          });
        }
      }
    }
</script>

<style scoped>

</style>
