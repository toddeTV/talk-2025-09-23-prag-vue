---
layout: basic
---

# Game, Code & Licenses

<!-- <div class="absolute right-15 top-18 p-1 pr-2 text-xs flex gap-2" v-mark="{ at: 0, color: '#26ab7a', type: 'box' }">
    <mdi-heart class="text-red-400 animate-pulse" />
    <span>NAME</span>
    <div>
      <mdi-github class="baseColor" />
      <MyLink to="https://github.com/NAME">NAME</MyLink>
    </div>
</div> -->

<div class="flex flex-row justify-between gap-8 mt-8">
    <div
        class="p-4 flex flex-col items-center"
        v-mark="{ at: 0, color: '#26ab7a', type: 'box' }"
    >
        <QRCode content="https://github.com/toddeTV/talk-2025-09-23-prag-vue" :size="128" class="mb-6" />
        <div class="flex flex-col gap-2">
            <div class="whitespace-nowrap">
                Presentation Slides Source
            </div>
            <div class="w-full text-sm">
                <mdi-github class="baseColor mx-2" />
                <MyLink to="https://github.com/toddeTV/talk-2025-09-23-prag-vue">https://github.com/toddeTV/talk-2025-09-23-prag-vue</MyLink>
            </div>
        </div>
    </div>
</div>

<div class="mt-8 flex gap-8">
    <div>
        <div class="p-2" v-mark="{ at: 0, color: '#26ab7a', type: 'box' }">
            <h2 class="!mb-2 !mt-0">Licenses</h2>
            <div class="text-xs">
                For detailed information regarding the materials used in this presentation - including 3D models, images, dependencies, icon packs, etc. - and their respective licenses and copyrights, please refer to the <code>README.md</code> file in the publicly available source code of these presentation slides, see above.
            </div>
        </div>
    </div>
    <div class="p-2 flex-shrink-0 flex gap-4">
        <div>
            <img
                alt="Avatar of Thorsten Seyschab"
                class="rounded-full w-full border-3 border-baseColor h-30 w-30"
                src="/assets/thorsten-seyschab.jpg"
            >
        </div>
        <div>
            <div class="baseColor font-semibold">Thorsten Seyschab</div>
            <div class="flex gap-4">
                <div>
                    <div class="flex">
                        <mdi-web class="baseColor mt-0.5 mr-2" />
                        <MyLink to="https://todde.tv/">todde.tv</MyLink>
                    </div>
                    <div class="flex">
                        <simple-icons-x class="baseColor mt-0.5 mr-2" />
                        <MyLink to="https://x.com/toddeTV">toddeTV</MyLink>
                    </div>
                    <div class="flex">
                        <simple-icons-twitch class="baseColor mt-0.5 mr-2" />
                        <MyLink to="https://www.twitch.tv/toddeTV">toddeTV</MyLink>
                    </div>
                </div>
                <div>
                    <div class="flex">
                        <mdi-github class="baseColor mt-0.5 mr-2" />
                        <MyLink to="https://github.com/toddeTV">toddeTV</MyLink>
                    </div>
                    <div class="flex">
                        <simple-icons-bluesky class="baseColor mt-0.5 mr-2" />
                        <MyLink to="https://bsky.app/profile/todde.tv">todde.tv</MyLink>
                    </div>
                    <div class="flex">
                        <mdi-linkedin class="baseColor mt-0.5 mr-2" />
                        <MyLink to="https://www.linkedin.com/in/toddetv/">toddeTV</MyLink>
                    </div>
                    <!-- TODO wrong discord URI? -->
                    <!-- <div class="flex">
                        <mdi-discord class="baseColor mt-0.5 mr-2" />
                        <MyLink to="https://discordapp.com/users/todde.tv/">todde.tv</MyLink>
                    </div> -->
                </div>
            </div>
        </div>
    </div>
</div>
