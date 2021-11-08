<template>
  <div>
    <header class="banner">
      <div class="banner-mask"></div>
      <div class="banner-content">
        <div class="container">
          <div class="row">
            <div class="col-12 col-md-4 col-lg-4">
              <div class="h-100 text-center">
                <!-- 圖片 -->
                <img
                  src="~image/headShot.jpg"
                  class="headShot"
                  alt="headShot"
                />
              </div>
            </div>
            <div
              class="
                col-12 col-md-8 col-lg-8
                text-center text-md-start text-lg-start
                pt-3 pt-md-3 pt-lg-0
              "
            >
              <h2 class="display-4 fw-bolder text-white">
                陳致劭 Chih Shao Chen
              </h2>
              <ul class="text-start">
                <li class="py-1">
                  <a class="h4" href="mailto:4a10h032@stust.edu.tw"
                    ><i class="bi bi-envelope"></i>：shao83524@gmail.com</a
                  >
                </li>
                <li class="py-1">
                  <a class="h4" href="tel:0958141997"
                    ><i class="bi bi-phone"></i>：0958141997</a
                  >
                </li>
                <li class="py-1">
                  <a class="h4" href="https://github.com/shao0524/"
                    ><i class="bi bi-github"></i
                    >：https://github.com/shao0524/</a
                  >
                </li>
              </ul>
            </div>
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
          在學習的過程中雖然常常會遇到一些難題，我會透過網路尋找解決問題的方式，這些難題讓我在學習的過程中得到了許多經驗，今後也會不斷地學習新的技術讓自己成長。
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
              <img src="~image/htmlCSS.jpg" alt="HTML&CSS" class="image" />
              <h3>HTML & CSS</h3>
              <ul class="align-self-start text-start">
                <li>
                  可依據設計稿切出版型以及手刻RWD版型，並且透過CSS3製作動畫效果
                </li>
              </ul>
            </div>
          </div>
          <div class="col-12 col-md-6 col-lg-4 mb-3">
            <div class="itemBox">
              <img src="~image/js.jpg" alt="JavaScript" class="image" />
              <h3>JavaScript</h3>
              <ul class="text-start">
                <li>了解ES6語法</li>
                <li>對JavaScript有基礎的了解，也常使用jQuery做練習</li>
                <li>JQuery-使用Ajax取得第三方API</li>
                <li>套用Plugin在網頁上，舉例Swiper、Leaflet…等</li>
              </ul>
            </div>
          </div>
          <div class="col-12 col-md-6 col-lg-4 mb-3">
            <div class="itemBox">
              <img src="~image/bs.jpg" alt="Bootstrap" class="image" />
              <h3>Bootstrap</h3>
              <ul class="text-start">
                <li>
                  了解Bootstrap4
                  Grid、Components以及Utilities的使用，並且修改成客製化的Bootstrap
                  SCSS
                </li>
              </ul>
            </div>
          </div>
          <div class="col-12 col-md-6 col-lg-4 mb-3">
            <div class="itemBox">
              <img src="~image/vue.jpg" alt="Vue" class="image" />
              <h3>Vue.js</h3>
              <ul class="text-start">
                <li>了解Vue的生命週期</li>
                <li>使用Vue Cli2&3，搭配Router切換路徑、Vuex資料的管理</li>
                <li>
                  搭配Plugin做開發，舉例Vue-axios串接API、Vee-validate輸入表單認證等
                </li>
              </ul>
            </div>
          </div>
          <div class="col-12 col-md-6 col-lg-4 mb-3">
            <div class="itemBox">
              <img src="~image/node.jpg" alt="Node.js" class="image" />
              <h3>Node.js</h3>
              <ul class="text-start">
                <li>使用Express建立RESTful API</li>
                <li>利用firebase，製作使用者認證與即時資料庫</li>
                <li>使用Nodemailer製作郵件發送功能</li>
              </ul>
            </div>
          </div>
          <div class="col-12 col-md-6 col-lg-4 mb-3">
            <div class="itemBox">
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
    </section>

    <!-- 作品集 -->
    <section class="my-5 pb-5">
      <div class="container">
        <h3 class="title text-center">作品集</h3>
        <div class="row">
          <div class="col-12 col-md-6 col-lg-4">
            <div class="production">
              <div class="production-header">
                <a href="https://shao0524.github.io/BMI/">
                  <img src="~image/bmi.jpg" alt="BMI" class="image" />
                </a>
              </div>
              <div class="production-body">
                <a href="https://shao0524.github.io/BMI/"
                  ><h5>BMI計算器</h5>
                </a>
                <p>作品簡介：六角學院的BMI作業，無套用任何框架。</p>
                <h6 class="text-end">（HTML、CSS、Javascript）</h6>
              </div>
              <div class="production-footer">
                <a href="https://shao0524.github.io/BMI/" class="btnDemo"
                  >Demo</a
                >
                <a href="https://github.com/shao0524/BMI" class="btnGit"
                  >Github</a
                >
              </div>
            </div>
          </div>

          <div class="col-12 col-md-6 col-lg-4">
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
                <p>作品簡介：六角學院Vue課程的最終練習作業。</p>
                <h6 class="text-end">（Vue 2、SCSS、Bootstrap 4、Swiper）</h6>
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

          <div class="col-12 col-md-6 col-lg-4">
            <div class="production">
              <div class="production-header">
                <a href="https://map-10-08.herokuapp.com/">
                  <img
                    src="~image/tourMap.jpg"
                    alt="台灣旅遊地圖"
                    class="image"
                  />
                </a>
              </div>
              <div class="production-body">
                <a href="https://map-10-08.herokuapp.com/"
                  ><h5>台灣旅遊地圖</h5>
                </a>
                <p>
                  作品簡介：練習使用Vue
                  3結合OpenStreetMap，搭配Express建立後端伺服器，串接政府資料公開平台API製作台灣旅遊地圖，並部屬至Heroku。
                </p>
                <h6 class="text-end">
                  （Vue 3、SCSS、Bootstrap
                  5、Leaflet、openStreetMap、Node.js、Heroku）
                </h6>
              </div>
              <div class="production-footer">
                <a href="https://map-10-08.herokuapp.com/" class="btnDemo"
                  >Demo</a
                >
                <a href="https://github.com/shao0524/Tour-Map" class="btnGit"
                  >Github</a
                >
              </div>
            </div>
          </div>

          <div class="col-12 col-md-6 col-lg-4">
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
                <p>作品簡介：練習使用Vue 3 結合Firebase建立todolist</p>
                <h6 class="text-end">（Vue 3、SCSS、Bootstrap 5、Firebase）</h6>
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
              <a
                href="https://goo.gl/maps/YfKtpe2ucSfYRqWb8"
                class="text-white"
              >
                <i class="bi bi-geo-alt-fill fa-2x me-2"></i
                >高雄市鳳山區復仁街31號5樓
              </a>
            </div>
            <div class="mb-1">
              <a href="tel+0958141997" class="text-white"
                ><i class="bi bi-phone-fill fa-2x me-2"></i>0958-141997</a
              >
            </div>
            <div class="mb-1">
              <a href="mailto:4a10h032@stust.edu.tw" class="text-white"
                ><i class="bi bi-envelope fa-2x me-2"></i>shao83524@gmail.com</a
              >
            </div>
          </div>
          <div class="col-6 d-flex justify-content-center align-items-center">
            <a href="https://github.com/shao0524" class="text-white me-3"
              ><i class="bi bi-github fa-2x"></i
            ></a>
            <a href="https://www.facebook.com/?ref=logo" class="text-white"
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
