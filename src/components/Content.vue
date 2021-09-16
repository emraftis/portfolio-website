<template>
  <div class="workspace">
    <div class="landing-page" id="landing-page">
      <div class="intro-text">
        <h2 class="main-intro-text">
          HI, I'M <span id="my-name-capital">E</span
          ><span id="my-name-lower">VAN</span>
          <span id="my-name-capital">R</span
          ><span id="my-name-lower">AFTIS</span>.
        </h2>
        <p class="base-intro-text">
          - a
          <span class="special-base-text">Finance & Tech Professional</span>
          looking for opportunities in
          <span class="special-base-text">Fintech</span> and
          <span class="special-base-text">Web Development!</span>
        </p>
        <div class="landing-buttons">
          <a
            class="landing-button"
            id="button1"
            href="https://drive.google.com/uc?id=1YjKZkQDb6Xe_gkZ4gvlISIZ5uMa9sWBF&export=download"
            >My Resume</a
          >
          <a class="landing-button" id="button2" href="#projects-page"
            >My Projects</a
          >
          <a
            href="mailto:raftisevan@gmail.com"
            id="button3"
            class="landing-button"
            >Let's Chat</a
          >
        </div>
      </div>
    </div>

    <div class="page-container" id="about-page">
      <h2 class="container-header">About Me</h2>

      <div class="page-content">
        <div class="profile-photo-container">
          <img
            id="profile-pic"
            src="../assets/evanProfile.jpg"
            alt="Photo of Evan"
          />
        </div>
        <ul>
          <li class="about-me-text">
            I'm a full-stack web developer - solving problems with
            <span id="skills">NodeJS, Express, VueJS, MongoDB & More!</span> I
            consider myself a lifelong learner and I'm motivated to take on a
            new challenge after 10 successful years in Commercial Finance. I
            have a passion for travel and I love to create things!
          </li>
        </ul>
      </div>
    </div>

    <div class="page-container" id="projects-page">
      <h2 class="container-header">My Projects</h2>
      <div class="project-container">
        <ul>
          <li>
            <div class="project-card" id="project-one">
              <div class="project-card-contents">
                <img
                  class="project-img"
                  id="project-one-img"
                  src="../assets/Project1Screen.jpg"
                  alt="Project Screenshot"
                />

                <div class="img-overlay" onclick>
                  <div class="overlay-title">Real Estate NOI & Valuation</div>
                  <p class="project-description">
                    CRUD Application with User Authentication (Demo Included)
                    using Google's Firebase. Calculator for NOI (Cash Flows) for
                    commercial real estate and to estimate market value.
                  </p>
                  <p class="project-description">
                    Technologies used include Firebase, VueJS, HTML, and CSS.
                  </p>
                  <div class="button-container">
                    <a
                      class="live-button"
                      target="_blank"
                      href="https://real-estate-project-14317.web.app/"
                      >Live Site</a
                    >
                    <a
                      class="github-button"
                      target="_blank"
                      href="https://github.com/emraftis/real-estate-project"
                      >GitHub</a
                    >
                  </div>
                </div>
                <div id="project-one-details">
                  <div class="project-icons">
                    <svg
                      height="40"
                      width="40"
                      xmlns="http://www.w3.org/2000/svg"
                      xmlns:xlink="http://www.w3.org/1999/xlink"
                      version="1.1"
                      id="Layer_1"
                      x="0px"
                      y="0px"
                      viewBox="0 0 95.39 131.07"
                      style="enable-background:new 0 0 95.39 131.07"
                      xml:space="preserve"
                    >
                      <title>Firebase</title>
                      <path
                        class="st0-firebase"
                        d="M0.05,105.75L16.18,2.52c0.2-1.27,1.18-2.26,2.44-2.48s2.52,0.4,3.13,1.53l16.68,31.12l6.65-12.66 c0.51-0.98,1.53-1.59,2.64-1.59s2.12,0.61,2.64,1.59l45.02,85.72L0.05,105.75L0.05,105.75z"
                      />
                      <path
                        class="st1-firebase"
                        d="M55.78,65.54L38.43,32.68L0.05,105.75L55.78,65.54z"
                      />
                      <path
                        class="st2-firebase"
                        d="M95.39,105.75L83.03,29.29c-0.19-1.1-0.97-2-2.03-2.34s-2.22-0.06-3.01,0.73L0.05,105.75l43.12,24.18 c2.71,1.51,6.01,1.51,8.71,0L95.39,105.75L95.39,105.75z"
                      />
                      <path
                        class="st3-firebase"
                        d="M83.03,29.29c-0.19-1.1-0.97-2-2.03-2.34s-2.22-0.06-3.01,0.73L62.52,43.19L50.36,20.03 c-0.51-0.98-1.53-1.59-2.64-1.59s-2.12,0.61-2.64,1.59l-6.65,12.66L21.75,1.57c-0.6-1.13-1.87-1.75-3.13-1.53s-2.25,1.22-2.44,2.48 L0.05,105.75H0l0.05,0.06l0.42,0.21l77.49-77.58c0.79-0.79,1.95-1.08,3.02-0.74s1.85,1.24,2.03,2.35l12.25,75.77l0.12-0.07 L83.03,29.29L83.03,29.29z M0.19,105.61L16.18,3.26c0.19-1.27,1.18-2.27,2.44-2.48s2.52,0.4,3.13,1.53l16.68,31.12l6.65-12.66 c0.51-0.98,1.53-1.59,2.64-1.59s2.12,0.61,2.64,1.59l11.92,22.66L0.19,105.61L0.19,105.61z"
                      />
                      <path
                        class="st4-firebase"
                        d="M51.89,129.2c-2.71,1.51-6.01,1.51-8.71,0L0.16,105.09l-0.1,0.66l43.12,24.18c2.71,1.51,6.01,1.51,8.71,0 l43.5-24.18l-0.11-0.69L51.89,129.2L51.89,129.2z"
                      />
                      <g>
                        <linearGradient
                          id="b_1_"
                          gradientUnits="userSpaceOnUse"
                          x1="-243.4794"
                          y1="345.2798"
                          x2="-242.4362"
                          y2="344.521"
                          gradientTransform="matrix(95 0 0 -130.9998 23127.4414 45253.9336)"
                        >
                          <stop
                            offset="0"
                            style="stop-color:#FFFFFF;stop-opacity:0.1"
                          />
                          <stop
                            offset="0.14"
                            style="stop-color:#FFFFFF;stop-opacity:0.08"
                          />
                          <stop
                            offset="0.61"
                            style="stop-color:#FFFFFF;stop-opacity:0.02"
                          />
                          <stop
                            offset="1"
                            style="stop-color:#FFFFFF;stop-opacity:0"
                          />
                        </linearGradient>
                        <path
                          id="b"
                          class="st5-firebase"
                          d="M82.91,29.3c-0.19-1.1-0.97-2-2.02-2.34c-1.06-0.34-2.21-0.06-3,0.73L62.47,43.2L50.35,20.05 c-0.51-0.98-1.53-1.59-2.63-1.59s-2.11,0.61-2.63,1.59l-6.63,12.66L21.84,1.6c-0.6-1.13-1.86-1.75-3.12-1.53s-2.24,1.22-2.43,2.48 L0.22,105.73l42.97,24.17c2.7,1.51,5.99,1.51,8.68,0l43.34-24.17L82.91,29.3L82.91,29.3z"
                        />
                      </g>
                    </svg>
                    <svg
                      height="40"
                      width="40"
                      xmlns="http://www.w3.org/2000/svg"
                      xmlns:xlink="http://www.w3.org/1999/xlink"
                      version="1.1"
                      id="Layer_1"
                      x="0px"
                      y="0px"
                      viewBox="0 0 122.88 106.42"
                      style="enable-background:new 0 0 122.88 106.42"
                      xml:space="preserve"
                    >
                      <title>VueJS</title>
                      <g>
                        <polygon
                          class="st0-vue"
                          points="75.63,0 61.44,24.58 47.25,0 0,0 61.44,106.42 122.88,0 75.63,0"
                        />
                        <polygon
                          class="st1-vue"
                          points="75.63,0 61.44,24.58 47.25,0 24.58,0 61.44,63.85 98.3,0 75.63,0"
                        />
                      </g>
                    </svg>
                    <svg
                      height="40"
                      width="40"
                      xmlns="http://www.w3.org/2000/svg"
                      xmlns:xlink="http://www.w3.org/1999/xlink"
                      version="1.1"
                      id="Layer_1"
                      x="0px"
                      y="0px"
                      viewBox="0 0 108.35 122.88"
                      style="enable-background:new 0 0 108.35 122.88"
                      xml:space="preserve"
                    >
                      <title>HTML5</title>
                      <g>
                        <polygon
                          class="st0-html"
                          points="108.35,0 98.48,110.58 54.11,122.88 9.86,110.6 0,0 108.35,0"
                        />
                        <polygon
                          class="st1-html"
                          points="54.17,113.48 90.03,103.54 98.46,9.04 54.17,9.04 54.17,113.48"
                        />
                        <path
                          class="st2-html"
                          d="M34.99,36.17h19.19V22.61H20.16l0.32,3.64l3.33,37.38h30.35V50.06H36.23L34.99,36.17L34.99,36.17L34.99,36.17z M38.04,70.41H24.43l1.9,21.3l27.79,7.71l0.06-0.02V85.29l-0.06,0.02l-15.11-4.08L38.04,70.41L38.04,70.41L38.04,70.41z"
                        />
                        <path
                          class="st3-html"
                          d="M54.13,63.63h16.7l-1.57,17.59L54.13,85.3v14.11l27.81-7.71l0.2-2.29l3.19-35.71l0.33-3.64H54.13V63.63 L54.13,63.63z M54.13,36.14v0.03h32.76l0.27-3.05l0.62-6.88l0.32-3.64H54.13V36.14L54.13,36.14L54.13,36.14z"
                        />
                      </g>
                    </svg>
                    <svg
                      height="40"
                      width="40"
                      xmlns="http://www.w3.org/2000/svg"
                      xmlns:xlink="http://www.w3.org/1999/xlink"
                      viewBox="0 0 296297 333333"
                      shape-rendering="geometricPrecision"
                      text-rendering="geometricPrecision"
                      image-rendering="optimizeQuality"
                      fill-rule="evenodd"
                      clip-rule="evenodd"
                    >
                      <defs>
                        <linearGradient
                          id="id4"
                          gradientUnits="userSpaceOnUse"
                          x1="54128.7"
                          y1="79355.5"
                          x2="240318"
                          y2="79355.5"
                        >
                          <stop offset="0" stop-color="#e8e7e5" />
                          <stop offset="1" stop-color="#fff" />
                        </linearGradient>
                        <linearGradient
                          id="id5"
                          gradientUnits="userSpaceOnUse"
                          x1="62019.3"
                          y1="202868"
                          x2="233515"
                          y2="202868"
                        >
                          <stop offset="0" stop-color="#e8e7e5" />
                          <stop offset="1" stop-color="#fff" />
                        </linearGradient>
                        <linearGradient
                          id="id6"
                          gradientUnits="userSpaceOnUse"
                          x1="104963"
                          y1="99616.9"
                          x2="104963"
                          y2="171021"
                        >
                          <stop offset="0" stop-color="#d1d3d4" />
                          <stop offset=".388" stop-color="#d1d3d4" />
                          <stop offset="1" stop-color="#d1d3d4" />
                        </linearGradient>
                        <linearGradient
                          id="id7"
                          gradientUnits="userSpaceOnUse"
                          xlink:href="#id6"
                          x1="194179"
                          y1="61185.8"
                          x2="194179"
                          y2="135407"
                        />
                        <mask id="id0">
                          <linearGradient
                            id="id1"
                            gradientUnits="userSpaceOnUse"
                            x1="104963"
                            y1="99616.9"
                            x2="104963"
                            y2="171021"
                          >
                            <stop
                              offset="0"
                              stop-opacity="0"
                              stop-color="#fff"
                            />
                            <stop offset=".388" stop-color="#fff" />
                            <stop
                              offset="1"
                              stop-opacity=".831"
                              stop-color="#fff"
                            />
                          </linearGradient>
                          <path
                            fill="url(#id1)"
                            d="M61737 99467h86453v71704H61737z"
                          />
                        </mask>
                        <mask id="id2">
                          <linearGradient
                            id="id3"
                            gradientUnits="userSpaceOnUse"
                            x1="194179"
                            y1="61185.8"
                            x2="194179"
                            y2="135407"
                          >
                            <stop
                              offset="0"
                              stop-opacity="0"
                              stop-color="#fff"
                            />
                            <stop offset=".388" stop-color="#fff" />
                            <stop
                              offset="1"
                              stop-opacity=".831"
                              stop-color="#fff"
                            />
                          </linearGradient>
                          <path
                            fill="url(#id3)"
                            d="M147890 61036h92578v74521h-92578z"
                          />
                        </mask>
                      </defs>
                      <g id="Layer_x0020_1">
                        <g id="_513085304">
                          <path
                            fill="#2062af"
                            d="M268517 300922l-120369 32411-120371-32411L0 0h296297z"
                          />
                          <path
                            fill="#3c9cd7"
                            d="M148146 24374v283109l273 74 97409-26229 22485-256954z"
                          />
                          <path
                            fill="#fff"
                            d="M148040 99617l-86153 35880 2857 35524 83296-35614 88604-37883 3674-36339-92278 38432z"
                          />
                          <path
                            mask="url(#id0)"
                            fill="url(#id6)"
                            d="M61887 135497l2857 35524 83295-35614V99617z"
                          />
                          <path
                            mask="url(#id2)"
                            fill="url(#id7)"
                            d="M240318 61186l-92278 38431v35790l88604-37883z"
                          />
                          <path
                            fill="url(#id5)"
                            d="M62019 135497l2858 35524 127806 407-2859 47365-42055 11840-40428-10208-2450-29399H67327l4900 56756 75950 22457 75538-22050 9800-112692z"
                          />
                          <path
                            class="fil6"
                            d="M148040 135497H61888l2857 35524 83295 266v-35790zm0 95022l-408 114-40422-10208-2450-29399H67197l4899 56756 75944 22457v-39720z"
                          />
                          <path
                            fill="url(#id4)"
                            d="M54129 61186h186189l-3674 36339H58620l-4491-36339z"
                          />
                          <path
                            class="fil6"
                            d="M148040 61186H54129l4491 36339h89420z"
                          />
                        </g>
                      </g>
                    </svg>
                  </div>
                </div>
              </div>
            </div>
          </li>

          <li>
            <div class="project-card" id="project-two">
              <div class="project-card-contents">
                <img
                  class="project-img"
                  id="project-two-img"
                  src="../assets/Project3Screen.jpg"
                  alt="Project Screenshot"
                />
                <div class="img-overlay" onclick>
                  <div class="overlay-title">Ethereum Gas Tracker</div>
                  <p class="project-description">
                    Simple application to track Ethereum Gas Fees paid by an
                    Ethereum Wallet address. This project was created to help
                    with personal taxes relating to Cryptocurrency.
                  </p>
                  <p class="project-description">
                    Technologies used include Express, NodeJS, VueJS, APIs from
                    Coinbase and Etherscan.
                  </p>
                  <div class="button-container">
                    <a
                      class="live-button"
                      target="_blank"
                      href="https://blockchain-project-gastax.herokuapp.com/"
                      >Live Site</a
                    >
                    <a
                      class="github-button"
                      target="_blank"
                      href="https://github.com/emraftis/blockchain-project-backend"
                      >GitHub</a
                    >
                  </div>
                </div>
                <div id="project-two-details">
                  <div class="project-icons">
                    <svg
                      height="40"
                      width="40"
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 1333.33 773.55"
                      shape-rendering="geometricPrecision"
                      text-rendering="geometricPrecision"
                      image-rendering="optimizeQuality"
                      fill-rule="evenodd"
                      clip-rule="evenodd"
                    >
                      <title>Express</title>
                      <path
                        d="M1333.33 753.49c-48.5 12.33-78.5.54-105.41-39.87L1036.5 448.79l-27.67-36.67L785.29 714.5c-25.54 36.38-52.33 52.2-100 39.33l286.25-384.25-266.5-347.09c45.83-8.91 77.5-4.38 105.62 36.67l198.54 268.13 200-266.67c25.62-36.38 53.17-50.2 99.17-36.8l-103.33 137-140 182.29c-16.67 20.83-14.38 35.09.96 55.2l267.33 355.18zM.34 363.16l23.41-115.17c63.75-227.92 325-322.63 505.17-181.8 105.29 82.83 131.46 200 126.25 331.25H61.67C52.76 633.69 222.8 776.27 439.58 703.53c76.04-25.54 120.83-85.09 143.25-159.58 11.38-37.33 30.2-43.17 65.29-32.5-17.91 93.17-58.33 171-143.75 219.71-127.62 72.91-309.8 49.33-405.62-52C41.66 620.36 18.08 545.87 7.5 466.2c-1.67-13.17-5-25.71-7.5-38.33.22-21.56.34-43.11.34-64.67v-.04zm62.41-15.83h536.33c-3.5-170.83-109.87-292.17-255.25-293.2-159.58-1.25-274.17 117.2-281.09 293.2h.01z"
                        fill-rule="nonzero"
                      />
                    </svg>
                    <svg
                      height="40"
                      width="40"
                      xmlns="http://www.w3.org/2000/svg"
                      id="Layer_1"
                      data-name="Layer 1"
                      viewBox="0 0 109 122.88"
                    >
                      <title>NodeJS</title>
                      <path
                        class="cls-1"
                        d="M68.43,87.08c-19.7,0-23.83-9-23.83-16.63a1.3,1.3,0,0,1,1.3-1.3h5.82A1.3,1.3,0,0,1,53,70.25c.88,5.93,3.49,8.92,15.41,8.92C77.9,79.17,81.93,77,81.93,72c0-2.9-1.15-5-15.89-6.49-12.33-1.22-20-3.93-20-13.8,0-9.08,7.66-14.49,20.5-14.49,14.42,0,21.56,5,22.46,15.76a1.31,1.31,0,0,1-.35,1,1.35,1.35,0,0,1-1,.42H81.9a1.29,1.29,0,0,1-1.26-1c-1.41-6.23-4.81-8.23-14.07-8.23C56.21,45.15,55,48.76,55,51.46c0,3.28,1.42,4.24,15.4,6.09S90.82,62,90.82,71.71,82.64,87.14,68.37,87.14l.06-.06Zm-13.91,35.8a9.45,9.45,0,0,1-4.72-1.26l-15-8.9c-2.25-1.26-1.15-1.7-.41-2a30.38,30.38,0,0,0,6.8-3.1,1.15,1.15,0,0,1,1.12.08l11.55,6.85a1.51,1.51,0,0,0,1.4,0l45-26a1.42,1.42,0,0,0,.69-1.22V35.43a1.44,1.44,0,0,0-.7-1.24l-45-26a1.38,1.38,0,0,0-1.39,0l-45,26a1.42,1.42,0,0,0-.71,1.23v52a1.39,1.39,0,0,0,.7,1.21l12.33,7.12C27.85,99.06,32,95.11,32,91.15V39.86a1.29,1.29,0,0,1,1.31-1.3H39a1.29,1.29,0,0,1,1.3,1.3V91.17c0,8.93-4.87,14-13.33,14-2.6,0-4.66,0-10.38-2.82L4.72,95.59A9.51,9.51,0,0,1,0,87.38v-52a9.47,9.47,0,0,1,4.72-8.21l45.07-26a9.89,9.89,0,0,1,9.47,0l45,26A9.49,9.49,0,0,1,109,35.43v52a9.54,9.54,0,0,1-4.72,8.21l-45,26a9.5,9.5,0,0,1-4.74,1.26v0Zm0,0Z"
                      />
                    </svg>
                    <svg
                      height="40"
                      width="40"
                      xmlns="http://www.w3.org/2000/svg"
                      xmlns:xlink="http://www.w3.org/1999/xlink"
                      version="1.1"
                      id="Layer_1"
                      x="0px"
                      y="0px"
                      viewBox="0 0 122.88 106.42"
                      style="enable-background:new 0 0 122.88 106.42"
                      xml:space="preserve"
                    >
                      <title>VueJS</title>
                      <g>
                        <polygon
                          class="st0-vue"
                          points="75.63,0 61.44,24.58 47.25,0 0,0 61.44,106.42 122.88,0 75.63,0"
                        />
                        <polygon
                          class="st1-vue"
                          points="75.63,0 61.44,24.58 47.25,0 24.58,0 61.44,63.85 98.3,0 75.63,0"
                        />
                      </g>
                    </svg>
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      xmlns:xlink="http://www.w3.org/1999/xlink"
                      xmlns:xodm="http://www.corel.com/coreldraw/odm/2003"
                      xml:space="preserve"
                      width="40"
                      height="40"
                      version="1.1"
                      shape-rendering="geometricPrecision"
                      text-rendering="geometricPrecision"
                      image-rendering="optimizeQuality"
                      fill-rule="evenodd"
                      clip-rule="evenodd"
                      viewBox="0 0 784.37 1277.39"
                    >
                      <g id="Layer_x0020_1">
                        <metadata id="CorelCorpID_0Corel-Layer" />
                        <g id="_1421394342400">
                          <g>
                            <polygon
                              fill="#343434"
                              fill-rule="nonzero"
                              points="392.07,0 383.5,29.11 383.5,873.74 392.07,882.29 784.13,650.54 "
                            />
                            <polygon
                              fill="#8C8C8C"
                              fill-rule="nonzero"
                              points="392.07,0 -0,650.54 392.07,882.29 392.07,472.33 "
                            />
                            <polygon
                              fill="#3C3C3B"
                              fill-rule="nonzero"
                              points="392.07,956.52 387.24,962.41 387.24,1263.28 392.07,1277.38 784.37,724.89 "
                            />
                            <polygon
                              fill="#8C8C8C"
                              fill-rule="nonzero"
                              points="392.07,1277.38 392.07,956.52 -0,724.89 "
                            />
                            <polygon
                              fill="#141414"
                              fill-rule="nonzero"
                              points="392.07,882.29 784.13,650.54 392.07,472.33 "
                            />
                            <polygon
                              fill="#393939"
                              fill-rule="nonzero"
                              points="0,650.54 392.07,882.29 392.07,472.33 "
                            />
                          </g>
                        </g>
                      </g>
                    </svg>
                  </div>
                </div>
              </div>
            </div>
          </li>

          <li>
            <div class="project-card" id="project-three">
              <div class="project-card-contents" id="reverse-column">
                <div id="project-three-details">
                  <div class="project-icons">
                    <svg
                      height="40"
                      width="40"
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 598.88 1333.33"
                      shape-rendering="geometricPrecision"
                      text-rendering="geometricPrecision"
                      image-rendering="optimizeQuality"
                      fill-rule="evenodd"
                      clip-rule="evenodd"
                    >
                      <title>MongoDB</title>
                      <g fill-rule="nonzero">
                        <path
                          d="M295.27 3.65l35.58 66.83c8 12.33 16.67 23.25 26.87 33.42 29.79 29.79 58.08 60.99 83.5 94.41 60.28 79.16 100.95 167.07 129.98 262.14 17.42 58.08 26.87 117.66 27.58 177.9 2.91 180.11-58.83 334.76-183.31 463.28-20.33 20.33-42.08 39.16-65.41 55.91-12.33 0-18.17-9.46-23.25-18.16-9.45-15.96-15.25-34.17-18.16-52.29-4.38-21.8-7.25-43.58-5.83-66.08v-10.16c-1-2.17-11.87-1002.07-7.54-1007.19v.01z"
                          fill="#599636"
                        />
                        <path
                          d="M295.27 1.43c-1.46-2.91-2.91-.71-4.38.71.71 14.58-4.38 27.58-12.33 40-8.75 12.33-20.33 21.8-31.96 31.96-64.57 55.91-115.4 123.45-156.11 198.98C36.33 374.74 8.41 483.68.5 598.38c-3.62 41.37 13.09 187.36 26.13 229.48 35.58 111.82 99.49 205.52 182.27 286.84 20.33 19.58 42.08 37.74 64.58 55.2 6.54 0 7.25-5.83 8.74-10.17 2.85-9.28 5.06-18.76 6.54-28.34l14.58-108.9L295.26 1.43z"
                          fill="#6cac48"
                        />
                        <path
                          d="M330.85 1201.77c1.46-16.67 9.46-30.5 18.17-44.29-8.75-3.62-15.25-10.83-20.33-18.87-4.38-7.25-8-15.96-10.83-23.96-10.17-30.5-12.33-62.5-15.25-93.66v-18.87c-3.62 2.91-4.38 27.58-4.38 31.25-2.03 32.85-6.54 65.8-13.08 98.05-2.17 13.08-3.62 26.12-11.67 37.74 0 1.46 0 2.91.71 5.09 13.08 38.5 16.67 77.7 18.87 117.66v14.58c0 17.41-.71 13.74 13.75 19.58 5.83 2.17 12.33 2.91 18.16 7.25 4.38 0 5.09-3.62 5.09-6.54l-2.17-23.96v-66.83c-.71-11.67 1.46-23.25 2.91-34.16l.05-.06z"
                          fill="#c2bfbf"
                        />
                      </g>
                    </svg>
                    <svg
                      height="40"
                      width="40"
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 1333.33 773.55"
                      shape-rendering="geometricPrecision"
                      text-rendering="geometricPrecision"
                      image-rendering="optimizeQuality"
                      fill-rule="evenodd"
                      clip-rule="evenodd"
                    >
                      <title>Express</title>
                      <path
                        d="M1333.33 753.49c-48.5 12.33-78.5.54-105.41-39.87L1036.5 448.79l-27.67-36.67L785.29 714.5c-25.54 36.38-52.33 52.2-100 39.33l286.25-384.25-266.5-347.09c45.83-8.91 77.5-4.38 105.62 36.67l198.54 268.13 200-266.67c25.62-36.38 53.17-50.2 99.17-36.8l-103.33 137-140 182.29c-16.67 20.83-14.38 35.09.96 55.2l267.33 355.18zM.34 363.16l23.41-115.17c63.75-227.92 325-322.63 505.17-181.8 105.29 82.83 131.46 200 126.25 331.25H61.67C52.76 633.69 222.8 776.27 439.58 703.53c76.04-25.54 120.83-85.09 143.25-159.58 11.38-37.33 30.2-43.17 65.29-32.5-17.91 93.17-58.33 171-143.75 219.71-127.62 72.91-309.8 49.33-405.62-52C41.66 620.36 18.08 545.87 7.5 466.2c-1.67-13.17-5-25.71-7.5-38.33.22-21.56.34-43.11.34-64.67v-.04zm62.41-15.83h536.33c-3.5-170.83-109.87-292.17-255.25-293.2-159.58-1.25-274.17 117.2-281.09 293.2h.01z"
                        fill-rule="nonzero"
                      />
                    </svg>
                    <svg
                      height="40"
                      width="40"
                      xmlns="http://www.w3.org/2000/svg"
                      id="Layer_1"
                      data-name="Layer 1"
                      viewBox="0 0 109 122.88"
                    >
                      <title>NodeJS</title>
                      <path
                        class="cls-1"
                        d="M68.43,87.08c-19.7,0-23.83-9-23.83-16.63a1.3,1.3,0,0,1,1.3-1.3h5.82A1.3,1.3,0,0,1,53,70.25c.88,5.93,3.49,8.92,15.41,8.92C77.9,79.17,81.93,77,81.93,72c0-2.9-1.15-5-15.89-6.49-12.33-1.22-20-3.93-20-13.8,0-9.08,7.66-14.49,20.5-14.49,14.42,0,21.56,5,22.46,15.76a1.31,1.31,0,0,1-.35,1,1.35,1.35,0,0,1-1,.42H81.9a1.29,1.29,0,0,1-1.26-1c-1.41-6.23-4.81-8.23-14.07-8.23C56.21,45.15,55,48.76,55,51.46c0,3.28,1.42,4.24,15.4,6.09S90.82,62,90.82,71.71,82.64,87.14,68.37,87.14l.06-.06Zm-13.91,35.8a9.45,9.45,0,0,1-4.72-1.26l-15-8.9c-2.25-1.26-1.15-1.7-.41-2a30.38,30.38,0,0,0,6.8-3.1,1.15,1.15,0,0,1,1.12.08l11.55,6.85a1.51,1.51,0,0,0,1.4,0l45-26a1.42,1.42,0,0,0,.69-1.22V35.43a1.44,1.44,0,0,0-.7-1.24l-45-26a1.38,1.38,0,0,0-1.39,0l-45,26a1.42,1.42,0,0,0-.71,1.23v52a1.39,1.39,0,0,0,.7,1.21l12.33,7.12C27.85,99.06,32,95.11,32,91.15V39.86a1.29,1.29,0,0,1,1.31-1.3H39a1.29,1.29,0,0,1,1.3,1.3V91.17c0,8.93-4.87,14-13.33,14-2.6,0-4.66,0-10.38-2.82L4.72,95.59A9.51,9.51,0,0,1,0,87.38v-52a9.47,9.47,0,0,1,4.72-8.21l45.07-26a9.89,9.89,0,0,1,9.47,0l45,26A9.49,9.49,0,0,1,109,35.43v52a9.54,9.54,0,0,1-4.72,8.21l-45,26a9.5,9.5,0,0,1-4.74,1.26v0Zm0,0Z"
                      />
                    </svg>
                    <svg
                      height="40"
                      width="40"
                      xmlns="http://www.w3.org/2000/svg"
                      xmlns:xlink="http://www.w3.org/1999/xlink"
                      version="1.1"
                      id="Layer_1"
                      x="0px"
                      y="0px"
                      viewBox="0 0 122.88 106.42"
                      style="enable-background:new 0 0 122.88 106.42"
                      xml:space="preserve"
                    >
                      <title>VueJS</title>
                      <g>
                        <polygon
                          class="st0-vue"
                          points="75.63,0 61.44,24.58 47.25,0 0,0 61.44,106.42 122.88,0 75.63,0"
                        />
                        <polygon
                          class="st1-vue"
                          points="75.63,0 61.44,24.58 47.25,0 24.58,0 61.44,63.85 98.3,0 75.63,0"
                        />
                      </g>
                    </svg>
                  </div>
                </div>
                <img
                  class="project-img"
                  id="project-three-img"
                  src="../assets/Project2Screen.jpg"
                  alt="Project Screenshot"
                />
                <div class="img-overlay" onclick>
                  <h3 class="overlay-title">Data Sorting & Custom API</h3>
                  <p class="project-description">
                    Full stack data sorting using custom API end points on open
                    source data from LinkedIn & the World Bank. Database
                    includes 10,835 objects and was seeded from an Excel file.
                  </p>
                  <p class="project-description">
                    Technologies used include MongoDB, Express, NodeJS, VueJS,
                    HTML, and CSS.
                  </p>
                  <div class="button-container">
                    <a
                      class="live-button"
                      target="_blank"
                      href="https://ancient-stream-56814.herokuapp.com/"
                      >Live Site</a
                    >
                    <a
                      class="github-button"
                      target="_blank"
                      href="https://github.com/emraftis/linkedin-keywords"
                      >GitHub</a
                    >
                  </div>
                </div>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </div>

    <div class="page-container" id="contact-page">
      <div class="contact-content">
        <h2 class="container-header">Contact Me</h2>
        <p class="contact-text">
          Let's chat at
          <a id="email" href="mailto:raftisevan@gmail.com"
            >raftisevan@gmail.com</a
          >
        </p>
      </div>
      <div class="hand-container">
        <svg
          height="300"
          width="300"
          xmlns="http://www.w3.org/2000/svg"
          id="Capa_1"
          enable-background="new 0 0 503.848 503.848"
          viewBox="0 0 503.848 503.848"
        >
          <title>Let's Chat!</title>
          <g>
            <path
              d="m416.782 131.559h-34.051l-13.334 14.548c-2.738 2.988-7.719 1.05-7.719-3.003v-85.383c0-20.053 16.256-36.309 36.309-36.309h69.553c20.053 0 36.309 16.256 36.309 36.309v37.529c0 20.053-16.256 36.309-36.309 36.309h-18.796z"
              fill="#a6e7f0"
            />
            <g>
              <path
                d="m321.015 70.239c-5.174-5.185-12.326-8.38-20.217-8.38-15.794 0-28.586 12.804-28.586 28.598v-32.419c0-7.891-3.206-15.044-8.38-20.206-5.174-5.185-12.314-8.38-20.217-8.38-15.794 0-28.597 12.804-28.597 28.586v-26.187c0-7.891-3.195-15.044-8.369-20.217-5.312-5.312-12.71-8.539-20.852-8.362-15.639.339-27.962 13.52-27.962 29.163v33.255c0-7.891-3.195-15.032-8.38-20.217-5.162-5.162-12.314-8.369-20.206-8.369-15.794 0-28.598 12.804-28.598 28.586v109.717l-.072 31.79 26.281 88.877 7.522 141.032-3.608 63.477h161.32c4.808 0 8.706-3.898 8.706-8.706v-74.807l11.052-16.101c11.428-16.658 17.545-36.386 17.545-56.592v-150.526-103.395c-.002-7.891-3.197-15.043-8.382-20.217z"
                fill="#ffe5c2"
              />
              <path
                d="m184.944 350.364c9.55 0 17.291-7.742 17.291-17.291 0-37.489-23.06-71.124-58.025-84.644l-14.369-5.558c-1.722-.666-2.857-2.322-2.857-4.169v-56.133c0-6.413-2.013-12.36-5.447-17.249-4.731-6.761-12.178-11.484-20.763-12.595v27.806c-5.435-7.766-14.452-12.849-24.663-12.849-1.953 0-3.86.192-5.71.547-2.313 4.263-3.626 9.149-3.626 14.34v132.663c0 12.347 3.144 24.421 9.034 35.132z"
                fill="#fed2a4"
              />
              <path
                d="m90.041 407.371v83.625c0 5.294 4.292 9.587 9.587 9.587h81.721v-157.422c0-37.489-23.06-71.124-58.025-84.644l-17.227-6.663v-59.196c0-6.413-2.013-12.36-5.447-17.249-5.435-7.766-14.452-12.849-24.663-12.849-8.312 0-15.84 3.366-21.286 8.812s-8.812 12.974-8.812 21.286v132.662c0 16.124 5.344 31.793 15.191 44.551z"
                fill="#ffe5c2"
              />
              <g fill="#fed2a4">
                <path
                  d="m90.041 407.371v83.625c0 5.294 4.292 9.587 9.587 9.587h192.465c4.808 0 8.706-3.898 8.706-8.706v-6.727c-5.349-.082-127.955-.102-137.372-.101-18.983.002-34.365-15.386-34.365-34.369v-40.742c0-9.375-3.109-18.486-8.839-25.906l-20.122-26.055c-9.847-12.758-15.191-28.427-15.191-44.551v-132.664c0-5.554 1.509-10.754 4.131-15.221-3.949-1.905-8.373-2.983-13.053-2.983-8.312 0-15.84 3.366-21.286 8.812-5.447 5.447-8.812 12.974-8.812 21.286v132.664c0 16.124 5.344 31.793 15.191 44.551z"
                />
                <path
                  d="m100.65 65.691-.072 111.2h26.281v-139.68c-14.675 1.215-26.209 13.502-26.209 28.48z"
                />
                <path
                  d="m186.431 3.265c-15.794 0-28.598 12.792-28.598 28.586v33.839c0-.174-.01-.346-.013-.519v142.421h1.194c16.57 0 30.002-13.432 30.002-30.002v-174.203c-.852-.076-1.713-.122-2.585-.122z"
                />
                <path
                  d="m243.614 29.452c-15.3 0-27.793 12.015-28.56 27.114v151.026h1.493c16.57 0 30.002-13.432 30.002-30.002l.004-147.981c-.964-.098-1.948-.157-2.939-.157z"
                />
                <path
                  d="m300.798 61.859c-14.649 0-26.708 11.017-28.38 25.215v120.518c16.57 0 30.002-13.432 30.002-30.002v-115.683c-.537-.03-1.078-.048-1.622-.048z"
                />
              </g>
            </g>
            <g fill="#6bd9e7">
              <path
                d="m429.007 47.732c-4.143 0-7.5 3.358-7.5 7.5v15.445h-16.694v-15.445c0-4.142-3.357-7.5-7.5-7.5s-7.5 3.358-7.5 7.5v45.89c0 4.142 3.357 7.5 7.5 7.5s7.5-3.358 7.5-7.5v-15.445h16.694v15.445c0 4.142 3.357 7.5 7.5 7.5s7.5-3.358 7.5-7.5v-45.89c0-4.142-3.357-7.5-7.5-7.5z"
              />
              <path
                d="m462.585 74.677c-4.143 0-7.5 3.358-7.5 7.5v18.945c0 4.142 3.357 7.5 7.5 7.5s7.5-3.358 7.5-7.5v-18.945c0-4.142-3.357-7.5-7.5-7.5z"
              />
              <path
                d="m462.585 44.308c-4.143 0-7.5 3.358-7.5 7.5v5.822c0 4.142 3.357 7.5 7.5 7.5s7.5-3.358 7.5-7.5v-5.822c0-4.142-3.357-7.5-7.5-7.5z"
              />
            </g>
          </g>
        </svg>
      </div>
    </div>
  </div>
