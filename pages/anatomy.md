---
layout: cover
background: https://images.unsplash.com/photo-1606318005254-bdb2bcd14d34?crop=entropy&cs=tinysrgb&fit=crop&fm=jpg&h=1080&ixid=MnwxfDB8MXxyYW5kb218MHw5NDczNDU2Nnx8fHx8fHwxNjk3Nzk1Mjcx&ixlib=rb-4.0.3&q=80&utm_campaign=api-credit&utm_medium=referral&utm_source=unsplash_source&w=1920
class: text-center
---

# Anatomy of a Design&nbsp;System

<!--
"What does it consist of?"
-->

---
layout: image-left
image: /images/blueprint_lego_block.jpg
---

# Design Tokens

The "specs" of your design system

<!--
- CSS/SCSS variables
- Design decisions
- Measurements
- Color palette
- Typography
- Themes
    - Dark, high contrast
    - Compact/porous
    - Larger/smaller text
- etc.

## Transition
"Handy styling utilities, but incomplete"
-->

---
background: /images/legos-sorted.png
---

# CSS Styling Utilities

<!--
- Layer around the design tokens

- Layout
- Breakpoints
- Repetitive group of styling rules
-->

---
background: /images/atomic-design.png
---

# Components

<!--
- Atomic design (Brad Frost)
    - Atoms & Molecules

- Must use the design tokens (and CSS Styling utilities, if not Shadow DOM)
- "Dumb" components
- Context unaware
- Applicable ("appropriate") technique
-->

---
layout: default
transition: slide-left
background: /images/legos_kind_of_sorted.jpg
---

<div class="relative h-full">
<h1 class="absolute z-40">Documentation</h1>

<img v-click class="absolute left-1/10 -top-4 w-6/10 rotate-3" src="/images/lego-instructions-workspace.jpg" alt="">
<img v-click class="absolute -right-24 -top-10 w-6/10 -rotate-1" src="/images/lego-instructions_king-kahuna.jpg" alt="">
<img v-click class="absolute -left-1/10 top-1/10 w-8/10 -rotate-2" src="/images/lego-instructions-firetruck.jpeg" alt="">
<img v-click class="absolute left-8 -top-2 w-6/10 rotate-1" src="/images/lego-instructions-golden-snitch.jpg" alt="">
<img v-click class="absolute -top-4 h-full rotate-2" src="/images/lego-instructions-be-like.jpg" alt="">
<img v-click class="absolute left-20 -top-8 w-6/10 rotate-4 z-50" src="/images/ikea-henj.jpg" alt="">
</div>

<!--

# Henj -> "Oh sorry! Wrong example"

- Describes how DS elements work and could be used together
- Kind of like a style guide, but not quite
- Not everything is a DS component
- Organisms/Templates
-->

---
background: https://images.unsplash.com/photo-1621237023000-6a628c285938?crop=entropy&cs=tinysrgb&fit=crop&fm=jpg&h=1080&ixid=MnwxfDB8MXxyYW5kb218MHw5NDczNDU2Nnx8fHx8fHwxNjk3Nzk1MjQ2&ixlib=rb-4.0.3&q=80&utm_campaign=api-credit&utm_medium=referral&utm_source=unsplash_source&w=1920
transition: slide-left
---

# Conclusion

<v-click>

<div class="flex justify-end items-center h-full">

- Not just a component library
- Faster UI development
- Focus feature > brand
- Consistency is key
- Brand recognition
- Themes
</div>
</v-click>

<!--
# Sum up

- More than just a component library
- It provides fast way to build consistent UI/UX/DX
- If done right: branding is back into the designers' hands

-->