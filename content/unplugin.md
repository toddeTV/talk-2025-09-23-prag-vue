---
layout: basic
---

<h1>
    <logos:unjs class="baseColor mr-2" />UnJs/Unplugin
</h1>

<div v-click class="my-7">
    The build-tool magician from UnJS.
</div>

<div class="flex justify-between">

<div class="w-[47%]">

<VClicks>

**Pros**

- ✅ Direct access to the build process
- ✅ **Write once, run everywhere**<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(Vite, Webpack, Rollup, etc.)

</VClicks>

</div>

<div class="w-[48%]">

<VClicks>

**Cons**

- ❌ Can be complex to set up for different build tools

</VClicks>

</div>

</div>

<!--
- This is where it gets powerful. We need access to the build process, and `unplugin` gives us exactly that.
- It's a unified plugin system created by the team behind Nuxt and Vite.
- The key idea is: you write your plugin logic once, and `unplugin` makes it compatible with Vite, Webpack, Rollup, and more. This is huge for library authors.
- This is exactly what we needed for the `gltf-type-toolkit`. We could read `.gltf` files and generate `.d.ts` files on the fly.
- This is the path we chose for our library because we wanted it to be usable not just in Nuxt, but in any project that uses a supported bundler.
- It's the perfect tool for framework-agnostic build-time logic. But... what if we *only* care about Nuxt?
-->
