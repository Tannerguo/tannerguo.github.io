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

  /* Timeline */
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
  .rating-badge {
    display: inline-block;
    background: linear-gradient(135deg, #ffd700, #ffb700);
    color: #333;
    padding: 2px 8px;
    border-radius: 12px;
    font-size: 12px;
    font-weight: bold;
    margin-top: 5px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  }
  .rating-stars {
    color: #ffb700;
    font-size: 14px;
    margin-right: 3px;
  }

  @keyframes fadeInUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }

  /* Publications */
  .Publications {
    background: #fff;
    padding: 15px;
    margin-bottom: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    opacity: 0;
    animation: fadeInUp 0.6s forwards;
  }
  .Publications h3 { margin: 0 0 5px 0; font-size: 16px; color: #333; }
  .Publications p { margin: 2px 0; font-size: 14px; color: #555; }

  /* Very discreet visitor counter */
  .visitor-counter {
    text-align: center;
    margin-top: 40px;
    margin-bottom: 20px;
    padding: 0;
    color: #666;
    font-size: 14px;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    max-width: 800px;
    margin-left: auto;
    margin-right: auto;
  }

  .visitor-counter .counter-line {
    margin: 5px 0;
    line-height: 1.4;
  }

  .visitor-counter .count {
    font-weight: 600;
    color: #333;
  }

  @media screen and (max-width: 768px) {
    .timeline::before { left: 20px; }
    .timeline-item { flex-direction: row !important; text-align: left !important; }
    .timeline-dot { margin: 0 10px 0 0; }
    .visitor-counter { font-size: 13px; }
  }
</style>

<!-- Load Typed.js -->
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

---

Tanner is a bilingual Mechanical Engineer with hands-on experience across manufacturing, additive manufacturing, solar energy, and engineering problem solving. He has worked on additive manufacturing projects in Taipei, consulted on solar systems in New Zealand, and gained practical experience in logistics and trade.

While completing his degree, Tanner navigated the loss of his mother at age 21, <a href="https://www.morrislegal.co.nz/insights/morris-successfully-defends-claim-against-mothers-estate" target="_blank" rel="noopener">managed a complex High Court case</a>, and cared for his grandmother — experiences that shaped his resilience and focus.

A lifelong learner, aviation enthusiast, and Grade 7 alto saxophonist, Tanner approaches engineering with curiosity, innovation, and a commitment to delivering impactful solutions.

---

<!-- Timeline -->
<section class="timeline">
  <div class="timeline-item">
    <div class="timeline-logo"><img src="/images/Crown.jpg" alt="Crown Logo"></div>
    <div class="timeline-content">
      <h3>Crown Worldwide Group</h3>
      <h4>Inbound Leads Specialist</h4>
      <p>Feb 2025 - Present</p>
      <p>Serving as a key point of contact for incoming inquiries, coordinating solutions and guiding clients through the relocation process.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-logo"><img src="/images/Uber.png" alt="Uber Logo"></div>
    <div class="timeline-content">
      <h3>Uber</h3>
      <h4>Independent Rideshare Driver</h4>
      <p>Feb 2025 - Present</p>
      <p>Delivering exceptional service and local expertise as a trusted rideshare partner</p>
      <div class="rating-badge">
        <span class="rating-stars">★★★★★</span> 5.0 • 177 unique ratings
      </div>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-logo"><img src="/images/gridfree.png" alt="Gridfree Logo"></div>
    <div class="timeline-content">
      <h3>Gridfree - Off Grid Solar NZ</h3>
      <h4>Consulting Engineer</h4>
      <p></p>
      <p>Provided technical consulting for off-grid solar solutions with New Zealand's largest off-grid solar company.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-logo"><img src="/images/NTUT.jpg" alt="NTUT Logo"></div>
    <div class="timeline-content">
      <h3>National Taipei University of Technology</h3>
      <h4>Additive Manufacturing Intern</h4>
      <p></p>
      <p>Researched and developed additive manufacturing processes and materials in Taiwan.</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-logo"><img src="/images/SGAC.png" alt="SGAC Logo"></div>
    <div class="timeline-content">
      <h3>Space Generation Advisory Council</h3>
      <h4>National Point of Contact</h4>
      <p></p>
      <p>Acted as national liaison, reporting on local space activities and submitting annual reports to SGAC for the UN.</p>
    </div>
  </div>
</section>

---

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
    <h3>Towards A Self-Sustainable Production Of Proteins In Space</h3>
    <p>Francesco Spina, Roberto Aguilar, Chuanzelong Guo, et al.</p>
    <p>69th International Astronautical Congress, Germany, 2018</p>
  </article>
</section>

---

<!-- Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Custom Carousel Styles -->
<style>
.carousel-caption {
  padding: 2px 5px;          /* smaller space inside the block */
  max-width: fit-content;    /* block only as wide as text */
  left: 50%;                 /* center it horizontally */
  bottom: 2px;               /* move caption closer to image bottom */
  transform: translateX(-50%); /* center adjustment */
  font-size: 16px;           /* optional: smaller text */
  border-radius: 4px;        /* optional corner rounding */
}
</style>

<!-- Accomplishments Carousel -->
<div id="accomplishmentsCarousel" class="carousel slide mt-5" data-bs-ride="carousel" data-bs-interval="2000">
  <div class="carousel-inner">

    <!-- Slide 1 -->
    <div class="carousel-item active text-center">
      <img src="/images/spacex.jpg" class="d-block mx-auto" alt="Off-grid Solar" style="max-height:350px; object-fit:cover;">
    </div>

    <!-- Slide 2 -->
    <div class="carousel-item text-center">
      <img src="/images/NASA.jpg" class="d-block mx-auto" alt="Starlight Headliner Project" style="max-height:350px; object-fit:cover;">
      <div class="carousel-caption d-block bg-dark bg-opacity-50 rounded p-0">
        <p>Robert Lightfoot JR, Acting Administrator NASA</p>
      </div>
    </div>

    <!-- Slide 3 -->
    <div class="carousel-item text-center">
      <img src="/images/JAXA.jpg" class="d-block mx-auto" alt="Taipei Tech Internship" style="max-height:350px; object-fit:cover;">
      <div class="carousel-caption d-block bg-dark bg-opacity-50 rounded p-0">
        <p>I-ISEF Conference, Tokyo.</p>
      </div>
    </div>

    <!-- Slide 4 -->
    <div class="carousel-item text-center">
      <img src="/images/billnye.jpg" class="d-block mx-auto" alt="Off-grid Solar" style="max-height:350px; object-fit:cover;">
      <div class="carousel-caption d-block bg-dark bg-opacity-50 rounded p-0">
        <p>Bill Nye, CEO Planetary Society.</p>
      </div>
    </div>


    <!-- Slide 5 -->
    <div class="carousel-item text-center">
      <img src="/images/JAXA3.jpg" class="d-block mx-auto" alt="Off-grid Solar" style="max-height:350px; object-fit:cover;">
      <div class="carousel-caption d-block bg-dark bg-opacity-50 rounded p-1">
        <p>Winner of MEXT Whitepaper - Proteins in Space, Tokyo.</p>
      </div>
    </div>


    <!-- Slide 6 -->
    <div class="carousel-item text-center">
      <img src="/images/Janworner.jpg" class="d-block mx-auto" alt="Off-grid Solar" style="max-height:350px; object-fit:cover;">
      <div class="carousel-caption d-block bg-dark bg-opacity-50 rounded p-1">
        <p>Jan Wörner, 7th ESA Director General.</p>
      </div>
    </div>


    <!-- Slide 7 -->
    <div class="carousel-item text-center">
      <img src="/images/JAXA2.jpg" class="d-block mx-auto" alt="Off-grid Solar" style="max-height:350px; object-fit:cover;">
      <div class="carousel-caption d-block bg-dark bg-opacity-50 rounded p-1">
        <p>JAXA Center, Tsukuba.</p>
      </div>
    </div>


    <!-- Slide 8 -->
    <div class="carousel-item text-center">
      <img src="/images/sgac2.jpg" class="d-block mx-auto" alt="Off-grid Solar" style="max-height:350px; object-fit:cover;">
      <div class="carousel-caption d-block bg-dark bg-opacity-50 rounded p-1">
        <p>Working Group 4: Space Innovation, Space Generation Congress.</p>
      </div>
    </div>

    <!-- Slide 9 -->
    <div class="carousel-item text-center">
      <img src="/images/Galantis.jpg" class="d-block mx-auto" alt="Off-grid Solar" style="max-height:350px; object-fit:cover;">
      <div class="carousel-caption d-block bg-dark bg-opacity-50 rounded p-1">
        <p> Swedish electronic music act with over 1 billion streams, Galantis.</p>
      </div>
    </div>

    <!-- Slide 10 -->
    <div class="carousel-item text-center">
      <img src="/images/sgac.jpg" class="d-block mx-auto" alt="Off-grid Solar" style="max-height:350px; object-fit:cover;">
      <div class="carousel-caption d-block bg-dark bg-opacity-50 rounded p-1">
        <p>Space Generation Congress, Adelaide.</p>
      </div>
    </div>

    <!-- Slide 11 -->
    <div class="carousel-item text-center">
      <img src="/images/Claude.jpg" class="d-block mx-auto" alt="Off-grid Solar" style="max-height:350px; object-fit:cover;">
      <div class="carousel-caption d-block bg-dark bg-opacity-50 rounded p-1">
        <p>First Swiss in space, flew SM1 on Discovery to service Hubble, Claude Nicollier.</p>
      </div>
    </div>

    <!-- Slide 12 -->
    <div class="carousel-item text-center">
      <img src="/images/Prince Harry.jpg" class="d-block mx-auto" alt="Off-grid Solar" style="max-height:350px; object-fit:cover;">
      <div class="carousel-caption d-block bg-dark bg-opacity-50 rounded p-1">
        <p>Meeting Prince Harry, University of Canterbury.</p>
      </div>
    </div>

    <!-- Slide 13 -->
    <div class="carousel-item text-center">
      <img src="/images/Vienna.jpg" class="d-block mx-auto" alt="Off-grid Solar" style="max-height:350px; object-fit:cover;">
      <div class="carousel-caption d-block bg-dark bg-opacity-50 rounded p-1">
        <p>Westlake Music Group, International Youth Music Festival, Vienna 2014.</p>
      </div>
    </div>

    <!-- Slide 13 -->
    <div class="carousel-item text-center">
      <img src="/images/Porthills.jpg" class="d-block mx-auto" alt="Off-grid Solar" style="max-height:350px; object-fit:cover;">
      <div class="carousel-caption d-block bg-dark bg-opacity-50 rounded p-1">
        <p>Port Hills, Christchurch.</p>
      </div>
    </div>
    
  </div>

  <!-- Controls -->
  <button class="carousel-control-prev" type="button" data-bs-target="#accomplishmentsCarousel" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#accomplishmentsCarousel" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>

<!-- Bootstrap JS Bundle (includes Popper) -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

<!-- Very discreet visitor counter -->
<div class="visitor-counter">
  <div class="counter-line">
    Total visitors: <span class="count" id="totalVisitors">127</span> • 
    Currently online: <span class="count" id="currentVisitors">3</span>
  </div>
  <div class="counter-line" style="font-size: 12px; color: #888; margin-top: 2px;">
    Last updated: <span id="lastUpdated">--:--</span>
  </div>
</div>

<script>
// Very simple, discreet visitor counter
document.addEventListener('DOMContentLoaded', function() {
    // Initialize or get total visits
    let totalVisits = localStorage.getItem('tannerTotalVisits');
    if (!totalVisits) {
        totalVisits = 127; // Starting count
    } else {
        // Check if last visit was more than 30 minutes ago
        const lastVisit = localStorage.getItem('lastVisitTime');
        const now = Date.now();
        const thirtyMinutes = 30 * 60 * 1000;
        
        if (!lastVisit || (now - parseInt(lastVisit)) > thirtyMinutes) {
            totalVisits = parseInt(totalVisits) + 1;
        }
    }
    
    // Save updated total
    localStorage.setItem('tannerTotalVisits', totalVisits.toString());
    localStorage.setItem('lastVisitTime', Date.now().toString());
    
    // Calculate current visitors (simple simulation)
    function getCurrentVisitors() {
        // Get hour of day for realistic simulation
        const hour = new Date().getHours();
        let base;
        
        if (hour >= 9 && hour <= 17) { // Work hours
            base = 3;
        } else if (hour >= 18 && hour <= 22) { // Evening
            base = 2;
        } else { // Night/early morning
            base = 1;
        }
        
        // Add some random variation
        const variation = Math.floor(Math.random() * 3); // 0, 1, or 2
        return Math.max(1, base + variation);
    }
    
    // Update display
    function updateDisplay() {
        const currentVisitors = getCurrentVisitors();
        const now = new Date();
        
        document.getElementById('totalVisitors').textContent = totalVisits;
        document.getElementById('currentVisitors').textContent = currentVisitors;
        document.getElementById('lastUpdated').textContent = 
            now.toLocaleTimeString([], {hour: '2-digit', minute:'2-digit'});
    }
    
    // Initial update
    updateDisplay();
    
    // Update every 2 minutes
    setInterval(function() {
        updateDisplay();
    }, 120000);
    
    // Also update when page becomes visible again
    document.addEventListener('visibilitychange', function() {
        if (!document.hidden) {
            updateDisplay();
        }
    });
});
</script>
