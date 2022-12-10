<template>
  <div>
    <nav class="navbar navbar-expand-lg bg-light fs-5">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">CV</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" @click="toggle = !toggle" href="#">About Me</a>
          <CvCurriculum />
        </li>
        <li class="nav-item">
          <a class="nav-link"  @click="isHidden = !isHidden"  href="#">My experiences</a>
          <MyExperiences />
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">searching for...</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
<div v-show="toggle" class="me">  <img class="rounded-circle mx-auto d-block" src="../assets/me.jpg" alt="my picture">  
<br>
<div class="name text-center"> <h1>Cristina Andreea Danescu</h1>
<h3>Junior Full stack developer</h3>
<h5>  West Midlands, England, United Kingdom </h5></div>


    
  </div></div>
</template>






<script>


export default {
  name: 'PrimaParte',
  data(){
    return {toggle:true,
    isHidden:true}
  },

}
  
</script>


<style scoped lang="scss">

img{width:20%;
&:hover {
    filter: sepia(30%) brightness(100%);} }

.me{padding: 5%;
  background: linear-gradient(to top, #cececa 0%, #727271 100%);
  &:hover{
    filter: sepia(30%) brightness(120%);}}
    nav{position:fixed!important;}
</style>
