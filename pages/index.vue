<template>
  <div class="home-container">
    <header data-role="Header" class="home-header">
      <img
        alt="logo"
        src="https://presentation-website-assets.teleporthq.io/logos/logo.png"
        class="home-image"
      />
      <div class="home-nav">
        <navigation-links rootClassName="rootClassName10"></navigation-links>
      </div>
      <div class="home-btn-group"><button class="button">Suscribete</button></div>
      <div data-role="BurgerMenu" class="home-burger-menu">
        <svg viewBox="0 0 1024 1024" class="home-icon">
          <path
            d="M128 554.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 298.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 810.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
          ></path>
        </svg>
      </div>
      <div data-role="MobileMenu" class="home-mobile-menu">
        <div class="home-nav1">
          <div class="home-container1">
            <img
              alt="image"
              src="https://presentation-website-assets.teleporthq.io/logos/logo.png"
              class="home-image1"
            />
            <div data-role="CloseMobileMenu" class="home-menu-close">
              <svg viewBox="0 0 1024 1024" class="home-icon02">
                <path
                  d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                ></path>
              </svg>
            </div>
          </div>
          <navigation-links rootClassName="rootClassName11"></navigation-links>
        </div>
        <div>
          <svg viewBox="0 0 950.8571428571428 1024" class="home-icon04">
            <path
              d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
            ></path></svg
          ><svg viewBox="0 0 877.7142857142857 1024" class="home-icon06">
            <path
              d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
            ></path></svg
          ><svg viewBox="0 0 602.2582857142856 1024" class="home-icon08">
            <path
              d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
            ></path>
          </svg>
        </div>
      </div>
    </header>
    <div class="home-hero">
      <div class="home-container2">
        <h1 class="home-text">Vive más, vive mejor</h1>
        <span class="home-text01">
          <span>Descubre los secretos de la longevidad y la salud óptima</span>
          <span><span v-html="rawbxzo"></span></span>
          <span><span v-html="rawdtiv"></span></span>
        </span>
        <div class="home-btn-group1">
          <button class="home-button button">Suscribete</button>
          <button class="home-button1 button">Contactar</button>
        </div>
      </div>
      <img
        alt="image"
        src="https://images.unsplash.com/photo-1525498128493-380d1990a112?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDI0fHxtaW5pbWFsaXNtJTIwZ3JlZW58ZW58MHx8fHwxNjI1ODQxMDcw&amp;ixlib=rb-1.2.1&amp;h=1500"
        class="home-image2"
      />
    </div>
    <div class="home-banner">
      <h2 class="home-text05">
        <br class="Content" />
        <span>VidaLonga</span>
        <br class="Content" />
        <span class="Content"><span v-html="raw9403"></span></span>
        <br class="home-text10" />
        <span class="Content"><span v-html="rawqvh6"></span></span>
      </h2>
      <span class="home-text12">
        un recurso en línea dedicado a la longevidad y la salud en general.
        Nuestra empresa fue fundada en 2023 por un equipo de expertos en
        nutrición, bienestar y ciencias biomédicas, con el objetivo de compartir
        información valiosa y ayudar a las personas a vivir vidas más largas y
        saludables.
      </span>
      <button class="home-button2 button">Leer Más</button>
    </div>
    <div class="home-container3">
      <iframe
        src="https://www.youtube.com/embed/d9Owtj668sI"
        allowfullscreen
        class="home-iframe"
      ></iframe>
    </div>
    <footer class="home-footer">
      <div class="home-container4">
        <img
          alt="logo"
          src="https://presentation-website-assets.teleporthq.io/logos/logo.png"
          class="home-image3"
        />
        <nav class="home-nav2">
          <span class="home-text13">About</span>
          <span class="home-text14">Features</span>
          <span class="home-text15">Pricing</span>
          <span class="home-text16">Team</span>
          <span class="home-text17">Blog</span>
        </nav>
      </div>
      <div class="home-separator"></div>
      <div class="home-container5">
        <span class="home-text18">© 2021 teleportHQ, All Rights Reserved.</span>
        <div class="home-icon-group1">
          <svg viewBox="0 0 950.8571428571428 1024" class="home-icon10">
            <path
              d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
            ></path></svg
          ><svg viewBox="0 0 877.7142857142857 1024" class="home-icon12">
            <path
              d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
            ></path></svg
          ><svg viewBox="0 0 602.2582857142856 1024" class="home-icon14">
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
  name: 'Home',
  components: {
    NavigationLinks,
  },
  data() {
    return {
      rawbxzo: ' ',
      rawdtiv: ' ',
      raw9403: ' ',
      rawqvh6: ' ',
    }
  },
  head: {
    title: 'Bouncy Grizzled Hedgehog',
    meta: [
      {
        property: 'og:title',
        content: 'Bouncy Grizzled Hedgehog',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  background-color: #97ca97;
}
.home-header {
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
.home-image {
  height: 2rem;
}
.home-nav {
  display: flex;
}
.home-btn-group {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-burger-menu {
  display: none;
}
.home-icon {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.home-mobile-menu {
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
.home-nav1 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-container1 {
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-threeunits);
  justify-content: space-between;
}
.home-image1 {
  height: 2rem;
}
.home-menu-close {
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-icon02 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.home-icon04 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.home-icon06 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.home-icon08 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.home-hero {
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
.home-container2 {
  display: flex;
  margin-right: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
}
.home-text {
  color: #191919;
  font-size: 3rem;
  max-width: 450px;
  font-family: Playfair Display;
}
.home-text01 {
  margin-top: var(--dl-space-space-twounits);
  margin-bottom: var(--dl-space-space-twounits);
}
.home-btn-group1 {
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-button {
  transition: 0.3s;
  padding-top: var(--dl-space-space-unit);
  padding-left: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-twounits);
  padding-bottom: var(--dl-space-space-unit);
}
.home-button:hover {
  color: var(--dl-color-gray-white);
  background-color: var(--dl-color-gray-black);
}
.home-button1 {
  transition: 0.3s;
  margin-left: var(--dl-space-space-unit);
  padding-top: var(--dl-space-space-unit);
  border-color: transparent;
  padding-left: var(--dl-space-space-twounits);
  padding-right: var(--dl-space-space-twounits);
  padding-bottom: var(--dl-space-space-unit);
}
.home-button1:hover {
  border-color: var(--dl-color-gray-black);
}
.home-image2 {
  width: 400px;
  object-fit: cover;
  border-color: var(--dl-color-gray-black);
  border-width: 1px;
  border-radius: var(--dl-radius-radius-radius8);
}
.home-banner {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: 200px;
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: 100px;
  justify-content: space-between;
}
.home-text05 {
  color: rgb(35, 35, 35);
  width: 503px;
  font-size: 3rem;
  font-style: normal;
  text-align: left;
  font-family: Playfair Display;
  font-weight: 400;
  line-height: 1.15;
  margin-bottom: var(--dl-space-space-halfunit);
  text-transform: none;
  text-decoration: none;
}
.home-text10 {
  color: #232323;
  font-style: normal;
  font-family: Inconsolata;
}
.home-text12 {
  height: 100%;
  max-width: 500px;
  font-family: Roboto;
  line-height: 2.5rem;
  margin-bottom: var(--dl-space-space-threeunits);
  letter-spacing: 1px;
}
.home-button2 {
  align-self: center;
  text-align: left;
  transition: 0.3s;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-halfunit);
}
.home-button2:hover {
  color: var(--dl-color-gray-white);
  background-color: var(--dl-color-gray-black);
}
.home-container3 {
  flex: 0 0 auto;
  width: 90%;
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
.home-iframe {
  width: 674px;
  height: 289px;
  border-color: #1e1e1e;
  border-width: 4px;
  border-radius: var(--dl-radius-radius-radius8);
}
.home-footer {
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
.home-container4 {
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  flex-direction: column;
  justify-content: space-between;
}
.home-image3 {
  height: 2rem;
  margin-bottom: var(--dl-space-space-twounits);
}
.home-nav2 {
  flex: 0 0 auto;
  display: flex;
  margin-top: 0px;
  align-items: center;
  flex-direction: row;
}
.home-text13 {
  margin-left: 0px;
}
.home-text14 {
  margin-left: var(--dl-space-space-unit);
}
.home-text15 {
  margin-left: var(--dl-space-space-unit);
}
.home-text16 {
  margin-left: var(--dl-space-space-unit);
}
.home-text17 {
  margin-left: var(--dl-space-space-unit);
}
.home-separator {
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
.home-container5 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-icon-group1 {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-icon10 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.home-icon12 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.home-icon14 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
@media(max-width: 991px) {
  .home-hero {
    flex-direction: column;
  }
  .home-container2 {
    align-items: center;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
    padding-right: 0px;
  }
  .home-text {
    text-align: center;
  }
  .home-text01 {
    text-align: center;
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
  }
  .home-text12 {
    line-height: 2.5rem;
  }
}
@media(max-width: 767px) {
  .home-header {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-nav {
    display: none;
  }
  .home-btn-group {
    display: none;
    flex-direction: row;
  }
  .home-burger-menu {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .home-hero {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-text01 {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .home-image2 {
    width: 80%;
  }
  .home-banner {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-footer {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-image3 {
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-separator {
    margin-top: var(--dl-space-space-oneandhalfunits);
    margin-left: 0px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-container5 {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .home-text18 {
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
@media(max-width: 479px) {
  .home-header {
    padding: var(--dl-space-space-unit);
  }
  .home-mobile-menu {
    padding: 16px;
  }
  .home-hero {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-container2 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-btn-group1 {
    flex-direction: column;
  }
  .home-button1 {
    margin-top: var(--dl-space-space-unit);
    margin-left: 0px;
  }
  .home-banner {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-text05 {
    align-self: flex-start;
  }
  .home-text12 {
    line-height: 2.5rem;
  }
  .home-footer {
    padding: var(--dl-space-space-unit);
  }
  .home-separator {
    margin-top: var(--dl-space-space-oneandhalfunits);
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-container5 {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .home-text18 {
    text-align: center;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
</style>
