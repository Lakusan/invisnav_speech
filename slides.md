---
theme: seriph
title: Welcome 
info: |
  ## Slides of Speech on 12th March 2025 @ XR-Symposium SRH University Heidelberg
  Learn more about me at [AboutMe](https://lakusan.github.io/portfolio/)
drawings:
  persist: false
transition: slide-left
mdc: true
---

<!-- Hero -->
<div class="items-center relative top-[-40px]">
  <p>
    XR-Syposium 12.03.2025 
    <img src="/SRH_Logo_sRGB_Orange_150dpi.png" alt="Image Description" class="inline w-6 h-5 pb-1">
    Universiy Heidelberg von Andreas Lakus
  </p>
</div>
<img src="/hero.png" alt="Rounded Hero Image" class="rounded-full w-48 h-48 shadow-lg bg-slate-800 border-5 border-amber-400 shadow-4xl relative top-[+50px]">
<img src="/map.png" alt="Rounded Hero Image" class="w-200 h-120 relative bottom-[200px] left-[60px]">
<div class="mb-4 absolute bottom-4 left-12">
  <span class="text-3xl text-primary-lighter text-opacity-80 text-left" style="font-weight:500;">
    Effiziente räumliche Rekonstruktion und XR-gestützte Navigation
  </span>
  <div class="text-6xl text-white text-opacity-80 text-left" style="font-weight:600;">
    mit ARCore und Unity Engine
  </div>
  </div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: iframe
url: https://lakusan.github.io/portfolio/
zoom: 0.68
---

---
transition: slide-left
layout: default
---

<!-- HEADER -->
<div class="grid grid-cols-3 w-full h-10 relative top-[-40px]">
  <div class="flex items-center">
      <img src="/hero.png" class="h5 mr-1"/>
    <p class="text-xs text-neutral-400">
      Andreas.Lakus@googlemail.com
    </p>
  </div>
  <div class="text-center text-xs text-neutral-400 col-start-2 row-start-1 h-full flex items-center justify-center">
    12.03.2025
  </div>
  <div  class="flex justify-end items-center">
  <img src="/SRH_Logo_sRGB_Orange_150dpi.png" alt="Image Description" class="h-5">
  </div> 
</div>
<!-- HEADER END  -->

<!-- CONTENT -->
<div class="text-amber-400 text-4xl mb-1">
Navigationsprobleme
</div>

<img src="/comparison_gps_indoor.png"/>

  <div class="h-20" grid="~ cols-2 gap-2" m="t-2">
  <div class="text-2xl">
    <ul>
      <li>Signalabhängig</li>
    </ul>
  </div>
  <div class="text-2xl">
    <ul>
      <li>Integriert in Infrastruktur</li>
      <li>Hohe Kosten</li>
      <li>Time to Market lang</li>
    </ul>
  </div>
</div>


<!-- FOOTER -->
<div class="w-full h-5 relative bottom-[-30px] flex justify-end">
  
  <SlideCurrentNo/>/<SlidesTotal class="text-neutral-400"/>
</div>
---
title: Anforderungen
layout: default
transition: slide-left
---

<!-- HEADER -->
<div class="grid grid-cols-3 w-full h-10 relative top-[-40px]">
  <div class="flex items-center">
      <img src="/hero.png" class="h5 mr-1"/>
    <p class="text-xs text-neutral-400">
      Andreas.Lakus@googlemail.com
    </p>
  </div>
  <div class="text-center text-xs text-neutral-400 col-start-2 row-start-1 h-full flex items-center justify-center">
    12.03.2025
  </div>
  <div  class="flex justify-end items-center">

  <img src="/SRH_Logo_sRGB_Orange_150dpi.png" alt="Image Description" class="h-5">
  </div> 
</div>
<!-- HEADER END  -->

<div class="text-amber-400 text-4xl mb-1">
Anforderungen
</div>


<div class="flex h-380px w-850px quote-box">
<ul class="space-y-4 pt-5">
<li class="text-2xl">📲 Mobil: Cross-Platform mobile App </li>
<li class="text-2xl">👷 Infrastruktur - Keine Itegration eines Leitsystems</li>
<li class="text-2xl">🗂️ Souverän - Minimalistisches Datenmodell in In-Memory-DB</li>
<li class="text-2xl">🛠 Anpassbar und Modular - Seperation of Concerns und Objektbasiert</li>
<li class="text-2xl">🛡️ Datenschutz - Minimalistische Datenspeicherung</li>
</ul>
</div>

<style>
  .quote-box {
    background-color: #1B1B1B;
    color: white;
    font-size: 1.25rem;
    padding: 1rem 1.5rem;
    border-radius: 5px;
    box-shadow: 3px 3px 8px rgba(238, 223, 223, 0.1), inset 1px 1px 5px rgba(48, 47, 47, 0.3);
    text-align: start;
    margin: 1rem auto;
  }
</style>


<!-- FOOTER -->
<div class="w-full h-5 relative bottom-[10px] flex justify-end">
  
  <SlideCurrentNo/>/<SlidesTotal class="text-neutral-400"/>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
title: uc_scan
transition: slide-left
---

<!-- HEADER -->
<div class="grid grid-cols-3 w-full h-10 relative top-[-40px]">
  <div class="flex items-center">
      <img src="/hero.png" class="h5 mr-1"/>
    <p class="text-xs text-neutral-400">
      Andreas.Lakus@googlemail.com
    </p>
  </div>
  <div class="text-center text-xs text-neutral-400 col-start-2 row-start-1 h-full flex items-center justify-center">
    12.03.2025
  </div>
  <div  class="flex justify-end items-center">

  <img src="/SRH_Logo_sRGB_Orange_150dpi.png" alt="Image Description" class="h-5">
  </div> 
</div>
<!-- HEADER END  -->

<div class="text-amber-400 text-4xl mb-1">
  Anwendungsfall: Scan
</div>


<div class="flex h-380px w-850px items-center">
  <img src="/uc_scan.png"/>
</div>




<!-- FOOTER -->
<div class="w-full h-5 relative bottom-[10px] flex justify-end">
  
  <SlideCurrentNo/>/<SlidesTotal class="text-neutral-400"/>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
title: uc_nav
transition: slide-left
---

<!-- HEADER -->
<div class="grid grid-cols-3 w-full h-10 relative top-[-40px]">
  <div class="flex items-center">
      <img src="/hero.png" class="h5 mr-1"/>
    <p class="text-xs text-neutral-400">
      Andreas.Lakus@googlemail.com
    </p>
  </div>
  <div class="text-center text-xs text-neutral-400 col-start-2 row-start-1 h-full flex items-center justify-center">
    12.03.2025
  </div>
  <div  class="flex justify-end items-center">

  <img src="/SRH_Logo_sRGB_Orange_150dpi.png" alt="Image Description" class="h-5">
  </div> 
</div>
<!-- HEADER END  -->

<div class="text-amber-400 text-4xl mb-1">
  Anwendungsfall: Navigation
</div>


<div class="flex h-380px w-850px items-center">
  <img src="/uc_nav.png"/>
</div>



<!-- FOOTER -->
<div class="w-full h-5 relative bottom-[10px] flex justify-end">
  
  <SlideCurrentNo/>/<SlidesTotal class="text-neutral-400"/>
</div>

---
layout: end
---

<div class="text-amber-400 text-4xl mb-10">
  Präsentation & Kontakt
</div>

<div class="flex h-380px w-850px items-center justify-center">
  <img src="/qr_code.png" class="border-4 border-amber-400 shadow-[0px_0px_10px_rgba(251,191,36,0.8)] max-h-full max-w-full object-contain"/>
  </div>


<div class="w-full h-5 relative bottom-[10px] flex justify-center">
  <PoweredBySlidev mt-10 />
</div>
