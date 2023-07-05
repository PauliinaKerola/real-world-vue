<script setup>
import EventCard from '@/components/EventCard.vue';
import { ref } from 'vue';
const events=ref([
  {
  id:5928101,
  category:'animal welfare',
  title:'Feed the animals',
  description:'Feed all animals.',
  location:'Meow Town',
  date:'January 28, 2023',
  time:'12:00',
  petsAllowed:true,
  organizwr:'Kat Laydee'
  },
  {
  id:5928101,
  category:'animal welfare',
  title:'Feed the animals',
  description:'Feed all animals.',
  location:'Meow Town',
  date:'January 28, 2023',
  time:'12:00',
  petsAllowed:true,
  organizwr:'Kat Laydee'
  },
  {
  id:5928101,
  category:'animal welfare',
  title:'Feed the animals',
  description:'Feed all animals.',
  location:'Meow Town',
  date:'January 28, 2023',
  time:'12:00',
  petsAllowed:true,
  organizwr:'Kat Laydee'
  },
  {
  id:5928101,
  category:'animal welfare',
  title:'Feed the animals',
  description:'Feed all animals.',
  location:'Meow Town',
  date:'January 28, 2023',
  time:'12:00',
  petsAllowed:true,
  organizwr:'Kat Laydee'
  },

])

</script>

<template>
  <h1>Events For Good</h1>

  <div class="events">
    <EventCard v-for="event in events" :key="event.id" :event="event"/>
  </div>
</template>

<style scoped>

.events{
  display:flex;
  flex-direction: column;
  align-items: center;
}
</style>
