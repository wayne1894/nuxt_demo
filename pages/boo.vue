<template>
  <div id="wrapper">

    <!-- Header -->
    <Header></Header>

    <!-- Menu -->
    <Menu></Menu>

    <!-- Main -->
    <div id="main">
      <div class="inner">
        <h1>BOO! 網站評分 - 爛網站給個噓</h1>
        <span class="image main"><img src="~/assets/images/unnamed.jpg" alt="" /></span>
        <p>BOO! 同國字「不」的讀音，是「發出噓聲」的意思，看到爛網站我們給他噓聲。功能簡單直覺，覺得網站是無用網站及內容農場文章，按下「爛 BOO!」的按鈕，減少自己跟別人下次再點進爛網站的機會。<br>

          ✓ 用「讚」跟「爛」為網站評分<br>
          好網站，點個「BOO!」<br>
          爛網站，點個「YEP!」<br>
          綜合計算所有使用者的評分，作為最終網站分數。<br>
          <br>
          ✓ 減少您的搜尋花費時間<br>
          搜尋查找資料時，直接參考 BOO! 廣大使用者給的評分，選擇相對高分的網站點擊進入，不用再把每個搜尋結果一個一個點開篩選，大幅降低搜尋的花費時間。<br>
          <br>
          ✓ 保護您的隱私<br>
          我們相當重視使用者的隱私問題，BOO! 不會記錄使用者搜尋的字詞內容，僅會記錄你主動評論網站的網址資訊，就是要提供最正確的評分給每個使用者參考。<br>
          <br>
          ✓ 支援和意見回饋<br>
          使用中遇到問題，歡迎與我們開發團隊聯繫，謝謝！<br>
          badwebnono@gmail.com<br>
          facebook粉絲專頁：<br>
          https://www.facebook.com/BOO-網站評分擴充元件-107774194016837</p>
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