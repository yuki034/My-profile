<template>
    <div class="container">
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
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* PC用（デフォルト） */
.container {
  width: 80%;
  margin: 0 auto;
}

/* タブレット用 */
@media (max-width: 1024px) {
  .container {
    width: 90%;
  }
}

/* スマートフォン用 */
@media (max-width: 768px) {
  .container {
    width: 95%;
    padding: 10px;
  }

    /* 各セクションの間隔を調整 */
    .container > * {
    margin-bottom: 20px;
  }

  /* フォントサイズの調整 */
  h1, h2, h3, p {
    font-size: 14px; /* スマホ用にフォントサイズを縮小 */
  }

  /* レイアウトの調整 */
  .container div {
    text-align: center;
  }

  /* 画像やコンテンツのサイズ調整 */
  img {
    max-width: 100%;
    height: auto;
  }
}
</style>