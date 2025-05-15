---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Decoding Your Science Presentation
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

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
# seoMeta:
#  ogImage: https://cover.sli.dev
---
<div class="grid grid-cols-2 h-full">
  <!-- Left column -->
  <div class="flex flex-col justify-center items-start text-left px-8">
    <h1 class="text-3xl font-bold mb-2">The golden shackles of Microsoft Word</h1>
    <p class="text-lg mb-4">How convenience hinders scientific production.</p>
    <div class="mt-auto text-sm">
      Giacomo Fantoni
    </div>
  </div>

  <!-- Right column -->
  <div class="flex justify-center items-center">
    <img src="./ball_and_chain_edited.png" class="h-full w-full object-cover object-center" />
  </div>
</div>

<!--
Because noone has taught us there are other solution and we don't want to loose time by learning by ourselve we choose the most "convenient" solution, the program that's already there thanks to a clever marketing strategy by microsoft.
-->
---
layout: default
class: image-slide
---
# A single program doing three jobs (badly) - Visualization
<img src="./word.png" class="w-full max-h-[80vh] object-contain mx-auto"/>
<!-- test -->

---
layout: image-left

image: visualization_logos.jpg

class: my-cool-content-on-the-right object-contain
backgroundSize: contain
---
<style>
/* Assuming the right column is the content container */
.my-cool-content-on-the-right {
  display: flex;
  flex-direction: column;
  justify-content: center; /* vertical center */
  height: 100%;
  /* optionally set min-height to ensure container stretches */
  min-height: 300px; /* adjust as needed */
}
</style>

- Open Standards.
- Free software available.
- Non Modifiable.
- Visualization is consistent in every device.
- Everyone shares everything this way.

---
layout: default
class: image-slide
---
# A single program doing three jobs (badly) - Writing
<img src="./notepad.png" class="w-full max-h-[80vh] object-contain mx-auto"/>
<!-- test -->


---
layout: image-left

image: writing_example.jpg

class: my-cool-content-on-the-right object-contain
backgroundSize: contain
---
<style>
/* Assuming the right column is the content container */
.my-cool-content-on-the-right {
  display: flex;
  flex-direction: column;
  justify-content: center; /* vertical center */
  height: 100%;
  /* optionally set min-height to ensure container stretches */
  min-height: 300px; /* adjust as needed */
}
</style>

- Open Standards.
- YOU choose how to write it.
- Free software available.
- Good documentation.
- Easily searchable.

---
layout: default
class: !pt-8 !pb-4
---
# A single program doing three jobs (badly) - Collaboration
<div class="flex justify-center items-start gap-4 mt-6">
  <img src="./version_control.png" class="w-1/3 h-auto object-contain" />
  <img src="./track_changes.png" class="w-2/3 h-auto object-contain" />
</div>

---
layout: default
class: !pt-8 !pb-4
---
<div class="flex justify-center items-center gap-4 mt-6">
  <img src="./git_tree.png" class="w-1/3 h-auto object-contain" />
  <img src="./github-diff.png" class="w-2/3 h-auto object-contain" />
</div>

---
layout: image
image: ./plato-allegory-of-the-cave_edited.png
---
  <div class="absolute bottom-4 right-4 w-40 text-center">
    <img src="./qr_code.png" alt="description" class="w-full h-auto" />
    <div class="text-black font-bold text-sm mt-2">Link to the source code for the slides</div>
  </div>
<!-- test -->
