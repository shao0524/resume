<template>
  <div>
    <header>
      <div class="container">
        <div class="header">
          <img src="~image/headShot.jpg" class="headShot" alt="headShot" />
          <h2 class="mt-3 text-center">陳致劭</h2>
          <div class="info">
            <h5>前端工程師</h5>
            <span class="line">|</span>
            <span>
              <i class="bi bi-envelope-open me-1"></i>
              <a href="mailto:shao83524@gmail.com">shao83524@gmail.com</a></span
            >
            <span class="line">|</span>
            <span>
              <i class="bi bi-phone me-1"></i>
              <a href="tel+0958141997">0958141997</a></span
            >
            <span class="line">|</span>
            <span>
              <i class="fab fa-codepen"></i>
              <a href="https://codepen.io/shao83524">CodePen</a>
            </span>
          </div>

          <h5></h5>
          <!-- img -->
        </div>
        <!-- 介紹 -->
        <p class="text-center mt-5">
          我是陳致劭，畢業於南台科技大學資訊工程系，畢業後由於還沒找到目標，在餐飲業工作了幾年，並在閒暇之餘不斷地學習其他的技能。
          今年偶然地看到六角學院的教學影片，發現與大學時期學過的網頁設計課程截然不同，因此產生了想要探求新知識動力，開始透過線上課程學習相關技術。
          在學習的過程中常常會遇到一些難題，我會透過網路尋找解決問題的方式，解決了這些難題讓我得到許多的成就感，也讓我對寫程式越來越投入。
        </p>
      </div>
    </header>

    <main class="mb-5">
      <section>
        <div class="container">
          <h3>Skill</h3>
          <hr />
          <ul class="list">
            <li class="list-item">
              <h3>Web Layout</h3>
              <ul class="subList">
                <li class="subList-item">熟悉SCSS用法</li>
                <li class="subList-item">使用Bootstrap切版</li>
                <li class="subList-item">建立RWD響應式網頁</li>
              </ul>
            </li>
            <li class="list-item">
              <h3>JavaScript</h3>
              <ul class="subList">
                <li class="subList-item">了解並會使用ES6語法</li>
                <li class="subList-item">透過AJAX串接第三方API</li>
                <li class="subList-item">使用jQuery做出動畫效果</li>
                <li class="subList-item">使用Node.js/Express建立簡易伺服器</li>
                <li class="subList-item">使用Express建立RESTful API</li>
                <li class="subList-item">使用Node.js串接MongoDB</li>
              </ul>
            </li>
            <li class="list-item">
              <h3>Vue.js</h3>
              <ul class="subList">
                <li class="subList-item">使用Vue-Cli建立專案</li>
                <li class="subList-item">使用Vue-Router管理路由</li>
                <li class="subList-item">使用Vue-Axios串接API</li>
                <li class="subList-item">使用Vuex</li>
              </ul>
            </li>
          </ul>
        </div>
      </section>

      <!-- project -->
      <section>
        <div class="container">
          <h3>作品</h3>
          <hr />
          <ProductComponent>
            <template v-slot:img>
              <img src="~image/cheeseny.jpg" class="image" alt="cheeseny" />
            </template>
            <template v-slot:title> Vue.js電商平台練習網站 Cheeseny </template>
            <template v-slot:btn>
              <a class="linkBtn" href="https://shao0524.github.io/cheeseShop/#/"
                >Demo</a
              >
              <span class="mx-1">|</span>
              <a class="linkBtn" href="https://github.com/shao0524/cheeseShop"
                >Github</a
              >
            </template>
            <template v-slot:content>
              <ul>
                <li>網站主要使用Vue.js架設</li>
                <li>使用Vue-Router管理路由</li>
                <li>使用Vue-Axios串接六角學院提供API</li>
                <li>使用SCSS管理樣式與RWD響應式網頁</li>
                <li>使用Vee-Validator表單驗證</li>
                <li>使用第三方套件Vue-Swiper做輪播效果</li>
              </ul>
            </template>
          </ProductComponent>
          <br />
          <ProductComponent>
            <template v-slot:img>
              <img
                src="~image/bikeMap.jpg"
                class="image"
                alt="自行車租借站與車道地圖"
              />
            </template>
            <template v-slot:title>
              Vue.js + TDX API 自行車租借站與車道地圖
            </template>
            <template v-slot:btn>
              <a class="linkBtn" href="https://shao0524.github.io/BikeMap/"
                >Demo</a
              >
              <span class="mx-1">|</span>
              <a class="linkBtn" href="https://github.com/shao0524/BikeMap"
                >Github</a
              >
            </template>
            <template v-slot:content>
              <ul>
                <li>網站主要使用Vue.js架設</li>
                <li>
                  使用Vue-Axios串接TDX API取得自行車道路與租借站的即時資訊
                </li>
                <li>使用Leaflet.js與OpenStreetMap製作地圖資訊</li>
                <li>
                  透過查詢地區找到該地區的自行車車道並顯示該車道附近的租借站資訊
                </li>
                <li>使用SCSS管理樣式並製作RWD響應式網頁</li>
                <li>使用第三方套件Swiper做輪播效果</li>
              </ul>
            </template>
          </ProductComponent>
          <br />
          <ProductComponent>
            <template v-slot:img>
              <img
                src="~image/chiuantaishin.jpg"
                class="image"
                alt="全台新商行"
              />
            </template>
            <template v-slot:title> 全台新商行 </template>
            <template v-slot:btn>
              <a class="linkBtn" href="http://www.chiuantaishin.com/">Demo</a>
            </template>
            <template v-slot:content>
              <ul>
                <li>此網站是為了向客戶展示主要販售商品而開發</li>
                <li>網站主要使用Vue.js架設</li>
                <li>使用Vue-Router管理路由</li>
                <li>串接至Firebase的Firestore Database和Storage</li>
                <li>使用Bootstrap 4切版</li>
                <li>使用SCSS管理樣式並製作RWD響應式網頁</li>
                <li>使用node.js渲染打包後的檔案部屬至Heroku</li>
              </ul>
            </template>
          </ProductComponent>
        </div>
      </section>
    </main>
  </div>
</template>

<script>
import ProductComponent from "components/ProductComponent";
import $ from "jquery";
import { onMounted } from "vue";
export default {
  components: {
    ProductComponent,
  },
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
