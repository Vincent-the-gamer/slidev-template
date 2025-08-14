---
# You can also start simply with 'default'
theme: seriph
background: /wallpaper.png
# some information about your slides (markdown enabled)
title: Slidev Template
info: |
  ## Slidev Template
  An opinionated template for Slidev.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# open graph
seoMeta:
  # By default, Slidev will use ./og-image.png if it exists,
  # or generate one from the first slide if not found.
  ogImage: auto
  # ogImage: https://cover.sli.dev
src: ./pages/home.md
---

---
src: ./pages/page-2.md
---

---
src: ./pages/page-3.md
---