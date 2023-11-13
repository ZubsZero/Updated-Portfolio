<template>
  <div class="nav">
      <nav>
          <div class="logo">
              <img src="https://i.postimg.cc/VLvmYJRn/image-removebg-preview-1.png" alt="logo" class="logo">
          </div>
          <ul class="NavBar">
              <router-link to="/" class="list-item">Home</router-link>
              <router-link to="/about" class="list-item">About</router-link>
              <router-link to="/contact" class="list-item">Contact</router-link>
              <router-link to="/projects" class="list-item">Projects</router-link>





          </ul>
       
      </nav>
  </div>
</template>

<script>
export default {

}
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Julius+Sans+One&family=Monoton&display=swap');


.list-item {
  color: rgb(255, 255, 255);
  text-decoration: none;
  margin-left: 17rem;

  position: relative;
  font-size: 0.9rem;
  font-family: 'Julius Sans One', sans-serif;

}

nav {
  background-color: black ;
  display: flex;
  position: fixed;
  width: 100%;
  z-index: 1;
}

.logo {
width: 4rem;
height: 4rem;    
margin-left: 1rem

}

.NavBar {
  margin-top: 1.4rem ;
}

.list-item:after{
  content: "";
  position: absolute;
  background-color: #cd8500;
  height: 4px;
  width: 0;
  left: 0px;
  bottom: -9px;
  transition: 0.3s;
}
.list-item:hover{
  color: #ffffff;
}
.list-item:hover:after{
  width: 100%;
}

@media only screen and (max-width:400px) {
  nav {
      width: 100% auto;
  }
  html,body {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
      overflow-x:hidden;
  }
  .NavBar {
      display: flex;
      margin-left: 0rem;
  }
  .list-item {
      margin-left: 1.4rem;
      font-size: 0.7rem;
  }
  .list-item:after{
  content: "";
  position: absolute;
  background-color: #ce0505;
  height: 4px;
  width: 0;
  left: 0px;
  bottom: 14px;
  transition: 0.3s;
}
.logo {
  width: 3rem;
  height: 3rem;
  margin-left: 0.1rem
}
}


</style>