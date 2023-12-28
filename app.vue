<template>
    <UContainer>
      <UCard class="mt-10">
        <template #header>
          <div class="flex justify-between">
            <h1>Welcome to Nuxt UI Starter</h1>
            <ColorScheme><USelect v-model="$colorMode.preference" :options="['system', 'light', 'dark']" /></ColorScheme>
          </div>
        </template>
        <UButton icon="i-heroicons-book-open" to="https://ui.nuxt.com" target="_blank">Open Nuxt UI Documentation</UButton>
      </UCard>
    </UContainer>
    <main class="flex justify-center flex-col items-center max-w-full">
      <NuxtPage />
    </main>
    <template>
      <article class="block w-96 max-w-full ml-auto mr-auto">
        <ContentDoc />
      </article>
    </template>
</template>
