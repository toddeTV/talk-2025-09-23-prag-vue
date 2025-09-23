---
layout: basic
---

# Talk Takeaway

<VClicks class="mt-7" :depth="2">

- Is it simple, framework-agnostic logic?
  - 👉 Use an **JS/TS Library**.

- Does it provide UI components or need Vue/Nuxt runtime access?
  - 👉 Use a **Vue Plugin** / **Nuxt Module**.

- Do you want the deepest integration and best DX for a Nuxt-only project?
  - 👉 Use a **Nuxt Module**.

- Do you need to hook into the build process for any framework?
  - 👉 Use **unplugin**.

</VClicks>

<div
  class="absolute w-fit h-fit px-5 py-3 left-150 top-30 font-bold text-4xl text-[#ab2657]"
  v-click="9"
  v-mark="{ at: 9, color: '#ab2657', type: 'box' }"
>
  Combine them?
</div>

<div
  class="absolute w-fit h-fit px-5 py-3 left-174 top-50 font-bold text-4xl text-[#ab2657]"
  v-click="10"
  v-mark="{ at: 10, color: '#ab2657', type: 'underline' }"
>
  YES
</div>

<!--
Summary: Choosing the Right Tool

Combining is actually already done often, e.g. see pinia, a Vue Plugin that has a Nuxt Module Wrapper.
-->
