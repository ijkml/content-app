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
}

:deep(pre .highlight) {
  background-color: black;
}
</style>
