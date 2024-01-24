<template>
 <NavBar/>
 <div class="hero">
    <div class="hero-info">
      <h1 class="this">THIS IS</h1>
      <h1 class="Main-title">Zubair Matthee</h1>
      <p class="text">Learn more about me through this portfolio</p>
      <div class="btns">
        <router-link :to="{ name : 'projects'}"><button class="btn1">View Projects</button></router-link>
        <a href="https://drive.google.com/file/d/1dfQxVdaCln8OuxFHkJPYyQeax1yMBiTy/view?usp=sharing" target="_blank"><button class="btn1">View CV</button></a>

      </div>
    </div>
  </div>
  <div class="container-brief" ref="containerBrief">
    <div class="img-con" ref="imgCon">
      <img
        src="https://i.postimg.cc/6Q80SGvw/C12-Zubair-Matthee-removebg-preview.png"
        alt="img"
        class="image"
      />
    </div>
    <div class="line"></div>
    <div class="line"></div>
    <div class="line"></div>

    <div class="brief" ref="brief">
      <h1 class="main-title">Zubair Matthee</h1>
      <h2 class="sub-title">Web Developer</h2>
      <hr class="line" />
      <p class="text2">
        An aspiring full stack developer with a quiet exterior looking to build
        and host websites as a passion and striving to gain more experience and
        knowledge in more languages as a way to up-skill myself and further
        myself in the IT sector. Why not learn more about me on the about page.
      </p>
      <hr class="line" />
    </div>
  </div>
  <h1 class="h1">Why Choose Me?</h1>
  <div class="cards-conatiner">
    <div class="cards">
      <div class="quiet">
        <div class="info">
          <h2 class="h2">Silent Working</h2>
          <p class="p">
            I am generally a quiet person but I am also hard working
          </p>
        </div>
      </div>
      <div class="deadline">
        <div class="info">
          <h2 class="h2">Deadline Driven</h2>
          <p class="p">
            Never fails to miss a deadline even when under pressure to deliver
          </p>
        </div>
      </div>
      <div class="dedicated">
        <div class="info">
            <h2 class="h2"> Dedicatation</h2>
            <p class="p">Very dedictated to further myself in the IT sector </p>
        </div>
      </div>
      <div class="learning">
        <div class="info">
            <h2 class="h2">A learner</h2>
            <p class="p">Always looking to learn wherever it can be taught</p>
        </div>
      </div>
      <div class="tech">
        <div class="info">
          <h2 class="h2">Tech Savvy</h2>
          <p class="p">Very informed about use cases of modern technology</p>
        </div>
      </div>

    </div>
  </div>
  
 <Footer/>
</template>

<script>
import NavBar from "@/components/NavBar-Comp.vue";
import Footer from "@/components/Footer-Comp.vue";

