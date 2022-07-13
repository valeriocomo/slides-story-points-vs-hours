---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS (experimental)
css: unocss
---

# Story Points vs Hours

Agile Estimation Misconception

<!-- <div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div> -->

<div class="abs-br m-6 flex gap-2">
  <!-- <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button> -->
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->
---

# Overview

- 📝 **Story Points** 
- **Story Points vs Hours**
- **Misconception side effects**

---
layout: section
---

# Story Points

---
layout: center
---

# What's Story Points?

---
layout: quote
---
# Definition from Scrum Guide

"N/A"

---
layout: quote
---
# Definition

“A Story Point is a relative unit of measure, decided upon and used by individual Scrum teams, to provide relative estimates of effort for completing requirements“

Derek Davidson 
from <a href="https://www.scrum.org/resources/blog/why-do-we-use-story-points-estimating">Scrum.org</a>


---
layout: center
---

# Why Story Points?

---

# Why Story Points?

- **Effort estimation** 
- **Relative estimation** 
- **Team estimation process**
- **Team velocity**
- **Less effort in estimation**

---
layout: center
---

# Why isn't related with time?

---

# Why isn't related with time?

- Absolute estimation
- Subjectivity
- Affected by people background & skill

---
layout: section
---

# Story Points vs Hours

---
layout: center
---

# How does Story Points are related with Hours?

---
layout: center
---

## Track time used per Product Backlog Item (PBI)

---
layout: center
---

## Time Distribution PBI with 1 SP

---
layout: image

# the image source
image: ./assets/images/lognormal-1.png
---

---
layout: center
---

## Time Distribution PBI with 2 SP

---
layout: image

# the image source
image: ./assets/images/lognormal-2.webp
---

---

# Track time used per (PBI)

- **x : 1 = 2x : 2** 
- **overlapping**
- **measure refinement accross time**

---
layout: section
---

# Misconception side effects

---

# Misconception side effects

- **Subjective estimation** 
- **Technical sequence**
- **Evolving Definition of Done (DoD)**
- **Improving domain understanding**
- **Product complexity evolution**
- **Team dynamics**

---

## Subjective estimation

- estimation related with task owner
- costly process

---

## Technical sequence

- handling complexity ahead of time
- difficult with hours easier with SP

---

## Evolving DoD

- could invalidate old estimation
- adapting relative estimation

---

## Improving domain understanding

- better understanding -> better estimation
- affect absolute estimation
- invalidate old estimation

---

## Product complexity evolution

- complexity grows accross time

---

## Team dynamics

- turnover affect estimation
- heterogeneity of team skills

---
layout: center
---

# Q&A

---
layout: center
---

# Thank you

---

# References

- https://www.scrum.org/resources/blog/why-do-we-use-story-points-estimating
- https://turboscrum.com/estimating-in-scrum-just-the-facts/
- https://www.mountaingoatsoftware.com/blog/its-effort-not-complexity
- https://www.mountaingoatsoftware.com/blog/how-do-story-points-relate-to-hours
- https://www.scruminc.com/story-points-why-are-they-better-than/
- https://www.scrum.org/resources/blog/myth-9-story-points-are-required-scrum
- https://www.youtube.com/watch?v=gSJVmemODYs