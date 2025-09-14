---
title: "The Urogyn Vault"
layout: splash
permalink: /
header:
  overlay_color: "#2a2a2a"
  overlay_filter: "0.4"
  actions:
    - label: "Start Reading"
      url: "#trials"
excerpt: "Urogynecology Landmark Trials — concise, physician-level summaries."
---
# About
A curated vault all about Urogynecology - for students, residents, fellows and lifelong learners.
- Inspired by Dr Jocelyn Fitzgerald's [Landmark Urogyn Trials](https://landmark-urogyn-trials.glide.page/)
- Concise, evidence-based notes designed for a quick review before clinic or the OR.
- Optimized for board prep and teaching. 
---

## Urogyn Landmark Trials (curated from Dr.Fitzgerald's list)
- [**ABC Trial**](abc.md) – Sling vs Burch for stress incontinence  
- [**ATLAS Trial**](atlas.md) – Behavioral therapy vs surgery outcomes  
- [**OPTIMAL Trial**](optimal.md) – Apical suspension techniques  


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
  background: #444;
  color: white;
  padding: 0.4rem 0.8rem;
  border-radius: 6px;
  cursor: pointer;
  font-size: 1.2rem;
  z-index: 9999;
  user-select: none;
  /* Default Light Mode highlight */
::selection {
  background: #111111;
  color: #ffffff;
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
