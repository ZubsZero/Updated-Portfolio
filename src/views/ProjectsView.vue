<template>
  <NavBar />
  <div class="hero">
    <div class="hero-info">
      <h1 class="this">View My</h1>
      <h1 class="Main-title">Previous Projects</h1>
      <p class="text">Learn more about me through Projects I worked on</p>
      <div class="btns">
        <router-link :to="{ name: 'home' }"
          ><button class="btn1">Go home</button></router-link
        >
      </div>
    </div>
  </div>

  <div class="project-sections">
    <div class="project-section">
      <div class="info">
        <h1 class="h1">JavaScript E-commerce Website</h1>
        <p class="p">
          A E-commerce website built using html, CSS, bootstrap and Javascript
          and selling Gardening equipment
        </p>
        <a href="https://github.com/ZubsZero/TheGardenOfEden"
        target="_blank" ><button class="button">Github</button></a
        >
        <a
          href="https://dancing-dieffenbachia-1e4ff9.netlify.app/"
          target="_blank"
          ><button class="button">Live</button></a
        >
      </div>
      <div class="project-card1">.</div>
    </div>
    <div class="line"></div>
    <div class="project-section2">
      <div class="info">
        <h1 class="h1">Bootstrap Portfolio</h1>
        <p class="p">
          A portfolio website that I mainly used html and Bootstrap to fully
          build it it was one of my first projects
        </p>
        <a href="https://github.com/ZubsZero/Project-_week"
        target="_blank" ><button class="button">Github</button></a
        >
        <a
          href="https://charming-beignet-9e5ad1.netlify.app/"
          target="_blank"
          ><button class="button">Live</button></a
        >
      </div>
      <div class="project-card2">.</div>
    </div>
    <div class="line"></div>

    <div class="project-section3">
      <div class="info">
        <h1 class="h1">Temperature Converter</h1>
        <p class="p">
          I built this temperature as for of practicing javascript and my first
          Javascript Project
        </p>
        <a href="https://github.com/ZubsZero/temp"
        target="_blank"><button class="button">Github</button></a
        >
        <a
          href="https://sunny-wisp-b9b0eb.netlify.app/"
          target="_blank"
          ><button class="button">Live</button></a
        >
      </div>
      <div class="project-card3">.</div>
    </div>
    <div class="line"></div>

    <div class="project-section4">
      <div class="info">
        <h1 class="h1">Calculator</h1>
        <p class="p">
          This is my second Javascript Project and I built a Calculator mainly
          using Html,CSS and Javascript
        </p>
        <a href="https://github.com/ZubsZero/calculator"
        target="_blank" ><button class="button">Github</button></a
        >
        <a
          href="https://snazzy-mochi-768236.netlify.app/"
          target="_blank"
          ><button class="button">Live</button></a
        >
      </div>
      <div class="project-card4">.</div>
    </div>
    <div class="line"></div>

    <div class="project-section5">
      <div class="info">
        <h1 class="h1">BMI Calculator</h1>
        <p class="p">
          My third practice of Javascript where I had to build a bmi calculator
        </p>
        <a href="https://github.com/ZubsZero/BMI"
        target="_blank" ><button class="button">Github</button></a
        >
        <a
          href="https://chic-moonbeam-ce1b21.netlify.app/"
          target="_blank"
          ><button class="button">Live</button></a
        >
      </div>
      <div class="project-card5">.</div>
    </div>
    <div class="line"></div>

    <div class="project-section6">
      <div class="info">
        <h1 class="h1">Recreation of the Hulu Website</h1>
        <p class="p">
          With the use of Vanilla html,css and Javascript I tasked myselfto
          recreate the Hulu Website here at the Academy
        </p>
        <a href="https://github.com/ZubsZero/completed-html"
        target="_blank" ><button class="button">Github</button></a
        >
        <a
          href="https://statuesque-melba-16cd16.netlify.app/"
          target="_blank"
          ><button class="button">Live</button></a
        >
      </div>
      <div class="project-card6">.</div>
    </div>
    <div class="line"></div>

    <div class="project-section7">
      <div class="info">
        <h1 class="h1">YokoHoma Drifters</h1>
        <p class="p">
          A website built using Vue.js and Node.js making use of mySQL as the
          database holding the cars details
        </p>
        <a href="https://github.com/ZubsZero/YokohamaDrifters"
        target="_blank" ><button class="button">Github</button></a
        >
        <a
          href="https://yokohamadrifters-20ebf.web.app/"
          target="_blank"
          ><button class="button">Live</button></a
        >
      </div>
      <div class="project-card7">.</div>
    </div>
    <div class="line"></div>

    <div class="project-section8">
      <div class="info">
        <h1 class="h1">WatchTime</h1>
        <p class="p">
          A 3 week project that makes use of everything I had learned Vue,Node
          ,MySQL ,html,CSS and Javascript so that you able to login and sign up
        </p>
        <a href="https://github.com/ZubsZero/capstone"
        target="_blank" ><button class="button">Github</button></a
        >
        <a
          href="https://watchtime-169a8.web.app/"
          target="_blank"
          ><button class="button">Live</button></a
        >
      </div>
      <div class="project-card8">.</div>
    </div>
    <div class="project-section9">
      <div class="info">
        <h1 class="h1">Vue Portfolio</h1>
        <p class="p">
          My old Vue portfolio made using vue and a github page file to store
          data
        </p>
        <a href="https://github.com/ZubsZero/vue-eomp"
        target="_blank" ><button class="button">Github</button></a
        >
        <a
          href="https://vue-portfolio-afa0d.web.app/"
          target="_blank"
          ><button class="button">Live</button></a
        >
      </div>
      <div class="project-card9">.</div>
    </div>
  </div>
  <Footer />
