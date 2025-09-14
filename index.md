---
title: "Welcome to 🏦The Urogyn Vault!"
layout: splash
permalink: /
header:
  overlay_color: "#111111"
  overlay_filter: "0.4"
excerpt: "A curated vault all about Urogynecology - for students, residents, fellows and lifelong learners."
---
# About
- Inspired by Dr Jocelyn Fitzgerald's [Landmark Urogyn Trials List](https://landmark-urogyn-trials.glide.page/).
- Concise, evidence-based notes designed for a quick review before clinic, the OR, or teaching each other.

---

## Urogyn Landmark Trials
Dr. Fitzgerald's [Landmark Urogyn Trials List](https://landmark-urogyn-trials.glide.page/)
- [**ABC Trial**](abc.md) – Sling vs Burch for stress incontinence  
- [**ATLAS Trial**](atlas.md) – Behavioral therapy vs surgery outcomes  
- [**OPTIMAL Trial**](optimal.md) – Apical suspension techniques  

---
## Urogyn Dot phrases for EMR (Designed for Epic)
Concise, de-cluttered Urogyn dot phrases to reclaim your time for better patient care.
- [**New & Return Patient H&P**]() - New Patient
- [**Pessary fitting/maintenance**]() - Pessary fitting/maintenance
- [**Post-op Visit**]() - Post-op visit
- [**Common Telephone/MyCharts**]() - Common Telephone/MyCharts

---

<!-- 🌓 Dark/Light mode toggle -->
<script>
document.addEventListener("DOMContentLoaded", function(){
  const btn = document.createElement("div");
  btn.innerText = "🌓";
  btn.className = "mode-toggle";
  btn.onclick = () => document.body.classList.toggle("dark-mode");
  document.body.appendChild(btn);
});
</script>

<style>
/* Toggle button */
.mode-toggle {
  position: fixed;
  top: 1rem;
  right: 1rem;
  background: #000000;
  color: white;
  padding: 0.4rem 0.8rem;
  border-radius: 6px;
  cursor: pointer;
  font-size: 1.2rem;
  z-index: 9999;
  user-select: none;
  
  /* Default Light Mode highlight */
::selection {
  background: #ffffff;
  color: #f7f7e9;
}

/* Dark Mode highlight override */
body.dark-mode ::selection {
  background: #ffffff;
  color: #111111;
}
}

/* Default Light Mode */
body {
  background: #ffffff;
  color: #111111;
}

/* Dark Mode */
body.dark-mode {
  background: #111111;
  color: #f4f4f4;
}
</style>
