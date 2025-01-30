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
  sans: 'Tomorrow'
  mono: 'Tomorrow'
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

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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

# Let the Show Begin! 🎬
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

---
layout: center
class: text-center
---

# Real-World Applications

<div class="grid grid-cols-3 gap-6 mt-8">
<div v-click class="app-card">
  <carbon:application class="text-4xl mb-4" />
  <h3>Web Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Loading states</li>
    <li>Micro-interactions</li>
    <li>Interactive forms</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:game-console class="text-4xl mb-4" />
  <h3>Games</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Character animations</li>
    <li>UI elements</li>
    <li>Menu transitions</li>
  </ul>
</div>

<div v-click class="app-card">
  <carbon:mobile class="text-4xl mb-4" />
  <h3>Mobile Apps</h3>
  <ul class="text-sm mt-2 text-left">
    <li>Onboarding flows</li>
    <li>Animated icons</li>
    <li>Navigation</li>
  </ul>
</div>
</div>

<style>
.app-card {
  @apply p-6 rounded-lg border border-gray-400/20 text-center;
}
.app-card ul {
  @apply list-none;
}
</style>

---
layout: center
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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
---

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era (1996-2020)
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption

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

<div class="mt-8 text-center text-sm opacity-75" v-click>
Flash revolutionized web animation but couldn't adapt to modern web needs
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
class
