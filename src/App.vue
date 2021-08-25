<template>
  <div class="content">
    <div class="nav-bar">
      <div class="mobile-nav">
        <h1 id="logo"><a href="#landing-page">emraftis</a></h1>
        <div class="burger-container">
          <div class="burger" @click="toggleNavActive">
            <div class="line1"></div>
            <div class="line2"></div>
            <div class="line3"></div>
          </div>
        </div>
      </div>
      <div :class="navIsActive ? 'overlay-active' : 'overlay'">
        <ul class="nav-links">
          <li class="link"><a href="#about-page" @click="closeOverlay">About Me</a></li>
          <li class="link"><a href="#projects-page" @click="closeOverlay">My Projects</a></li>
          <li class="link"><a href="#contact-page" @click="closeOverlay">Contact Me</a></li>
          <li class="link"><a href="https://drive.google.com/uc?id=1YjKZkQDb6Xe_gkZ4gvlISIZ5uMa9sWBF&export=download" @click="closeOverlay">Resume Link</a></li>
          <li>
            <div class="svg-icon-list">
              <div class="hover-icon">
                <a target="_blank" href="https://github.com/emraftis">
                  <svg height="50" width="50" xmlns="http://www.w3.org/2000/svg" role="img" viewBox="0 0.27 24 24">
                    <title>GitHub</title>
                    <path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/>
                  </svg>
                </a>
              </div>
              <div class="hover-icon">
                <a target="_blank" href="https://linkedin.com/in/emraftis">
                  <svg height="50" width="50" xmlns="http://www.w3.org/2000/svg" role="img" viewBox="0 0 24 24">
                    <title>LinkedIn</title>
                    <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                  </svg>
                </a>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </div>
    <the-content></the-content>
  </div>
</template>

<script>
import TheContent from './components/Content.vue';
export default {
  components: {
    TheContent,
  },
  data() {
    return {
      navIsActive: false,
    }
  },
  methods: {
    toggleNavActive() {
      return this.navIsActive = !this.navIsActive;
    },
    closeOverlay() {
      this.navIsActive = false;
    }
  },
}
</script>

<style scoped>
/* CSS Reset */
html {
  scroll-behavior: smooth;
}
* {
  margin: 0;
  padding: 0;
  border: 0;
  outline: 0;
  font-size: 100%;
  vertical-align: baseline;
  background: transparent;
  font-family: 'Ubuntu', sans-serif;
  font-weight: 300;
}
ul {
  list-style: none;
}

/* Nav Bar link hovers */
a, #logo {
  text-decoration: none;
  color: white;
  font-size: 1.6rem;
}
a:hover {
  text-decoration: underline rgb(72, 166, 255);
}

/* Nav overlay */
.svg-icon-list {
  display: flex;
  margin-left: -2rem;
}
.nav-links {
  position: fixed;
  left: 75%;
  top: 25%;
}
.hover-icon {
  cursor: pointer;
  margin-left: 2rem;
}
.hover-icon:hover {
  box-shadow: 0 -0.5rem 0.1rem rgb(72, 166, 255);
  border-radius: 1.2rem;
  transform: translateY(-4px);
  transition: transform 0.2s ease-in-out;
}
.overlay ul,
.overlay-active ul {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
.overlay li,
.overlay-active li {
  padding: 1.5rem;
}

/* Nav Bar */
.burger {
  margin-top: 0rem;
  cursor: pointer;
}
.burger:hover {
  transform: scale(1.25);
  transition: 0.25s;
}
.burger-container {
  margin: 0 4rem 0 auto;
}
.burger div {
  width: 1.5rem;
  height: 2px;
  background-color: white;
  margin: 5px;
}
.mobile-nav {
  display: flex;
  align-items: center;
  width: 100%;
  padding: 1rem 2rem;
  background-color: rgba(15, 10, 22, 0.945);
  position: fixed;
  z-index: 999;
}
.overlay {
  position: fixed;
  bottom: 0rem;
  left: 0%;
  background-color: rgba(94, 94, 94, 0.98);
  height: 100vh;
  width: 100%;
  transform: translateX(-100%);
  transition: transform 0.25s ease-in-out;
  z-index: 100;
}
.overlay-active {
  position: fixed;
  bottom: 0rem;
  left: 0%;
  background-color: rgba(94, 94, 94, 0.98);
  height: 100vh;
  width: 100%;
  transform: translateX(0%);
  transition: transform 0.25s ease-in-out;
  z-index: 100;
}


@media screen and (max-width: 899px) {
  .nav-links {
    display: absolute;
    left: 5%;
  }
  .link a {
    font-size: 1.75rem;
  }
}

@media screen and (min-width: 900px) {
  .overlay-active {
    transform: translateX(-50%);
  }
  .link a {
    font-size: 2rem;
  }
}

@media screen and (min-width: 1300px) {
  .svg-icon-list {
    margin-left: -2rem;
  }
  .link a {
    font-size: 3rem;
  }
}
</style>