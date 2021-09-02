<template>
  <div class="landing-page-container">
    <div class="landing-page-container1">
      <div class="landing-page-top-container">
        <nav class="landing-page-navbar">
          <h1>Travel</h1>
          <div class="landing-page-right-side">
            <div class="landing-page-links-container">
              <span class="landing-page-text">Home</span>
              <span class="landing-page-text01">About</span>
              <span class="landing-page-text02">Tour Packages</span>
              <span class="landing-page-text03">Contact</span>
            </div>
            <a href="#main-section" class="landing-page-link">
              <solid-button
                button="Explore places"
                class="thqLink"
              ></solid-button>
            </a>
          </div>
          <svg viewBox="0 0 1024 1024" class="landing-page-burger-menu">
            <path
              d="M810.667 725.333h-597.333c-47.061 0-85.333 38.272-85.333 85.333s38.272 85.333 85.333 85.333h597.333c47.061 0 85.333-38.272 85.333-85.333s-38.272-85.333-85.333-85.333z"
            ></path>
            <path
              d="M810.667 426.667h-597.333c-47.061 0-85.333 38.272-85.333 85.333s38.272 85.333 85.333 85.333h597.333c47.061 0 85.333-38.272 85.333-85.333s-38.272-85.333-85.333-85.333z"
            ></path>
            <path
              d="M810.667 128h-597.333c-47.061 0-85.333 38.272-85.333 85.333s38.272 85.333 85.333 85.333h597.333c47.061 0 85.333-38.272 85.333-85.333s-38.272-85.333-85.333-85.333z"
            ></path>
          </svg>
        </nav>
        <div class="landing-page-hero">
          <div class="landing-page-content-container">
            <h1 class="heading landing-page-text04">John Jonny</h1>
            <h2 class="subheading landing-page-subheading">
              home for your personal travel
            </h2>
            <span class="landing-page-text05">
              <span>
                Each property is hand-picked,
                <span v-html="rawl7lv"></span>
              </span>
              <br />
              <span>personally visited and cannot be found elsewhere.</span>
            </span>
            <solid-button button="Explore homes"></solid-button>
          </div>
        </div>
      </div>
    </div>
    <div id="main-section" class="landing-page-main">
      <h1>Most famous places</h1>
      <span class="landing-page-text10">Recommended</span>
      <div class="landing-page-cards-container">
        <place-card
          city="London"
          image="https://images.unsplash.com/photo-1529655683826-aba9b3e77383?ixlib=rb-1.2.1&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb&amp;h=1000"
        ></place-card>
        <place-card
          city="Rome"
          image="https://images.unsplash.com/photo-1552832230-c0197dd311b5?ixlib=rb-1.2.1&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb&amp;h=1000"
        ></place-card>
        <place-card
          city="Cluj-Napoca"
          image="https://images.unsplash.com/photo-1513342791620-b106dc487c94?ixlib=rb-1.2.1&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb&amp;h=1000"
        ></place-card>
        <place-card
          city="Paris"
          image="https://images.unsplash.com/photo-1551634979-2b11f8c946fe?ixlib=rb-1.2.1&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb&amp;h=1000"
        ></place-card>
        <place-card
          city="Amsterdam"
          image="https://images.unsplash.com/photo-1585211969224-3e992986159d?ixlib=rb-1.2.1&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb&amp;h=1000"
        ></place-card>
        <place-card
          city="Barcelona"
          image="https://images.unsplash.com/photo-1564221710304-0b37c8b9d729?ixlib=rb-1.2.1&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb&amp;h=1000"
        ></place-card>
      </div>
    </div>
    <div class="landing-page-footer">
      <div class="landing-page-menu">
        <h1>Travel</h1>
        <div class="landing-page-links-container1">
          <div class="landing-page-container2">
            <a
              href="https://example.com"
              target="_blank"
              rel="noreferrer noopener"
              class="landing-page-link01 thqLink"
            >
              Tour packages
            </a>
            <a
              href="https://example.com"
              target="_blank"
              rel="noreferrer noopener"
              class="landing-page-link02 thqLink"
            >
              Personalized offers
            </a>
            <a
              href="https://example.com"
              target="_blank"
              rel="noreferrer noopener"
              class="landing-page-link03 thqLink"
            >
              Special deals
            </a>
            <a
              href="https://example.com"
              target="_blank"
              rel="noreferrer noopener"
              class="landing-page-link04 thqLink"
            >
              Summer holiday
              <span v-html="raw75a1"></span>
            </a>
          </div>
          <div class="landing-page-container3">
            <a
              href="https://example.com"
              target="_blank"
              rel="noreferrer noopener"
              class="landing-page-link05 thqLink"
            >
              About us
            </a>
            <a
              href="https://example.com"
              target="_blank"
              rel="noreferrer noopener"
              class="landing-page-link06 thqLink"
            >
              FAQ
            </a>
            <a
              href="https://example.com"
              target="_blank"
              rel="noreferrer noopener"
              class="landing-page-link07 thqLink"
            >
              Terms and conditions
            </a>
            <a
              href="https://example.com"
              target="_blank"
              rel="noreferrer noopener"
              class="landing-page-link08 thqLink"
            >
              Contact
            </a>
          </div>
        </div>
        <div class="landing-page-follow-container">
          <span class="landing-page-text11">
            Follow us on
            <span v-html="rawakzk"></span>
          </span>
          <div class="landing-page-icons-container">
            <a
              href="https://instagram.com"
              target="_blank"
              rel="noreferrer noopener"
              class="landing-page-link09"
            >
              <svg
                viewBox="0 0 877.7142857142857 1024"
                class="landing-page-icon3 thqLink"
              >
                <path
                  d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
                ></path>
              </svg>
            </a>
            <a
              href="https://facebook.com"
              target="_blank"
              rel="noreferrer noopener"
              class="landing-page-link10"
            >
              <svg
                viewBox="0 0 602.2582857142856 1024"
                class="landing-page-icon5 thqLink"
              >
                <path
                  d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
                ></path>
              </svg>
            </a>
            <a
              href="https://twitter.com"
              target="_blank"
              rel="noreferrer noopener"
              class="landing-page-link11"
            >
              <svg
                viewBox="0 0 950.8571428571428 1024"
                class="landing-page-icon7 thqLink"
              >
                <path
                  d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                ></path>
              </svg>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import SolidButton from '../components/solid-button'
