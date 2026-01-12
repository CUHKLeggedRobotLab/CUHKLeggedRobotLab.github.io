---
layout: splash
classes:
  - landing
  - dark-theme
title: "Join"
permalink: /join/
---

<br>

<!-- ===================== Page-local styles ===================== -->
<style>
/* Heading sizes */
.page__content h1 { font-size: 30px; }
.page__content h2 { font-size: 24px; }

/* ===== REMOVE heading underline ONLY on Join page ===== */
.page__content h1,
.page__content h2,
.page__content h3 {
  border-bottom: none !important;
  padding-bottom: 0 !important;
}

/* ===== Contact section ===== */
.page__content .contact-section{
  margin: 18px 0 36px 0;
}

.page__content .contact-card{
  display: grid;
  grid-template-columns: 360px 1fr;
  gap: 20px;
  align-items: start;
  background: rgba(255,255,255,0.03);
  border: 1px solid rgba(255,255,255,0.12);
  border-radius: 14px;
  padding: 20px;
}

.page__content .contact-info{
  display: grid;
  gap: 16px;
}

.page__content .contact-row{
  display: grid;
  grid-template-columns: 34px 1fr;
  gap: 12px;
  align-items: start;
}

.page__content .contact-icon{
  width: 34px;
  height: 34px;
  display: grid;
  place-items: center;
  border-radius: 10px;
  background: rgba(255,255,255,0.06);
  border: 1px solid rgba(255,255,255,0.10);
  font-size: 16px;
}

.page__content .contact-text{
  font-size: 13.5pt;
  line-height: 1.4;
}

.page__content .contact-text a{
  text-decoration: none;
  border-bottom: 1px solid rgba(255,255,255,0.35);
}
.page__content .contact-text a:hover{
  border-bottom-color: rgba(255,255,255,0.85);
}

/* Map */
.page__content #join-map{
  width: 100%;
  height: 320px;
  border-radius: 14px;
  border: 1px solid rgba(255,255,255,0.12);
  overflow: hidden;
}

/* Responsive */
@media (max-width: 900px){
  .page__content .contact-card{
    grid-template-columns: 1fr;
  }
  .page__content #join-map{
    height: 280px;
  }
}
</style>

# Contact & Location

<div class="contact-section">
  <div class="contact-card">

    <!-- Left: contact info -->
    <div class="contact-info">
      <div class="contact-row">
        <div class="contact-icon">✉️</div>
        <div class="contact-text">
          <a href="mailto:cuhksiriusteamlegged@gmail.com">
            cuhksiriusteamlegged@gmail.com
          </a>
        </div>
      </div>

      <div class="contact-row">
        <div class="contact-icon">📍</div>
        <div class="contact-text">
          Sha Tin, Hong Kong, HK
        </div>
      </div>

      <div class="contact-row">
        <div class="contact-icon">🏢</div>
        <div class="contact-text">
          ERB 106, CUHK
        </div>
      </div>

      <div class="contact-row">
        <div class="contact-icon">🕒</div>
        <div class="contact-text">
          Weekdays 10:00 – 00:00
        </div>
      </div>
    </div>

    <!-- Right: map -->
    <div>
      <div id="join-map"></div>

      <!-- Leaflet -->
      <link
        rel="stylesheet"
        href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css"
        crossorigin=""
      />
      <script
        src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"
        crossorigin=""
      ></script>
      <script>
        (function () {
          const lat = 22.4197;
          const lng = 114.2068;
          const map = L.map("join-map").setView([lat, lng], 15);
          L.tileLayer("https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png", {
            maxZoom: 19,
            attribution: '&copy; OpenStreetMap'
          }).addTo(map);
          L.marker([lat, lng]).addTo(map)
            .bindPopup("<b>CUHK Legged Robot Lab</b><br>ERB 106<br>CUHK")
            .openPopup();
        })();
      </script>
    </div>

  </div>
</div>

---

# Prospective Ph.D. Students

<p style="font-size:13.5pt;">
We recruit Ph.D. students annually, subject to the availability of positions and funding.
We seek highly motivated applicants who are interested in, or have prior experience in,
one or more of the following research areas:
</p>

<ul style="font-size:13.5pt;">
  <li><b>Robust and Precise Locomotion for Legged Robots</b></li>
  <li><b>Environment-aware Perception and Navigation</b></li>
  <li><b>Dexterous and Whole-Body Coordinated Loco-Manipulation</b></li>
  <li><b>Safe Actuator and Mechanical System Design</b></li>
  <li><b>Reinforcement Learning and Imitation Learning</b></li>
</ul>

<p style="font-size:13.5pt;">
Please refer to our ongoing research projects for more details on the research directions
and methodologies.
</p>

## Ph.D. Openings for Fall 2027

<p style="font-size:13.5pt;">
For <b>Fall 2027</b>, we have Ph.D. openings in the following research areas:
</p>

<ul style="font-size:13.5pt;">
  <li><b>Robust and Precise Locomotion for Legged Robots</b></li>
  <li><b>Environment-aware Perception and Navigation</b></li>
  <li><b>Dexterous and Whole-Body Coordinated Loco-Manipulation</b></li>
</ul>

## Notes

<ul style="font-size:13.5pt;">
  <li>The official Ph.D. application deadline in Hong Kong is <b>December 1st</b> each year.</li>
  <li>We strongly recommend prospective applicants contact us before <b>September 1st</b>.</li>
  <li>The best time to reach out is between <b>January 1st and September 1st</b> each year.</li>
</ul>

---

# Prospective Research Assistants (RAs)

<p style="font-size:13.5pt;">
We continuously offer a large number of Research Assistant (RA) positions to support our
long-term research and system development efforts.
</p>

<p style="font-size:13.5pt;">
Applicants are expected to have experience in <b>at least two</b> of the following areas:
</p>

<ul style="font-size:13.5pt;">
  <li>Reinforcement learning for legged robots</li>
  <li>Sim-to-real transfer for robotic systems</li>
  <li>Perception algorithms using LiDAR or depth cameras</li>
  <li>Motor control and low-level actuator control</li>
  <li>Robot SLAM and motion planning</li>
  <li>Impedance control for manipulators</li>
</ul>

<p style="font-size:13.5pt;">
Successful candidates will have opportunities to work closely with real robotic platforms
and contribute to cutting-edge research on <b>locomotion, navigation, and
loco-manipulation</b>.
</p>

---

# How to Apply

<div class="join-section">
<p>
Please send the following materials via email:
</p>

<ul class="join-list">
  <li>Curriculum Vitae (CV)</li>
  <li>Brief statement of research interests</li>
  <li>Transcript (for Ph.D. applicants)</li>
  <li>Representative publications or projects (if available)</li>
  <li>GitHub link or other relevant project materials (optional but encouraged)</li>
</ul>

<p>
Email subject format:
<span class="highlight">[Application] Position – Your Name</span>
</p>
</div>
