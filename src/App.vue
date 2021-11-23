<template>
  <div>
    <header class="banner">
      <div class="banner-mask"></div>
      <div class="banner-content">
        <div class="container">
          <div class="h-100 text-center">
            <!-- 圖片 -->
            <img src="~image/headShot.jpg" class="headShot" alt="headShot" />
            <h2 class="fw-bolder mt-3">陳致劭</h2>
            <h2>Chih Shao Chen</h2>
            <ul class="d-flex justify-content-center">
              <li class="mx-3">
                <a class="h4" href="mailto:4a10h032@stust.edu.tw"
                  ><i class="bi bi-envelope fa-2x"></i
                ></a>
              </li>
              <li class="mx-3">
                <a class="h4" href="tel:0958141997"
                  ><i class="bi bi-phone fa-2x"></i
                ></a>
              </li>
              <li class="mx-3">
                <a class="h4" href="https://github.com/shao0524/"
                  ><i class="bi bi-github fa-2x"></i
                ></a>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <button type="button" class="scrollerBtn" id="scrollerDown"></button>
    </header>
    <!-- 介紹 -->
    <section class="mt-5" id="about">
      <div class="container">
        <h3 class="title text-center">關於我</h3>
        <p>
          大學自資訊工程系畢業，畢業後由於還沒找到目標，於是進入餐飲業，並在閒暇之餘學習其他的技能。
          偶然地看到六角學院的教學影片，發現與大學時期學過的網頁設計課程截然不同，因此萌生了想要探求新的知識的想法，於是開始透過線上課程學習相關技術。
          在學習的過程中常常會遇到一些難題，我會透過網路尋找解決問題的方式，解決了這些難題讓我得到許多的成就感，也讓我對寫程式越來越投入。
        </p>
      </div>
    </section>
    <!-- skill -->
    <section class="mt-5">
      <div class="container">
        <h3 class="title text-center">主要技能</h3>
        <div class="row">
          <div class="col-12 col-md-6 col-lg-4 mb-3">
            <div class="itemBox">
              <div class="container">
                <img src="~image/htmlCSS.jpg" alt="HTML&CSS" class="image" />
                <h3>HTML & CSS</h3>
                <ul class="align-self-start text-start">
                  <li>可依據設計稿切手刻版型</li>
                  <li>熟悉SCSS語法</li>
                  <li>使用CSS製作動畫效果</li>
                  <li>建立RWD響應式網頁</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-12 col-md-6 col-lg-4 mb-3">
            <div class="itemBox">
              <div class="container">
                <img src="~image/js.jpg" alt="JavaScript" class="image" />
                <h3>JavaScript</h3>
                <ul class="text-start">
                  <li>了解並會使用ES6語法</li>
                  <li>使用jQuery做網頁互動效果</li>
                  <li>jQuery-使用Ajax取得第三方API</li>
                  <li>套用Plugin在網頁上，舉例Swiper、Leaflet…等</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-12 col-md-6 col-lg-4 mb-3">
            <div class="itemBox">
              <div class="container">
                <img src="~image/bs.jpg" alt="Bootstrap" class="image" />
                <h3>Bootstrap</h3>
                <ul class="text-start">
                  <li>
                    了解Bootstrap 4
                    Grid、Components以及Utilities的使用，並且修改成客製化的Bootstrap
                    SCSS
                  </li>
                  <li>Bootstrap 5 學習中</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-12 col-md-6 col-lg-4 mb-3">
            <div class="itemBox">
              <div class="container">
                <img src="~image/vue.jpg" alt="Vue" class="image" />
                <h3>Vue.js</h3>
                <ul class="text-start">
                  <li>使用Vue-Cli開發專案</li>
                  <li>了解Vue的生命週期</li>
                  <li>使用Vue-Axios套件串接API</li>
                  <li>使用 components管理元件</li>
                  <li>使用Vue第三方套件</li>
                  <li>使用Vuex集中管理狀態</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-12 col-md-6 col-lg-4 mb-3">
            <div class="itemBox">
              <div class="container">
                <img src="~image/node.jpg" alt="Node.js" class="image" />
                <h3>Node.js</h3>
                <ul class="text-start">
                  <li>使用Express建立RESTful API</li>
                  <li>利用Firebase，製作使用者認證與即時資料庫</li>
                  <li>使用Nodemailer製作郵件發送功能</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-12 col-md-6 col-lg-4 mb-3">
            <div class="itemBox">
              <div class="container">
                <img src="~image/git.jpg" alt="Git" class="image" />
                <h3>Git/Github</h3>
                <ul class="text-start">
                  <li>基礎Git操作及版本控制</li>
                  <li>使用過Github管理專案、Heroku架設伺服器</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- 作品集 -->
    <section class="my-5 pb-5">
      <div class="container">
        <h3 class="title text-center">作品集</h3>
        <div class="row">
          <div class="col-12 col-md-6 col-lg-4 mb-3">
            <div class="production">
              <div class="production-header">
                <a href="https://shao0524.github.io/cheeseShop/#/">
                  <img src="~image/cheeseny.jpg" alt="Cheeseny" class="image" />
                </a>
              </div>
              <div class="production-body">
                <a href="https://shao0524.github.io/cheeseShop/#/"
                  ><h5>Cheeseny Shop</h5>
                </a>
                <p>
                  作品簡介：vue.js使用axios串接六角學院提供的練習用電商API製作個人電商網頁
                </p>
                <h6 class="text-end">
                  （Vue.js、SCSS、Bootstrap、Swiper、jQuery）
                </h6>
              </div>
              <div class="production-footer">
                <a
                  href="https://shao0524.github.io/cheeseShop/#/"
                  class="btnDemo"
                  >Demo</a
                >
                <a href="https://github.com/shao0524/cheeseShop" class="btnGit"
                  >Github</a
                >
              </div>
            </div>
          </div>

          <div class="col-12 col-md-6 col-lg-4 mb-3">
            <div class="production">
              <div class="production-header">
                <a href="https://map-10-08.herokuapp.com/">
                  <img
                    src="~image/bikeMap.jpg"
                    alt="自行車租借站與車道地圖"
                    class="image"
                  />
                </a>
              </div>
              <div class="production-body">
                <a href="https://map-10-08.herokuapp.com/"
                  ><h5>自行車租借站與車道地圖</h5>
                </a>
                <p>
                  作品簡介：Vue.js練習作品，使用axios串接TDX
                  API並用leaflet建立座標至OpenStreetMap上。可藉由查詢自行車車道的地點後，顯示附近的可租借自行車資訊。
                </p>
                <h6 class="text-end">
                  （Vue.js、SCSS、Bootstrap 、Leaflet、OpenStreetMap、TDX API）
                </h6>
              </div>
              <div class="production-footer">
                <a href="https://shao0524.github.io/BikeMap/" class="btnDemo"
                  >Demo</a
                >
                <a href="https://github.com/shao0524/BikeMap" class="btnGit"
                  >Github</a
                >
              </div>
            </div>
          </div>

          <div class="col-12 col-md-6 col-lg-4 mb-3">
            <div class="production">
              <div class="production-header">
                <a href="https://shao0524.github.io/todolist/">
                  <img src="~image/todolist.jpg" alt="代辦事項" class="image" />
                </a>
              </div>
              <div class="production-body">
                <a href="https://shao0524.github.io/todolist/"
                  ><h5>TodoList</h5>
                </a>
                <p>作品簡介：使用Vue.js串接Firebase即時資料庫建立todolist</p>
                <h6 class="text-end">（Vue.js、SCSS、Bootstrap、Firebase）</h6>
              </div>
              <div class="production-footer">
                <a href="https://shao0524.github.io/todolist/" class="btnDemo"
                  >Demo</a
                >
                <a href="https://github.com/shao0524/todolist" class="btnGit"
                  >Github</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <footer class="footer">
      <div class="container py-3">
        <div class="row">
          <div class="col-6">
            <div class="mb-1">
              <a href="https://goo.gl/maps/YfKtpe2ucSfYRqWb8">
                <i class="bi bi-geo-alt-fill fa-2x me-2"></i
                >高雄市鳳山區復仁街31號5樓
              </a>
            </div>
            <div class="mb-1">
              <a href="tel+0958141997"
                ><i class="bi bi-phone fa-2x me-2"></i>0958-141997</a
              >
            </div>
            <div class="mb-1">
              <a href="mailto:4a10h032@stust.edu.tw"
                ><i class="bi bi-envelope fa-2x me-2"></i>shao83524@gmail.com</a
              >
            </div>
          </div>
          <div class="col-6 d-flex justify-content-center align-items-center">
            <a href="https://github.com/shao0524" class="me-3"
              ><i class="bi bi-github fa-2x"></i
            ></a>
            <a href="https://www.facebook.com/?ref=logo"
              ><i class="bi bi-facebook fa-2x"></i
            ></a>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import $ from "jquery";
import { onMounted } from "vue";
export default {
  setup() {
    onMounted(() => {
      $("#scrollerDown").click(() => {
        console.log("h1");
        $("html,body").animate({ scrollTop: $("#about").offset().top }, 0);
      });
    });
    return {};
  },
};
</script>

<style lang="scss">
@import "~sass/all.scss";
</style>