</template>

<style>
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
  font-family: "Ubuntu", sans-serif;
  font-weight: 300;
}
ul {
  list-style: none;
}

/* Intro Page */
.intro-text {
  font-family: "Titan One", cursive;
  color: rgb(205, 196, 245);
}
.landing-page {
  background-color: rgba(15, 0, 39, 0.911);
  display: flex;
  flex-direction: column;
  justify-content: center;
  min-height: 92vh;
}
.main-intro-text,
#my-name-capital,
#my-name-lower {
  font-family: "Titan One", cursive;
  color: white;
}
#my-name-capital {
  font-size: 120%;
}
.special-base-text {
  font-weight: 400;
  font-style: italic;
  color: rgb(137, 123, 201);
  font-size: 110%;
  padding: 0 0.2rem;
}
.landing-buttons {
  margin-top: 2rem;
}
.landing-button {
  text-decoration: none;
  padding: 0.5rem 1rem;
  margin-right: 1rem;
  border-radius: 1rem;
  color: black;
  font-weight: 600;
}
#button1 {
  background-image: linear-gradient(
    to right,
    rgb(137, 123, 201) 0%,
    rgb(52, 35, 80) 51%,
    rgb(137, 123, 201) 100%
  );
}
#button1 {
  margin: 10px;
  padding: 0.75rem 1.5rem;
  text-align: center;
  text-transform: uppercase;
  transition: 0.5s;
  background-size: 200% auto;
  color: white;
  box-shadow: 0 0 0px rgba(238, 238, 238, 0.45);
  border-radius: 10px;
}
#button1:hover {
  background-position: right center; /* change the direction of the change here */
  color: #fff;
  text-decoration: none;
  box-shadow: 0 0 15px rgba(238, 238, 238, 0.65);
  transition: box-shadow 0.25s ease-in-out;
}
#button2 {
  background-image: linear-gradient(
    to right,
    rgb(137, 123, 201) 0%,
    rgb(52, 35, 80) 51%,
    rgb(137, 123, 201) 100%
  );
}
#button2 {
  margin: 10px;
  padding: 0.75rem 1.5rem;
  text-align: center;
  text-transform: uppercase;
  transition: 0.5s;
  background-size: 200% auto;
  color: white;
  box-shadow: 0 0 0px rgba(238, 238, 238, 0.45);
  border-radius: 10px;
}
#button2:hover {
  background-position: right center; /* change the direction of the change here */
  color: #fff;
  text-decoration: none;
  box-shadow: 0 0 15px rgba(238, 238, 238, 0.65);
  transition: box-shadow 0.25s ease-in-out;
}

