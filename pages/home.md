---
layout: center
background: /wallpaper.png
class: font-cover
glowSeed: 45499218
glow: full
---

<div translate-y-10>

<h1 text="6xl!" font-bold>
Slidev Template
</h1>

<p text="white/70" text-xl mt-4>
An opinionated template with glass-morphism dark theme
</p>

<div mt-8 flex items-center gap-4 text-lg justify-center>
  <div i-carbon:3d-software text-3xl text-sky-300 />
  <span text="white/60">Built with Slidev + UnoCSS</span>
</div>

<div @click="$slidev.nav.next" class="mt-12 py-2 px-6 rounded-full inline-flex items-center gap-2 cursor-pointer transition duration-300" border="~ sky-500/30" hover:bg="sky-500/10">
  <span>Press Space to start</span>
  <div i-carbon:arrow-right />
</div>

</div>

<div class="abs-br m-6 text-xl flex gap-3">
  <a href="https://github.com/Vincent-the-gamer/slidev-template" target="_blank" class="slidev-icon-btn">
    <div i-carbon:logo-github />
  </a>
</div>
