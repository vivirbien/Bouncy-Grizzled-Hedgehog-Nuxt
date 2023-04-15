<template>
  <div class="post-container">
    <header data-role="Header" class="post-header">
      <img
        alt="logo"
        src="https://presentation-website-assets.teleporthq.io/logos/logo.png"
        class="post-image"
      />
      <div class="post-nav">
        <navigation-links rootClassName="rootClassName12"></navigation-links>
      </div>
      <div class="post-btn-group"><button class="button">Suscribete</button></div>
      <div data-role="BurgerMenu" class="post-burger-menu">
        <svg viewBox="0 0 1024 1024" class="post-icon">
          <path
            d="M128 554.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 298.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 810.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
          ></path>
        </svg>
      </div>
      <div data-role="MobileMenu" class="post-mobile-menu">
        <div class="post-nav1">
          <div class="post-container1">
            <img
              alt="image"
              src="https://presentation-website-assets.teleporthq.io/logos/logo.png"
              class="post-image1"
            />
            <div data-role="CloseMobileMenu" class="post-menu-close">
              <svg viewBox="0 0 1024 1024" class="post-icon02">
                <path
                  d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                ></path>
              </svg>
            </div>
          </div>
          <navigation-links rootClassName="rootClassName13"></navigation-links>
        </div>
        <div>
          <svg viewBox="0 0 950.8571428571428 1024" class="post-icon04">
            <path
              d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
            ></path></svg
          ><svg viewBox="0 0 877.7142857142857 1024" class="post-icon06">
            <path
              d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
            ></path></svg
          ><svg viewBox="0 0 602.2582857142856 1024" class="post-icon08">
            <path
              d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
            ></path>
          </svg>
        </div>
      </div>
    </header>
    <div class="post-hero">
      <div class="post-container2">
        <h1 class="post-text">
          <span class="post-text01">Ultimos</span>
          <br />
          <span>artículos</span>
          <br />
        </h1>
        <span class="post-text05">
          <span>Descubre los secretos de la longevidad y la salud óptima</span>
          <span><span v-html="rawa6i4"></span></span>
          <span><span v-html="rawm4xq"></span></span>
        </span>
      </div>
    </div>
    <div class="post-container3"></div>
    <footer class="post-footer">
      <div class="post-container4">
        <img
          alt="logo"
          src="https://presentation-website-assets.teleporthq.io/logos/logo.png"
          class="post-image2"
        />
        <nav class="post-nav2">
          <span class="post-text09">About</span>
          <span class="post-text10">Features</span>
          <span class="post-text11">Pricing</span>
          <span class="post-text12">Team</span>
          <span class="post-text13">Blog</span>
        </nav>
      </div>
      <div class="post-separator"></div>
      <div class="post-container5">
        <span class="post-text14">© 2021 teleportHQ, All Rights Reserved.</span>
        <div class="post-icon-group1">
          <svg viewBox="0 0 950.8571428571428 1024" class="post-icon10">
            <path
              d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
            ></path></svg
          ><svg viewBox="0 0 877.7142857142857 1024" class="post-icon12">
            <path
              d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
            ></path></svg
          ><svg viewBox="0 0 602.2582857142856 1024" class="post-icon14">
            <path
              d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
            ></path>
          </svg>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import NavigationLinks from '../components/navigation-links'

export default {
  name: 'Post',
  components: {
    NavigationLinks,
  },
  data() {
    return {
      rawa6i4: ' ',
      rawm4xq: ' ',
    }
  },
  head: {
    title: 'Post - Bouncy Grizzled Hedgehog',
    meta: [
      {
        property: 'og:title',
        content: 'Post - Bouncy Grizzled Hedgehog',
      },
    ],
  },
}
</script>

