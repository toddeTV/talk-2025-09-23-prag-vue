---
layout: basic
---

<h1>
    <logos:vue class="baseColor mr-2" />Vue Plugin
</h1>

<div v-click class="my-7">
    A step closer to the framework.
</div>

<div class="flex justify-between">

<div class="w-[47%]">

<VClicks>

**Pros**

- ✅ Integrates with the Vue app instance
- ✅ Can provide components, directives, and<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;global properties (`app.provide`)
- ✅ Good for UI-related libraries

</VClicks>

</div>

<div class="w-[47%]">

<VClicks>

**Cons**

- ❌ Still no deep integration with the build process
- ❌ Limited to Vue's runtime capabilities

</VClicks>

</div>

</div>

<!--
- Okay, so a pure JS/TS Library is not enough. What if we make it a Vue plugin?
- This is much better for anything that needs to interact with Vue itself. We can register global components, add custom directives, or inject helpers available in every component.
- Many UI libraries like Vuetify or PrimeVue are essentially Vue plugins.
- But for our GLTF problem, we're still stuck. A Vue plugin operates at *runtime*. It's executed when your Vue application starts in the browser. Our type generation needs to happen at *build time*.
- So, a Vue plugin alone doesn't solve our core issue, but it's a good tool for other kinds of problems.
-->
