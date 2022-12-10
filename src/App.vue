<template>
  <div id="app">
  <HeaderComp/>
  <MySelf/>
  <MyExperiences/>
  <FullStack />
  </div>
</template>
<script> 

import HeaderComp from'./components/HeaderComp.vue'
import MySelf from'./components/MySelf.vue'
import MyExperiences from'./components/MyExperiences.vue'
import FullStack from'./components/FullStack.vue'


export default {
   

  components: {
    HeaderComp,
    MySelf,
    MyExperiences,
    FullStack,
  }
}
</script>

<style lang="scss">
</style>
