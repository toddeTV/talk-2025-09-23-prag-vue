<script setup lang="ts">
import sdk from '@stackblitz/sdk'
import { onMounted, toRefs } from 'vue'

const props = withDefaults(defineProps<{
  projectId: string // The StackBlitz project ID to embed.
  domElementId?: string // The ID or class of the element where the StackBlitz project will be embedded.
  forceEmbedLayout?: boolean
  hideExplorer?: boolean
  hideNavigation?: boolean
  clickToLoad?: boolean
  showSidebar?: boolean
  openFile?: string | string[]
  theme?: 'light' | 'dark' | 'default'
  view?: 'default' | 'editor' | 'preview'
}>(), {
  clickToLoad: false,
  domElementId: `stackblitz-embed-${Math.random().toString(36).substring(2, 15)}`, // Default to a random string
  forceEmbedLayout: true,
  hideExplorer: false,
  hideNavigation: false,
  openFile: 'README.md',
  showSidebar: false,
  theme: 'light',
  view: 'default',
})

const { clickToLoad, domElementId, forceEmbedLayout, hideExplorer, hideNavigation, openFile, projectId, showSidebar, theme, view } = toRefs(props)

onMounted(() => {
  sdk.embedProjectId(
    domElementId.value,
    projectId.value,
    {
      // crossOriginIsolated: true,
      clickToLoad: clickToLoad.value,
      forceEmbedLayout: forceEmbedLayout.value,
      hideExplorer: hideExplorer.value,
      hideNavigation: hideNavigation.value,
      openFile: openFile.value,
      showSidebar: showSidebar.value,
      theme: theme.value,
      view: view.value,
    },
  )
})
</script>

<template>
  <div
    :id="domElementId"
    class="h-full w-full"
  />
</template>
