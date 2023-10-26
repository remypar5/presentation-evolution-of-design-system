---
layout: default
clicks: 1
---

# Evolution

<div class="relative">
  <img
    v-click-hide
    class="absolute w-2/5"
    src="/images/eeveelutions.webp"
    alt="Pokémon's Eevee and its eight evolutions circled around it"
  />
  <img
    v-after
    class="absolute w-3/5"
    src="/images/lego-logo-evolution.jpg"
    alt="All of LEGO's logos throughout the years"
  />
</div>

<!--
### Eeveelutions
- Design Systems didn't appear out of thin air
- Eevee just to grab your attention

### LEGOs
- August 1934 Ole Kirk Christiansen
- Wooden furniture miniatures
- Danish: "Leg Godt" -> English: "Play Well" -> Dutch: "Speel Goed" or "Lekker Spelen"
- Latin: "Lego" -> "I compile"
-->

---
transition: slide-up
class: text-center
background: /images/heap-of-large-blocks.jpg
---

# DIY a.k.a. "Free for All"

<div class="relative">
<div class="absolute flex justify-around" v-click-hide>
    <img style="width: 45%" src="/images/knock-off-legos.webp" alt="Unsorted pile of building blocks resembling LEGOs. Brand unknown.">
    <img style="width: 45%" src="/images/CaDA_delorean_86.webp" alt="CaDA super car 86 building block set resembling LEGOs. The car resembles a DeLorean 86 as seen in the film series Back to the Future">
</div>

<div v-after class="absolute flex justify-center -top-12 -rotate-2"><img class="w-7/10" src="/images/lego-millennium-falcon.jpg" alt="Star Wars' Millennium Falcon space ship model built using LEGOs according to the appropriate color scheme"></div>
<div v-click class="absolute flex justify-center -top-12 rotate-2"><img class="w-8/10" src="/images/lego-millennium-falcon-colorful.jpg" alt="Star Wars' Millennium Falcon space ship model built using LEGOs. The ship is built using randomly colored bricks"></div>
</div>

<!--
- Designers had a blast
- "Carnival" or "Times Square in NYC"
- Pages might look alike, but not a given
- Reinvent the wheel each time

### Transition
"We can do better"
-->

---
background: /images/lego-set-6_in_1.jpg
---

# Style Guide

<!--
- "A button needs to look like this"

### Pros
- More alignment
- Everything started to look alike

### Cons
- Repetition in code
- Many are alike, but not the same
- New branding? Everybody needed to do rework. At the same time
  - Rabobank's "Granite gray"

### Transition
When modularity in FE came around: "We can do better"
-->

---
background: /images/adam_savage-sorted-legos.jpg
---

# Component Library

<!--
### Pros
- Even more alignment
- Often documented
- (way) less repetition
- Build your UI faster
- Easier to apply rebranding
- (possibly) part of a11y comes out of the box

### Cons
- Often shared effort
    - Tweaks
    - Still comparable (but no equal) components
- Often vendor lock-in
- Only components

### Transition
"This is a good start, but we can still do better"
-->

---
transition: slide-left
background: /images/legos-sorted.png
---

# Design System

<!--
### Pros
- Full UI building suite
- Fully aligned
- Same UX in all nooks and crannies in your application(s)
    - Brand recognition
- Your design is hard-coded
    - Designers are no longer free to recreate NYC's Times Square

### Cons
- Your org needs to be ready for this
  - Otherwise, designers still tweak
- "Fine! I'll build it my self"
    - Not part of the design system?
    - Not according to brand design?

### Transition
"Before I tell you about DS, let's look at OSS first"
-->

---
transition: slide-left
---

# Open Source

<div class="relative">
  <img v-click-hide class="absolute z-10" src="/images/ionic.png" alt="Logo of Ionic">
  <img v-after class="absolute inset-x-17 inset-y-16 w-3/10 z-30" src="/images/material-logo.svg" alt="Logo of Google's Material UI">
  <img v-click class="absolute w-7/10 z-40" src="/images/react95-logo.jpeg" alt="Logo of React95">
  <img v-click class="absolute z-50" src="/images/react95-example.png" alt="Visualization of what the React95 design system looks like">
</div>

<!--
- Great start

# Cons
- Vendor lock-in
- Stick to their "open-ness"
-->
