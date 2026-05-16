---
layout: page
title: About Us
permalink: /about/
---

<div class="about-hero">

  <div class="about-left">
    <span class="about-tag">Independent Marine Protected Animals Community</span>

    <h1>IMPACT</h1>

    <p>
      A student community from Marine Science, Universitas Padjadjaran,
      focused on marine conservation, endangered species, and ocean awareness.
    </p>

    <div class="about-motto">
      <em>“It’s a blue hope.”</em>
    </div>
  </div>

  <div class="about-right">
    <div class="about-box">
      <h3>Research</h3>
      <p>
        Encouraging scientific exploration and marine conservation studies.
      </p>
    </div>

    <div class="about-box">
      <h3>Education</h3>
      <p>
        Creating collaborative spaces for learning, discussion, and growth.
      </p>
    </div>

    <div class="about-box">
      <h3>Awareness</h3>
      <p>
        Raising public awareness through campaigns and environmental action.
      </p>
    </div>
  </div>

</div>

<div class="quote-section">
  <p>
    “The sea, once it casts its spell, holds one in its net of wonder forever.”
  </p>

  <span>— Jacques Yves Cousteau</span>
</div>

<style>
.about-hero {
  display: grid;
  grid-template-columns: 1.1fr 1fr;
  gap: 2rem;
  align-items: center;
  margin-top: 2rem;
}

.about-left {
  padding-right: 1rem;
}

.about-tag {
  display: inline-block;
  font-size: 0.8rem;
  letter-spacing: 1px;
  text-transform: uppercase;
  color: #75C5F0;
  margin-bottom: 1rem;
}

.about-left h1 {
  font-size: 4rem;
  color: #1a3a4a;
  margin-bottom: 1rem;
  line-height: 1;
}

.about-left p {
  color: #4f6672;
  line-height: 1.8;
  font-size: 1rem;
  max-width: 520px;
}

.about-motto {
  margin-top: 1.5rem;
  color: #75C5F0;
  font-size: 1rem;
  letter-spacing: 0.5px;
}

.about-right {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.about-box {
  background: #f7fbfe;
  border: 1px solid #dceef8;
  border-radius: 16px;
  padding: 1.4rem;
  transition: all 0.3s ease;
}

.about-box:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 18px rgba(0,0,0,0.05);
}

.about-box h3 {
  margin-bottom: 0.5rem;
  color: #1a3a4a;
}

.about-box p {
  margin: 0;
  color: #58707c;
  line-height: 1.7;
  font-size: 0.95rem;
}

.quote-section {
  margin-top: 3rem;
  padding-top: 1.5rem;
  border-top: 1px solid #e5eef3;
  text-align: center;
}

.quote-section p {
  font-style: italic;
  color: #1a3a4a;
  font-size: 1.05rem;
  margin-bottom: 0.5rem;
}

.quote-section span {
  color: #75C5F0;
  font-size: 0.9rem;
}

@media screen and (max-width: 768px) {
  .about-hero {
    grid-template-columns: 1fr;
  }

  .about-left h1 {
    font-size: 3rem;
  }
}
</style>