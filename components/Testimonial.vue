<template>
  <section class="testimonials-one">
    <div class="container">
      <div class="block-title text-center">
        <h2 class="block-title__title">Mensagens de <span>amor</span> que nossos amigos mandaram❤</h2><!-- /.block-title__title -->
      </div><!-- /.block-title -->
      <div class="testimonials-one__carousel-outer">
        <div class="testimonials-one__carousel owl-carousel owl-theme">
          <div class="item">
            <div class="testimonials-one__single">
              <div class="testimonials-one__inner">
                <p>Enzo sem Mykelly é como feijoada sem feijão, feijoada sem feijão não é feijoada 🌹❤️💋</p>
                <h3>Odeig Ferraz</h3>
                <span>Best do Enxoi</span>
                <img src="/assets/images/testimonials/disa.webp" alt="Foto do Diego e Isa" />
              </div><!-- /.testimonials-one__inner -->
            </div><!-- /.testimonials-one__single -->
          </div><!-- /.item -->
          <div class="item">
            <div class="testimonials-one__single">
              <div class="testimonials-one__inner">
                <p>This is due to their excellent service, competitive pricing and <br> customer support. It’s throughly refresing to get such a personal <br> touch. Duis aute irure dolor in reprehenderit.</p>
                <h3>Isinha drip</h3>
                <span>Best da Myk</span>
                <img src="/assets/images/testimonials/disa.webp" alt="Foto da isinha" />
              </div><!-- /.testimonials-one__inner -->
            </div><!-- /.testimonials-one__single -->
          </div><!-- /.item -->
          <div class="item">
            <div class="testimonials-one__single">
              <div class="testimonials-one__inner">
                <p>Acho bem tóxicos. <br> Brincadeira😻 <br> Fofinhos.</p>
                <h3>Fernanda Bacaninha</h3>
                <span>Best da Myk</span>
                <img src="/assets/images/testimonials/niver-fer.webp" alt="Foto da Fernanda, Myk e Enxoi" />
              </div><!-- /.testimonials-one__inner -->
            </div><!-- /.testimonials-one__single -->
          </div><!-- /.item -->
          <div class="item">
            <div class="testimonials-one__single">
              <div class="testimonials-one__inner">
                <p>Bem fofichos.</p>
                <h3>Mafe</h3>
                <span>Best da Myk</span>
                <img src="/assets/images/testimonials/profile-mafe.jpg" alt="Foto da Mafe" />
              </div><!-- /.testimonials-one__inner -->
            </div><!-- /.testimonials-one__single -->
          </div><!-- /.item -->
          <div class="item">
            <div class="testimonials-one__single">
              <div class="testimonials-one__inner">
                <p>Eu acho bonito a forma como vcs se esforçam pra estarem juntos, no sentido de esforço pra fazer dar certo e acho mt bonito tbm q vcs são a própria idealização de casal adolescente engraçado. Apoio muito vcs dois. Sei q existem problemas, mas vcs se entendem</p>
                <h3>Sarolas</h3>
                <span>Best do Enxoi</span>
                <img src="/assets/images/testimonials/sarolas.jpeg" alt="Foto da Sarolas" />
              </div><!-- /.testimonials-one__inner -->
            </div><!-- /.testimonials-one__single -->
          </div><!-- /.item -->
          <div class="item">
            <div class="testimonials-one__single">
              <div class="testimonials-one__inner">
                <p>Vei vcs são um casal tão fofos ,tão unidos ,tão criativos e com tanto amor um pro outros ,vcs passam confiança e espero ver vcs juntos pra sempre viu KSKS</p>
                <h3>Lucinha</h3>
                <span>Best da Myk</span>
                <img src="/assets/images/testimonials/lucinha.jpeg" alt="Foto da Lucinha" />
              </div><!-- /.testimonials-one__inner -->
            </div><!-- /.testimonials-one__single -->
          </div><!-- /.item -->
          <div class="item">
            <div class="testimonials-one__single">
              <div class="testimonials-one__inner">
                <p>Feliz 1 anoo Enzo e Mykelly, vcs merecem ser mto felizes juntos. vcs se completam e eu tenho certeza que ainda vão conquistar mais muitas coisas juntos. conta comigo pra sempre, eu apoio muito vcs :)</p>
                <h3>Felipe</h3>
                <span>Best da Myk</span>
                <img src="/assets/images/testimonials/felipe-myk.jpeg" alt="Foto do Felipe" />
              </div><!-- /.testimonials-one__inner -->
            </div><!-- /.testimonials-one__single -->
          </div><!-- /.item -->
        </div><!-- /.testimonials-one__carousel -->
        <div class="testimonials-one__carousel__shape-one"></div><!-- /.testimonials-one__carousel__shape-one -->
        <div class="testimonials-one__carousel__shape-two"></div><!-- /.testimonials-one__carousel__shape-two -->
        <div class="testimonials-one__nav">
          <a class="testimonials-one__nav-left" href="#"><i class="dimon-icon-left-arrow"></i></a>
          <a class="testimonials-one__nav-right" href="#"><i class="dimon-icon-right-arrow"></i></a>
        </div><!-- /.testimonials-one__nav -->
      </div><!-- /.testimonials-one__carousel-outer -->
    </div><!-- /.container -->
  </section>
</template>

<script>
    export default {
      name: "Testimonial",
      mounted() {
        if ($('.testimonials-one__carousel').length) {
          $('.testimonials-one__carousel').owlCarousel({
            loop: true,
            margin: 0,
            nav: false,
            dots: false,
            autoWidth: false,
            autoplay: true,
            smartSpeed: 700,
            autoplayTimeout: 5000,
            autoplayHoverPause: true,
            items: 1
          });

          $('.testimonials-one__nav-left').on('click', function() {
            $('.testimonials-one__carousel').trigger('next.owl.carousel');
            return false;
          });
          $('.testimonials-one__nav-right').on('click', function() {
            $('.testimonials-one__carousel').trigger('prev.owl.carousel');
            return false;
          });
        }
      }
    }
</script>

<style scoped>

</style>
