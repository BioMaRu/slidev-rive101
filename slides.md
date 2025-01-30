---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://rive.app/static/img/features/editor.png
# some information about your slides (markdown enabled)
title: Rive 101
info: |
  Introduction to Rive - Interactive Graphics & Animation Platform
  for Developers and Designers
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
highlighter: shiki
lineNumbers: false
fonts:
  # Automatically host from Google Fonts
  sans: 'Noto Sans'
  mono: 'Noto Sans Mono'
---

<div class="flex justify-center items-center mb-4">
  <img src="/rive.svg" class="w-24 h-24 filter dark:invert" />
</div>

# Rive 101

<div class="text-2xl text-gray-200 font-bold mt-4">
EMPOWER DESIGNERS × SLASH DEV TIMES
</div>

<div class="pt-8 text-gray-400">
The Modern Platform for Interactive Graphics & Animation
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://rive.app" target="_blank" alt="Rive Website"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:link />
  </a>
  <a href="https://rive.app/docs" target="_blank" alt="Rive Docs"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:document />
  </a>
</div>

---
layout: center
class: text-center
---

# The Evolution of Web Animation

<div class="grid grid-cols-3 gap-8">
<div v-click>

### Flash Era
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

</div>
<div v-click>

### HTML5 Era
- Canvas & SVG animations
- CSS animations/transitions
- Web Animations API
- JavaScript libraries
- WebGL capabilities
- Open web standards

</div>
<div v-click>

### The End of Flash
- Performance issues
- Security vulnerabilities
- Mobile incompatibility
- Closed ecosystem
- Resource intensive
- Deprecated by browsers

</div>
</div>

---
layout: center
---

# The Modern Solution: Rive

<div class="grid grid-cols-2 gap-12 mt-8">
<div v-click>

### Core Advantages
- Native performance
- Security by design
- Mobile-first approach
- Open standards
- Resource efficient
- Cross-platform support

</div>
<div v-click>

### Technical Improvements
- Vector-based efficiency
- State-driven interactions
- Real-time rendering
- Modern web standards
- Developer-friendly APIs
- Runtime optimization

</div>
</div>

---
layout: center
class: text-center
---

# Rive example
## Watch, interact, and be amazed

<div class="example-showcase">
  <RiveExample
    src="/fastwork_seasonal_logo.riv"
    :width="600"
    :height="400"
    fit="contain"
    alignment="center"
  />
</div>

---
layout: center
class: text-center
---

# Character Animation from Arcane

<div class="example-showcase">
  <RiveExample
    src="/arcane.riv"
    :width="600"
    :height="400"
    fit="contain"
    alignment="center"
  />
</div>

---
layout: center
class: text-center
---

# Interactive Guitar Character

<div class="example-showcase">
  <RiveExample
    src="/guitargirl.riv"
    :width="600"
    :height="400"
    fit="contain"
    alignment="center"
  />
</div>

---
layout: center
class: text-center
---

# Interactive Icon Pack

<div class="example-showcase">
  <RiveExample
    src="/nguyen_sieu_interactive_icon_pack.riv"
    :width="600"
    :height="400"
    fit="contain"
    alignment="center"
  />
</div>

---
layout: center
class: text-center
---

# Speed Animation

<div class="example-showcase">
  <RiveExample
    src="/bici_speed.riv"
    :width="600"
    :height="400"
    fit="contain"
    alignment="center"
  />
</div>

---
layout: center
class: text-center
---

# What about Lottie? 🤔

<div class="text-xl text-gray-400 mt-4">
Let's compare two leading animation solutions
</div>

---
layout: center
---

# Rive vs Lottie

<div class="grid grid-cols-2 gap-12 mt-8">
<div v-click>

### Lottie
- Export from After Effects
- Like a vector-based GIF
- Limited interactivity
- Needs code for interactions
- Larger animation files
- Best for simple animations

</div>
<div v-click>

### Rive
- Purpose-built animation tool
- Real-time interactivity
- Built-in state machines
- Designer-friendly controls
- Smaller animation files
- Complex interactions possible

</div>
</div>

<div class="mt-8 text-sm opacity-75" v-click>
While Lottie is great for simple animations, Rive offers a complete platform for interactive content
</div>

---
layout: center
---

# Runtime Support

<div class="grid grid-cols-2 gap-12 mt-8">
<div v-click>

### Lottie Runtime
- Plays pre-rendered animations
- Like playing a video file
- Limited to playback controls
  - Play/Pause
  - Speed control
  - Frame by frame
- Static content once exported

</div>
<div v-click>

### Rive Runtime
- Real-time animation engine
- Like a game engine
- Rich interactive controls
  - State machines
  - Dynamic mixing
  - Live parameters
- Content remains dynamic

</div>
</div>

<div class="mt-8 text-sm opacity-75" v-click>
While Lottie plays back animations like a video player, Rive runs them in real-time like a game engine
</div>

---
layout: center
---

# Real World Use Cases

<div class="grid grid-cols-2 gap-12 mt-8">
<div v-click>

### Dynamic Graphics
- Loading animations
- Micro-interactions
- Form feedback
- Menu transitions
- Component libraries
- Icon sets

</div>
<div v-click>

### Interactive Media
- Game characters
- Educational content
- Product showcases
- Marketing assets
- TV program interfaces
- Interactive menus
- Streaming app UIs

</div>
</div>

<div class="mt-8 text-sm opacity-75" v-click>
From UI components to complex interactive experiences, Rive powers modern digital interfaces
</div>

<style>
.example-showcase {
  @apply flex flex-col items-center p-8 rounded-lg border border-gray-400/20;
  max-width: 800px;
  margin: 0 auto;
}

kbd {
  @apply px-2 py-1 text-sm rounded bg-gray-200 dark:bg-gray-800;
}
</style>
