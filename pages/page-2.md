---
layout: center
transition: fade-out
glowSeed: 311
glow: right
---

<div flex flex-col gap-8>
  <div text-4xl font-bold>What is Slidev?</div>
  <div grid="~ cols-2" gap-5>
    <div v-click border="2 solid sky-500/30" bg="sky-500/10" rounded-xl p-6 transition duration-300>
      <div i-carbon:text-annotation-toggle text-5xl text-sky-300 mb-5 />
      <div text-xl font-semibold>Text-based</div>
      <div mt-3 text="white/55" leading-6>Focus on content with Markdown, style later.</div>
    </div>
    <div v-click border="2 solid teal-500/30" bg="teal-500/10" rounded-xl p-6 transition duration-300>
      <div i-carbon:paint-brush text-5xl text-teal-300 mb-5 />
      <div text-xl font-semibold>Themable</div>
      <div mt-3 text="white/55" leading-6>Themes shared and re-used as npm packages.</div>
    </div>
    <div v-click border="2 solid violet-500/30" bg="violet-500/10" rounded-xl p-6 transition duration-300>
      <div i-carbon:code text-5xl text-violet-300 mb-5 />
      <div text-xl font-semibold>Developer Friendly</div>
      <div mt-3 text="white/55" leading-6>Code highlighting, live coding with autocompletion.</div>
    </div>
    <div v-click border="2 solid amber-500/30" bg="amber-500/10" rounded-xl p-6 transition duration-300>
      <div i-carbon:cube text-5xl text-amber-300 mb-5 />
      <div text-xl font-semibold>Interactive</div>
      <div mt-3 text="white/55" leading-6>Embed Vue components to enhance expressions.</div>
    </div>
  </div>
</div>

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->
