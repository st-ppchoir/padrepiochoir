---
layout: blog_list
title: Blog
permalink: /blog/
---

<section class="page-section">
  <div class="container">
    <div class="text-center mb-5">
      <h2 class="section-heading text-uppercase">News & Updates</h2>
      <h3 class="section-subheading text-muted">Stories, announcements, and reflections from our choir community</h3>
    </div>
    <div class="row">
      {% for post in site.posts %}
      <div class="col-md-6 col-lg-4 mb-4">
        <div class="card h-100 shadow-sm">
          {% if post.image %}
          <img src="{{ post.image | relative_url }}" class="card-img-top" alt="{{ post.title }}" style="height:200px;object-fit:cover;">
          {% else %}
          <div style="height:200px;background:linear-gradient(135deg,#1a4a8a,#2d6cc0);display:flex;align-items:center;justify-content:center;">
            <i class="fas fa-music fa-3x" style="color:rgba(232,213,163,0.7);"></i>
          </div>
          {% endif %}
          <div class="card-body">
            <p class="small text-muted mb-1">
              <i class="fas fa-calendar-alt me-1"></i>{{ post.date | date: "%B %d, %Y" }}
              {% if post.author %}&nbsp;·&nbsp;<i class="fas fa-user me-1"></i>{{ post.author }}{% endif %}
            </p>
            <h5 class="card-title" style="color:#1a4a8a;">{{ post.title }}</h5>
            <p class="card-text text-muted">{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
          </div>
          <div class="card-footer bg-transparent">
            <a href="{{ post.url | relative_url }}" class="btn btn-primary btn-sm">Read More →</a>
          </div>
        </div>
      </div>
      {% endfor %}
    </div>
  </div>
</section>
