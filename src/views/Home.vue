<template>
  <div class="home">
    <EventCard v-for="event in events" :key ="event.id" :event="event" />
  <!-- <EventCard/> -->
  </div>
</template>

<script>
// @ is an alias to /src
import EventCard from '../components/EventCard.vue';

export default {
  name: "Home",
    data(){
    return{
      events:[
        {
          id: 1,
          date: "Feburary 20",
          time: "13:30"
        },
        {      
          id: 2,
          date: "januar 15",
          time: "15:30"
        },
        {
          id: 3,
          date: "june 12",
          time: "17:24"
        }
      ]}},
  components: {
    EventCard
  },
  
};
</script>
