<template>
  	<div id="wrapper">

				<!-- Header -->
          <Header></Header>

				<!-- Menu -->
            <Menu></Menu>

				<!-- Main -->
				<div id="main">
						<div class="inner">
							<header>
								<p>
                                    1、網站後端 - node.js、資料庫系統、firebase <br>
                                    2、網頁前端 - CSS / JS / 動畫網頁 <br>
                                    3、前端工程開發- vue.js / nuxt.js<br>
                                    4、其他 - linux 架站管理、wordpress 、網頁設計<br>
                                 </p>
							</header>
							<section class="tiles">
								<article>
									<span class="image">
										<img src="~/assets/images/pic01.jpg" alt="" />
									</span>
									<nuxt-link to="/bbqnotes">
<!--										<h2>烤肉?專業喔!</h2>-->
										<div class="content">
											<p>烤肉?專業喔!</p>
										</div>
									</nuxt-link>
								</article>
								<article>
									<span class="image">
										<img src="~/assets/images/2.png" alt="" />
									</span>
									<nuxt-link to="/infometro">
<!--										<h2>infometro 資訊地鐵站</h2>-->
										<div class="content">
											<p>infometro 資訊地鐵站</p>
										</div>
									</nuxt-link>
								</article>
								<article>
									<span class="image">
										<img src="~/assets/images/unnamed2.jpg" alt="" />
									</span>
									<nuxt-link to="/boo">
										<div class="content">
											<p>BOO! 網站評分 - 爛網站給個噓</p>
										</div>
									</nuxt-link>
								</article>
								<article>
									<span class="image">
										<img src="~/assets/images/5.png" alt="" />
									</span>
									<nuxt-link to="/teach">
										<div class="content">
											<p>wayne1894教學網</p>
										</div>
									</nuxt-link>
								</article>
							</section>
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

<style lang="scss" scoped>
  h1{
    font-size: 1.75em;
  }
  .content{
    font-weight: bold;
  }
</style>
