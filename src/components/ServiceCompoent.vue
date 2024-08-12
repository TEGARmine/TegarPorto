<template>
  <div class="dizme_tm_section" id="service">
    <div class="dizme_tm_services">
      <div class="container">
        <div class="dizme_tm_main_title" data-align="center">
          <h3>My Service</h3>
        </div>
        <div class="service_list">
          <ul>
            <li class="wow fadeInLeft" data-wow-duration="1s">
              <div class="list_inner tilt-effect">
                <span class="icon">
                  <img class="svg" src="/img/svg/service/laravel.svg" alt="" />
                  <img
                    class="back"
                    :src="`/img/brushes/service${dark ? '/dark' : ''}/3.png`"
                    alt=""
                  />
                </span>
                <div class="title">
                  <h3>Laravel Development</h3>
                </div>
                <div class="text">
                  <p>
                    I have more than 5+ years of experience in Laravel and
                    Vue.js Technologies, skilled in developing responsive and
                    interactive web applications
                  </p>
                </div>
                <a
                  class="dizme_tm_full_link"
                  targer="_blank"
                  href="https://www.upwork.com/freelancers/~019b2ef6d52ddd90a0?mp_source=share"
                ></a>
              </div>
            </li>

            <li
              class="wow fadeInRight"
              data-wow-duration="1s"
              data-wow-delay="0.2s"
            >
              <div class="list_inner tilt-effect">
                <span class="icon">
                  <img
                    class="svg"
                    src="/img/svg/service/wordpress.svg"
                    alt=""
                  />
                  <img
                    class="back"
                    :src="`/img/brushes/service${dark ? '/dark' : ''}/4.png`"
                    alt=""
                  />
                </span>
                <div class="title">
                  <h3>Wordpress Development</h3>
                </div>
                <div class="text">
                  <p>
                    I have experience with WordPress using Elementor, creating
                    custom templates, converting HTML to WordPress, and
                    developing plugins.
                  </p>
                </div>
                <a
                  class="dizme_tm_full_link"
                  target="_blank"
                  href="https://www.upwork.com/freelancers/~019b2ef6d52ddd90a0?mp_source=share"
                ></a>
              </div>
            </li>

            <li class="wow fadeInLeft" data-wow-duration="1s">
              <div class="list_inner tilt-effect">
                <span class="icon">
                  <img class="svg" src="/img/svg/service/python.svg" alt="" />
                  <img
                    class="back"
                    :src="`/img/brushes/service${dark ? '/dark' : ''}/2.png`"
                    alt=""
                  />
                </span>
                <div class="title">
                  <h3>Python Development</h3>
                </div>
                <div class="text">
                  <p>
                    Experienced Python Developer skilled in crafting custom web
                    applications, seamless integration of functionalities, and
                    third-party API integration.
                  </p>
                </div>
                <a
                  class="dizme_tm_full_link"
                  target="_blank"
                  href="https://www.upwork.com/freelancers/~019b2ef6d52ddd90a0?mp_source=share"
                ></a>
              </div>
            </li>

            <li
              class="wow fadeInRight"
              data-wow-duration="1s"
              data-wow-delay="0.2s"
            >
              <div class="list_inner tilt-effect">
                <span class="icon">
                  <img class="svg" src="/img/svg/service/php.svg" alt="" />
                  <img
                    class="back"
                    :src="`/img/brushes/service${dark ? '/dark' : ''}/1.png`"
                    alt=""
                  />
                </span>
                <div class="title">
                  <h3>PHP Development</h3>
                </div>
                <div class="text">
                  <p>
                    I have speciality in PHP for 5+ years. I am building modern
                    web development, responsive, and interactive application.
                  </p>
                </div>
                <a
                  class="dizme_tm_full_link"
                  target="_blank"
                  href="https://www.upwork.com/freelancers/~019b2ef6d52ddd90a0?mp_source=share"
                ></a>
              </div>
            </li>
          </ul>
        </div>
      </div>
      <div class="brush_1 wow fadeInLeft" data-wow-duration="1s">
        <img src="/img/brushes/service/5.png" alt="" />
      </div>
      <div class="brush_2 wow zoomIn" data-wow-duration="1s">
        <img src="/img/brushes/service/6.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ServiceCompoent",
  data() {
    return {
      active: 0,
    };
  },
  mounted() {
    let VanillaTilt = require("vanilla-tilt");
    VanillaTilt.init(document.querySelectorAll(".tilt-effect"), {
      maxTilt: 6,
      easing: "cubic-bezier(.03,.98,.52,.99)",
      speed: 500,
      transition: true,
    });
  },
  methods: {
    close() {
      this.active = 0;
    },
  },
  props: {
    dark: { type: Boolean },
  },
};
</script>
