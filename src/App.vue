<template>
    <div>
      <Header />
      <Hero />
      <About />
      <Projects />
      <Works />
      <Footer />
    </div>
</template>



<script setup>
import Header from './components/Header.vue';
import Hero from './components/Hero.vue';
import About from './components/About.vue';
import Projects from './components/Projects.vue';
import Footer from './components/Footer.vue';
import Works from './components/Works.vue';
</script>

<style>
*{
  margin: 0px;
}
/* PC用（デフォルト） */
.container {
  width: 80%;
  margin: 0 auto;
  font-size: 18px;
}

/* タブレット以下 */
@media (max-width: 768px) {
  .container {
    width: 90%;
    font-size: 16px;
  }
}

/* スマホ以下 */
@media (max-width: 480px) {
  .container {
    width: 100%;
    font-size: 14px;
  }
}
.flex-box {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}
img {
  max-width: 100%;
  height: auto;
}

</style>
