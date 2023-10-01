<script setup lang="ts">
useHead({
  bodyAttrs: {
    class: 'min-h-screen'
  },
})
</script>

<template>
  <div class="min-h-screen flex flex-col bg-white dark:bg-gray-900">
    <AppHeader />
    <main class="flex-grow">
      <section class="bg-white dark:bg-gray-900">
        <slot />
      </section>
    </main>
    <AppFooter />
  </div>
</template>
