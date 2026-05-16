---
layout: page
title: Artikel
permalink: /artikel/
---

## Publikasi & Artikel IMPACT

Kumpulan tulisan, hasil riset, dan publikasi dari anggota IMPACT seputar konservasi biota laut.

---

{% for post in site.posts %}
<div class="artikel-card">
  <span class="artikel-date">{{ post.date | date: "%d %B %Y" }}</span>
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
  <span class="artikel-tag">{{ post.categories | join: ", " }}</span>
</div>
{% endfor %}

<style>
.artikel-card {
  border-left: 4px solid #75C5F0;
  padding: 1rem 1.2rem;
  margin-bottom: 1.5rem;
  background: #f0f9ff;
  border-radius: 0 8px 8px 0;
}
.artikel-card h3 { margin: 0.3rem 0; font-size: 1.1rem; }
.artikel-card h3 a { color: #1a3a4a; text-decoration: none; }
.artikel-card h3 a:hover { color: #75C5F0; }
.artikel-date { font-size: 0.8rem; color: #888; }
.artikel-tag {
  display: inline-block;
  margin-top: 0.5rem;
  background: #75C5F0;
  color: white;
  font-size: 0.75rem;
  padding: 2px 8px;
  border-radius: 20px;
}
</style>