---
title: "📚 Publications & Research"
date: 2025-09-14
draft: false
---

<!-- 引入自定义 CSS（PaperMod 会自动载入 extended/ 下文件） -->
<link rel="stylesheet" href="/css/extended/publications.css">

<div class="page-intro">
  <p>
    Selected publications, conference presentations, and posters.<br>
    My research focuses on <b>cognitive aging</b>, <b>cross-cultural measurement</b>, and <b>statistical modeling</b>.
  </p>
</div>

---

## 📰 Peer-Reviewed Publication
<div class="pub-grid">
  <div class="pub-card">
    <b>Selig, T.</b>, <b>Kang, Y.</b>, <b>Yang, G.</b>, <b>Zhang, Y.</b>, & <b>Zhu, H.</b> (2024).  
    <i>On friendship and cyclic parking functions.</i>  
    <em>Enumerative Combinatorics and Applications</em>, 4(3), S2R21.  
    <a href="https://doi.org/10.54550/ECA2024V4S3R21" target="_blank">DOI</a>
  </div>
</div>

<hr class="section-divider">

## 🎤 Conference Abstracts & Presentations
<div class="pub-list">

  <div class="pub-card">
    <b>Yang, G.</b>, Ghimire, D., Dhakal, U., Bogati, U., Sapkota, H., Shrestha, L., Pandit, P., Jalan, P., Mendes de Leon, C., & Brice&#241;o, E. M.  
    <i>Adaptation of a Visuospatial Construction and Visual Memory Test for an Educationally Diverse Older Adult Population in Nepal.</i>  
    <em>International Neuropsychological Society (INS) 54th Annual North American Meeting, Philadelphia, Feb 2026.</em>  
    (First Author, Abstract under review)
  </div>

  <div class="pub-card">
    <b>Brice&#241;o, E. M.</b>, <b>Yang, G.</b>, Bogati, U., Jalan, P., Shrestha, L., Dhakal, U., Sapkota, H., Rai, J., Pandit, P., Mendes de Leon, C., & Ghimire, D.  
    <i>Development of a Cognitive Screening Test for Educationally Diverse Older Adults in Nepal.</i>  
    <em>International Neuropsychological Society (INS) 2026 Annual Meeting.</em>  
    (Co-author, Abstract under review)
  </div>

</div>

<hr class="section-divider">

## 🧠 Posters
<div class="pub-grid">

  <div class="pub-card">
    <b>Yang, G.</b> (presenter), with the Nepal HCAP research team.  
    <i>Nepal Harmonized Cognitive Assessment Protocol (HCAP): Cognitive Assessment Adaptation.</i>  
    <em>Center for Global Health Equity (CGHE), University of Michigan, 2025.</em>  
    <br><br>
    <a href="/images/CGHE_Poster.png" target="_blank">
      <img src="/images/CGHE_Poster.png" alt="CGHE Poster" class="poster-thumb">
    </a>
  </div>

  <div class="pub-card">
    <b>Yang, G.</b>  
    <i>Parking Functions and Graph Theory: From Algorithms to Simulations.</i>  
    <em>SURF 2023, Xi’an Jiaotong–Liverpool University.</em>  
    <br><br>
    <a href="/images/SURF-2023-0167.jpg" target="_blank">
      <img src="/images/SURF-2023-0167.jpg" alt="SURF Poster" class="poster-thumb">
    </a>
  </div>

</div>

<hr class="section-divider">

## 🧩 In Preparation
<div id="inprep" class="pub-grid">

  <div class="pub-card">
    <b>Yang, G.</b>, Ghimire, D., Dhakal, U., Bogati, U., Sapkota, H., Shrestha, L., Pandit, P., Jalan, P., Mendes de Leon, C., & Brice&#241;o, E. M.  
    <i>Tentative title:</i> *Adaptation of a Visuospatial Construction and Visual Memory Test for an Educationally Diverse Older Adult Population in Nepal.*
  </div>

  <div class="pub-card">
    Brice&#241;o, E. M., <b>Yang, G.</b>, Bogati, U., Jalan, P., Shrestha, L., Dhakal, U., Sapkota, H., Rai, J., Pandit, P., Mendes de Leon, C., & Ghimire, D.  
    <i>Tentative title:</i> *Development of a Cognitive Screening Test for Educationally Diverse Older Adults in Nepal.*
  </div>

  <div class="pub-card">
    Jeon, S., Kunicki, Z., Kamalyan, L., Prieto, S., <b>Yang, G.</b>, Snider, M., Marshall, L. W., Saenz, J., Mejia Arango, S., Wong, R., Arce Rentería, M., & Brice&#241;o, E. M.  
    <i>Tentative title:</i> *Longitudinal Measurement Invariance of the Harmonized Cognitive Assessment Protocol in the Mexican Cognitive Aging Ancillary Study (Mex-Cog).*
  </div>

  <div class="pub-card">
    Snider, M., Kunicki, Z., Jeon, S., Kamalyan, L., Marshall, L., Prieto, S., Rich, A., <b>Yang, G.</b>, Brice&#241;o, E. M., & Arce Rentería, M.  
    <i>Tentative title:</i> *Cross-national comparison of hospitalization on cognition.*
  </div>

</div>

<div style="text-align:center;margin-top:1em;">
  <button id="toggleBtn">Show more ▼</button>
</div>

<script>
const cards = document.querySelectorAll('#inprep .pub-card');
const btn = document.getElementById('toggleBtn');
let expanded = false;

if (cards.length > 2) {
  for (let i = 2; i < cards.length; i++) cards[i].style.display = 'none';
}

btn.onclick = () => {
  expanded = !expanded;
  for (let i = 2; i < cards.length; i++) {
    cards[i].style.display = expanded ? 'block' : 'none';
    cards[i].style.opacity = expanded ? 1 : 0;
    cards[i].style.transition = 'opacity .4s ease';
  }
  btn.textContent = expanded ? 'Show less ▲' : 'Show more ▼';
};
</script>

<div class="footer-quote">
  “Bringing clarity through data — and empathy through research.”
</div>
