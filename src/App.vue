<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
</script>

<template>

  <Header msg="header" />
   <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <HelloWorld msg="Hello Vue 3 + Vite 6" />
  <Footer msg="footer" />
</template>

<style>
#app {

}

@import url('https://fonts.googleapis.com/css2?family=Noto+Serif+TC:wght@200;300;400;500;600;700&display=swap');

body {
  
  font-family: 'Noto Serif TC', serif;
  letter-spacing: 4.5px;
  overflow-x: hidden;
}
section {
  padding: 20px 40px;
}
h1,h2,h3,h4,h5 {
  font-size: 24px;
  font-family: 'Noto Serif TC', serif;
  letter-spacing: 31px;
}
p{
  color: #7e7e7e;
}

h1.titlestyle:before{
  content: '';
  position: absolute;
  width: 37vw;
  height: 1px;
  left: 0;
  margin-top: 22px;
  clear: both;
  background-color: #AF6363;
}
h1.titlestyle:after{
  content: '';
  position: absolute;
  width: 37vw;
  height: 1px;
  right: 0;
  margin-top: 22px;
  clear: both;
  background-color: #AF6363;
}

ul,li {
  margin: 0;
  padding: 0;
  justify-content: center;
    display: table-cell;
  vertical-align: middle;

}
a{
  text-decoration:none!important;
}

.header-top{
  background-color: #FFF5E2;
  position: sticky;
}
.booking-icon{
  background-color: #E58E9B;
  padding: 20px;
  border-radius: 0 0 20px 20px;
  color: #ffffff;
  text-decoration:none;
  display: flex;
  right: 120px;
  position: absolute;
  top: 0;
}

ul.header-top-link li{
  color: #847A62;
  font-size: 10px;
  white-space:nowrap;
}
ul.header-top-link li a{
  color: #847A62;
}

header {
  background-color: #845B5B;
}

.logo img {
  position: relative;
  top: 42px;
  right: 20px;
}
ul.header-menu li{
  color: #ffffff;
  border-right: 1px solid #ffffff;
  margin: 14px;
  padding-right: 30px;
}

ul.header-menu li a:hover {
  content: " ";
  background-image: url(../img/linkicon.png);
  background-repeat: no-repeat;
  background-position: 32px 180px;
  color:#847A62;
}

.banner-block{
  height: 100vh;

}
.banner-block img{
  width: 100%;
  overflow: hidden;
}
span.titleicon {
    background-image: url(../img/titleicon.png);
    background-repeat: no-repeat;
    position: relative;
    top: -65px;
    left: 47%;
    max-width: 100%;
}

.sister-brand{
  background-repeat: repeat-y;
  background-color: #FBF1ED;
}
.sister-brand-bg{
  background-image: url("../img/footer-bg.png");
  background-size: 60%;
}
.page-top{
  background-color: #C0554B;
  height: 20px;
  margin-bottom: 200px;
}
.page-top img {
  position: relative;
  left: 90%;
  top: 0;
  margin-top: -34px;
}
.page-top-text{
  position: relative;
  top: 0;
  margin-top: 24px;
  color: #C0554B;
  right: 30px;
}
.row.footer-block{
  max-width: 1440px;
  margin: 0 auto;
}
.row.footer-block img{
  margin-bottom: 120px;
}

.footer-menu{
  -webkit-writing-mode: vertical-lr;
  writing-mode: vertical-lr; 
  display: inline-grid;
  cursor: pointer; 
  line-height: 5rem;
  letter-spacing: 0.6rem;
  font-size: 22px;
  color: #333333;

}
.footer-menu li{
  padding: 12px;
}
p.info-list-title{
  color: #333333;
  font-weight: 700;
  margin-bottom: 0px;
}
ul.footer-menu li:hover {
  content: " ";
  background-image: url(../img/linkicon.png);
  background-repeat: no-repeat;
  background-position: 32px 180px;
  margin-bottom: -66px;
  color: #7c7c7c;
}

</style>
