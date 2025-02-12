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

<div class="flex justify-center items-center mb-8">
  <img src="/images/flash-logo.png" class="w-24 h-24" alt="Flash Logo">
</div>

# The Evolution of Web Animation

<div class="grid grid-cols-2 gap-8">
<div v-click>

### Flash Era
- Dominated web interactivity
- Rich animation capabilities
- Cross-browser compatibility
- Designer-friendly tools
- Interactive content creation
- Widespread adoption
- Industry standard for years
- Powerful animation tools

</div>
<div v-click>

### The End of Flash & Rise of HTML5
- Performance & security issues
- Mobile incompatibility
- Closed ecosystem
- Resource intensive
- Deprecated by browsers
- Replaced by open standards (HTML5 Era)

</div>
</div>


---
layout: center
class: text-center
---

<div class="w-full">
  <img src="/images/flash-example3.png" class="w-4/5 mx-auto" alt="Flash Website Example - Higher Source">
</div>

---
layout: center
class: text-center
---

<div class="w-full">
  <img src="/images/flash-example2.png" class="w-4/5 mx-auto" alt="Flash Content Example - K10k">
</div>

---
layout: center
class: text-center
---

<div class="w-full">
  <img src="/images/flash-example1.png" class="w-4/5 mx-auto" alt="Flash Games and Applications">
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
class: text-center
---

# Lottie Creator App

<div class="w-full">
  <img src="/lottie-creator.png" class="w-6/12 mx-auto" alt="Lottie Creator Application">
</div>

---
layout: center
class: text-center
---

# Rive App

### Can import Lottie

<div class="w-full">
  <img src="/lottie-rive-import.png" class="w-4/5 mx-auto" alt="Lottie vs Rive Import Comparison">
</div>

---
layout: center
---

# Rive Runtime Support

<div class="grid grid-cols-3 gap-8 mt-8">
<div v-click>

### Web
- JavaScript/TypeScript
- React
- Vue
- Angular
- WebGL/Canvas
- Web Components

</div>
<div v-click>

### Mobile
- iOS Native
- Android Native
- React Native
- Flutter
- Cross-platform APIs
- Mobile Optimization

</div>
<div v-click>

### Game Engines
- Unity
- Bevy
- GameKit
- Custom Renderers
- State Machine Integration
- Asset Management

</div>
</div>

<div class="mt-4 text-sm opacity-75" v-click>
Source: <a href="https://help.rive.app/runtimes/overview" target="_blank" class="text-blue-500">Rive Runtimes Documentation</a>
</div>


---
layout: center
---

# Lottie Player Cross-Platform Inconsistencies

<div class="grid grid-cols-2 gap-4">
<div>
  <img src="/images/lottie-compare.png" class="w-full" alt="Lottie inconsistencies across platforms">
</div>
<div class="text-left">

Lottie runtime
- Different rendering results across platforms
- Inconsistent animation timing
- Platform-specific bugs and limitations
- Web vs Native implementations vary

</div>
</div>


---
layout: default
---

# Rive Implementation Examples

<div class="grid grid-cols-2 gap-4">

```js {all|2-8|all}
// Web Implementation
const r = new rive.Rive({
    src: "https://cdn.rive.app/animations/vehicles.riv",
    canvas: document.getElementById("canvas"),
    autoplay: true,
    stateMachines: "bumpy",
    onLoad: () => {
        r.resizeDrawingSurfaceToCanvas();
    },
});
```

```dart {all|1-2|4-13|all}
// Flutter Integration
import 'package:rive/rive.dart';

class MyRiveAnimation extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return const Scaffold(
      body: Center(
        child: RiveAnimation.network(
          'https://cdn.rive.app/animations/vehicles.riv',
          fit: BoxFit.cover,
        ),
      ),
    );
  }
}
```

</div>

<div class="mt-4 text-sm opacity-75" v-click>
Source: <a href="https://rive.app/community/doc/web-js/docvlgbnS1mp" target="_blank" class="text-blue-500">Rive Web Documentation</a>
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

.slidev-layout {
  background: #ffffff;
  color: #121212;
}
</style>


---
layout: default
---

# Rive Event Handling & State Management

<div class="grid grid-cols-2 gap-4">