#button3 {
  background-image: linear-gradient(
    to right,
    rgb(137, 123, 201) 0%,
    rgb(52, 35, 80) 51%,
    rgb(137, 123, 201) 100%
  );
}
#button3 {
  margin: 10px;
  padding: 0.75rem 1.5rem;
  text-align: center;
  text-transform: uppercase;
  transition: 0.5s;
  background-size: 200% auto;
  color: white;
  box-shadow: 0 0 0px rgba(238, 238, 238, 0.45);
  border-radius: 10px;
}
#button3:hover {
  background-position: right center; /* change the direction of the change here */
  color: #fff;
  text-decoration: none;
  box-shadow: 0 0 15px rgba(238, 238, 238, 0.65);
  transition: box-shadow 0.25s ease-in-out;
}

/* General Containers */
.page-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 7rem 30rem;
}
.container-header {
  font-size: 200%;
  padding-bottom: 2rem;
}
.page-content {
  display: flex;
}
.live-button,
.github-button {
  text-decoration: none;
  color: white;
  padding: 0.25rem 1.5rem;
  margin: 0.25rem 0.75rem;
  background-color: rgb(137, 123, 201);
  -webkit-transition: 0.25s ease-in-out;
  -moz-transition: 0.25s ease-in-out;
  transition: 0.25s ease-in-out;
  border-radius: 1rem;
  font-size: 1.5rem;
}
.live-button:hover,
.github-button:hover {
  background-color: rgb(52, 35, 80);
  -webkit-transition: 0.25s ease-in-out;
  -moz-transition: 0.25s ease-in-out;
  transition: 0.25s ease-in-out;
}

