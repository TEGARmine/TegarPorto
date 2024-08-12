<template>
  <div class="dizme_tm_section" id="portfolio">
    <div class="dizme_tm_portfolio">
      <div class="container">
        <div class="dizme_tm_main_title" data-align="center">
          <h3>My Portfolio</h3>
          <p>Explore my portfolio, where my skills in full stack development come to life. These projects highlight my expertise in technologies like Laravel, Python, and NextJs, demonstrating my dedication to creating innovative solutions.</p>
        </div>
        <div class="portfolio_filter">
          <ul>
            <li>
              <a
                class="c-pointer"
                :class="activeNav === '1' ? 'current' : ''"
                @click.prevent="() => (this.activeNav = '1')"
                data-filter="*"
                >All</a
              >
            </li>
            <li>
              <a
                class="c-pointer"
                :class="activeNav === '2' ? 'current' : ''"
                @click.prevent="() => (this.activeNav = '2')"
                data-filter=".vimeo, .detail, .popups"
                >Web</a
              >
            </li>
            <li>
              <a
                class="c-pointer"
                :class="activeNav === '3' ? 'current' : ''"
                @click.prevent="() => (this.activeNav = '3')"
                data-filter=".youtube, .soundcloud, .popup"
                >Mobile</a
              >
            </li>
          </ul>
        </div>


        <div class="dizme_tm_portfolio_titles"></div>
        <div class="portfolio_list wow fadeInUp" data-wow-duration="1s">
          <ul class="gallery_zoom grid">
            <li class="youtube grid-item">
              <div class="inner">
                <div
                  class="entry dizme_tm_portfolio_animation_wrap"
                  data-title="Sales Tracking"
                  data-category="Indosat"
                >
                  <a
                    class=""
                    href="https://www.upwork.com/freelancers/~019b2ef6d52ddd90a0?p=1821446306531409920"
                    target="_blank"
                  >
                    <img src="/img/thumbs/42-56.jpg" alt="" />
                    <div class="main" data-img-url="/img/portfolio/6.jpg"></div>
                  </a>
                </div>
                <div class="mobile_title">
                  <h3>Sales Tracking</h3>
                  <span>Indosat</span>
                </div>
              </div>
            </li>

            <li class="vimeo grid-item">
              <div class="inner">
                <div
                  class="entry dizme_tm_portfolio_animation_wrap"
                  data-title="Marketing Apps"
                  data-category="Indosat Ooredoo"
                >
                  <a
                    class=""
                    href="https://www.upwork.com/freelancers/~019b2ef6d52ddd90a0?p=1821447959377375232"
                    target="_blank"
                  >
                    <img src="/img/thumbs/42-34.jpg" alt="" />
                    <div class="main" data-img-url="/img/portfolio/1.jpg"></div>
                  </a>
                </div>
                <div class="mobile_title">
                  <h3>Marketing Apps</h3>
                  <span>Indosat Ooredoo</span>
                </div>
              </div>
            </li>

            <li class="soundcloud grid-item">
              <div class="inner">
                <div
                  class="entry dizme_tm_portfolio_animation_wrap"
                  data-title="Waste Cycling Apps"
                  data-category="Indonesia Port"
                >
                  <a
                    class="soundcloude_link mfp-iframe audio"
                    href="https://www.upwork.com/freelancers/~019b2ef6d52ddd90a0?p=1821445626057101312"
                    target="_blank"
                  >
                    <img src="/img/thumbs/42-56.jpg" alt="" />
                    <div class="main" data-img-url="/img/portfolio/3.jpg"></div>
                  </a>
                </div>
                <div class="mobile_title">
                  <h3>Waste Cycling Apps</h3>
                  <span>Indonesia Port</span>
                </div>
              </div>
            </li>

            <li class="popup grid-item">
              <div class="inner">
                <div
                  class="entry dizme_tm_portfolio_animation_wrap"
                  data-title="E-book Apps"
                  data-category="Islamic State University"
                >
                  <a
                    class="zoom"
                    href="https://www.upwork.com/freelancers/~019b2ef6d52ddd90a0?p=1821444970235727872"
                    target="_blank"
                  >
                    <img src="/img/thumbs/42-56.jpg" alt="" />
                    <div class="main" data-img-url="/img/portfolio/9.jpg"></div>
                  </a>
                </div>
                <div class="mobile_title">
                  <h3>E-book Apps</h3>
                  <span>Islamic State University</span>
                </div>
              </div>
            </li>

            <li class="popups grid-item">
              <div class="inner">
                <div
                  class="entry dizme_tm_portfolio_animation_wrap"
                  data-title="Organization Management"
                  data-category="Pharmacy Organization"
                >
                  <a
                    class=""
                    href="https://www.upwork.com/freelancers/~019b2ef6d52ddd90a0?p=1821445280986333184"
                    target="_blank"
                  >
                    <img src="/img/thumbs/42-34.jpg" alt="" />
                    <div class="main" data-img-url="/img/portfolio/10.jpg"></div>
                  </a>
                </div>
                <div class="mobile_title">
                  <h3>Organization Management</h3>
                  <span>Pharmacy Organization</span>
                </div>
              </div>
            </li>

            <li class="detail grid-item">
              <div class="inner">
                <div
                  class="entry dizme_tm_portfolio_animation_wrap"
                  data-title="Tech Insurance"
                  data-category="Yuk Takaful"
                >
                  <a
                    class=""
                    href="https://www.upwork.com/freelancers/~019b2ef6d52ddd90a0?p=1821443394024873984"
                    target="_blank"
                  >
                    <img src="/img/thumbs/42-34.jpg" alt="" />
                    <div class="main" data-img-url="/img/portfolio/12.jpg"></div>
                  </a>
                </div>
                <div class="mobile_title">
                  <h3>Tech Insurance</h3>
                  <span>Yuk Takaful</span>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
      
      <div class="brush_1 wow zoomIn" data-wow-duration="1s">
        <img src="/img/brushes/portfolio/1.png" alt="" />
      </div>
      <div class="brush_2 wow fadeInRight" data-wow-duration="1s">
        <img src="/img/brushes/portfolio/2.png" alt="" />
      </div>
    </div>
  </div>
  <MagnificPopUpVue
    :modal="modal"
    :close="closeModal"
    :name="name"
    :src="src"
  />
