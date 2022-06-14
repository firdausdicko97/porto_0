<template>
  <div>
    <Navbar />
    <div class="body">
      <div class="container">
        <div class="profile">
          <div class="profile_img">
            <img src="~/assets/img/ilus1.svg" width="400px" />
          </div>
          <div class="content">
            <h5>My name is</h5>
            <h1>Firdaus Dicko</h1>
            <p>
              I’m a Product Owner and Machine Learning <br />
              enthusiast, loves to learn web development <br />
              and web design, eager to learn new things
            </p>
            <!-- SOCIAL MEDIA -->
            <div class="social">
            <div class="icon">
              <a href="https://www.google.com">
                <img src="~/assets/img/discord.png" alt="" />
              </a>
            </div>
            <div class="icon">
              <a href="https://www.instagram.com/firdausdicko" target="_blank">
                <img src="~/assets/img/instagram.png" alt="" />
              </a>
            </div>
            <div class="icon">
              <a href="https://www.linkedin.com/in/firdaus-dicko-648517141/" target="_blank">
              <img src="~/assets/img/linkedin.png" alt="" />
              </a>
            </div>
            <div class="icon">
              <a  href="https://www.github.com/firdausdicko97" target="_blank">
              <img src="~/assets/img/github.png" alt="" />
              </a>
            </div>
            <div class="icon" >
              <a href="https://steamcommunity.com/id/zkael97/" target="_blank">
                <img src="~/assets/img/steam.png" alt="" />
              </a>
            </div>
            <div class="icon">
              <a href="https://www.twitter.com/firdausdicko_" target="_blank">
                <img src="~/assets/img/twitter.png" alt="" />
              </a>
            </div>
          </div>
          <!--END OF SOCIAL DIV  -->
          </div>
          <!-- END OF CONTENT DIV -->
        </div>
        <!--  -->
      </div>
    </div>
  </div>
</template>

<script>
// import Navbar from '../components/Navbar/index.vue';
import Navbar from "@/components/Navbar";
export default {
  name: "IndexPage",
  components: { Navbar },
};
</script>

<style scoped>
@import "~/static/css/dua.css";
</style>

<!-- <div class="icon">
              <img src="~/assets/img/css.svg" alt="" />
            </div> -->
<!-- <div class="icon">
              <img src="~/assets/img/figma.svg" alt="" />
            </div> -->
<!-- <div class="icon">
              <img src="~/assets/img/html.svg" alt="" />
            </div> -->
<!-- <div class="icon">
              <img src="~/assets/img/ml.svg" alt="" />
            </div>
            <div class="icon">
              <img src="~/assets/img/php.svg" alt="" />
            </div>
            <div class="icon">
              <img src="~/assets/img/python.svg" alt="" />
            </div>
            <div class="icon">
              <img src="~/assets/img/sql.svg" alt="" />
            </div>