/* About Page */
#about-page {
  background-color: white;
}
.about-me-text {
  font-size: 1.4rem;
  line-height: 2rem;
  text-align: justify;
  margin-top: 1rem;
  padding: 1rem 2rem;
  border-left: 9px solid rgba(137, 123, 201, 0.85);
  border-right: 5px solid rgba(137, 123, 201, 0.25);
  -webkit-transition: 0.5s ease-in-out;
  -moz-transition: 0.5s ease-in-out;
  transition: 0.5s ease-in-out;
  border-top-left-radius: 1rem;
  border-bottom-right-radius: 1rem;
}
.about-me-text:hover {
  border-left: 9px solid rgba(137, 123, 201, 0.25);
  border-right: 5px solid rgba(137, 123, 201, 0.85);
  -webkit-transition: 0.5s ease-in-out;
  -moz-transition: 0.5s ease-in-out;
  transition: 0.5s ease-in-out;
}
#profile-pic {
  max-width: 15rem;
  height: auto;
  padding-right: 3rem;
  border-radius: 50%;
}
#skills {
  font-weight: 600;
  font-size: 110%;
  color: rgba(15, 0, 39, 0.7);
}

/* Project Page */
#projects-page {
  background-color: white;
}
.project-container {
  display: flex;
  justify-content: center;
}
.project-card {
  box-shadow: 0.35rem 0.25rem 1.25rem rgba(15, 0, 39, 0.5);
  border-radius: 1rem;
  margin: 3rem 0;
}
.project-img {
  max-width: 20rem;
  border-top-left-radius: 1rem;
  border-top-right-radius: 1rem;
  border-bottom: 2px solid rgba(15, 0, 39, 0.25);
}
.img-overlay {
  position: absolute;
  width: 100%;
  height: 100%;
  border-radius: 1rem;
  background-color: rgba(35, 33, 37, 0.9);
  opacity: 0;
  -webkit-transition: opacity 0.3s ease-in-out;
  -moz-transition: opacity 0.3s ease-in-out;
  transition: opacity 0.3s ease-in-out;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  color: white;
}
.img-overlay:hover {
  opacity: 1;
  -webkit-transition: opacity 0.3s ease-in-out;
  -moz-transition: opacity 0.3s ease-in-out;
  transition: opacity 0.3s ease-in-out;
}
.project-card-contents {
  display: flex;
  position: relative;
}
#project-one-details,
#project-two-details,
#project-three-details {
  display: flex;
  flex-direction: column;
  padding: 0 2rem 1rem 2rem;
}
.project-icons {
  display: flex;
  justify-content: space-around;
  margin-top: 1.5rem;
}
.overlay-title {
  margin: 0.75rem;
}
.project-description {
  padding: 0 3rem;
}

