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
          <li><div class="svg-icon-list">
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

          <div class="hover-icon">
            <a target="_blank" href="https://instagram.com/emraftis">
              <svg height="50" width="50" xmlns="http://www.w3.org/2000/svg" role="img" viewBox="0 0 24 24">
                <title>Instagram</title>
                <path d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913.306.788.717 1.459 1.384 2.126.667.666 1.336 1.079 2.126 1.384.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558.788-.306 1.459-.718 2.126-1.384.666-.667 1.079-1.335 1.384-2.126.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913-.306-.789-.718-1.459-1.384-2.126C21.319 1.347 20.651.935 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227-.224.562-.479.96-.899 1.382-.419.419-.824.679-1.38.896-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421-.569-.224-.96-.479-1.379-.899-.421-.419-.69-.824-.9-1.38-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678c-3.405 0-6.162 2.76-6.162 6.162 0 3.405 2.76 6.162 6.162 6.162 3.405 0 6.162-2.76 6.162-6.162 0-3.405-2.76-6.162-6.162-6.162zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405c0 .795-.646 1.44-1.44 1.44-.795 0-1.44-.646-1.44-1.44 0-.794.646-1.439 1.44-1.439.793-.001 1.44.645 1.44 1.439z"/>
              </svg>
            </a>
          </div>
          <div class="hover-icon">
            <a href="https://drive.google.com/uc?id=1iie0UHXChDesYNLIPxzR_27k8FgPz23t&export=download">
              <svg height="50" width="50" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" id="Layer_1" x="0px" y="0px" viewBox="0 0 299.998 299.998" style="enable-background:new 0 0 299.998 299.998;" xml:space="preserve">
                <title>Resume</title>
                <g>
                  <g>
                    <path d="M149.995,0.001C67.156,0.001,0,67.16,0,149.999s67.156,149.997,149.995,149.997s150.003-67.161,150.003-149.997    C299.997,67.157,232.834,0.001,149.995,0.001z M217.205,217.204c0,10.066-8.159,18.225-18.223,18.225h-97.967    c-10.068,0-18.225-8.159-18.225-18.225V82.79c0-10.066,8.159-18.225,18.225-18.225h76.892v36.45h39.298V217.204z M185.688,93.232    V64.563l31.517,28.669H185.688z"/>
                  </g>
                </g>
              </svg>
            </a>
          </div>
        </div></li>
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
    getView() {
      this.mobile = window.innerWidth <= 990;
    },
    closeOverlay() {
      this.navIsActive = false;
    }
  },
  created() {
    this.getView();
  }
}
</script>

<style scoped>
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
a, #logo {
  text-decoration: none;
  color: white;
  font-size: 1.6rem;
}
a:hover {
  text-decoration: underline rgb(72, 166, 255);
}

.svg-icon-list {
  position: fixed;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
}
.nav-links {
  color: black;
  position: fixed;
  left: 75%;
  top: 25%;
}

.link a {
  font-size: 3rem;
}

.hover-icon {
  cursor: pointer;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-left: 2rem;
}
.hover-icon svg {
  display: flex;
  justify-content: center;
  align-items: center;
}
.hover-icon:hover {
  box-shadow: 0 -0.5rem 0.1rem rgb(72, 166, 255);
  border-radius: 1.2rem;
  transform: translateY(-4px);
  transition: transform 0.2s ease-in-out;
}

.overlay ul,
.overlay-active ul {
  color: black;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-top: 5%;
}

.overlay li,
.overlay-active li {
  padding: 1.5rem;
  color: black;
}

.nav-bar {
  display: flex;
  width: 100%;
}
.nav-active {
  height: 100vh;
  display: fixed;
}
.burger {
  margin-top: 0rem;
  cursor: pointer;
}
.burger-container {
  margin-left: auto;
  margin-right: 4rem;
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
  padding-left: 2rem;
  background-color: rgba(15, 10, 22, 0.945);
  padding-top: 1rem;
  padding-bottom: 1rem;
  position: fixed;
  z-index: 999;
}



@media screen and (max-width: 899px) {
  .svg-icon-list {
    position: absolute;
    left: 0;
  }
  .overlay {
    position: fixed;
    bottom: 0rem;
    left: 0%;
    background-color: rgba(48, 48, 48, 0.95);
    height: 100vh;
    width: 100%;
    transform: translateX(-100%);
    transition: transform 0.25s ease-in-out;
    z-index: 100;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    color: black;
    justify-content: center;
    z-index: 5;
  }
  .overlay-active {
    position: fixed;
    bottom: 0rem;
    left: 0%;
    background-color: rgba(48, 48, 48, 0.95);
    height: 100vh;
    width: 100%;
    transform: translateX(0%);
    transition: transform 0.25s ease-in-out;
    z-index: 100;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    color: black;
    justify-content: center;
    z-index: 5;
  }
  .nav-links {
    display: absolute;
    left: 5%;
  }
  .link a {
    font-size: 1.75rem;
  }
}

@media screen and (min-width: 900px) {
  .svg-icon-list {
    position: absolute;
    left: -60%;
  }
  .overlay {
    position: fixed;
    bottom: 0rem;
    left: 0%;
    background-color: rgba(48, 48, 48, 0.95);
    height: 100vh;
    width: 100%;
    transform: translateX(-100%);
    transition: transform 0.25s ease-in-out;
    z-index: 100;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    color: black;
    justify-content: center;
    z-index: 5;
  }
  .overlay-active {
    position: fixed;
    bottom: 0rem;
    left: 0%;
    background-color: rgba(48, 48, 48, 0.95);
    height: 100vh;
    width: 100%;
    transform: translateX(-50%);
    transition: transform 0.25s ease-in-out;
    z-index: 100;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    color: black;
    justify-content: center;
    z-index: 5;
  }
  .link a {
    font-size: 1.75rem;
  }
}


@media screen and (min-width: 1200px) {
  .svg-icon-list {
    position: absolute;
  }
  .overlay {
    position: fixed;
    bottom: 0rem;
    left: 0%;
    background-color: rgba(48, 48, 48, 0.95);
    height: 100vh;
    width: 100%;
    transform: translateX(-100%);
    transition: transform 0.25s ease-in-out;
    z-index: 100;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    color: black;
    justify-content: center;
    z-index: 5;
  }
  .overlay-active {
    position: fixed;
    bottom: 0rem;
    left: 0%;
    background-color: rgba(48, 48, 48, 0.95);
    height: 100vh;
    width: 100%;
    transform: translateX(-50%);
    transition: transform 0.25s ease-in-out;
    z-index: 100;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    color: black;
    justify-content: center;
    z-index: 5;
  }
  .link a {
    font-size: 2rem;
  }
}


@media screen and (min-width: 1400px) {
  .svg-icon-list {
    position: absolute;
    left: -10%;
  }
  .overlay {
    position: fixed;
    bottom: 0rem;
    left: 0%;
    background-color: rgba(48, 48, 48, 0.95);
    height: 100vh;
    width: 100%;
    transform: translateX(-100%);
    transition: transform 0.25s ease-in-out;
    z-index: 100;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    color: black;
    justify-content: center;
    z-index: 5;
  }
  .overlay-active {
    position: fixed;
    bottom: 0rem;
    left: 0%;
    background-color: rgba(48, 48, 48, 0.95);
    height: 100vh;
    width: 100%;
    transform: translateX(-50%);
    transition: transform 0.25s ease-in-out;
    z-index: 100;
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    color: black;
    justify-content: center;
    z-index: 5;
  }
  .link a {
    font-size: 3rem;
  }
  
}
</style>