</template>

<script>
import MagnificPopUpVue from "./popup/MagnificPopUp.vue";
import ModalBox from "./popup/ModalBox.vue";
export default {
  name: "PortfolioComponent",
  data() {
    return {
      activeNav: "1", // props
      name: "",
      src: "",
      modal: false,
      // Content
      active: 0,
    };
  },
  mounted() {
    let Isotope = require("isotope-layout");
    setTimeout(() => {
      let iso = new Isotope(".gallery_zoom", {
        itemSelector: ".grid-item",
        //    layoutMode: "fitRows",
        percentPosition: true,
        masonry: {
          columnWidth: ".grid-item",
        },
        animationOptions: {
          duration: 750,
          easing: "linear",
          queue: false,
        },
      });
      let filterFns = {
        // show if number is greater than 50
        numberGreaterThan50: function (itemElem) {
          let number = itemElem.querySelector(".number").textContent;
          return parseInt(number, 10) > 50;
        },
        // show if name ends with -ium
        ium: function (itemElem) {
          let name = itemElem.querySelector(".name").textContent;
          return name.match(/ium$/);
        },
      };
      // bind filter button click filter main funtion
      let filtersElem = document.querySelector(".portfolio_filter ul");
      filtersElem.addEventListener("click", function (event) {
        if (event.target.getAttribute("data-filter")) {
          let filterValue = event.target.getAttribute("data-filter");
          filterValue = filterFns[filterValue] || filterValue;
          iso.arrange({ filter: filterValue });
        }
      });
    }, 1000);
  },
  methods: {
    onClick(name, src) {
      this.name = name;
      this.src = src;
      this.modal = true;
    },
    closeModal() {
      this.modal = false;
      this.name = "";
      this.src = "";
    },
    close() {
      this.active = 0;
    },
  },
  components: { MagnificPopUpVue, ModalBox },
};
</script>
