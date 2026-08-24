<script setup lang="ts">
defineProps<{
  title: string
  description: string
  tags: string[]
  category?: string
}>()
</script>

<template>
  <article class="card project">
    <div>
      <span v-if="category" class="project-category">{{ category }}</span>
      <h3>{{ title }}</h3>
      <p>{{ description }}</p>
      <div class="tags">
        <span v-for="tag in tags" :key="tag" class="tag">{{ tag }}</span>
      </div>
    </div>
  </article>
</template>
