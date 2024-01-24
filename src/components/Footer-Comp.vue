<template>
    <div class="container">
  <footer class="row row-cols-1 row-cols-sm-2 row-cols-md-5 py-5 my-5 border-top">
    <div class="col mb-3">
      <img src="https://cdn-thumbs.imagevenue.com/31/df/25/ME17J0I3_t.png" alt="" class="img">
      <p class="text-muted">&copy; Zubair Matthee 2022</p>
    </div>

    <div class="col mb-3">

    </div>

    <div class="col mb-3">
      <h5>Section</h5>
      <ul class="nav flex-column">
        <li class="nav-item mb-2"><router-link  class="nav-link p-0 text-muted" to="/">Home</router-link></li>
        <li class="nav-item mb-2"><router-link  class="nav-link p-0 text-muted" to="/about">About</router-link></li>
        <li class="nav-item mb-2"><router-link  class="nav-link p-0 text-muted" to="/projects">Projects</router-link></li>
        <li class="nav-item mb-2"><router-link  class="nav-link p-0 text-muted" to="/contact">Contact</router-link></li>

      </ul>
    </div>
    <div class="col mb-3">
        <h5>Contact</h5>
        <p class="orange">Click on my email to contact</p>
        <a href="mailto:zubairmatthee262@gmail.com">zubairmatthee262@gmail.com</a>
        <p><br>Or <br><br>
        <span>069 244 5575</span>
        </p>
    </div>
  </footer>
</div>

<div class="b-example-divider"></div>


</template>
<style scoped>
 .nav-link.p-0.text-muted {
    color: #ae6006 !important;
 ;
}

footer {
    color: white; 
}

.text-muted {
    color: white !important;
}

.img {
    height:4rem ;
    width: 4rem;
}

.orange {
    color: #ae6006;
}

p{
  color: #ae6006;
}


span {
  color: aliceblue !important;
}
a {
    color: aliceblue;
}
</style>