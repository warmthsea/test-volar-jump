<template>
  <main font-sans p="x-4 y-10" text="center gray-700 dark:gray-200">
    <RouterView />
    <TheFooter />
    <img w-10 src="./assets/1.svg" alt="">
    <!--
      volar version 1.2.0 jump normal
      new volar version alias jump error
    -->
    <img w-10 src="@/assets/1.svg" alt="">
  </main>
</template>
