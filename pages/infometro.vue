<template>
  <div id="wrapper">

    <!-- Header -->
    <Header></Header>

    <!-- Menu -->
    <Menu></Menu>

    <!-- Main -->
    <div id="main">
      <div class="inner">
        <h1>infometro 資訊地鐵站</h1>
        <span class="image main"><a target="_blank" href="https://infometro.cc"><img src="~/assets/images/3.png" alt="" /></a></span>
        <p>infometro 是一款利用地鐵圖來整理資訊的網站，用來保存創意和想法。<br>infometro 大量的採用拖曳動作來編輯地鐵，編輯的動作不需在額外存檔，讓您能夠靈活的將資訊存放在不同的地方。<br>把你容易忘記得事情先記在地鐵站上，透過有效的分類與管理，就能從容不迫的去處理其他更重要的事。</p>
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