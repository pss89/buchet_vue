<template>
  <Header />
  <!-- 
    - 각 컴포넌트 실제 호출?
    - msg 변수는 각 컴포넌트에서 사용 가능
   -->
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <!-- <SubPage msg="두번째 단락임"/> -->
  <Footer />
</template>

<script>
// 컴포넌트 import
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/common/Header.vue';
import Footer from './components/common/Footer.vue';
// import SubPage from './components/SubPage.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Header,
    Footer
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
