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

<h1 class="font-bold">What I learned from my internship & life in Danang</h1>

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

<h1 class="font-bold">Table of contents</h1>

<br />

- **Brief Self-Introduction**
- **Projects and Technical Sharing**
- **Life in Danang**
- **Summary**


---
layout: image-right
image: /images/profile.png
---

<h1 class="font-bold">Introduce Myself</h1>

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

<h1 class="font-bold">Projects</h1>

<br />

- **Bedycle** - Medical Application (already closed)
- **Telegran Bot** - Trading chat bot

<div class="border-t border-gray-300 my-12 mx-4"></div>

<div class="flex justify-around text-md text-gray-600 px-4">
  <span>July</span>
  <span>August</span>
  <span>September</span>
  <span>October</span>
  <span>November</span>
  <span>December</span>
  <span>January</span>
</div>

<div class="relative mt-4 mx-4">
  <div class="absolute top-0 left-1/6 w-110 p-2 border-2 font-bold border-blue-400 text-center rounded-full">
    Bedycle<br />
    (Client-Side・Server-Side)
  </div>

  <div class="absolute top-20 left-5/9 w-4/9 p-2 border-2 font-bold border-green-400 text-center rounded-full">
    Telegran Bot <br />
    (Server-Side)
  </div>
</div>

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
          </ul>
        </div>
        <div>
          <h4 class="font-bold">Others</h4>
          <ul>
            <li>
              <span style="color: mediumblue"><mdi-docker /></span> Docker
            </li>
            <li>
              <logos-redis /> Redis
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

<h1 class="font-bold">Project System Detail</h1>

<p>
Python is running three processes.
The data that ofthen used is stored into Redis.
</p>

<img class="block h-4/5 w-auto mx-auto mt-8" src="/images/structure-of-app.png">

---
layout: default
---

<h1 class="font-bold">What I Learned Newly From Projects</h1>

<ul>
  <li>
    What is Web3, What is blockchain
  </li>
  <li>
    The principle of front-end dev (React.js)
  </li>
  <li>
    Difference between SQL and NoSQL
  </li>
  <li>
    Multiprocess and multithread
  </li>
  <li>
    The way of Scrum development
  </li>
  <li>
    etc...
  </li>
</ul>


---
layout: default
---

<h1 class="font-bold">Challenging</h1>

<div class="mb-2 p-4 bg-blue-200 rounded-lg shadow-md">
  <h4 class="font-bold">First Challeng of Client Side dev</h4>
  <p class="text-gray-700 text-sm" style="margin: 0;">
    When I've joined internship in Japan, I focused on Backend side (PHP) <br />
    PHP is "Object-oriented programming" React is "Functional programming" PHP isn't strict for type Typescript is strict for type <br />
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

<h1 class="font-bold">Success</h1>

<div class="mb-2 p-4 bg-purple-200 rounded-lg shadow-md">
  <h4 class="font-bold">Improve the response time of bot</h4>
  <p class="text-gray-700 text-sm" style="margin: 0;">
    (Telegram Bot) <br />
    Our bot had a problem of response time. When we send message to user, sometime we need many information (like Current ETH price, Current commission, etc) so our bot need to request so many times. That's is because our bot's response time is so late. (when execute order, user needed to wait for 20-30sec).<br />
    I needed to fix this problem, so firstly, I investigated another OSS product code, and found what they use. And then I introduce that one, I could reduce the response time from 20-30sec => 2sec.<br />
    It was so difficult problem for me, but when I success to solve this problem, I was so happy and I could learn a lot of things.
  </p>
</div>


---
layout: iframe-right
url: https://my-blog-yuta-2001.vercel.app
---

<h1 class="font-bold">Technical Output</h1>

I output what I learned on the internship and outside of work.

<div class="mb-2 p-4 bg-blue-200 rounded-lg shadow-md">
  <h4 class="font-bold">My Tech Blog</h4>
  <p class="text-gray-700 text-sm" style="margin: 0;">
    I used TypeScript and React.js, so I made a Tech blog as output.
    Before joining here, I only focus on Backend Side, so I feel my growth.
  </p>
  <a class="text-xs" href="https://my-blog-yuta-2001.vercel.app/">https://my-blog-yuta-2001.vercel.app/</a>
</div>
<div class="mb-2 p-4 bg-green-200 rounded-lg shadow-md">
  <h4 class="font-bold">Final Presentation</h4>
  <p class="text-gray-700 text-sm" style="margin: 0;">
    This presentation is using Slidev (Vue.js)<br />
  </p>
  <a class="text-xs" href="https://my-blog-yuta-2001.vercel.app/">https://my-blog-yuta-2001.vercel.app/</a>
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
layout: default
---
<h1 class="font-bold text-3xl mb-6">
  What I suprised when I came here
</h1>

---
layout: default
---
<h1 class="font-bold text-3xl mb-6">
  I tried so many delicious foods
</h1>


---
layout: default
---
<h1 class="font-bold text-3xl mb-6">
  I tried so many delicious foods
</h1>


---
layout: default
---
<h1 class="font-bold text-3xl mb-6">
  I tried so many delicious foods
</h1>

---
layout: end
---

# Thanks for your kindness till today and I wish yours prosperity.
