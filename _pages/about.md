---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- Animated Biography Heading -->
<h2 id="biography"><span id="element"></span></h2>
<style>
  #biography {
    margin-top: 10px;
    margin-bottom: 20px;
    font-size: 28px;
  }
  #element {
    display: inline-block;
  }
</style>

<!-- Typed.js -->
<script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
<script>
document.addEventListener("DOMContentLoaded", function() {
  new Typed('#element', {
    strings: ['', '<strong>Biography</strong>'],
    typeSpeed: 80,
    backSpeed: 50,
    backDelay: 1000,
    loop: true,
    showCursor: true,
    cursorChar: '|'
  });
});
</script>

Tanner is a bilingual Mechanical Engineer with hands-on experience across manufacturing, additive manufacturing, solar energy, and engineering problem solving. He has worked on additive manufacturing projects in Taipei, consulted on solar systems in New Zealand, and gained practical experience in logistics and trade.

While completing his degree, Tanner navigated the loss of his mother, <a href="https://www.morrislegal.co.nz/insights/morris-successfully-defends-claim-against-mothers-estate" target="_blank" rel="noopener">managed a complex High Court case</a>, and cared for his grandmother — experiences that shaped his resilience and focus.

A lifelong learner, aviation enthusiast, and Grade 7 alto saxophonist, Tanner approaches engineering with curiosity, innovation, and a commitment to delivering impactful solutions.

<!-- Timeline Section -->
<section class="timeline">
  <div class="timeline-item">
    <div class="timeline-logo"><img src="/images/Crown.jpg" alt="Crown Logo"></div>
    <div class="timeline-content">
      <h3>Crown Worldwide Group</h3>
      <h4>Inbound Leads Specialist</h4>
      <p>Feb 2025 - Present</p>
      <p>Serving as a key point of contact for incoming inquiries, coordinating solutions and guiding clients through the relocation process to ensure exceptional service and operational efficiency.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-logo"><img src="/images/gridfree.png" alt="Gridfree Logo"></div>
    <div class="timeline-content">
      <h3>Gridfree - Off Grid Solar NZ</h3>
      <h4>Consulting Engineer</h4>
      <p></p>
      <p>Provided technical consulting for off-grid solar solutions at New Zealand’s largest company in the sector. Assisted customers in system design and implementation, supporting energy independence through renewable technology.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-logo"><img src="/images/NTUT.jpg" alt="Taipei Tech Logo"></div>
    <div class="timeline-content">
      <h3>National Taipei University of Technology</h3>
      <h4>Additive Manufacturing Intern</h4>
      <p></p>
      <p>Researched and developed additive manufacturing processes and materials, gaining exposure to advanced prototyping techniques and materials science applications.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-logo"><img src="/images/SGAC.png" alt="SGAC Logo"></div>
    <div class="timeline-content">
      <h3>Space Generation Advisory Council</h3>
      <h4>National Point of Contact</h4>
      <p></p>
      <p>Acted as the national liaison for SGAC, reporting on local space activities and submitting annual reports to the Executive Office for the UN.</p>
    </div>
  </div>
</section>

<!-- Featured Publications -->
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

<!-- Bootstrap Carousel -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

<div id="accomplishmentsCarousel" class="carousel slide mt-5" data-bs-ride="carousel">
  <div class="carousel-inner">

    <div class="carousel-item active text-center">
      <img src="/images/solar.jpg" class="d-block mx-auto" alt="Off-grid Solar" style="max-height:350px; object-fit:cover;">
      <div class="carousel-caption d-none d-md-block bg-dark bg-opacity-50 rounded p-2">
        <h5>Consulting Engineer</h5>
        <p>Specialized in off-grid solar solutions at New Zealand’s largest company in the sector.</p>
      </div>
    </div>

    <div class="carousel-item text-center">
      <img src="/images/headliner.jpg" class="d-block mx-auto" alt="Starlight Headliner Project" style="max-height:350px; object-fit:cover;">
      <div class="carousel-caption d-none d-md-block bg-dark bg-opacity-50 rounded p-2">
        <h5>46-Hour Starlight Headliner</h5>
        <p>Threaded 780 fiber optic cables to complete a luxury automotive interior upgrade.</p>
      </div>
    </div>

    <div class="carousel-item text-center">
      <img src="/images/ntut.jpg" class="d-block mx-auto" alt="Taipei Tech Internship" style="max-height:350px; object-fit:cover;">
      <div class="carousel-caption d-none d-md-block bg-dark bg-opacity-50 rounded p-2">
        <h5>Additive Manufacturing Internship</h5>
        <p>Conducted research and development in 3D printing processes at NTUT, Taiwan.</p>
      </div>
    </div>

  </div>

  <button class="carousel-control-prev" type="button" data-bs-target="#accomplishmentsCarousel" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#accomplishmentsCarousel" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
