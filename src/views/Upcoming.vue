<template>
  <div class="upcoming">
    <NewMovie />
  </div>
</template>

<script>
import NewMovie from "../components/blog/NewMovie.vue";

export default {
  name: "Upcoming",
  components: {
    NewMovie,
  },
};
</script>
