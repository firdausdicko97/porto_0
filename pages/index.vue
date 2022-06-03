<template>
  <div>
    <Navbar />
    <div class="body">
      <div class="container">
        <img src="~/assets/img/ilus1.svg" width="400px" />
        <div class="content">
          <div class="title">My name is</div>
          <div class="subtitle">
            <strong> Firdaus Dicko </strong>
          </div>
          <div class="word">
            I’m a Product Owner and Machine Learning <br />
            enthusiast, loves to learn web development <br />and web design,
            eager to learn new things
          </div>
          <div class="social">
            <ul style="list-style-type: none">
              <li>
                <a href="">
                  <button type="button" style="border: none; background: none">
                    <img src="~/assets/img/discord.png" alt="" />
                  </button>
                </a>
              </li>
              <!-- ===================================================================== -->
              <li>
                <a
                  href="https://www.instagram.com/firdausdicko"
                  target="_blank"
                >
                  <button type="button" style="border: none; background: none">
                    <img src="~/assets/img/instagram.png" alt="" />
                  </button>
                </a>
              </li>
              <!-- ===================================================================== -->
              <li>
                <a
                  href="https://www.github.com/firdausdicko97 "
                  target="_blank"
                >
                  <button type="button" style="border: none; background: none">
                    <img src="~/assets/img/github.png" alt="" />
                  </button>
                </a>
              </li>
              <!-- ===================================================================== -->
              <li>
                <a
                  href="https://www.linkedin.com/in/firdaus-dicko-648517141/"
                  target="_blank"
                >
                  <button type="button" style="border: none; background: none">
                    <img src="~/assets/img/linkedin.png" alt="" />
                  </button>
                </a>
              </li>
              <!-- ===================================================================== -->
              <li>
                <a
                  href="https://steamcommunity.com/id/zkael97/"
                  target="_blank"
                >
                  <button type="button" style="border: none; background: none">
                    <img src="~/assets/img/steam.png" alt="" />
                  </button>
                </a>
              </li>
              <!-- ===================================================================== -->
              <li>
                <a href="https://www.twitter.com/firdausdicko_" target="_blank">
                  <button type="button" style="border: none; background: none">
                    <img src="~/assets/img/twitter.png" alt="" />
                  </button>
                </a>
              </li>
            </ul>
          </div>
        </div>
        <!-- ============================== -->
        <div class="timeline">
          <div class="tltitle">
            <strong>timeline</strong>
          </div>
          <div class="tlcontent"></div>
        </div>
        <!-- ============================== -->
        <div class="knowledge">
          <div class="kntitle">
            <strong>Area of knowledge</strong>
          </div>
          <div class="knimg">
            <ul style="list-style-type: none">
              <li>
                <img src="~/assets/img/css.svg" alt="" />
              </li>
              <!-- ===================================================================== -->
              <li>
                <img src="~/assets/img/figma.svg" alt="" />
              </li>
              <!-- ===================================================================== -->
              <li>
                <img src="~/assets/img/html.svg" alt="" />
              </li>
              <!-- ===================================================================== -->
              <li>
                <img src="~/assets/img/ml.svg" alt="" />
              </li>
              <!-- ===================================================================== -->
              <li>
                <img src="~/assets/img/sql.svg" alt="" />
              </li>
              <!-- ===================================================================== -->
              <li>
                <img src="~/assets/img/php.svg" alt="" />
              </li>
              <!-- ===================================================================== -->
              <li>
                <img src="~/assets/img/python.svg" alt="" />
              </li>
              <!-- ===================================================================== -->
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// import Navbar from '../components/Navbar/index.vue';
import Navbar from "@/components/Navbar";
import Footer from "@/components/Footer";
export default {
  name: "IndexPage",
  components: { Navbar, Footer },
};
</script>

<style scoped>
@import "~/static/css/home.css";
</style>
