<script setup lang="ts">
import EventCard from '@/components/EventCard.vue'
</script>

<template>
  <div class="event-list">
    <EventCard />
    <EventCard />
    <EventCard />
  </div>
</template>

<style scoped>
.event-list {
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
