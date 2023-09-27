<template>
  <div class="prose">
    <NuxtPage />
  </div>
</template>

<style scoped>
.prose {
  max-width: 65ch;
  margin: auto;
  padding: 4rem 1rem;
}

:deep(pre) {
  padding: 1rem;
  border-radius: 6px;
  outline: 1px solid black;
}
</style>
