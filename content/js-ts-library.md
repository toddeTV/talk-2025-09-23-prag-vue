---
layout: basic
---

<h1>
    <logos:javascript class="baseColor mr-2" />JS/TS Library
</h1>

<div v-click class="my-7">
    The simplest way to share code.
</div>

<div class="flex justify-between">

<div class="w-[40%]">

<VClicks>

**Pros**

- ✅ Framework-agnostic
- ✅ Easy to publish and consume
- ✅ Good for pure logic (utils, helpers)

</VClicks>

</div>

<div class="w-[57%]">

<VClicks>

**Cons**

- ❌ No integration with the build process (Vite, Webpack)
- ❌ No access to Vue's/Nuxt's context (hooks, runtime config)
- ❌ Configuration can be complex for the user
- ❌ No auto-imports or conventions

</VClicks>

</div>

</div>

<!--
- Start with the most basic approach. We have some code, we want to reuse it. The first thought is often: let's put it in a JS/TS Library.
- This works perfectly for simple, self-contained logic. Think of libraries like `lodash` or `date-fns`.
- For our GLTF problem, this falls short. Why? Because we need to hook into the build process. We need to find all `.gltf` files, parse them, and generate TypeScript types *before* the application code is even compiled.
- A simple JS/TS Library can't do that. It's just a collection of functions or objects that you import. It doesn't have the power to interact with the build tools. -->
