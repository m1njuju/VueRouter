<template>
  <div class="home">
    <h3>HomeView에서 수정하고 있습니다</h3>
    <p>라우터의 / 위치입니다</p>
    <p>아래 HelloWorld 컴포넌트를 불러오고 있습니다.</p>
    <img alt="Vue logo" src="../assets/logo.png">

    <p>아래에 HelloWorld를 불러오고 있습니다</p>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
