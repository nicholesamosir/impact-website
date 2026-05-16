---
layout: page
title: Contact
permalink: /contact/
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

## Contact Us

Interested in learning more about IMPACT, collaborating with us, or getting in touch? Feel free to reach out, we would be glad to connect with you.

---

<div class="kontak-wrapper">

  <div class="kontak-info">
    <h3>Contact Information</h3>

    <div class="kontak-item">
      <span class="kontak-icon">
        <i class="fa-solid fa-envelope"></i>
      </span>
      <a href="mailto:contact.impact.id@gmail.com">
        contact.impact.id@gmail.com
      </a>
    </div>

    <div class="kontak-item">
      <span class="kontak-icon">
        <i class="fa-brands fa-instagram"></i>
      </span>
      <a href="https://instagram.com/impact.unpad" target="_blank">
        @impact.unpad
      </a>
    </div>

    <div class="kontak-item">
      <span class="kontak-icon">
        <i class="fa-brands fa-x-twitter"></i>
      </span>
      <a href="https://twitter.com/impactunpad" target="_blank">
        @impactunpad
      </a>
    </div>
  </div>

  <div class="kontak-form">
    <h3>Send Messages</h3>

    <form action="https://formspree.io/f/xpqnazre" method="POST">

      <div class="form-group">
        <label for="name">Name</label>
        <input type="text" id="name" name="name" placeholder="Your name" required>
      </div>

      <div class="form-group">
        <label for="email">Email</label>
        <input type="email" id="email" name="email" placeholder="email@gmail.com" required>
      </div>

      <div class="form-group">
        <label for="message">Message</label>
        <textarea id="message" name="message" rows="5" placeholder="Write ur messages..." required></textarea>
      </div>

      <button type="submit">Kirim Pesan</button>

    </form>
  </div>

</div>

<style>
.kontak-wrapper {
  display: flex;
  gap: 3rem;
  margin-top: 1.5rem;
  flex-wrap: wrap;
}

.kontak-info {
  flex: 1;
  min-width: 220px;
}

.kontak-info h3,
.kontak-form h3 {
  color: #1a3a4a;
  margin-bottom: 1.2rem;
}

.kontak-item {
  display: flex;
  align-items: center;
  gap: 0.8rem;
  margin-bottom: 1rem;
  font-size: 0.95rem;
}

.kontak-icon {
  font-size: 1.1rem;
  color: #75C5F0;
  width: 20px;
  text-align: center;
}

.kontak-item a {
  color: #1a3a4a;
  text-decoration: none;
  transition: color 0.3s ease;
}

.kontak-item a:hover {
  color: #75C5F0;
}

.kontak-form {
  flex: 2;
  min-width: 280px;
}

.form-group {
  margin-bottom: 1rem;
}

.form-group label {
  display: block;
  font-size: 0.85rem;
  font-weight: 600;
  color: #1a3a4a;
  margin-bottom: 0.3rem;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 10px 12px;
  border: 1px solid #75C5F0;
  border-radius: 6px;
  font-family: 'Inter', sans-serif;
  font-size: 0.9rem;
  color: #1a3a4a;
  box-sizing: border-box;
}

.form-group input:focus,
.form-group textarea:focus {
  outline: none;
  border-color: #1a3a4a;
}

button[type="submit"] {
  background: #75C5F0;
  color: white;
  border: none;
  padding: 12px 28px;
  border-radius: 6px;
  font-family: 'Archivo Black', sans-serif;
  font-size: 0.95rem;
  cursor: pointer;
  transition: background 0.3s ease;
}

button[type="submit"]:hover {
  background: #1a3a4a;
}
</style>