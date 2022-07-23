<template>
<div class="events">
  <EventCard v-for="event in events" :key="event.id" :event="event"/>
</div>
</template>
<script>
import EventCard from "../components/EventCard.vue";
export default {
  name: "EventList",
  components: {
    EventCard
  },
  data() {
    return {
      events: [
        {
          id: 234623452,
          title: "Cat Adoption Date",
          description: "Find your new feline friend at this event.",
          location: "Meow Town",
          date: "January 28, 2022",
          time: "12:00",
          petsAllowed: true,
          organizer: "Kat Laydee"
        },
        {
          id: 234623452,
          title: "Cat Adoption Date",
          description: "Find your new feline friend at this event.",
          location: "Meow Town",
          date: "January 28, 2022",
          time: "12:00",
          petsAllowed: true,
          organizer: "Kat Laydee"
        },
        {
          id: 234623452,
          title: "Cat Adoption Date",
          description: "Find your new feline friend at this event.",
          location: "Meow Town",
          date: "January 28, 2022",
          time: "12:00",
          petsAllowed: true,
          organizer: "Kat Laydee"
        },
        {
          id: 234623452,
          title: "Cat Adoption Date",
          description: "Find your new feline friend at this event.",
          location: "Meow Town",
          date: "January 28, 2022",
          time: "12:00",
          petsAllowed: true,
          organizer: "Kat Laydee"
        },
        {
          id: 234623452,
          title: "Cat Adoption Date",
          description: "Find your new feline friend at this event.",
          location: "Meow Town",
          date: "January 28, 2022",
          time: "12:00",
          petsAllowed: true,
          organizer: "Kat Laydee"
        },
        {
          id: 234623452,
          title: "Cat Adoption Date",
          description: "Find your new feline friend at this event.",
          location: "Meow Town",
          date: "January 28, 2022",
          time: "12:00",
          petsAllowed: true,
          organizer: "Kat Laydee"
        },
        {
          id: 234623452,
          title: "Cat Adoption Date",
          description: "Find your new feline friend at this event.",
          location: "Meow Town",
          date: "January 28, 2022",
          time: "12:00",
          petsAllowed: true,
          organizer: "Kat Laydee"
        },
        {
          id: 234623452,
          title: "Cat Adoption Date",
          description: "Find your new feline friend at this event.",
          location: "Meow Town",
          date: "January 28, 2022",
          time: "12:00",
          petsAllowed: true,
          organizer: "Kat Laydee"
        },
        {
          id: 234623452,
          title: "Cat Adoption Date",
          description: "Find your new feline friend at this event.",
          location: "Meow Town",
          date: "January 28, 2022",
          time: "12:00",
          petsAllowed: true,
          organizer: "Kat Laydee"
        }
        ]
    }
  }
}
</script>
<style>
.events {
  display: flex;
  flex-direction: column;
  align-items: center;

}
</style>