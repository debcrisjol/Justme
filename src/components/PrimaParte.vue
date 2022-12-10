<template>
  <div id="start">
    <nav class="navbar w-100 navbar-expand-lg bg-light fs-5">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">CV</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#cv">About Me</a>

            </li>
            <li class="nav-item">
              <a class="nav-link" href="#exp">My experiences</a>

            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">searching for...</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <div id="me"> <img class=" rounded-circle mx-auto d-block" src="../assets/me.jpg" alt="my picture">
      <br>
      <div class="name text-center">
        <h1>Cristina Andreea Danescu</h1>
        <h3>Junior Full stack developer</h3>
        <h5> West Midlands, England, United Kingdom </h5>
      </div>



    </div>
  </div>
</template>






<script>


export default {
  name: 'PrimaParte',

}
</script>


<style scoped lang="scss">
#start{height: 100vh;}
img{
padding:70px;}
nav {
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  background: linear-gradient(45deg, #4d4c4c, #f8f5f6fc, #b3b3b2, #0e0e0e);
  background-size: 400% 400%;
  animation: gradient 20s ease infinite;
  


@keyframes gradient {
  0% {
    background-position: 0% 50%;
  }

  50% {
    background-position: 100% 50%;
  }

  100% {
    background-position: 0% 50%;
  }
}


img {
  width: 10%;

  &:hover {
    filter: sepia(40%) brightness(100%);
  }
}

}

nav {
  position: fixed !important;

}
</style>