```js {all|2-3|5-8|10-14|all}
// Event Listeners
const riveInstance = new rive.Rive({
    stateMachines: 'state_machine_1'

    // Listen to state changes
    onStateChange: (event) => {
        console.log('State changed:', event.data);
    },
});

// Update state machine inputs
riveInstance.setNumberState('state_machine_1', 'level', 5);
riveInstance.setBooleanState('state_machine_1', 'isHovered', true);
riveInstance.fireState('state_machine_1', 'trigger');
riveInstance.setTextState('state_machine_1', 'message', 'Hello!');
```

```js {all|2-12|14-19|all}
// Common Events
riveInstance.on('play', () => {
    console.log('Animation started');
});

riveInstance.on('pause', () => {
    console.log('Animation paused');
});

riveInstance.on('loop', () => {
    console.log('Animation looped');
});

// State Machine Inputs
const inputs = riveInstance
    .stateMachineInputs('state_machine_1');

// Get specific input
const levelInput = inputs.find(i => i.name === 'level');
```

</div>

<div class="mt-4 text-sm opacity-75" v-click>
Rive provides a rich event system and state management capabilities for interactive animations
</div>

---
layout: center
---

# Rive Real World Use Cases

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


---
layout: center
class: text-center
---

# Rive in Action: Smahjong Game UI

<div class="w-full">
  <img src="/images/example-tv.png" class="w-4/5 mx-auto" alt="Smahjong Game UI with Rive">
</div>

<div class="text-sm opacity-75 mt-4" v-click>
Interactive game interface with real-time animations and state management
</div>

---
layout: center
class: text-center
---

# Rive in Action: FigJam

<div class="w-full">
  <img src="/images/example-figjam.png" class="w-4/5 mx-auto" alt="FigJam with Rive Integration">
</div>

<div class="text-sm opacity-75 mt-4" v-click>
Collaborative design tool powered by Rive animations
</div>

---
layout: center
class: text-center
---

# Rive in Action: Interactive Learning

<div class="w-full">
  <img src="/images/example-duolingo.png" class="w-4/5 mx-auto" alt="Rive Editor Interface">
</div>

<div class="text-sm opacity-75 mt-4" v-click>
Complex state machines and character animations in Rive editor
</div>

---
layout: center
class: text-center
---

# Rive in Action: Notion Assistant

<div class="w-full">
  <img src="/images/example-notion.png" class="w-4/5 mx-auto" alt="Rive AI Integration Example">
</div>

<div class="text-sm opacity-75 mt-4" v-click>
Smart interactions with AI-powered chat interfaces and dynamic animations
</div>

---
layout: center
---

# How Rive Empowers Designers

<div class="grid grid-cols-2 gap-12 mt-8">
<div v-click>

### Design Freedom
- Familiar design tools
- Real-time preview
- Vector-based workflow
- Responsive layouts
- Asset optimization
- Direct state control

</div>
<div v-click>

### Designer → Developer
- No code required
- Built-in state machines
- Visual interaction design
- Cross-platform export

</div>
</div>

<div class="mt-8 grid grid-cols-2 gap-8">
<div v-click>

```js
// No coding required for basic interactions
<RiveComponent
  src="animation.riv"
  stateMachines="designer_states"
  autoplay={true}
/>
```

</div>
<div v-click class="text-sm opacity-75 mt-4">

"Rive removes the need for hard-coded graphics, empowering teams to iterate faster and build better products."

[Source: Rive Documentation](https://rive.app)

</div>
</div>

---
layout: center
class: text-center
---

# Interactive Rating Animation

<div class="w-full flex justify-center">
  <video
    src="/rating-star.mp4"
    class="w-3/4 mx-auto rounded-lg shadow-lg"
    autoplay
    loop
    muted
    playsinline
  ></video>
</div>

<div class="text-sm opacity-75 mt-4" v-click>
Smooth, interactive rating component built with Rive's state machine system
</div>

---
layout: center
---

# Rive State Machine Power

<div class="grid grid-cols-2 gap-12 mt-8">
<div v-click>

### Core Features
- Visual State Management
- Multiple Animation Mixing
- Input Triggers & Listeners
- Layered Animations
- Transition Controls
- Event System

</div>
<div v-click>

### State Machine Types
- Simple Playback
- Interactive Animations
- Game Logic
- Character Controllers
- Multi-state Transitions

</div>
</div>

<div class="mt-4 text-sm opacity-75" v-click>
Source: <a href="https://help.rive.app/editor/state-machine" target="_blank" class="text-blue-500">Rive State Machine Documentation</a>
</div>

---
layout: end
class: text-center
---

# Rive: The Future of Interactive Animation

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
  font-size: 2.5em;
  margin-bottom: 0.5em;
}
</style>
