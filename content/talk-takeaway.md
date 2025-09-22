---
layout: basic
---

# Talk Takeaway

Summary: Choosing the Right Tool

- Is it simple, framework-agnostic logic?
  - 👉 Use an **JS/TS Library**.

- Does it provide UI components or need Vue/Nuxt runtime access?
  - 👉 Use a **Vue Plugin** / **Nuxt Module**.

- Do you want the deepest integration and best DX for a Nuxt-only project?
  - 👉 Use a **Nuxt Module**.

- Do you need to hook into the build process for any framework?
  - 👉 Use **unplugin**.

<div
  class="absolute w-fit h-fit px-5 py-3 left-150 top-30 font-bold text-4xl text-[#ab2657]"
  v-click="1"
  v-mark="{ at: 1, color: '#ab2657', type: 'box' }"
>
  Combine them?
</div>

<div
  class="absolute w-fit h-fit px-5 py-3 left-174 top-50 font-bold text-4xl text-[#ab2657]"
  v-click="2"
  v-mark="{ at: 2, color: '#ab2657', type: 'underline' }"
>
  YES
</div>

<!--
Combining is actually already done often, e.g. see pinia, a Vue Plugin that has a Nuxt Module Wrapper.
-->
