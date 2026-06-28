---
layout: center
transition: slide-up
glowSeed: 91
glow: bottom-right
---

<div flex flex-col items-center gap-6>

<div text-5xl font-bold>How to use Slidev</div>

<div text="white/60" text-lg>
  Check the documentation to get started
</div>

<div flex gap-6 mt-4>
  <a href="https://sli.dev/guide/" target="_blank"
     class="glass-card rounded-xl px-6 py-4 flex items-center gap-3 transition duration-300"
     hover:scale-105>
    <div i-carbon:book text-2xl text-sky-300 />
    <div>
      <div font-semibold>English Docs</div>
      <div text-sm text="white/50">sli.dev</div>
    </div>
  </a>
  <a href="https://cn.sli.dev/guide/" target="_blank"
     class="glass-card rounded-xl px-6 py-4 flex items-center gap-3 transition duration-300"
     hover:scale-105>
    <div i-carbon:translate text-2xl text-teal-300 />
    <div>
      <div font-semibold>简体中文</div>
      <div text-sm text="white/50">cn.sli.dev</div>
    </div>
  </a>
</div>

<div mt-8 w-full max-w-lg>
  <div text="white/50" text-sm mb-3 uppercase tracking-wider>Try UnoCSS in your slides:</div>
  <div glass-card rounded-xl p-5 text-left font-mono text-sm space-y-2>
    <div><span text-red-400>&lt;div</span> <span text-sky-300>color-red</span><span text-red-400>&gt;</span>red<span text-red-400>&lt;/div&gt;</span></div>
    <div><span text-red-400>&lt;div</span> <span text-sky-300>color-blue</span><span text-red-400>&gt;</span>blue<span text-red-400>&lt;/div&gt;</span></div>
    <div><span text-red-400>&lt;div</span> <span text-sky-300>font-size-8</span><span text-red-400>&gt;</span>哈哈<span text-red-400>&lt;/div&gt;</span></div>
  </div>
  <div mt-4 flex gap-4 justify-center text-lg>
    <span color-red font-bold>red</span>
    <span color-blue font-bold>blue</span>
    <span font-size-8>哈哈</span>
  </div>
</div>

<div>
  <Counter :count="0"/>
</div>

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
