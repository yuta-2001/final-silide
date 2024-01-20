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
layout: default
---

<h1 class="text-center font-bold mt-20" style="font-size: 4rem;">Brief Self-Introduction</h1>

<div class="pt-12 mx-auto text-center">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<span class="font-bold absolute bottom-4 left-1/2 -translate-x-1/2 text-xl w-40 h-40 text-center rounded-full border-4" style="font-size: 7rem; line-height: 10rem; color: #5d8392;">
１
</span>


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

<span class="font-bold absolute bottom-4 left-1/2 -translate-x-1/2 text-xl w-40 h-40 text-center rounded-full border-4" style="font-size: 7rem; line-height: 10rem; color: #5d8392;">
2
</span>

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
          Facilitate bed sharing between hospitals
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
This app are running three Python processes. For frequently used data, This app retrieve it using the second process and store it in Redis.
</p>

<img class="block h-4/5 w-auto mx-auto mt-8" src="/images/structure-of-app.png">

---
layout: default
---

<h1 class="font-bold">What I Newly Learned From Projects</h1>

<ul>
  <li>
    Understanding of Web3 and Blockchain
  </li>
  <li>
    Principles of Front-End Development with React.js
  </li>
  <li>
    Difference between SQL and NoSQL
  </li>
  <li>
    Understanding of Multiprocessing and Multithreading
  </li>
  <li>
    Approaches to Scrum Development
  </li>
  <li>
    etc...
  </li>
</ul>


---
layout: default
---

<h1 class="font-bold">Challenges</h1>

<div class="mb-2 p-4 bg-blue-200 rounded-lg shadow-md">
  <h4 class="font-bold">First Challenge in Client-Side Development</h4>
  <p class="text-gray-700 text-sm" style="margin: 0;">
    When I joined the internship in Japan, I focused on the backend side (PHP) <br />
    PHP is object-oriented programming, while React is functional programming, PHP is not strict about types, whereas TypeScript is <br />
    I needed to understand caching, state management, and re-rendering, etc. <br />
  </p>
</div>
<div class="mb-2 p-4 bg-green-200 rounded-lg shadow-md">
  <h4 class="font-bold">Understand What is Web3, How to trade</h4>
  <p class="text-gray-700 text-sm" style="margin: 0;">
    When I joined, I could understand Python easily because it's similar to PHP, but understanding trading was challenging. <br />
    There are so many terms, like (collateral, pool, tp/ls, short, long, limit...etc) <br />
    However, every member supported me, and I gradually understood how to trade in the Web3 network.
  </p>
</div>
<div class="mb-2 p-4 bg-purple-200 rounded-lg shadow-md">
  <h4 class="font-bold">Different Language</h4>
  <p class="text-gray-700 text-sm" style="margin: 0;">
    I didn't have enough skills to communicate with people from other countries. (Lack of listening and speaking skill) <br />
    Additionally, my English is akin to JP English, making it difficult to express myself. <br /> 
    But now,My English has improved and it's easier for me to speak and understand 🙆
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
    Our bot had a response time issue. When sending messages to users, it often required a lot of information (like the current ETH price, current commission, etc.), leading to numerous requests. This was the reason for our bot's delayed response time. For instance, when executing orders, users had to wait for 20-30 seconds.<br />
    To address this issue, I first investigated the code of another OSS product to understand their approach. After implementing their solution, I managed to reduce the response time from 20-30 seconds to just 2 seconds.<br />
    It was a challenging problem, but solving it brought me great joy and taught me many things.
  </p>
</div>


---
layout: iframe-right
url: https://my-blog-yuta-2001.vercel.app/blogs
---

<h1 class="font-bold">Technical Output</h1>

I output what I learned on the internship and outside of work.

<div class="mb-2 p-4 bg-blue-200 rounded-lg shadow-md">
  <h4 class="font-bold">My Tech Blog</h4>
  <p class="text-gray-700 text-sm" style="margin: 0;">
    Having used TypeScript and React.js, I created a tech blog to showcase my work.
    Before joining this program, I primarily focused on backend development, so I can really see my growth.
  </p>
  <a class="text-xs" href="https://my-blog-yuta-2001.vercel.app/">https://my-blog-yuta-2001.vercel.app/</a>
</div>
<div class="mb-2 p-4 bg-green-200 rounded-lg shadow-md">
  <h4 class="font-bold">Final Presentation</h4>
  <p class="text-gray-700 text-sm" style="margin: 0;">
    This presentation was created using Slidev (Vue.js).<br />
  </p>
  <a class="text-xs" href="https://final-silide.vercel.app/1">https://final-silide.vercel.app/1</a>
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

<span class="font-bold absolute bottom-4 left-1/2 -translate-x-1/2 text-xl w-40 h-40 text-center rounded-full border-4" style="font-size: 7rem; line-height: 10rem; color: #5d8392;">
３
</span>


---
layout: default
---
<h1 class="font-bold text-3xl" style="margin-bottom: 2rem;">
  What I suprised when I came here
</h1>