/* Contact Page */
#contact-page {
  background-color: white;
  min-height: 30vh;
  z-index: 999;
}
.contact-content {
  z-index: 50;
}
.hand-container {
  position: absolute;
  right: 30%;
}
#email {
  font-weight: 400;
  font-size: 110%;
}

/* SVG Fills */
.st0-vue {
  fill: #4dba87;
}
.st1-vue {
  fill: #425466;
}
.st0-firebase {
  fill: #ffa000;
}
.st1-firebase {
  fill: #f57c00;
}
.st2-firebase {
  fill: #ffca28;
}
.st3-firebase {
  fill: #ffffff;
  fill-opacity: 0.2;
}
.st4-firebase {
  opacity: 0.2;
  fill: #a52714;
  enable-background: new;
}
.st5-firebase {
  fill: url(#b_1_);
}
.st0-html {
  fill-rule: evenodd;
  clip-rule: evenodd;
  fill: #e44d26;
}
.st1-html {
  fill-rule: evenodd;
  clip-rule: evenodd;
  fill: #f16529;
}
.st2-html {
  fill-rule: evenodd;
  clip-rule: evenodd;
  fill: #ebebeb;
}
.st3-html {
  fill-rule: evenodd;
  clip-rule: evenodd;
  fill: #ffffff;
}
.fil6 {
  fill: #000;
  fill-opacity: 0.05098;
}

/* S Screen */
@media screen and (max-width: 699px) {
  .landing-page {
    padding: 0 1rem;
  }
  .main-intro-text {
    font-size: 1.65rem;
  }
  #my-name-capital {
    font-size: 2.1rem;
  }
  #my-name-lower {
    font-size: 1.7rem;
  }
  .landing-page p {
    width: 90%;
  }
  .page-container {
    padding: 5rem 1rem 0 1rem;
  }
  .page-content {
    flex-direction: column;
    align-items: center;
  }
  .container-header {
    font-size: 3rem;
  }
  .about-me-text {
    font-size: 1.2rem;
    line-height: 1.5rem;
  }
  .contact-text {
    font-size: 1.2rem;
  }
  .project-img {
    max-width: 100%;
    max-height: auto;
  }
  .project-card-contents {
    flex-direction: column;
  }
  #reverse-column {
    flex-direction: column-reverse;
  }
  .project-description {
    font-size: 0.8rem;
    padding: 0rem 1rem 1rem 1rem;
  }
  .overlay-title {
    margin: 0.8rem;
    font-size: 1.5rem;
  }
  .live-button,
  .github-button {
    margin-top: 0.5rem;
  }
  .landing-buttons {
    display: flex;
    flex-direction: column;
    width: 62%;
  }
}

