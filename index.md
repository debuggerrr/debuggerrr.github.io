---
layout: default
title: "Home"
---

<div class="home-grid">
  <div class="profile-card card">
    {% if site.static_files | where: "path", "/sid.png" %}
      <img src="/sid.png" alt="Sid" class="avatar">
    {% else %}
      <div class="avatar placeholder">S</div>
    {% endif %}
    <h2>Sid</h2>
    <p class="lead">Software engineer building reliable, scalable web apps.</p>
    <p><a class="btn" href="https://www.linkedin.com/in/sid1992/" target="_blank">LinkedIn</a></p>
  </div>

  <div>
    <section>
      <h3>Latest posts</h3>
      <ul>
        {% for post in site.posts limit:5 %}
          <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%b %-d, %Y" }}</small></li>
        {% else %}
          <li>No posts yet — create one in `_posts/`</li>
        {% endfor %}
      </ul>
    </section>

    <section>
      <h3>Projects</h3>
      <p>Replace these with your actual project links.</p>
      <ul>
        <li><a href="#">Project One</a></li>
        <li><a href="#">Project Two</a></li>
      </ul>
    </section>
  </div>
</div>
