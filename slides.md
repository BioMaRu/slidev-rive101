---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://rive.app/static/img/features/editor.png
# some information about your slides (markdown enabled)
title: Rive 101
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
highlighter: shiki
lineNumbers: false
---

# Rive 101
Interactive Graphics & Animation Platform

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
layout: image-right
image: https://rive.app/static/img/features/state-machine.png
---

# What is Rive?

<v-clicks>

- Modern platform for **interactive animations**
- Real-time vector graphics engine
- State-driven animations
- Cross-platform runtime
- Single source of truth for design & development
- Production-ready assets

</v-clicks>

---
layout: two-cols
---

# For Designers 🎨

<v-clicks>

- Familiar vector design tools
- Timeline-based animation
- State Machine for interactions
- Real-time preview
- No code required
- Asset optimization

</v-clicks>

::right::

# For Developers 💻

<v-clicks>

- Multiple runtime SDKs
- High performance (120 fps)
- Small file sizes
- Programmatic control
- State-driven architecture
- Easy integration

</v-clicks>

---
layout: center
class: text-center
---

# Core Concepts

<div class="grid grid-cols-2 gap-4 mt-4">
<div v-click class="flex flex-col items-center">
  <div class="text-3xl mb-2">🎨</div>
  <h3>Artboards</h3>
  <p class="text-sm opacity-75">Canvas for your designs</p>
</div>
<div v-click class="flex flex-col items-center">
  <div class="text-3xl mb-2">⚡</div>
  <h3>State Machine</h3>
  <p class="text-sm opacity-75">Control interactive behaviors</p>
</div>
<div v-click class="flex flex-col items-center">
  <div class="text-3xl mb-2">🎬</div>
  <h3>Animations</h3>
  <p class="text-sm opacity-75">Timeline-based animations</p>
</div>
<div v-click class="flex flex-col items-center">
  <div class="text-3xl mb-2">🔄</div>
  <h3>Runtime</h3>
  <p class="text-sm opacity-75">Cross-platform playback</p>
</div>
</div>

---
layout: default
---

# Code Examples

<div class="grid grid-cols-2 gap-4">

```ts {all|1-2|4-9|all}
// React Integration
import { useRive } from '@rive-app/react-canvas';

function RiveComponent() {
  const { RiveComponent } = useRive({
    src: 'animation.riv',
    stateMachines: 'state_machine_name',
    autoplay: true
  });

  return <RiveComponent />;
}
```

```dart {all|1-2|4-8|all}
// Flutter Integration
import 'package:rive/rive.dart';

class RiveAnimation extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return RiveAnimation.asset('assets/animation.riv');
  }
}
```

</div>

---
layout: center
---

# Live Rive Example

<div class="grid grid-cols-2 gap-4">
<div class="w-full">

### Interactive Animation
Try interacting with this Rive animation:

<RiveExample
  src="/how-reward.riv"
  width="400"
  height="300"
  fit="contain"
  alignment="center"
/>

</div>
<div class="w-full">

```ts
// Vue Integration
import { Rive, Layout } from '@rive-app/canvas';

new Rive({
  canvas: canvasElement,
  src: '/how-reward.riv',
  layout: new Layout({
    fit: 'contain',
    alignment: 'center'
  }),
  autoplay: true
});
```

</div>
</div>

---
layout: center
class: text-center
---

# Use Cases

<div class="grid grid-cols-3 gap-4 mt-4">
<div v-click class="text-center p-4">
  <carbon:application class="text-3xl mb-2" />
  <h3>UI/UX</h3>
  <p class="text-sm opacity-75">Interactive interfaces</p>
</div>
<div v-click class="text-center p-4">
  <carbon:game-console class="text-3xl mb-2" />
  <h3>Games</h3>
  <p class="text-sm opacity-75">Game UI & characters</p>
</div>
<div v-click class="text-center p-4">
  <carbon:mobile class="text-3xl mb-2" />
  <h3>Mobile</h3>
  <p class="text-sm opacity-75">Rich experiences</p>
</div>
</div>

---
layout: center
class: text-center
---

# Getting Started

<v-clicks>

1. Download Rive Editor
2. Choose your platform runtime
3. Create or import assets
4. Add states and animations
5. Export and integrate

</v-clicks>

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Visit <a href="https://rive.app" target="_blank">rive.app</a> to start <carbon:arrow-right class="inline"/>
  </span>
</div>

---
layout: end
---

# Resources

- 📚 [Documentation](https://rive.app/docs)
- 💬 [Community](https://discord.gg/rive)
- 🎨 [Examples](https://rive.app/community)
- 🛠️ [Runtime SDKs](https://rive.app/runtimes)

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>
