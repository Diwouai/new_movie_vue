<template>
  <div class="home">
    <TopRated />
  </div>
</template>

<script>
  import TopRated from '../components/blog/TopRated.vue';
  export default {
    name: 'Home',
    components: {
      TopRated,
    },
  };
</script>
