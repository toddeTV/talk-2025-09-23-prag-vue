---
layout: basic
---

<h1>
    <logos:nuxt-icon class="baseColor mr-2" />Nuxt Module
</h1>

<div class="w-full h-[470px] flex justify-center items-center">
  <TalkOverviewSvg :force-click="8" class="w-[100%]" />
</div>

<!-- dummy only to force the click count on this slide manually -->
<div v-click="0" />

<div class="absolute w-62 h-9 left-120 top-67" v-mark="{ at: 1, color: '#ab2657', type: 'box' }"></div>
