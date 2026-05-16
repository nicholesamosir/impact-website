---
layout: page
title: Kegiatan
permalink: /kegiatan/
---

<div class="pillar-section">

  <div class="pillar-tabs">
    <button class="pillar-tab active" data-target="rd">Research & Development</button>
    <button class="pillar-tab" data-target="et">Education & Training</button>
    <button class="pillar-tab" data-target="ac">Awareness & Campaign</button>
  </div>

  <div class="pillar-slider">
    <div class="pillar-slides">

      <div class="pillar-slide active" id="rd">
        <h2>Research and Development</h2>
        <div class="program-grid">
          <div class="program-card">
            <h3>SKOLA</h3>
            <p>Media diskusi antar pilar dalam mengkaji isu-isu kelautan. Hasilnya digunakan sebagai bahan publikasi IMPACTNEWS.</p>
          </div>
          <div class="program-card">
            <h3>IMPACT Pillarization</h3>
            <p>Program magang terhadap tiga pilar IMPACT untuk menyiapkan calon generasi yang berorientasi pada ilmu pengetahuan dan berdampak.</p>
          </div>
        </div>
      </div>

      <div class="pillar-slide" id="et">
        <h2>Education and Training</h2>
        <div class="program-grid">
          <div class="program-card">
            <h3>Class of Cagen</h3>
            <p>Tahap awal bagi calon generasi IMPACT untuk mengenal komunitas dan memahami prinsip konservasi biota laut.</p>
          </div>
          <div class="program-card">
            <h3>IMPACTOR</h3>
            <p>Media edukasi dan adaptasi melalui keterlibatan langsung di lapangan, berfokus pada praktik konservasi biota laut.</p>
          </div>
          <div class="program-card">
            <h3>IMPACT Visit</h3>
            <p>Media edukasi dan kolaborasi dengan berbagai pihak untuk membangun kerja sama antarorganisasi di bidang konservasi.</p>
          </div>
        </div>
      </div>

      <div class="pillar-slide" id="ac">
        <h2>Awareness and Campaign</h2>
        <div class="program-grid">
          <div class="program-card">
            <h3>IMPACTNEWS</h3>
            <p>Media informasi bagi masyarakat mengenai upaya konservasi biota laut, mencakup publikasi dari setiap pilar.</p>
          </div>
          <div class="program-card">
            <h3>Seminar</h3>
            <p>Sarana pertukaran pengetahuan antara IMPACT, masyarakat, dan pakar konservasi untuk memperkuat kesadaran bersama.</p>
          </div>
          <div class="program-card">
            <h3>Ber-IMPACT</h3>
            <p>Aksi nyata IMPACT untuk menghadirkan manfaat bagi masyarakat sekaligus mendorong keterlibatan dalam konservasi.</p>
          </div>
        </div>
      </div>

    </div>
  </div>

</div>

<style>
.pillar-section { margin-top: 2rem; }

.pillar-tabs {
  display: flex;
  gap: 0;
  border-bottom: 3px solid #75C5F0;
}

.pillar-tab {
  flex: 1;
  padding: 14px 10px;
  background: #f0f9ff;
  border: none;
  border-bottom: none;
  font-family: 'Archivo Black', sans-serif;
  font-size: 0.85rem;
  color: #1a3a4a;
  cursor: pointer;
  transition: all 0.3s ease;
  clip-path: polygon(0 0, 92% 0, 100% 100%, 0% 100%);
  margin-right: -8px;
  position: relative;
  z-index: 0;
}

.pillar-tab:last-child {
  clip-path: polygon(0 0, 100% 0, 100% 100%, 8% 100%);
  margin-right: 0;
}

.pillar-tab:hover {
  background: #c8eaf8;
}

.pillar-tab.active {
  background: #75C5F0;
  color: white;
  z-index: 1;
}

.pillar-slider {
  overflow: hidden;
  max-width: 100%;
  border: 1px solid #75C5F0;
  border-top: none;
  border-radius: 0 0 10px 10px;
  background: white;
}

.pillar-slides {
  display: flex;
  transition: transform 0.4s cubic-bezier(0.4, 0, 0.2, 1);
  width: 300%;
}

.pillar-slide {
  width: 33.333%;
  min-width: 33.333%;
  padding: 2rem;
  flex-shrink: 0;
  box-sizing: border-box;
  overflow: hidden;
}

.pillar-slide h2 {
  color: #1a3a4a;
  margin-bottom: 1.5rem;
  font-size: 1.4rem;
}

.program-grid {
  display: flex;
  gap: 1rem;
  flex-direction: column;
}

.program-card {
  width: 100%;
  background: #f0f9ff;
  border-left: 4px solid #75C5F0;
  border-radius: 0 8px 8px 0;
  padding: 1.2rem;
}

.program-card h3 {
  font-size: 1rem;
  color: #75C5F0;
  margin-bottom: 0.5rem;
}

.program-card p {
  font-size: 0.9rem;
  color: #333;
  line-height: 1.6;
}
</style>

<script>
const tabs = document.querySelectorAll('.pillar-tab');
const slides = document.querySelector('.pillar-slides');

tabs.forEach((tab, index) => {
  tab.addEventListener('click', () => {
    tabs.forEach(t => t.classList.remove('active'));
    tab.classList.add('active');
    slides.style.transform = `translateX(-${index * 33.333}%)`;
  });
});
</script>