<style scoped>
.post-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  background-color: #97ca97;
}
.post-header {
  width: 90%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  box-shadow: 5px 5px 10px 0px rgba(105, 105, 105, 0.11);
  margin-top: var(--dl-space-space-twounits);
  align-items: center;
  padding-top: var(--dl-space-space-oneandhalfunits);
  padding-left: var(--dl-space-space-oneandhalfunits);
  border-radius: var(--dl-radius-radius-radius8);
  padding-right: var(--dl-space-space-oneandhalfunits);
  padding-bottom: var(--dl-space-space-oneandhalfunits);
  justify-content: space-between;
  background-color: rgba(189, 218, 173, 0.56);
}
.post-image {
  height: 2rem;
}
.post-nav {
  display: flex;
}
.post-btn-group {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.post-burger-menu {
  display: none;
}
.post-icon {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.post-mobile-menu {
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100vh;
  display: none;
  padding: 32px;
  z-index: 100;
  position: absolute;
  flex-direction: column;
  justify-content: space-between;
  background-color: #fff;
}
.post-nav1 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.post-container1 {
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-threeunits);
  justify-content: space-between;
}
.post-image1 {
  height: 2rem;
}
.post-menu-close {
  display: flex;
  align-items: center;
  justify-content: center;
}
.post-icon02 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.post-icon04 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.post-icon06 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.post-icon08 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.post-hero {
  width: 90%;
  margin: auto;
  display: flex;
  padding: var(--dl-space-space-threeunits);
  max-width: var(--dl-size-size-maxwidth);
  min-height: 80vh;
  align-items: center;
  align-content: center;
  flex-direction: row;
  justify-content: space-between;
}
.post-container2 {
  display: flex;
  margin-right: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
}
.post-text {
  color: rgb(25, 25, 25);
  font-size: 3rem;
  max-width: 450px;
  font-family: Playfair Display;
}
.post-text05 {
  margin-top: var(--dl-space-space-twounits);
  margin-bottom: var(--dl-space-space-twounits);
}
.post-container3 {
  flex: 0 0 auto;
  width: 90%;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  margin: auto;
  display: flex;
  padding: var(--dl-space-space-sixunits);
  overflow: hidden;
  align-self: center;
  align-items: flex-start;
  margin-left: 5%;
  border-radius: var(--dl-radius-radius-radius8);
  justify-content: center;
  background-color: rgba(86, 140, 57, 0.19);
}
.post-footer {
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  padding-top: var(--dl-space-space-twounits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-twounits);
  justify-content: space-between;
}
.post-container4 {
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  flex-direction: column;
  justify-content: space-between;
}
.post-image2 {
  height: 2rem;
  margin-bottom: var(--dl-space-space-twounits);
}
.post-nav2 {
  flex: 0 0 auto;
  display: flex;
  margin-top: 0px;
  align-items: center;
  flex-direction: row;
}
.post-text09 {
  margin-left: 0px;
}
.post-text10 {
  margin-left: var(--dl-space-space-unit);
}
.post-text11 {
  margin-left: var(--dl-space-space-unit);
}
.post-text12 {
  margin-left: var(--dl-space-space-unit);
}
.post-text13 {
  margin-left: var(--dl-space-space-unit);
}
.post-separator {
  flex: 0 0 auto;
  width: 100%;
  height: 0px;
  display: flex;
  margin-top: var(--dl-space-space-twounits);
  align-items: flex-start;
  margin-left: 0px;
  border-color: var(--dl-color-gray-900);
  border-style: solid;
  border-width: 1px;
  margin-right: 0px;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
  border-top-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
}
.post-container5 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.post-icon-group1 {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.post-icon10 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.post-icon12 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.post-icon14 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
@media(max-width: 991px) {
  .post-hero {
    flex-direction: column;
  }
  .post-container2 {
    align-items: center;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
    padding-right: 0px;
  }
  .post-text {
    text-align: center;
  }
  .post-text01 {
    text-align: center;
  }
  .post-text05 {
    text-align: center;
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
  }
}
@media(max-width: 767px) {
  .post-header {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .post-nav {
    display: none;
  }
  .post-btn-group {
    display: none;
    flex-direction: row;
  }
  .post-burger-menu {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .post-hero {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .post-text05 {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .post-footer {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .post-image2 {
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .post-separator {
    margin-top: var(--dl-space-space-oneandhalfunits);
    margin-left: 0px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .post-container5 {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .post-text14 {
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
@media(max-width: 479px) {
  .post-header {
    padding: var(--dl-space-space-unit);
  }
  .post-mobile-menu {
    padding: 16px;
  }
  .post-hero {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .post-container2 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .post-footer {
    padding: var(--dl-space-space-unit);
  }
  .post-separator {
    margin-top: var(--dl-space-space-oneandhalfunits);
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .post-container5 {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .post-text14 {
    text-align: center;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
</style>