</template>
<script>
import Footer from "@/components/Footer-Comp.vue";
import NavBar from "@/components/NavBar-Comp.vue";
export default {
  name: "Projects",
  components: { NavBar, Footer },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Zilla+Slab:wght@400;700&display=swap");

.hero {
  background-image: url("/src/Images/wp2808718-black-gold-wallpaper-hd.jpg");
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
.line {
  border-bottom: 1px solid #ae6006;
  height: 1rem;
}

.hero-info {
  position: relative;
  top: 30%;
  margin-left: 8rem;
  color: white;
}

.this,
.Main-title,
.text,
.btn1 {
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

.project-section {
  display: flex;
  gap: 1rem;
}

.project-section2 {
  display: flex;
  gap: 1rem;
  flex-direction: row-reverse;
}

.project-section3 {
  display: flex;
  gap: 1rem;
}

.project-section4 {
  display: flex;
  gap: 1rem;
  flex-direction: row-reverse;
}
.project-section5 {
  display: flex;
  gap: 1rem;
}
.project-section6 {
  display: flex;
  gap: 1rem;
  flex-direction: row-reverse;
}
.project-section7 {
  display: flex;
  gap: 1rem;
}
.project-section8 {
  display: flex;
  gap: 1rem;
  flex-direction: row-reverse;
}

.project-section9 {
  display: flex;
  gap: 1rem;
}

.image {
  height: 27rem;
  width: 50rem;
}
.project-sections {
  margin: 6rem;
  display: flex;
  flex-direction: column;
  gap: 4rem;
}

.info {
  margin-top: 8rem;
}

.h1 {
  color: #cd8500;
}

.p {
  color: #ffffff;
}

.project-card1 {
  background-image: url("https://i.postimg.cc/zvGF24tg/Screenshot-2023-07-05-160254.png");
  background-position: center;
  width: 50rem;
  background-size: cover;
  background-repeat: no-repeat;
  height: 25rem;
}

.project-card2 {
  background-image: url("https://i.postimg.cc/xTS0HYZ8/Screenshot-2023-07-05-160213.png");
  background-position: center;
  width: 50rem;
  background-size: cover;
  background-repeat: no-repeat;
  height: 25rem;
}

.project-card3 {
  background-image: url("https://i.postimg.cc/BbN44PBz/Screenshot-2023-07-05-160514.png");
  background-position: center;
  width: 50rem;
  background-size: cover;
  background-repeat: no-repeat;
  height: 25rem;
}

.project-card4 {
  background-image: url("https://i.postimg.cc/fRzScYPV/Screenshot-2023-07-05-160346.png");
  background-position: center;
  width: 50rem;
  background-size: cover;
  background-repeat: no-repeat;
  height: 25rem;
}

.project-card5 {
  background-image: url("https://i.postimg.cc/vTvHTNb3/Screenshot-2023-07-05-160425.png");
  background-position: center;
  width: 50rem;
  background-size: cover;
  background-repeat: no-repeat;
  height: 25rem;
}

.project-card6 {
  background-image: url("https://i.postimg.cc/QtXzs4YX/Screenshot-2023-07-05-160625.png");
  background-position: center;
  width: 50rem;
  background-size: cover;
  background-repeat: no-repeat;
  height: 25rem;
}

.project-card7 {
  background-image: url("https://i.postimg.cc/13cv6mMf/Screenshot-2023-11-10-113327.png");
  background-position: center;
  width: 50rem;
  background-size: cover;
  background-repeat: no-repeat;
  height: 25rem;
}

.project-card8 {
  background-image: url("https://i.postimg.cc/mZd7Wxn0/image-8.png");
  background-position: center;
  width: 50rem;
  background-size: cover;
  background-repeat: no-repeat;
  height: 25rem;
}
.project-card9 {
  background-image: url("https://i.postimg.cc/WtRNxqR0/Screenshot-2023-11-10-124720.png");
  background-position: center;
  width: 50rem;
  background-size: cover;
  background-repeat: no-repeat;
  height: 25rem;
}

.button {
  margin-left: 1rem;
  border-radius: 1rem;
  width: 6rem;
  background-color: black;
  color: #cd8500;
}

.button:hover {
  color: white;
  transition: 0.3s all;
  cursor: pointer;
  box-shadow: 1px 7px 2px white;
}
</style>
