<template>
  <div id="wrapper">

    <!-- Header -->
    <Header></Header>

    <!-- Menu -->
    <Menu></Menu>

    <!-- Main -->
    <div id="main">
      <div class="inner">
        <h1>wayne1894 教學網</h1>
        <span class="image main"><a target="_blank" href="https://wayne1894.com"><img src="~/assets/images/5.png" alt="" /></a></span>
        <p>使用 nuxt.js 開發的教學網系統，後端資料庫使用 firebase</p>
      </div>
    </div>

    <!-- Footer -->
    <Footer></Footer>

  </div>
</template>



<script>
  import Header from "~/components/Header.vue";
  import Menu from "~/components/Menu.vue";
  import Footer from "~/components/Footer.vue";

  export default {
    components: {
      Header,
      Menu,
      Footer
    }
  }
</script>