<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <div class="header-top fixed-top">
    <div class="container">
      <div class="row">
        <div class="col">
          <ul>
          <li class="nav-item"><a href="#" class="nav-link link-dark px-2 active" aria-current="page">回首頁</a></li>
          </ul>
        </div>
        <div class="col-md-auto ml-4 pt-2">
          <div class="row">
            <div class="col">
              <ul class="header-top-link">
              <li class="nav-item  mr-4">Vita微光心靈塔羅</li>
              <li class="nav-item"><a href="#" class="px-2"><i class="fab fa-facebook-square"></i></a></li>
              <li class="nav-item"><a href="#" class="px-2"><i class="fab fa-instagram"></i></a></li>
              </ul>
            </div>
            <div class="col">
              <ul class="header-top-link">
              <li class="nav-item">微光文創工作室</li>
              <li class="nav-item"><a href="#" class="px-2"><i class="fab fa-facebook-square"></i></a></li>
              <li class="nav-item"><a href="#" class="px-2"><i class="fab fa-instagram"></i></a></li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col col-lg-2">
            <a><h4 class="booking-icon">立即預約</h4></a>
        </div> 
      </div>
    </div>
  </div>

    <div class="banner-block">
      <img src="../img/banner-1.jpg">
    </div>

  <header class="border-bottom fixed-bottom sticky-top">
    <div class="container">
      <a href="/" class="logo">
        <img src="../img/logo-wh.png" width="38px">
      </a>
      <div class="container">
        <nav class="mb-4">
          <div class="container">
             <ul class="nav header-menu">
              <li class="nav-item">首頁</li>
              <li class="nav-item">關於微光</li>
              <li class="nav-item">商品頁面</li>
              <li class="nav-item">租賃方案</li>
              <li class="nav-item">文創商品</li>
              <li class="nav-item">手作課程</li>
              <li class="nav-item">歷年活動</li>
              <li class="nav-item">cart</li>
            </ul>
          </div>
        </nav>
      </div>
    </div>
  </header>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>
