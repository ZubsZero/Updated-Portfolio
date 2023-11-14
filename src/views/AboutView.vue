<template>
  <NavBar />
  <div class="hero">
    <div class="hero-info">
      <h1 class="this">Learn More</h1>
      <h1 class="Main-title">About</h1>
      <h1 class="Main-title">Me</h1>
      <div class="btns">
        <router-link :to="{ name : 'projects'}"><button class="btn1">View Projects</button></router-link>
      </div>
    </div>
  </div>
  <div class="Profile-Cards">
    <div class="column">
      <div class="Profile">
        <div class="profile-card">
          <div class="image3">
            <img
              src="https://i.postimg.cc/3xLnjgVm/C12-Zubair-Matthee-removebg-preview.png"
              alt=""
              class="image1"
            />
          </div>
          <div class="info">
            <ul class="aboutme">
              <h2 class="h2">Profile Card</h2>
              <li class="list-item">
                Full Name : <span class="color">Zubair Matthee</span>
              </li>
              <li class="list-item">
                Location: <span class="color">Cape Town</span>
              </li>
              <li class="list-item">
                Email: <span class="color">zubairmatthee262@gmail.com</span>
              </li>
              <li class="list-item">
                Github: <span class="color">ZubsZero</span>
              </li>
              <li class="list-item">
                LinkedIn: <span class="color">Zubair Matthee</span>
              </li>
            </ul>
          </div>
        </div>
        <div class="line2"></div>
      </div>
      <div class="experience">
        <div class="experience-card">
          <div class="info2">
            <h3 class="h3">Life Choices Studio - Experience</h3>
            <div class="line"></div>
            <div class="p">Status : Current</div>
            <div class="line"></div>
            <p class="p">
              I completed a six-month course at Life Choices Academy, where I
              learned HTML, CSS, JavaScript, Vue.js, Node.js, and MySQL, gaining
              skills in both front-end and back-end web development. This
              program has prepared me for a career in web development and taught
              me to be prepared for the workplace and am now up-skilling myself
              as an intern at Life Choices Studio to further my knowlegdge and
              broaden my horizon
            </p>
          </div>
        </div>
      </div>
    </div>

    <div class="line3"></div>

    <div class="biography">
      <div class="biography-card">
        <h2 class="h22">My Biography</h2>
        <div class="line"></div>
        <p class="p">
          The words to describe me best is observant , I visually learn from my
          surroundings , I am patient , I love solving problems . All my life I
          grew up around technology Xbox and PlayStation both ,with that have
          been infatuated with anything technologically made
        </p>
        <div class="General">
          <h2 class="h22">General Information</h2>
          <div class="line"></div>
          <ul class="general">
            <li class="list-item">Date Of Birth: 17 January 2005</li>
            <li class="list-item">Residence: Matroosfontein - Elsies River</li>
            <li class="list-item">Language: English</li>
          </ul>
        </div>
        <div class="passion">
          <h2 class="h22">My Passion Board</h2>
          <div class="line"></div>
          <p class="p">
            I enjoy playing games on the pc I have bought recently , which is
            also the PC I use to practice my code , I also enjoy watching Anime
            which is a Japanese styled series , I like listening to music that
            gives motivation and music that makes you relax
          </p>
        </div>
      </div>
    </div>
  </div>
  <h2 class="h222">Education</h2>
  <div class="education-row">
    <div class="education">
      <div class="high">
        <div class="high-info">
          <h4 class="h4">Elsie's River High School - 2022</h4>
          <div class="line"></div>
          <p class="p">
            During my time at Elsies River High School, I dedicated myself to
            mastering Computer Applications and Technology (CAT). Through hard
            work and perseverance, I became the top achiever in my class and
            proudly received a certificate in CAT during my 12th-grade year,
            marking a significant achievement in my academic journey. This
            accomplishment not only reflects my passion for technology but also
            showcases my commitment to excellence in education.
          </p>
        </div>
      </div>
      <div class="LC">
        <div class="LC-info">
          <h4 class="h4">Life Choices Academy - 2023</h4>
          <div class="line"></div>
          <p class="p">
            After high school, I was eager to further my knowledge in the realm
            of technology. I enrolled in Life Choices Academy, where I embarked
            on an exciting journey to learn various coding languages, including
            Vue, HTML, JavaScript, CSS, Node.js, MySQL, and Bootstrap. This
            decision has been instrumental in shaping my career and opening up a
            world of opportunities in the field of web development and software
            engineering.
          </p>
        </div>
      </div>
    </div>
  </div>
  <div class="skills-row">
    <h1 class="h1">Skills</h1>
    <div class="skills">
      <div class="skill">
        <div class="img">
          <img
            src="https://i.postimg.cc/yYQHWZnf/icons8-html-480.png"
            alt=""
            class="image"
          />
        </div>
        <div class="skill-info">
          <h4>HTML</h4>
        </div>
      </div>
      <div class="skill">
        <div class="img">
          <img
            src="https://i.postimg.cc/sDDzVcPQ/icons8-css-480.png"
            alt=""
            class="image"
          />
        </div>
        <div class="skill-info">
          <h4>CSS</h4>
        </div>
      </div>
      <div class="skill">
        <div class="img">
          <img
            src="https://i.postimg.cc/Xqx0fGWY/icons8-javascript-480.png"
            alt=""
            class="image"
          />
        </div>
        <div class="skill-info">
          <h4>JavaScript</h4>
        </div>
      </div>
      <div class="skill">
        <div class="img">
          <img
            src="https://i.postimg.cc/d12F0NSd/icons8-vue-js-480.png"
            alt=""
            class="image"
          />
        </div>
        <div class="skill-info">
          <h4>Vue.js</h4>
        </div>
      </div>
      <div class="skill">
        <div class="img">
          <img
            src="https://i.postimg.cc/9XBV5S9H/icons8-mysql-480.png"
            alt=""
            class="image"
          />
        </div>
        <div class="skill-info">
          <h4>MySQL</h4>
        </div>
      </div>
      <div class="skill">
        <div class="img">
          <img
            src="https://i.postimg.cc/Y0tHLNJP/icons8-node-js-240.png"
            alt=""
            class="image"
          />
        </div>
        <div class="skill-info">
          <h4>Node.js</h4>
        </div>
      </div>
      <div class="skill">
        <div class="img">
          <img
            src="https://i.postimg.cc/Y2NYW14z/icons8-bootstrap-240.png"
            alt=""
            class="image"
          />
        </div>
        <div class="skill-info">
          <h4>Bootstrap</h4>
        </div>
      </div>
      <div class="skill">
        <div class="img">
          <img
            src="https://i.postimg.cc/htwQw47G/icons8-microsoft-office-240.png"
            alt=""
            class="image"
          />
        </div>
        <div class="skill-info">
          <h4>Microsoft Office</h4>
        </div>
      </div>
    </div>
  </div>
  <div class="testimonals-row">
    <h2 class="h222">Testimonials</h2>
    <div class="testimonials">
      <div class="marcel">
        <div class="images">
          <img src="https://i.postimg.cc/13577j93/image-1.png" alt="" class="imgs">
        </div>
        <div class="marcels-info">
          <ul class="ul">
            <li>Marcel Brown</li>
            <li>Web Developer</li>
          </ul>
        </div>
        <div class="testify">
          <p class="p">"Zubair is like a comedian who uses self-deprecating humor to make light of his shyness and show how hard he work to overcome it."</p>
        </div>
      </div>
      <div class="line"></div>
      <div class="imti">
        <div class="images">
          <img src="../Images/imti (1).png" alt="" class="imgs">
        </div>
        <div class="imti-info">
          <ul class="ul">
            <li>Imtiyaaz Damon</li>
            <li>Web Developer</li>
          </ul>
        </div>
        <div class="testify">
          <p class="p">"Zubair is a hardworking and intelligent individual with a knack for problem-solving. In collaborative settings, he proves to be resourceful and readily offers assistance, making him a valuable team member."</p>
        </div>
      </div>
      <div class="line"></div>

      <div class="liyabona">
        <div class="images">
          <img src="https://i.postimg.cc/htw2p8pJ/image-5.png" alt="" class="imgs">
        </div>
        <div class="liyabona-info">
          <ul class="ul">
            <li>Liyabona Mxhhalis</li>
            <li>Web Developer</li>
          </ul>
        </div>
        <div class="testify">
          <p class="p">"Zubair is like a lovable underdog, always pushing himself to work harder despite his shyness and making us laugh with his endearing quirks."</p>
        </div>
      </div>
      <div class="line"></div>

      <div class="lyle">
        <div class="images">
          <img src="https://i.postimg.cc/05HHHqtX/image-4.png" alt="" class="imgs">
        </div>
        <div class="lyle-info">
          <ul class="ul">
            <li>Lyle Kepkey</li>
            <li>Web Developer</li>
          </ul>
        </div>
        <div class="testify">
          <p class="p">"Zubair is an exceptional individual who combines unwavering dedication, punctuality, and a passion for gaming. His strong work ethic and ambition to become a developer make him an invaluable asset to any team."</p>
        </div>
      </div>
      <div class="line"></div>

      <div class="sakhe">
        <div class="images">
          <img src="https://i.postimg.cc/HW9czpBX/image-2.png" alt="" class="imgs">
        </div>
        <div class="sakhe-info">
          <ul class="ul">
            <li>Sakhe Mzolisa</li>
            <li>Web Developer</li>
          </ul>
        </div>
        <div class="testify">
          <p class="p">"I'm Impressed by Zubair's web development skills, dedication, and ability to learn and apply new technologies. Highly recommended for ICT companies."</p>
        </div>
      </div>
      <div class="line"></div>

    </div>
  </div>
  <Footer/>
