---
theme: seriph
background: /images/background.jpg
class: text-center
highlighter: shikiji
lineNumbers: false
drawings:
  persist: false
transition: slide-left
title: Final Presentation
mdc: true
---

<h1>What I learned from my internship & life in Vietnam</h1>

<p class="pt-2">
    Presentation slides for Code Complete & FPT internship program
</p>

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="absolute bottom-0 right-0 mr-4 mb-4 flex items-center">
  <img class="w-8 h-8 rounded-full" src="/images/profile_icon.png">
  <p class="ml-2">Yuta Sugimine</p>
</div>

---
layout: default
---

# Table of contents

<br />

- **Introduce Myself**
- **Projects and Technical Sharing**
- **Life in Danang**
- **Activities**
- **Summary**


---
layout: image-right
image: /images/profile.png
---

# Introduce Myself

<br />

- **Name**: Yuta Sugimine
- **Age**: 21
- **Residence**: Tokyo
- **School**: Yokohama City University
- **Major**: Accounting
- **Hobby**: Football

---
class: p-0
---

<div class="flex text-center h-full">
  <div class="w-1/2 h-full overflow-hidden relative flex items-center justify-center" style="text-align: center;">
    <h2 class="font-bold z-10" style="color: white; font-size: 5rem;">Tokyo</h2>
    <img class="absolute top-0 left-0" src="/images/shibuya.jpg">
  </div>

  <div class="w-1/2 h-full overflow-hidden relative flex items-center justify-center" style="text-align: center;">
    <h2 class="font-bold z-10" style="color: white; font-size: 5rem;">Yokohama</h2>
    <img class="absolute top-0 bottom-1/2 left-0" src="/images/yokohama.jpg">
    <img class="absolute top-1/2 bottom-0 left-0" src="/images/yokohama-chaina.jpg">
  </div>
</div>


---
layout: default
---

# Project & Technical Sharing

<br />

- **Bedycle** - Medical Application (already closed)
- **Telegran Bot** - Trading chat bot

---
layout: default
---

<div class="flex">
  <div class="w-1/2 px-2">
    <h2 class="text-center font-bold mb-8" style="color: deeppink">
      <mdi-medication /> Bedycle
    </h2>
    <div class="mb-6">
      <h3 class="font-bold">Project Description</h3>  
      <ul>
        <li>
          Make it easy to Bed sharing between hospitals
        </li>
        <li>
          Hospital-to-hospital matching services
        </li>
      </ul>
    </div>
    <div>
      <h3 class="font-bold mb-3">Technology</h3>
      <div class="grid grid-cols-2 gap-4">
        <div class="mb-4">
          <h4 class="font-bold">Server Side</h4>
          <ul>
            <li>
              <logos-php /> PHP
            </li>
            <li>
              <logos-laravel /> Laravel
            </li>
          </ul>
        </div>
        <div>
          <h4 class="font-bold">Client Side</h4>
          <ul>
            <li>
              <span style="color: dodgerblue"><mdi-language-typescript /></span> TypeScript <span class="inline-block text-xl animate-bounce" style="color: deepskyblue;"><mdi-new-box /></span>
            </li>
            <li>
              <logos-react /> React.js <span class="inline-block text-xl animate-bounce" style="color: deepskyblue;"><mdi-new-box /></span>
            </li>
          </ul>
        </div>
        <div>
          <h4 class="font-bold">Middleware</h4>
          <ul>
            <li>
              <logos-mysql /> MySQL
            </li>
          </ul>
        </div>
        <div>
          <h4 class="font-bold">Others</h4>
          <ul>
            <li>
              <span style="color: mediumblue"><mdi-docker /></span> Docker
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <div class="w-1/2 px-2">
    <h2 class="text-center font-bold mb-8" style="color: gold">
      <logos-Bitcoin /> Telegram Bot
    </h2>
    <div class="mb-6">
      <h3 class="font-bold">Project Description</h3>  
      <ul>
        <li>
          A system that enables trading through chat
        </li>
        <li>
          Using technologies related to Web3
        </li>
      </ul>
    </div>
    <div>
      <h3 class="font-bold mb-3">Technology</h3>
      <div class="grid grid-cols-2 gap-4">
        <div class="mb-4">
          <h4 class="font-bold">Server Side</h4>
          <ul>
            <li>
              <logos-python /> Python <span class="inline-block text-xl animate-bounce" style="color: deepskyblue;"><mdi-new-box /></span>
            </li>
            <li>
              <logos-flask /> Flask <span class="inline-block text-xl animate-bounce" style="color: deepskyblue;"><mdi-new-box /></span>
            </li>
          </ul>
        </div>
        <div>
          <h4 class="font-bold">Client Side</h4>
          <ul>
            <li>
              <span style="color: dodgerblue"><mdi-language-typescript /></span> TypeScript <span class="inline-block text-xl animate-bounce" style="color: deepskyblue;"><mdi-new-box /></span>
            </li>
            <li>
              <logos-react /> React.js <span class="inline-block text-xl animate-bounce" style="color: deepskyblue;"><mdi-new-box /></span>
            </li>
          </ul>
        </div>
        <div>
          <h4 class="font-bold">Middleware</h4>
          <ul>
            <li>
              <logos-mongodb /> MongoDB <span class="inline-block text-xl animate-bounce" style="color: deepskyblue;"><mdi-new-box /></span>
            </li>
            <li>
              <logos-redis /> Redis
            </li>
          </ul>
        </div>
        <div>
          <h4 class="font-bold">Others</h4>
          <ul>
            <li>
              <span style="color: mediumblue"><mdi-docker /></span> Docker
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</div>


<style>
@keyframes jump {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-20px);
  }
}
</style>


---
layout: end
---

# Thanks for your kindness till today and I wish yours prosperity.
