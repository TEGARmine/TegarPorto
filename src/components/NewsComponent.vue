<template>
  <div class="dizme_tm_section" id="blog">
    <div class="dizme_tm_news">
      <div class="container">
        <div class="dizme_tm_main_title" data-align="center">
          <h3>From My Blog</h3>
          <p>Our Recent Updates, Blog, Tips, Tricks &amp; More</p>
        </div>
        <div class="news_list">
          <ul>
            <li class="wow fadeInUp" data-wow-duration="1s">
              <div class="list_inner">
                <div class="image">
                  <img src="/img/thumbs/42-29.jpg" alt="" />
                  <div class="main" data-img-url="/img/news/4.png"></div>
                  <div class="date">
                    <h3>11</h3>
                    <span>Aug</span>
                  </div>
                  <a
                    class="dizme_tm_full_link"
                    href="https://medium.com/@TegarPratamaa/tutorial-belajar-html-part-1-pengenalan-html-dasar-dasar-html-untuk-pemula-8c86709512ea"
                    target="_blank"
                  ></a>
                </div>
                <div class="details">
                  <span class="category"
                    ><a
                      href="https://medium.com/@TegarPratamaa/tutorial-belajar-html-part-1-pengenalan-html-dasar-dasar-html-untuk-pemula-8c86709512ea"
                      target="_blank"
                      >Tutorial Belajar HTML Part 1</a
                    ></span
                  >
                  <h3 class="title">
                    <a
                      href="https://medium.com/@TegarPratamaa/tutorial-belajar-html-part-1-pengenalan-html-dasar-dasar-html-untuk-pemula-8c86709512ea"
                      target="_blank"
                      >Pengenalan HTML Dasar-dasar HTML untuk Pemula</a
                    >
                  </h3>
                </div>
              </div>
            </li>

            <li
              class="wow fadeInUp"
              data-wow-duration="1s"
              data-wow-delay="0.2s"
            >
              <div class="list_inner">
                <div class="image">
                  <img src="/img/thumbs/42-29.jpg" alt="" />
                  <div class="main" data-img-url="/img/news/5.png"></div>
                  <div class="date">
                    <h3>11</h3>
                    <span>Aug</span>
                  </div>
                  <a
                    class="dizme_tm_full_link"
                    href="https://medium.com/@TegarPratamaa/tutorial-belajar-html-part-2-memahami-element-dalam-html-struktur-dasar-halaman-web-14cf0ff325e0"
                    target="_blank"
                  ></a>
                </div>
                <div class="details">
                  <span class="category"
                    ><a
                      href="https://medium.com/@TegarPratamaa/tutorial-belajar-html-part-2-memahami-element-dalam-html-struktur-dasar-halaman-web-14cf0ff325e0"
                      target="_blank"
                      >Tutorial Belajar HTML Part 2</a
                    ></span
                  >
                  <h3 class="title">
                    <a
                      href="https://medium.com/@TegarPratamaa/tutorial-belajar-html-part-2-memahami-element-dalam-html-struktur-dasar-halaman-web-14cf0ff325e0"
                      target="_blank"
                      >Memahami Element dalam HTML: Struktur Dasar Halaman
                      Web</a
                    >
                  </h3>
                </div>
              </div>
            </li>

            <li
              class="wow fadeInUp"
              data-wow-duration="1s"
              data-wow-delay="0.4s"
            >
              <div class="list_inner">
                <div class="image">
                  <img src="/img/thumbs/42-29.jpg" alt="" />
                  <div class="main" data-img-url="/img/news/6.png"></div>
                  <div class="date">
                    <h3>11</h3>
                    <span>Aug</span>
                  </div>
                  <a
                    class="dizme_tm_full_link"
                    href="https://medium.com/@TegarPratamaa/tutorial-belajar-html-part-3-penggunaan-attribute-dalam-html-menambahkan-informasi-tambahan-0051421a23ab"
                    target="_blank"
                  ></a>
                </div>
                <div class="details">
                  <span class="category"
                    ><a
                      href="https://medium.com/@TegarPratamaa/tutorial-belajar-html-part-3-penggunaan-attribute-dalam-html-menambahkan-informasi-tambahan-0051421a23ab"
                      target="_blank"
                      >Tutorial Belajar HTML Part 3</a
                    ></span
                  >
                  <h3 class="title">
                    <a
                      href="https://medium.com/@TegarPratamaa/tutorial-belajar-html-part-3-penggunaan-attribute-dalam-html-menambahkan-informasi-tambahan-0051421a23ab"
                      target="_blank"
                      >Penggunaan Attribute dalam HTML: Menambahkan Informasi
                      Tambahan</a
                    >
                  </h3>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
      <div class="brush_1 wow zoomIn" data-wow-duration="1s">
        <img src="/img/brushes/news/1.png" alt="" />
      </div>
      <div class="brush_2 wow zoomIn" data-wow-duration="1s">
        <img src="/img/brushes/news/2.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NewsComponent",
  data() {
    return {
      active: 0,
    };
  },
  methods: {
    close() {
      this.active = 0;
    },
  },
};
</script>
