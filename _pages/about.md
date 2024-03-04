---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>

  <!-- Element to contain animated typing -->
  <span id="element"></span>

  <!-- Load library from the CDN -->
  <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>

  <!-- Setup and start animation! -->
  <script>
    var typed = new Typed('#element', {
      strings: ['', '<strong>Tanner&apos;s website is still under construction...Please wait - attempting to reestablish</strong>'],
      typeSpeed: 80, loop: true, loopCount: Infinity
    });
  </script>

This is the front page of a website that is powered and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. 

A data-driven personal website
======



Heading 2
======


Heading 3
------


Heading 4
------


  <style>
    body {
      background: #F1F1F1;
      text-align: center;
      font-family: Montserrat, Arial, "Helvetica Neue", Helvetica, sans-serif;
      display: flex;
      align-items: center;
      justify-content: center;
      margin: auto;
      box-sizing: border-box;
      height: 100vh;
      padding: 30px;
    }

    .margin {
      margin: 25px;
    }

    /* ==================== Semi Donut Chart ======================== */

    .resource {
      --percentage: 0;
      --fill: #082B67;
      width: 300px;
      height: 150px;
      position: relative;
      color: #fff;
      font-size: 22px;
      font-weight: 600;
      overflow: hidden;
      color: var(--fill);
      display: flex;
      align-items: flex-end;
      justify-content: center;
      box-sizing: border-box;
    }

    .percentage-text {
      position: absolute;
      top: 70%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 24px;
    }
    .label {
      font-size: 24px;
      text-align: center;
      font-family: Montserrat, Arial, "Helvetica Neue", Helvetica, sans-serif;
      font-weight: 300;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .resource:after {
      content: '';
      width: 300px;
      height: 300px;
      border: 50px solid;
      border-color: rgba(0, 0, 0, 0.15) rgba(0, 0, 0, 0.15) var(--fill) var(--fill);
      position: absolute;
      border-radius: 50%;
      left: 0;
      top: 0;
      box-sizing: border-box;
      transform: rotate(calc(1deg * (-45 + var(--percentage) * 1.8)));
      animation: fillAnimation 1s ease-in;
    }

    /* ==================== Keyframes ======================== */

    @keyframes fillAnimation {
      0% {
        transform: rotate(-45deg);
      }

      50% {
        transform: rotate(135deg);
      }
    }
  </style>
</head>

<body>
  <div class="tophalf">
    <div class="resource margin" style="--percentage: 90; --fill: #545698;">
      <div class="percentage-text">90%</div>
      <a class="label">Latex</a>
    </div>

    <div class="resource margin" style="--percentage: 75; --fill: #00A86B;">
      <div class="percentage-text">75%</div>
      <a class="label">RAM</a>
    </div>
  </div>
  <div class="btmhalf">
    <div class="resource margin" style="--percentage: 30; --fill: #FF9F00;">
      <div class="percentage-text">30%</div>
      <a class="label">HDD</a>
    </div>
    <div class="resource margin" style="--percentage: 70; --fill: #00ff34;">
      <div class="percentage-text">70%</div>
      <a class="label">HDD</a>
    </div>
  </div>
  <script>
    // This script is for updating the percentage text dynamically
    document.querySelectorAll('.resource').forEach((resource) => {
      const percentageText = resource.querySelector('.percentage-text');
      percentageText.textContent = `${resource.style.getPropertyValue('--percentage')}%`;
    });
  </script>
</body>




Heading 5
------


For more info
------

