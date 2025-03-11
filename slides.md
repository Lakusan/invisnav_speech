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
title: AboutMe
layout: iframe
url: https://lakusan.github.io/portfolio/
zoom: 0.68
---

---
title: Problems
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
<div class="w-full h-5 relative bottom-[-40px] flex justify-end">
  
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
<div class="w-full h-5 relative bottom-[-10px] flex justify-end">
  
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
<div class="w-full h-5 relative bottom-[-10px] flex justify-end">
  
  <SlideCurrentNo/>/<SlidesTotal class="text-neutral-400"/>
</div>

---
title: App Scan Showcase
layout: default
---

<script setup>
import { ref } from 'vue';

// Create a reactive variable for the active button
const activeContent = ref(1);

// Function to set active content
const showContent = (buttonNumber) => {
  activeContent.value = buttonNumber;
};
</script>
<div class="grid relative top-[-30px]">
  <!-- Buttons -->
  <div class="space-x-4">
    <button @click="showContent(1)" class="px-4 bg-slate-800 text-white rounded-5px">Mapping</button>
    <button @click="showContent(2)" class="px-4 bg-slate-800 text-white rounded-5px">Tiles</button>
    <button @click="showContent(3)" class="px-4 bg-slate-800 text-white rounded-5px">Anchors</button>
  </div>
</div>

<!-- Dynamic Content -->
<div class="grid grid-cols-[70%_30%]">
  <!-- Left Column -->
  <div>
    <!-- Active Content MAP -->
    <div v-if="activeContent === 1" class="p-4 flex h-full">
      <div class="grid h-full w-full grid-rows-2">
    <div>
        <ul class="space-y-2">
            <li class="text-2xl">Scan (gelb), wird zu Map (blau) validiert</li>
            <li class="text-2xl">Tiles (lila) NavMesh (grün)</li>
          </ul>
          <img src="/map_segments.png" alt="map img" class="pt-3 object-contain">
    </div>
  </div>
    </div>
    <!-- Active Content TILE -->
<div v-if="activeContent === 2" class="p-4 flex h-full">
  <div class="flex flex-col h-full w-full">
    <ul class="space-y-2 text-left">
      <li class="text-2xl">Prüfen sie auf einem Mapsegement liegen</li>
      <li class="text-2xl">Prüfen auf nachbarn -> Nein -> Zellteilung</li>
    </ul>
    <div class="flex justify-center pt-8">
      <img src="/tiles.png" alt="tiles img" class="w-72 object-contain">
    </div>
  </div>
</div>
    <!-- Active Content ANCHROS -->
  <div v-if="activeContent === 3" class="p-4 flex h-full">
  <div class="flex flex-col h-full w-full">
    <ul class="space-y-2 text-left">
      <li class="text-1xl">Rytrace settzt Anchor</li>
      <li class="text-1xl">Anchor sucht MapComponent und registerit sich </li>
      <li class="text-1xl">Camera nutzt tracker, der Pfad zum Anchor geniert</li>
      <li class="text-1xl">Wenn der Pfad gültig ist, fügt sich Anchor der Karte hinzu</li>
    </ul>
    <div class="flex justify-center pt-8">
      <img src="/anchor.png" alt="Anchor img" class="object-contain">
    </div>
  </div>
</div>
  </div>
  <!-- Right Column: Video -->
  <div class="h-480px">
    <video class="styled-video" controls>
      <source src="/scan.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
  </div>
</div>

<style>
  .styled-video {
    width: 100%; 
    max-width: 300px; 
    height: 100%;
    max-height: 900px; 
  }
</style>
 
---
layout: default
title: App Navigation Showcase
---



<!-- Dynamic Content -->
<div class="grid grid-cols-[70%_30%] h-full">
  <!-- Left Column -->
  <div class="flex items-center h-full">
    <ul class="space-y-2">
      <li class="text-2xl">IMU: GPS, Magnetometer Daten werden zur Ausrichtung genutzt</li>
      <li class="text-2xl">Karte wird aus DB geladen und rekonstruiert</li>
      <li class="text-2xl">Anchors werden mit Content gerendert</li>
      <li class="text-2xl">Navigationsziele können verfolgt werden</li>
    </ul>
  </div>

  <!-- Right Column: Video -->
  <div class="h-480px">
    <video class="styled-video" controls>
      <source src="/navigate.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
  </div>
</div>


<style>
  .styled-video {
    width: 100%; 
    max-width: 300px; 
    height: 100%;
    max-height: 900px; 
  }
</style>


---
layout: default
title: Ausblick
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
Auslick
</div>

<div class="flex h-380px w-850px quote-box">
<ul class="space-y-4 pt-5">
<li class="text-2xl">Leitsystem für visuell eingeschränkte Personen </li>
<li class="text-2xl">Kombiniert mit Objekterkennung topologische Kartengenerierung und Raumkathegorisierung</li>
<li class="text-2xl">Kariterung öffentlicher Einrichtungen</li>
<li class="text-2xl">Kariterung temorärer Einrichtungen</li>
<li class="text-2xl">Kombiniert mit GPS-Navigation Navitgation bis zum Büro</li>
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

---
layout: end
title: Ende
---

<div class="text-amber-400 text-4xl mb-10">
  Präsentation & Kontakt
</div>

<div class="p-4 flex h-full">
  <!-- Two Columns -->
  <div class="items-center h-full w-full">
    <!-- Left Column: Image -->
    <div class="flex justify-center mb-3">
      <img src="/qr_code.png" alt="MAP" class="w-72 object-contain">
    </div>
      Andreas@Lakus@googlemail.com
  </div>
</div>


<div class="w-full h-5 relative bottom-[10px] flex justify-center">
  <PoweredBySlidev mt-10 />
</div>

