<template>
  <div id="app">
  <PrimaParte />
  <CvCurriculum />
  <MyExperiences />
  </div>
</template>

<script>
import PrimaParte from  './components/PrimaParte.vue'
import CvCurriculum from  './components/CvCurriculum.vue'
import MyExperiences from  './components/MyExperiences.vue'

export default {
  name: 'App',
  components: {
    PrimaParte,
    CvCurriculum,
    MyExperiences
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
