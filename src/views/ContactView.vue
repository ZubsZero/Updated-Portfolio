<template>
    <NavBar/>
<section class="mb-4">

<h2 class="h1-responsive font-weight-bold text-center my-4">Contact us</h2>
<p class="text-center w-responsive mx-auto mb-5">Please feel free to reach out to me, and I will respond promptly within a few hours. You can reach out via the email link ,The form below and lastly my phone number</p>

<div class="row">

    <div class="col-md-9 mb-md-0 mb-5">
        <form id="contact-form" name="contact-form" action="https://formspree.io/f/xjvqdkew" method="POST">

            <div class="row">

                <div class="col-md-6">
                    <div class="md-form mb-0">
                        <input type="text" id="name" name="name" class="form-control">
                        <label for="name" class="">Your name</label>
                    </div>
                </div>
              
                <div class="col-md-6">
                    <div class="md-form mb-0">
                        <input type="text" id="email" name="email" class="form-control">
                        <label for="email" class="">Your email</label>
                    </div>
                </div>

            </div>
           
            <div class="row">
                <div class="col-md-12">
                    <div class="md-form mb-0">
                        <input type="text" id="subject" name="subject" class="form-control">
                        <label for="subject" class="">Subject</label>
                    </div>
                </div>
            </div>

            <div class="row">

                <div class="col-md-12">

                    <div class="md-form">
                        <textarea type="text" id="message" name="message" rows="2" class="form-control md-textarea"></textarea>
                        <label for="message">Your message</label>
                    </div>

                </div>
            </div>

        </form>

        <div class="text-center text-md-left">
            <a class="btn btn-primary" onclick="document.getElementById('contact-form').submit();">Send</a>
        </div>
        <div class="status"></div>
    </div>
  
    <div class="col-md-3 text-center">
        <ul class="list-unstyled mb-0">
            <li><i class="fas fa-map-marker-alt fa-2x"></i>
                <p> Matroosfontein</p>
            </li>

            <li><i class="fas fa-phone mt-4 fa-2x"></i>
                <p>+27 69 244 5575</p>
            </li>

            <li><i class="fas fa-envelope mt-4 fa-2x"></i>
                <a href="mailto:zubairmatthee262@gmail.com">zubairmatthee262@gmail.com</a>

            </li>
        </ul>
    </div>

</div>

</section>
<Footer/>
</template>

<script>
import NavBar from '@/components/NavBar-Comp.vue'
import Footer from '@/components/Footer-Comp.vue'

export default {
    name: 'Contact',
    components:{
      NavBar,Footer
    }
}

</script>
<style scoped>
.mb-4{
    margin: 6rem;
}

label {
    color: #ffffff ; 
margin: 1rem;
}

h2 {
    color: #cd8500;
}

p {
    color: white;
}

.md-form {
    display: flex;
    flex-direction: column-reverse;
}

a {
    color: white;
}

.btn {
    background-color:#cd8500;
    border-radius:10px;
    border: none;
    color: white;
    margin-top: 1rem;
}

@media only screen and (max-width: 300px){
    .mb-4{
        margin: 1rem;
    }
}

</style>