</template>
<script>
import NavBar from "@/components/NavBar-Comp.vue";
import Footer from "@/components/Footer-Comp.vue";

export default {
  components: { NavBar, Footer },
  
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Zilla+Slab:wght@400;700&display=swap");

.hero {
  background-image: url("/src/Images/532702.jpg");
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

.Profile,
.experience {
  margin: 6rem;
  border: 1px solid #cd8500;
  height: 21rem;
  width: 42rem;
  box-shadow: 9px 5px 12px #cd8500;
}

.image1 {
  width: 15rem !important;
  height: 19rem !important;
  border-radius: 100%;
  background-color: #5c3408;
  margin: 0rem;
}

.profile-card {
  display: flex !important;
  margin: 1rem;
}

.aboutme {
  margin-top: 2rem;
  list-style-type: none;
}

.list-item {
  font-size: 1.2rem !important;
  color: white;
}

.color {
  color: #cd8500;
  font-family: "Zilla Slab", serif;
}

.Profile-Cards {
  display: flex;
}

.biography {
  margin: 6rem;
  border: 1px solid #cd8500;
  height: 49rem;
  width: 32rem;
  text-align: center;
}

.biography-card {
  margin: 2rem;
}

.h2 {
  color: white;
}

.h22 {
  color: #cd8500;
}

.p {
  color: white;
  margin-top: 1rem;
}

.line {
  border-bottom: 1px solid #ae6006;
  height: 1rem;
}

.passion {
  margin-top: 4rem;
}

.info2 {
  margin: 2rem;
}

.h3 {
  color: white;
}

.skills-row {
  margin: 6rem;
  height: 35rem;
}

.h1 {
  color: white;
  text-align: center;
  margin: 1rem;
}

.image {
  width: 5rem;
}

.image:hover {
width: 5.5rem;
transition: 0.2s all ;
}

.skill {
  display: flex;
  flex-direction: column;
  text-align: center;
}

.skill-info {
  color: white;
}

.skills {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  margin: 2rem;
  gap: 4rem;
}

.general {
  list-style-type: none;
}

.General {
  margin-top: 4rem;
}

.line2 {
  border-bottom: 1px solid #cd8500;
  margin-top: 5.2rem;
  width: 48rem;
}

.line3 {
  border-left: 1px solid #cd8500;
  height: 49rem;
  margin-top: 6rem;
}

.education-row {
  margin: 6rem;
  display: flex;
  height: 27rem;
  align-items: center;
  justify-content: center;
  box-shadow: 1px 1px 12px 1px #cd8500;
}

.high,
.LC {
  text-align: center;
  width: 25rem;
}

.education {
  display: flex;
  gap: 20rem;
}

.h4 {
  color: #cd8500;
}

.h222 {
  color: white;
  text-align: center;
}

.testimonals-row {
  margin: 6rem;
}

.imgs {
  width: 9rem;
  height: 9rem;
  border-radius: 100%;
}

.marcel,  .liyabona,.sakhe {
  display: flex;
  gap: 2rem;
}

.imti {
  display: flex;
  flex-direction: row-reverse;
}

.lyle {
  display: flex;
  flex-direction: row-reverse;
}

.ul {
list-style-type: none;
color: white;
margin-top: 2.8rem;
width: 12rem;
}

.marcels-info, .imti-info,.liyabona-info,.lyle-info, .sakhe-info {
  font-weight: 700;
}

.testify {
  margin-top: 2.8rem;
}

.testimonials {
display: flex;
flex-direction: column;
gap: 4rem;
}

@media only screen and (max-width:300px){
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

.profile-card {
  display: flex !important;
  flex-direction: column;
  margin: 1rem;
  gap: 1rem;
}

.Profile,
.experience {
  margin: 0rem;
  border: 1px solid #cd8500;
  height: 41rem;
  width: 100% !important;
  box-shadow: 9px 5px 12px #cd8500;
}

.aboutme {
  margin-top: 2rem;
  list-style-type: none;
}

.list-item {
  font-size: 1.2rem !important;
  color: white;
}

.color {
  color: #cd8500;
  font-family: "Zilla Slab", serif;
}

.Profile-Cards {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.biography {
  margin: 0rem;
  border: 1px solid #cd8500;
  height: 59rem;
  width: 100%;
  text-align: center;
}

.line2 {
  border-bottom: 0px solid #cd8500;
  margin-top: 0rem;
  width: 0rem;
}

.line3 {
  border-left: 0px solid #cd8500;
  height: 0rem;
  margin-top: 0rem;
}

.column {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.education {
  display: flex;
  flex-direction: column;
  gap: 10rem;
}

.education-row {
  margin: 0rem;
  display: flex;
  height: 77rem;
  align-items: center;
  justify-content: center;
  box-shadow: 1px 1px 12px 1px #cd8500;
}

.high-info {
 width: 20rem;
 text-align: center;
}

.LC-info {
  width: 20rem;
  font-size: 0.9rem;
  margin-left: 0rem;
}

.LC {
  width: 100%;
}

.high {
  width:  20rem;
}





.skills-row {
  margin: 0;
  height: 44rem;
}

.skills {
  display: grid;
  grid-template-columns: 1fr 1fr ;
}


.marcel,  .liyabona,.sakhe {
  display: flex;
  flex-direction: column;
  gap: 0rem;
}

.imti {
  display: flex;
  flex-direction: column;
}

.lyle {
  display: flex;
  flex-direction: column;
}

.marcels-info, .imti-info,.liyabona-info,.lyle-info, .sakhe-info {
  font-weight: 700;
  text-align: center;

}

.testify {
  margin-top: 2.8rem;
}

.testimonials {
display: flex;
flex-direction: column;
gap: 2rem;
align-items: center;
justify-content: center;
margin-top: 3rem;
margin-left: 2rem;
}

.ul {
list-style-type: none;
color: white;
margin-top: 2.8rem;
width: 12rem;
margin-left: 0.5rem;
}
.p {
width: 15rem;
text-align: center;
}

.testimonals-row {
  margin-top : 3rem;
}

.imgs {
  margin-left: 3rem;
}

}


</style>
