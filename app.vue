<template>
  <NuxtLayout>
    <NuxtPage />
    <UNotifications />
  </NuxtLayout>
</template>

<script setup lang="ts">
useHead({
  titleTemplate: "%s - Finance Tracker",
  link: [
    {
      rel: "apple-touch-icon",
      sizes: "180x180",
      href: "/apple-touch-icon.png",
    },
    {
      rel: "icon",
      type: "image/png",
      sizes: "32x32",
      href: "/favicon-32x32.png",
    },
    {
      rel: "icon",
      type: "image/png",
      sizes: "16x16",
      href: "/favicon-16x16.png",
    },
    { rel: "manifest", href: "/site.webmanifest" },
  ],
});
</script>

<style>
/* Set the font family for the entire site */
body {
  font-family: "Inter";
}
/* Set the background color for the entire site */
body {
  @apply bg-white text-gray-800 dark:bg-gray-900 dark:text-gray-200;
}
</style>
