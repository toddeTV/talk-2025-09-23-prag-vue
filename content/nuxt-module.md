---
layout: basic
---

<h1>
    <logos:nuxt-icon class="baseColor mr-2" />Nuxt Module
</h1>

<div v-click class="my-7">
    The ultimate integration for Nuxt.
</div>

<div class="flex justify-between">

<div class="w-[50%]">

<VClicks>

**Pros**

- ✅ Deep integration with Nuxt's build and runtime
- ✅ Access to hooks, virtual file system, and more

</VClicks>

</div>

<div class="w-[43%]">

<VClicks>

**Cons**

- ❌ Nuxt-only

</VClicks>

</div>

</div>

<!--
- This brings us to the final option: a Nuxt module.
- Think of a Nuxt module as a super-powered plugin specifically for Nuxt. It can do everything the other options can, and more.
- A Nuxt module can interact with the build process (often by using `unplugin` internally!), but it also has full access to the Nuxt runtime via a powerful hook system.
- It can add pages, components, composables, server routes, and configure almost every aspect of a Nuxt application.
- The biggest advantage is the developer experience. A user just installs the module, adds it to their `nuxt.config.ts`, and everything is set up automatically. No complex configuration needed.
- The only 'downside' is that it's Nuxt-specific. But if your target audience is the Nuxt ecosystem, this is the most powerful and elegant solution.
-->
