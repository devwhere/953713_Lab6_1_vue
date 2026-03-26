<script setup lang="ts">
import type { Event } from '@/types'
defineProps<{ event: Event }>()
</script>

<template>
  <div class="event-class">
    <div class="event-card">
      <h2>{{ event.title }}</h2>
      <p>{{ event.description }}</p>
      <span>@{{ event.time }} on {{ event.date }}</span>
    </div>
  </div>
</template>
