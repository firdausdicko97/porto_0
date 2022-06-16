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
                <a
                  href="https://www.instagram.com/firdausdicko"
                  target="_blank"
                >
                  <img src="~/assets/img/instagram.png" alt="" />
                </a>
              </div>
              <div class="icon">
                <a
                  href="https://www.linkedin.com/in/firdaus-dicko-648517141/"
                  target="_blank"
                >
                  <img src="~/assets/img/linkedin.png" alt="" />
                </a>
              </div>
              <div class="icon">
                <a href="https://www.github.com/firdausdicko97" target="_blank">
                  <img src="~/assets/img/github.png" alt="" />
                </a>
              </div>
              <div class="icon">
                <a
                  href="https://steamcommunity.com/id/zkael97/"
                  target="_blank"
                >
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
        <!--START OF TIMELINE DIV  -->
        <div class="tl">
          <div class="education">
            <div class="timeline">
              <div class="timeline-month">Education</div>
              <div class="timeline-section">
                <div class="timeline-date">2014 - 2017</div>
                <div class="row">
                  <div class="col-sm-4">
                    <div class="timeline-box">
                      <div class="box-title">
                        <i
                          class="fa fa-tasks text-success"
                          aria-hidden="true"
                        ></i>
                        SMAN 8 Bekasi
                      </div>
                      <div class="box-content">
                        <div class="box-item">
                          <strong>Major</strong>: Science
                        </div>
                        <div class="box-item">
                          <strong>Activity</strong>:
                          <li>1</li>
                          <li>2</li>
                        </div>
                      </div>
                      <div class="box-footer">- Carol</div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="timeline-section">
                <div class="timeline-date">2017 - 2021</div>
                <div class="row">
                  <div class="col-sm-4">
                    <div class="timeline-box">
                      <div class="box-title">
                        <i
                          class="fa fa-tasks text-success"
                          aria-hidden="true"
                        ></i>
                        Institut Teknologi Bandung
                      </div>
                      <div class="box-content">
                        <div class="box-item">
                          <strong>Major</strong>: Mechanical Engineering
                        </div>
                        <div class="box-item">
                          <strong>Activity</strong>: Lorem ipsum dolor sit amet,
                          consectetur adipiscing elit. Nullam nisi nulla,
                          viverra quis felis sit amet, lacinia feugiat odio.
                          Aliquam sed orci elementum, volutpat dolor eget,
                          venenatis nunc
                        </div>
                      </div>
                      <div class="box-footer">- Carol</div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="experience">
            <div class="timeline">
              <div class="timeline-month">Education</div>
              <div class="timeline-section">
                <div class="timeline-date">2014 - 2017</div>
                <div class="row">
                  <div class="col-sm-4">
                    <div class="timeline-box">
                      <div class="box-title">
                        <i
                          class="fa fa-tasks text-success"
                          aria-hidden="true"
                        ></i>
                        SMAN 8 Bekasi
                      </div>
                      <div class="box-content">
                        <div class="box-item">
                          <strong>Major</strong>: Science
                        </div>
                        <div class="box-item">
                          <strong>Activity</strong>:
                          <li>1</li>
                          <li>2</li>
                        </div>
                      </div>
                      <div class="box-footer">- Carol</div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="timeline-section">
                <div class="timeline-date">2017 - 2021</div>
                <div class="row">
                  <div class="col-sm-4">
                    <div class="timeline-box">
                      <div class="box-title">
                        <i
                          class="fa fa-tasks text-success"
                          aria-hidden="true"
                        ></i>
                        Institut Teknologi Bandung
                      </div>
                      <div class="box-content">
                        <div class="box-item">
                          <strong>Major</strong>: Mechanical Engineering
                        </div>
                        <div class="box-item">
                          <strong>Activity</strong>: Lorem ipsum dolor sit amet,
                          consectetur adipiscing elit. Nullam nisi nulla,
                          viverra quis felis sit amet, lacinia feugiat odio.
                          Aliquam sed orci elementum, volutpat dolor eget,
                          venenatis nunc
                        </div>
                      </div>
                      <div class="box-footer">- Carol</div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- END OF TIMELINE -->
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
