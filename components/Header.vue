<template>
  <header id="header">
      <div class="inner">

          <!-- Logo -->
           
                <nuxt-link to="/" class="logo">
                  <span class="symbol"><img style="width:100px;height:100px;" src="~/assets/images/logo.png" alt="" /></span><span class="title">wayne1894 個人作品集</span>
                </nuxt-link>
         

          <!-- Nav -->
              <nav>
                  <ul>
                      <li><a href="#menu">Menu</a></li>
                  </ul>
              </nav>

      </div>
  </header>
</template>
<style lang="scss" scoped>
  .symbol img{
    border-radius: 100px;
  }
  .title{
    font-size: 30px;
  }
</style>