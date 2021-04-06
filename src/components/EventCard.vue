<template>
  <div class="event-card">
    <span>{{ event.date }} on {{event.time}} </span>
    <!-- hello -->
  </div>
</template>

<script>
export default {
  name: "EventCard",
  props: {
    event: Object
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.event-card {
  padding: 20px;
  width: 250px;
  cursor: pointer;
  border: 1px solid #39495c;
  margin-bottom: 18px;
}
</style>
