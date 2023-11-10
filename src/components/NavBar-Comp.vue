<template>
<header class="header">  
      <nav class="navbar navbar-dark bg-dark fixed-top">
  <div class="container-fluid">
    <a class="navbar-brand" href="#"><img src="https://i.postimg.cc/VLvmYJRn/image-removebg-preview-1.png" alt="" class="img"></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasDarkNavbar" aria-controls="offcanvasDarkNavbar">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasDarkNavbar" aria-labelledby="offcanvasDarkNavbarLabel">
      <div class="offcanvas-header">
        <h5 class="offcanvas-title" id="offcanvasDarkNavbarLabel">Menu</h5>
        <button type="button" class="btn-close btn-close-white" data-bs-dismiss="offcanvas" aria-label="Close"></button>
      </div>
      <div class="offcanvas-body">
         <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
          <li class="nav-item">
            <router-link class="nav-link active" :to="{ name: 'home'}" >Home</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" :to="{name: 'about'}" >About</router-link>
          </li>
            <li class="nav-item">
            <router-link  class="nav-link" href="#" :to="{name : 'projects'}" @click="reloadPage">Projects</router-link>
          </li>
          <div class="cv">
            <label for="CV"> View my CV</label>
            <a :href="pdfUrl" download="ZubairMatthee_CV.pdf"><button class="button">CV</button></a>
          </div>
          <div class="line"></div>
          <div class="line"></div>
          <div class="line"></div>
         
        </ul>
      </div>
    </div>
  </div>
</nav>
</header>
</template>
<script >
  export default {
  data() {
    return {
      pdfUrl: "https://drive.google.com/file/d/1TJJ2n-wQoRcy1YC7Gp8ggTJJlFeJlNZJ/view?usp=sharing", 
    };
  },
};
</script>


<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Zilla+Slab:wght@400;700&display=swap");


.navbar.navbar-dark.bg-dark.fixed-top{
    background-color: transparent !important;
    margin: 1rem;
}

.img {
    height:4rem ;
    width: 4rem;
}

.offcanvas-header{
  background-color: black !important;
  color: white;
}

.offcanvas-title {
color: #ae6006;
 font-family: "Zilla Slab", serif;
}

.offcanvas-body {
  background-color: black;
}

label {
  color: #ae6006;
}

.cv {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  text-align: center;
  margin-top: 2rem ;
}

.button {
  width: 7rem;
  height: 3rem;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-left: 7.5rem ;
  background-color: black;
  color: white;
}

.button:hover {
  cursor: pointer;
  transition: all 0.4s ease-in-out;
  background: #ae6006;
  color: black;

}

.nav-item {
  margin-top: 3rem;
  text-align: center;
}


.line {
  border-bottom: 1px solid #ae6006 ;
  margin-top: 3rem ;
}

.nav-item {
  color: white;
}

.nav-link:after {
  content: "";
  position: absolute;
  background-color: #ae6006;
  height: 4px;
  width: 0;
  left: 0px;
  bottom: -9px;
  transition: 0.3s;
}

.nav-link {
  color: rgb(255, 255, 255);
  text-decoration: none;
  position: relative;
  font-size: 0.9rem;
}

a {
  text-decoration: none;
}


.nav-link:hover {
  color: #ffffff;
}
.nav-link:hover:after {
  width: 100%;
}

label {
  font-size: 1.6rem;
  font-family: "Zilla Slab", serif;

}

@media only screen and (max-width: 300px) {
  .navbar.navbar-dark.bg-dark.fixed-top{
    background-color: transparent !important;
    margin: 1rem;
    position: relative;
}
}
</style>