<div class="grid grid-cols-2 gap-4">
  <div class="h-50 flex justify-center items-center relative overflow-hidden group">
    <h3 class="font-bold z-20 text-white group-hover:z-10" style="font-size: 2rem; text-shadow: 1px 2px 3px #808080;">Too Many Bike</h3>
    <div class="absolute top-0 left-0 w-full h-full bg-black opacity-50 group-hover:opacity-0 z-10 transition-opacity duration-200"></div>
    <img class="absolute top-0 left-0 w-full z-0" src="/images/bike.jpg">
  </div>
  <div class="h-50 flex justify-center items-center relative overflow-hidden group">
    <h3 class="font-bold z-20 text-white group-hover:z-10" style="font-size: 2rem; text-shadow: 1px 2px 3px #808080;">Many Young People</h3>
    <div class="absolute top-0 left-0 w-full h-full bg-black opacity-50 group-hover:opacity-0 z-10 transition-opacity duration-200"></div>
    <img class="absolute top-0 left-0 w-full z-0" src="/images/population.webp">
  </div>
  <div class="h-50 flex justify-center items-center relative overflow-hidden group">
    <h3 class="font-bold z-20 text-white group-hover:z-10" style="font-size: 2rem; text-shadow: 1px 2px 3px #808080;">Early Morning</h3>
    <div class="absolute top-0 left-0 w-full h-full bg-black opacity-50 group-hover:opacity-0 z-10 transition-opacity duration-200"></div>
    <img class="absolute top-0 left-0 w-full z-0" src="/images/morning.png">
  </div>
  <div class="h-50 flex justify-center items-center relative overflow-hidden group">
    <h3 class="font-bold z-20 text-white group-hover:z-10 text-center" style="font-size: 1.7rem; text-shadow: 1px 2px 3px #808080;">People talk to me in japanese <br />(Sometime in Korea🤣)</h3>
    <div class="absolute top-0 left-0 w-full h-full bg-black opacity-50 group-hover:opacity-0 z-10 transition-opacity duration-200"></div>
    <img class="absolute top-0 left-0 w-full z-0" src="/images/japan.png">
  </div>
</div>


---
layout: image-right
image: /images/activity-background.png
---

<h1 class="font-bold text-3xl" style="margin-bottom: 2rem;">
  Activities
</h1>

<p class="mb-4">I've mainly joined two activities.</p>
<div class="h-47 flex justify-center items-center relative overflow-hidden group mb-4">
  <div class="p-2 z-20 text-white">
    <h3 class="font-bold z-20 text-white group-hover:z-10 text-center" style="font-size: 1.7rem; text-shadow: 1px 2px 3px #808080;">
      Football
    </h3>
    <p class="text-xs text-center">
      Every Wednesday evening, we played football.<br />
      On the first day of my internship, Hoa-san invited us to play football.<br />
      I didn't expect to play football on my first day, but it was very interesting. 😄
    </p>
  </div>
  <div class="absolute top-0 left-0 w-full h-full bg-black opacity-50 group-hover:opacity-0 z-10 transition-opacity duration-200"></div>
  <img class="absolute top-0 left-0 w-full z-0" src="/images/football.png">
</div>

<div class="h-47 flex justify-center items-center relative overflow-hidden group">
  <div class="p-2 z-20 text-white">
    <h3 class="font-bold z-20 text-white group-hover:z-10 text-center" style="font-size: 1.7rem; text-shadow: 1px 2px 3px #808080;">
      Cycling
    </h3>
    <p class="text-xs text-center">
      One day, Nhung-san and Trang-san invited us to go cycling.<br />
      It helped me maintain good health, and I saw monkeys and beautiful views.<br />
      I also enjoyed eating noodles after cycling.<br />
      I was very happy to participate. 😄
    </p>
  </div>
  <div class="absolute top-0 left-0 w-full h-full bg-black opacity-50 group-hover:opacity-0 z-10 transition-opacity duration-200"></div>
  <img class="absolute top-0 left-0 w-full z-0" src="/images/cycling.png">
</div>

---
layout: image
image: /images/album.png
---


---
layout: default
---

<h1 class="text-center font-bold mt-20" style="font-size: 4rem;">Summary</h1>

<div class="pt-12 mx-auto text-center">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<span class="font-bold absolute bottom-4 left-1/2 -translate-x-1/2 text-xl w-40 h-40 text-center rounded-full border-4" style="font-size: 7rem; line-height: 10rem; color: #5d8392;">
4
</span>

---
layout: default
---

<h1 class="font-bold">
  What I Learned from This Internship
</h1>

<ul>
  <li>New technical skills such as Python and TypeScript</li>
  <li>Knowledge of Web3</li>
  <li>Life in Vietnam</li>
  <li>How to work and communicate with people from other countries</li>
  etc
</ul>

<h2 class="font-bold" style="color: #5d8392">Appreciate</h2>
<p>
  CC provided me with many growth opportunities. <br />
  The team members gave me a lot of support.<br />
  Some members invited me to various activities and to eat delicious food, etc.<br />
  I appreciate all the help, the times we spent playing together, and our conversations!
</p>

---
layout: default
---

<h1 class="font-bold">
  Reference
</h1>

<ul>
  <li>
    https://danang-holic.com/tips/danang-travel-budget/
  </li>
  <li>
    https://ganref.jp/m/badboy1975/portfolios/photo_detail/2200563
  </li>
  <li>
    https://www.asahi.com/articles/DA3S15670989.html
  </li>
  <li>
    https://www.fun-japan.jp/vn/articles/12611
  </li>
  <li>
    https://r-vietnam.com/blog/basic-information-about-vietnam-in-2023-422.html
  </li>
</ul>

---
layout: end
---

<div class="flex items-center justify-center">
  <h1 class="text-center">
  Thanks for your kindness till today.<br />
  I wish yours prosperity.
  </h1>
</div>