/* M Screen */
@media screen and (min-width: 700px) {
  .landing-page {
    padding: 0 5rem;
  }
  .main-intro-text {
    font-size: 3rem;
  }
  .landing-page p {
    font-size: 120%;
    width: 85%;
  }
  .page-container {
    font-size: 2rem;
    padding: 7rem 5rem 7rem 5rem;
  }
  .page-content {
    flex-direction: column;
    align-items: center;
  }
  .project-img {
    max-width: 100%;
  }
  .project-card-contents {
    display: flex;
    flex-direction: column;
  }
  #reverse-column {
    flex-direction: column-reverse;
  }
  #project-one-details,
  #project-two-details {
    padding: 0 2rem 1rem 2rem;
  }
  .project-description {
    font-size: 1rem;
    padding: 1rem 2rem;
  }
}

/* L Screen */
@media screen and (min-width: 1210px) {
  .landing-page {
    padding: 0 10rem;
  }
  .main-intro-text {
    font-size: 5rem;
  }
  .landing-page p {
    font-size: 150%;
    width: 75%;
  }
  .project-container ul {
    width: 75%;
  }
  .page-container {
    height: 100%;
    font-size: 2rem;
    padding: 7rem 10rem;
  }
  .page-content {
    flex-direction: row;
  }
  #project-one,
  #project-three {
    margin: 3rem 10rem 3rem 0;
  }
  #project-two,
  #project-four {
    margin: 3rem 0 0 10rem;
  }
  .project-card-contents {
    flex-direction: column;
  }
  .project-description {
    font-size: 1.1rem;
  }
}

/* XL Screen */
@media screen and (min-width: 1700px) {
  .landing-page {
    padding: 0 15rem;
  }
  .main-intro-text {
    font-size: 6rem;
  }
  .landing-page p {
    font-size: 175%;
    width: 60%;
  }
  .page-container {
    font-size: 2rem;
    padding: 7rem 30rem;
  }
  .project-img {
    max-width: 100%;
  }
  .project-card-contents {
    flex-direction: column;
  }
  .project-description {
    font-size: 1.17rem;
  }
  #project-one-details {
    display: flex;
    flex-direction: column;
    padding: 0 1rem 1rem 1rem;
  }
}
</style>