export default {
  name: "HomeView",
  components: {
    NavBar,
    Footer,
  },
 
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Zilla+Slab:wght@400;700&display=swap");
.hero {
  background-image: url("/src/Images/1236755.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed !important;
  height: 50rem;
  width: 100% !important;
  margin: 0;
  padding: 0;
  overflow: hidden; 
}

.hero-info {
  position: relative;
  top: 30%;
  margin-left: 8rem; 
  color: white;
}



.this, .Main-title, .text, .btn1 {
  opacity: 0; 
  animation: fade-in 1s forwards;  
}

.this {
  animation-delay: 1s; 
}

.Main-title {
  animation-delay: 1.5s; 
  font-size: 7rem;
  font-family: "Zilla Slab", serif;
  font-weight: 700;
  color: #ae6006;
  -webkit-text-stroke-width: 0.9px;
  -webkit-text-stroke-color: rgb(5, 5, 5);
  text-shadow: 0 0 6px #cd8500;
}
.btns {
  gap: 1rem;
  display: flex;
}

.text {
  animation-delay: 2s; 
  font-size: 1.3rem;
}

.btn1 {
  animation-delay: 2.5s; 
  height: 3.5rem;
  width: 8rem;
  border-radius: 1.3rem;
  color: rgb(255, 255, 255);
  background: #000000;
  margin-top: 2rem;
}

.btn1:hover {
  height: 3.5rem;
  width: 8rem;
  border-radius: 1.3rem;
  color: rgb(255, 255, 255);
  background: #000000;
  margin-top: 2rem;
  box-shadow: 0 0 7px white;
  transition: 400ms all;
  background-color: transparent;
}

@keyframes fade-in {
  0% {
    opacity: 0; 
    transform: translateY(-20px); 
  }
  100% {
    opacity: 1; 
    transform: translateY(0); 
  }
}

@import url("https://fonts.googleapis.com/css2?family=Zilla+Slab:wght@400;700&display=swap");

.container-brief {
  display: flex;
  background-color: rgb(0, 0, 0);
  border-top: 1px solid white;
  border-bottom: 1px solid white;
  margin: 4rem;
  gap: 5rem;
  opacity: 1;
  transform: translateX(0);
}

.img-con {
  width: 15rem;
  height: 20rem;
  margin: 4rem;
  opacity: 1;
  transform: translateX(-50px);
}

.image {
  width: 15rem;
  height: 20rem;
  object-fit: cover;
}

.brief {
  margin: 4rem;
}

.main-title {
  font-family: "Zilla Slab", serif;
  font-size: 4rem;
  color: #ae6006;
}

.sub-title {
  font-family: "Zilla Slab", serif;
  font-size: 2rem;
  color: white;
}

.text2 {
  color: white;
}

.line {
  color: white;
}

.in-view .image {
  animation: fadeInLeft 1s forwards;
}

.in-view .brief {
  animation: fadeInRight 1s forwards;
}

@keyframes fadeInLeft {
  to {
    opacity: 1;
    transform: translateX(20px);
  }
}

@keyframes fadeInRight {
  to {
    opacity: 1;
    transform: translateX(-20px);
  }
}

.line {
  border-left: 1px solid #ae6006;
}

@import url("https://fonts.googleapis.com/css2?family=Zilla+Slab:wght@400;700&display=swap");

.h1 {
  text-align: center;
  color: #ae6006;
  font-family: "Zilla Slab", serif;
}

.cards {
  margin: 4rem;
  display: flex;
  align-items: center;
  justify-content: center;
}

.quiet,
.deadline,
.dedicated,
.learning,
.tech {
  width: 17rem;
  height: 15rem;
  border: 1px solid white;
  transition: background-color 0.6s, color 0.6s;
}

.quiet:hover {
  background-color: #ae6006;
  color: black;
}

.deadline:hover {
  background-color: #ae6006;
  color: black;
}

.dedicated:hover {
  background-color: #ae6006;
  color: black;
}
.learning:hover {
  background-color: #ae6006;
  color: black;
}

.tech:hover {
  background-color: #ae6006;
  color: black;
}




.quiet:hover .h2,
.quiet:hover .p {
  color: black;
}

.deadline:hover .h2,
.deadline:hover .p {
  color: black;
}

.dedicated:hover .h2,
.dedicated:hover .p {
  color: black;
}

.learning:hover .h2,
.learning:hover .p {
  color: black;
}

.tech:hover .h2,
.tech:hover .p {
  color: black;
}

.h2 {
  font-size: 1.6rem;
  text-align: center;
  font-family: "Zilla Slab", serif;
  color: #ae6006;
}

.p {
  text-align: center;
  color: white;
  margin: 2rem;
}

.info {
  margin-top: 3rem;
}

@media only screen and (max-width: 300px) {
  .hero {
  background-image: url("/src/Images/1236755.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: fixed;
  height: 50rem;
  width: 100% !important;
  margin: 0;
  padding: 0;
  overflow: hidden; 
}

  .hero-info {
  position: relative;
  top: 20%;
  margin-left: 2rem; 
  color: white;
}



.Main-title {
  animation-delay: 1.5s; 
  font-size: 4rem;
  font-family: "Zilla Slab", serif;
  font-weight: 700;
  color: #ae6006;
  -webkit-text-stroke-width: 0.9px;
  -webkit-text-stroke-color: rgb(5, 5, 5);
  text-shadow: 0 0 6px #cd8500;
}

.container-brief {
  display: flex;
  flex-direction: column;
  background-color: rgb(0, 0, 0);
  border-top: 1px solid white;
  border-bottom: 1px solid white;
  margin: 0rem;
  gap: 0rem;
  opacity: 1;
  transform: translateX(0);
}

.img-con {
  width: 15rem;
  height: 20rem;
  margin-left: 5rem;
  opacity: 1;
  transform: translateX(-50px);
}

.image {
  width: 15rem;
  height: 20rem;
  object-fit: cover;
}

.brief {
  margin-left: 0rem;
  text-align: center;
  width: 100%;
}

.main-title {
  font-family: "Zilla Slab", serif;
  font-size: 4rem;
  color: #ae6006;
}

.sub-title {
  font-family: "Zilla Slab", serif;
  font-size: 2rem;
  color: white;
}

.text2 {
  color: white;
}

.cards {
  margin: 0rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin-left: rem;
}


}
</style>