import PlaceCard from '../components/place-card'

export default {
  name: 'LandingPage',
  components: {
    SolidButton,
    PlaceCard,
  },

  data() {
    return {
      rawl7lv: ' ',
      raw75a1: ' ',
      rawakzk: ' ',
    }
  },

  metaInfo: {
    title: 'Travel Agency',
    meta: [
      {
        property: 'og:title',
        content: 'Travel Agency',
      },
    ],
  },
}
</script>

<style scoped>
.landing-page-container {
  width: 100%;
  height: auto;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.landing-page-container1 {
  flex: 0 0 auto;
  width: 100%;
  height: 600px;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
.landing-page-top-container {
  width: 100%;
  height: 600px;
  display: flex;
  align-items: center;
  flex-direction: column;
  background-size: cover;
  background-image: url("https://images.unsplash.com/photo-1484627147104-f5197bcd6651?ixlib=rb-1.2.1&q=85&fm=jpg&crop=entropy&cs=srgb&w=1000");
  background-position: 0% 40%;
}
.landing-page-navbar {
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-doubleunit);
  max-width: 1000px;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.landing-page-right-side {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.landing-page-links-container {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.landing-page-text {
  margin-right: var(--dl-space-space-doubleunit);
}
.landing-page-text01 {
  margin-right: var(--dl-space-space-doubleunit);
}
.landing-page-text02 {
  margin-right: var(--dl-space-space-doubleunit);
}
.landing-page-text03 {
  margin-right: var(--dl-space-space-doubleunit);
}
.landing-page-link {
  display: contents;
}
.landing-page-burger-menu {
  width: 24px;
  height: 24px;
  display: none;
}
.landing-page-hero {
  flex: 1;
  width: 100%;
  display: flex;
  max-width: 1000px;
  align-items: center;
  padding-top: var(--dl-space-space-tripleunit);
  padding-left: var(--dl-space-space-doubleunit);
  padding-right: var(--dl-space-space-doubleunit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-tripleunit);
  justify-content: space-between;
}
.landing-page-content-container {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.landing-page-text05 {
  padding-top: var(--dl-space-space-doubleunit);
  padding-bottom: var(--dl-space-space-doubleunit);
}
.landing-page-main {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-quadruple);
  padding-left: var(--dl-space-space-doubleunit);
  padding-right: var(--dl-space-space-doubleunit);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-quadruple);
  justify-content: flex-start;
}
.landing-page-text10 {
  color: var(--dl-color-gray-500);
}
.landing-page-cards-container {
  width: 100%;
  display: flex;
  grid-gap: var(--dl-space-space-doubleunit);
  flex-wrap: wrap;
  max-width: 1000px;
  margin-top: var(--dl-space-space-doubleunit);
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-doubleunit);
  flex-direction: row;
  justify-content: space-between;
}
.landing-page-footer {
  color: var(--dl-color-gray-white);
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-tripleunit);
  align-items: center;
  flex-direction: row;
  justify-content: center;
  background-color: var(--dl-color-gray-black);
}
.landing-page-menu {
  width: 100%;
  display: flex;
  max-width: 1000px;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.landing-page-links-container1 {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.landing-page-container2 {
  display: flex;
  align-items: flex-start;
  margin-left: 100px;
  flex-direction: column;
}
.landing-page-link01 {
  margin-bottom: var(--dl-space-space-unit);
  text-decoration: none;
}
.landing-page-link02 {
  margin-bottom: var(--dl-space-space-unit);
  text-decoration: none;
}
.landing-page-link03 {
  margin-bottom: var(--dl-space-space-unit);
  text-decoration: none;
}
.landing-page-link04 {
  text-decoration: none;
}
.landing-page-container3 {
  display: flex;
  align-items: flex-start;
  margin-left: 100px;
  flex-direction: column;
}
.landing-page-link05 {
  margin-bottom: var(--dl-space-space-unit);
  text-decoration: none;
}
.landing-page-link06 {
  margin-bottom: var(--dl-space-space-unit);
  text-decoration: none;
}
.landing-page-link07 {
  margin-bottom: var(--dl-space-space-unit);
  text-decoration: none;
}
.landing-page-link08 {
  text-decoration: none;
}
.landing-page-follow-container {
  display: flex;
  align-items: center;
  margin-left: 50px;
  flex-direction: column;
  justify-content: space-between;
}
.landing-page-text11 {
  padding-bottom: var(--dl-space-space-halfunit);
}
.landing-page-icons-container {
  width: 100px;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.landing-page-link09 {
  display: contents;
}
.landing-page-icon3 {
  fill: var(--dl-color-gray-white);
  width: 24px;
  height: 24px;
}
.landing-page-link10 {
  display: contents;
}
.landing-page-icon5 {
  fill: var(--dl-color-gray-white);
  width: 24px;
  height: 24px;
}
.landing-page-link11 {
  display: contents;
}
.landing-page-icon7 {
  fill: var(--dl-color-gray-white);
  width: 24px;
  height: 24px;
}
@media(max-width: 991px) {
  .landing-page-hero {
    padding-left: var(--dl-space-space-tripleunit);
    padding-right: var(--dl-space-space-tripleunit);
  }
  .landing-page-cards-container {
    justify-content: center;
  }
}
@media(max-width: 767px) {
  .landing-page-right-side {
    display: none;
  }
  .landing-page-burger-menu {
    display: flex;
  }
  .landing-page-hero {
    justify-content: center;
  }
  .landing-page-content-container {
    align-items: center;
  }
  .landing-page-text04 {
    font-size: 2.5rem;
  }
  .landing-page-text05 {
    text-align: center;
  }
  .landing-page-main {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
  .landing-page-menu {
    flex-direction: column;
  }
  .landing-page-links-container1 {
    margin-top: var(--dl-space-space-tripleunit);
    margin-bottom: var(--dl-space-space-tripleunit);
    justify-content: space-between;
  }
  .landing-page-container2 {
    margin-left: 0px;
  }
}
@media(max-width: 479px) {
  .landing-page-text04 {
    font-size: 2rem;
    text-align: center;
  }
  .landing-page-subheading {
    font-size: 1.3rem;
    text-align: center;
  }
  .landing-page-links-container1 {
    margin-top: var(--dl-space-space-doubleunit);
    align-items: flex-start;
    justify-content: flex-start;
  }
  .landing-page-link01 {
    margin-bottom: var(--dl-space-space-halfunit);
  }
  .landing-page-link02 {
    margin-bottom: var(--dl-space-space-halfunit);
  }
  .landing-page-link03 {
    margin-bottom: var(--dl-space-space-halfunit);
  }
  .landing-page-link04 {
    margin-bottom: var(--dl-space-space-halfunit);
  }
  .landing-page-container3 {
    height: 100%;
    align-items: flex-start;
    margin-left: 50px;
  }
  .landing-page-link05 {
    margin-bottom: var(--dl-space-space-halfunit);
  }
  .landing-page-link06 {
    margin-bottom: var(--dl-space-space-halfunit);
  }
  .landing-page-link07 {
    margin-bottom: var(--dl-space-space-halfunit);
  }
  .landing-page-link08 {
    margin-bottom: var(--dl-space-space-halfunit);
  }
  .landing-page-follow-container {
    margin-left: 0px;
  }
}
</style>
