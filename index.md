---
layout: home
title: Dev Patch Notes
---

<link rel="stylesheet" href="{{ site.baseurl }}/assets/css/style.css">

<header class="site-header">
  <div class="header-container">
    <a href="{{ site.baseurl }}/" class="site-title">FaR Team Devlog</a>
    <nav class="site-nav">
      <a href="{{ site.baseurl }}/" class="nav-link active">Home</a>
      <a href="{{ site.baseurl }}/archive" class="nav-link">Archive</a>
      <a href="https://github.com/FaR-Team" class="nav-link" target="_blank">GitHub</a>
    </nav>
  </div>
</header>

<div class="hero-section">
  <h1>Development Updates</h1>
  <p>Latest patch notes and development progress for FARMOXEL and Room Makers</p>
</div>

<div class="container">
  <h2 class="page-title">Recent Updates</h2>
  <div class="featured-works">
    {% for post in site.posts %}
      <div class="featured-work">
        <h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
        <p class="meta">{{ post.date | date: "%B %d, %Y" }}</p>
        <p class="excerpt">{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
        <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">View Changes →</a>
      </div>
    {% endfor %}
  </div>
  
  <div class="archive-link-container">
    <a href="{{ site.baseurl }}/archive" class="archive-link">View All Updates →</a>
  </div>
</div>

<footer class="site-footer">
  <p>&copy; 2025 FaR Team. Patch notes.</p>
</footer>
