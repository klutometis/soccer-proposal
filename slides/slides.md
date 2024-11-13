---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Soccer proposal
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
# take snapshot for each slide in the overview
overviewSnapshots: true
---

# Don't Fucking Change Anything

## Peter Danenberg

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/klutometis/soccer-proposal" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
  <a href="https://www.linkedin.com/in/peterdanenberg/" target="_blank" alt="LinkedIn" title="Connect on LinkedIn"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-linkedin />
  </a>
</div>

---

# Send me some <span v-mark.circle.red>playlists</span>, though!

<span v-mark.highlight.yellow>For instance:</span>

- [Mansión Reggaetón](https://open.spotify.com/playlist/37i9dQZF1DWZjqjZMudx9T)
- [Angry hard rock mix](https://open.spotify.com/playlist/37i9dQZF1EIfLeXYo5Rqhb)
- [Baroque bangers](https://open.spotify.com/playlist/4A4DwhBNHsOVK8AdtZ3HFr)
