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
      strings: ['', '<strong>Check out Tanner\'s recent 46 hour project, starlight headliner modification.</strong>'],
      typeSpeed: 80, loop: true, loopCount: Infinity
    });
  </script>


Biography
======
Hi, I’m Tanner Guo — a mechanical engineer with experience in manufacturing, solar energy, and hands-on problem solving. I’ve worked on additive manufacturing projects in Taipei, consulted on solar systems in New Zealand, and gained practical experience across industries from logistics to trade. I’m also the founder of China Business Tours, helping Kiwi businesses connect with suppliers in China. Outside of work, I’m an aviation enthusiast working toward my private pilot’s license.


<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tanner Guo </title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
    background: #f9f9f9;
  }

  /* Timeline container */
  .timeline {
    position: relative;
    max-width: 800px;
    margin: auto;
    padding: 40px 0;
  }

  .timeline::before {
    content: '';
    position: absolute;
    top: 0;
    bottom: 0;
    left: 50%;
    width: 4px;
    background: #ccc;
    transform: translateX(-50%);
    z-index: 0;
  }

  .timeline-item {
    display: flex;
    align-items: flex-start;
    position: relative;
    margin-bottom: 60px;
    width: 100%;
    opacity: 0;
    animation: fadeInUp 0.6s forwards;
  }

  /* Stagger animations */
  .timeline-item:nth-child(1) { animation-delay: 0.2s; }
  .timeline-item:nth-child(2) { animation-delay: 0.4s; }
  .timeline-item:nth-child(3) { animation-delay: 0.6s; }

  @keyframes fadeInUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .timeline-item:nth-child(odd) {
    flex-direction: row-reverse;
    text-align: right;
  }

  .timeline-dot {
    width: 16px;
    height: 16px;
    background: #3b82f6;
    border-radius: 50%;
    border: 3px solid #fff;
    margin: 0 20px;
    flex-shrink: 0;
  }

  .timeline-logo {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    overflow: hidden;
    border: 2px solid #ccc;
    background: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-shrink: 0;
  }

  .timeline-logo img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .timeline-content {
    max-width: 300px;
    background: #fff;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }

  .timeline-content h3 { margin: 0; font-size: 18px; color: #333; }
  .timeline-content h4 { margin: 5px 0; font-size: 16px; color: #666; }
  .timeline-content p { margin: 10px 0 0; font-size: 14px; color: #555; }

  .Publications {
    background: #fff;
    padding: 15px;
    margin-bottom: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    opacity: 0;
    animation: fadeInUp 0.6s forwards;
  }

  .Publications:nth-child(1) { animation-delay: 0.2s; }
  .Publications:nth-child(2) { animation-delay: 0.4s; }
  .Publications:nth-child(3) { animation-delay: 0.6s; }

  .Publications h3 { margin: 0 0 5px 0; font-size: 16px; color: #333; }
  .Publications p { margin: 2px 0; font-size: 14px; color: #555; }

  @media screen and (max-width: 768px) {
    .timeline::before { left: 20px; }
    .timeline-item { flex-direction: row !important; text-align: left !important; }
    .timeline-dot { margin: 0 10px 0 0; }
  }
</style>
</head>
<body>
  <section class="timeline">
    <div class="timeline-item">
      <div class="timeline-logo"><img src="images/SGAC.png" alt="SGAC Logo"></div>
      <div class="timeline-content">
        <h3>Space Generation Advisory Council</h3>
        <h4>National Point of Contact</h4>
        <p>Jun 2021 – Jun 2023</p>
        <p>Prepared technical documentation, reviewed design outputs, and provided technical support for engineering projects.</p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-logo"><img src="images/NTUT.jpg" alt="Taipei Tech Logo"></div>
      <div class="timeline-content">
        <h3>National Taipei University of Technology</h3>
        <h4>Additive Manufacturing Intern</h4>
        <p>2020</p>
        <p>Conducted research and development in additive manufacturing processes and materials.</p>
      </div>
    </div>

    <div class="timeline-item">
      <div class="timeline-logo"><img src="images/Crown.jpg" alt="Crown Logo"></div>
      <div class="timeline-content">
        <h3>Crown Worldwide Group</h3>
        <h4>Inbound Leads Specialist</h4>
        <p>2025 - Present</p>
        <p>Serve as a key point of contact for incoming inquiries, coordinating solutions and guiding clients through the relocation process to ensure exceptional service and operational efficiency.</p>
      </div>
    </div>
  </section>

  <section style="max-width:800px;margin:auto;padding:40px 20px;">
    <h2>Featured Publications</h2>

    <article class="Publications">
      <h3>Heat Generation and Prevention of Overheating in Lithium Ion Batteries</h3>
      <p>Chuanzelong Guo</p>
      <p>Auckland University of Technology, New Zealand, 2020</p>
    </article>

    <article class="Publications">
      <h3>Additive Manufacturing Internship - National Taipei University of Technology</h3>
      <p>Chuanzelong Guo</p>
      <p>Auckland University of Technology, New Zealand, 2020</p>
    </article>

    <article class="Publications">
      <h3>Towards A Self-Sustainable Production Of Proteins In Space: A Proposed Solution And Roadmap</h3>
      <p>Francesco Spina, Roberto Aguilar, Chuanzelong Guo, Mami Sugaya, Ryunosuke Yokoya, Catherine Mandigma and Kensuke Wada</p>
      <p>69th International Astronautical Congress, Germany, 2018</p>
    </article>
  </section>
</body>
</html>

<br/>

