<template>
  <div id="wrapper">

    <!-- Header -->
    <Header></Header>

    <!-- Menu -->
    <Menu></Menu>

    <!-- Main -->
    <div id="main">
      <div class="inner">
        <h1>烤肉?專業喔!</h1>
        <span class="image main"><a target="_blank" href="https://bbqnotes.tw/"><img src="~/assets/images/pic01.jpg" alt="" /></a></span>
        <p>在 2018 年中秋節前，我們完成了一個關於烤肉知識的網站。不論是過節或各種出遊場合，很愛跟朋友聚在一起烤肉，但網路上關於事前準備、升火、怎麼烤更好吃的資訊實在太豐富了欠整理，這個網站就在大家舉雙手贊成之下著手進行。</p>
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