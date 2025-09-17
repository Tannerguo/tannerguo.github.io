---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">
    You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.
  </div>
{% endif %}

{% include base_path %}

<!-- Include AOS library for scroll animations -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css">
<script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>

<style>
  .publications-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    padding: 2rem 1rem;
  }

  .publication-card {
    background: #fff;
    border-radius: 12px;
    border: 2px solid #e2e8f0;
    box-shadow: 0 6px 18px rgba(0,0,0,0.05);
    padding: 1.5rem;
    transition: transform 0.3s ease, box-shadow 0.3s ease, border-color 0.3s ease;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }

  .publication-card:nth-child(3n+1) { border-color: #63b3ed; }
  .publication-card:nth-child(3n+2) { border-color: #f6ad55; }
  .publication-card:nth-child(3n+3) { border-color: #9f7aea; }

  .publication-card:hover {
    transform: translateY(-5px) scale(1.02);
    box-shadow: 0 12px 30px rgba(99, 179, 237, 0.3);
    border-color: #3182ce;
  }

  .publication-title {
    font-size: 1.2rem;
    font-weight: 600;
    color: #1a202c;
    text-decoration: none;
    margin-bottom: 0.5rem;
  }

  .publication-title:hover {
    color: #3182ce;
  }

  .publication-excerpt {
    font-size: 0.95rem;
    color: #4a5568;
    margin-bottom: 1rem;
  }

  .publication-meta {
    font-size: 0.85rem;
    color: #718096;
  }

  .download-btn {
    margin-top: 1rem;
    align-self: flex-start;
    background: #3182ce;
    color: #fff;
    padding: 0.5rem 1rem;
    border-radius: 6px;
    text-decoration: none;
    font-size: 0.9rem;
    transition: background 0.3s ease, transform 0.3s ease;
  }

  .download-btn:hover {
    background: #2b6cb0;
    transform: scale(1.05);
  }

  @media (max-width: 600px) {
    .publications-container {
      padding: 1rem;
      gap: 1rem;
    }
  }
</style>

<div class="publications-container">
  {% assign delay = 0 %}
  {% for post in site.publications reversed %}
    <div class="publication-card" data-aos="fade-up" data-aos-duration="800" data-aos-delay="{{ delay }}">
      <!-- Title links directly to PDF -->
      <a class="publication-title" href="{{ post.paperurl | prepend: site.baseurl }}" target="_blank">{{ post.title }}</a>
      <div class="publication-excerpt">{{ post.excerpt }}</div>
      <div class="publication-meta">{{ post.venue }} | {{ post.date | date: "%Y-%m-%d" }}</div>
      {% if post.paperurl %}
        <a class="download-btn" href="{{ post.paperurl | prepend: site.baseurl }}" target="_blank">Download PDF</a>
      {% endif %}
    </div>
    {% assign delay = delay | plus: 100 %}
  {% endfor %}
</div>

<script>
  AOS.init({
    once: true,
    offset: 100
  });
</script>
