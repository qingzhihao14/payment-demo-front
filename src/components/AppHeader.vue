<template>
  <!-- 公共头 -->
  <header id="header">
    <section class="container">
      <!-- <h1 id="logo">
        <a href="#/" title="">
          <img src="../assets/img/logo.png" width="100%" alt="">
        </a>
      </h1> -->
      <div>
        <ul class="nav">
          <router-link to="/" tag="li" active-class="current" exact>
            <a>服务选择</a>
          </router-link>
          <router-link to="/orders" tag="li" active-class="current">
            <a>我的订单</a>
          </router-link>
          <router-link to="/download" tag="li" active-class="current">
            <a>下载账单</a>
          </router-link>
        </ul>
      </div>
      <div class="clear"></div>
    </section>
  </header>
</template>