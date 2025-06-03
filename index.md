---
layout: home
---

<link rel="stylesheet" href="{{ site.baseurl }}/assets/css/style.css">

<div class="hero-section">
  <h1>F.a.R Team Patch Notes</h1>
</div>

<div class="container">
  <div class="featured-works">
    {% for post in site.posts %}
      <div class="featured-work">
        <h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
        <p class="meta">
          {{ post.date | date: "%d %B %Y" }} • 
          {% if post.genre %}
            {{ post.genre }}
            <span class="game-tag">{{ post.genre }}</span>
          {% else %}
            {% if post.tags %}
              {{ post.tags | first }}
              <span class="game-tag">{{ post.tags | first }}</span>
            {% else %}
              Uncategorized
            {% endif %}
          {% endif %}
        </p>
        <p class="excerpt">{{ post.excerpt | strip_html | truncatewords: 25 }}</p>
        <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More →</a>
      </div>
    {% endfor %}
  </div>
  
  <div class="archive-link-container">
    <a href="{{ site.baseurl }}/archive" class="archive-link">Ver Archivo Completo →</a>
  </div>
</div>