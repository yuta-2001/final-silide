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

- **Brief Self-Introduction**
- **Projects and Technical Sharing**
- **Life in Danang**
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

<h1 class="text-center font-bold mt-20" style="font-size: 4rem;">Project & Technical Sharing</h1>

<div class="pt-12 mx-auto text-center">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

---
layout: default
---

# Projects I joined

<br />

- **Bedycle** - Medical Application (already closed) (from Augast to November)
- **Telegran Bot** - Trading chat bot (from November to January)

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


---
layout: default
---

# Challenging

<div class="mb-2 p-4 bg-blue-200 rounded-lg shadow-md">
  <h4 class="font-bold">First Challeng of Client Side dev</h4>
  <p class="text-gray-700 text-sm" style="margin: 0;">
    When I've joined internship in Japan, I focused on Backend side (PHP) <br />
    PHP is "Object-oriented programming" React is "Functional programming" <br />
    Needed to understand how to cache, how to manage state, how to rerendering etc... <br />
    (This slide is using slidev (vue.js))
  </p>
</div>
<div class="mb-2 p-4 bg-green-200 rounded-lg shadow-md">
  <h4 class="font-bold">Understand What is Web3, How to trade</h4>
  <p class="text-gray-700 text-sm" style="margin: 0;">
    When I joined, I can understand python easily because similar to PHP, but it was hard to understand how to trade. <br />
    There are so many terms, like (collateral, pool, tp/ls, short, long, limit...etc) <br />
    But every members support me and I was getting understand how to trade in Web3 network.
  </p>
</div>
<div class="mb-2 p-4 bg-purple-200 rounded-lg shadow-md">
  <h4 class="font-bold">Different Language</h4>
  <p class="text-gray-700 text-sm" style="margin: 0;">
    My English is kind of JP English, so hard to tell. <br />
    And CC member's English is also kind of Viet English. Hard to understand. <br />
    But now I used to pronounce and easy to understand 🙆
  </p>
</div>

---
layout: default
---

<h1 class="text-center font-bold mt-20" style="font-size: 4rem;">Life In Danang</h1>

<div class="pt-12 mx-auto text-center">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

---
layout: end
---

# Thanks for your kindness till today and I wish yours prosperity.
