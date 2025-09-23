---
layout: basic
---

<h1>
    <logos:unjs class="baseColor mr-2" />UnJs/Unplugin challenges
</h1>

<VClicks class="mt-7" :depth="2">

- <ant-design-frown-filled class="text-red-400" /> Esbuild does only allow watching files during specific phases of the build process
  - This limits the watch benefits for esbuild as it might not detect added/ updated models

- <ant-design-frown-filled class="text-red-400" /> `emitFiles` does not provide a way to retrieve the generated filename<br>
  (Reason is that for some bundler implementations this simply writes a file into the out dir, see esbuild)
  - Solution is to simply generate fixed filenames that bundlers take without modifications

- <ant-design-frown-filled class="text-red-400" /> No unified way to detect dev/serve vs. build
  - Solution: custom checks for the bundlers which have this distinction and where it is possible to detect this

</VClicks>

<div class="flex justify-center mt-20 font-bold text-xl text-[#ab2657]" v-click>
  The Build Tools are different and unifying them is not easy!
</div>

<div class="absolute w-150 h-17 left-52 top-117" v-mark="{ at: 8, color: '#ab2657', type: 'box' }"></div>
