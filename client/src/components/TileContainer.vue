<template>
  <div class="columns">
    <div class="column is-one-quarter">
    </div>
    <div class="column is-three-quarters">
      <div class="columns is-multiline">
        <jobtile v-for="job in 5"></jobtile>
      </div>
    </div>
  </div>
</template>

<script>
  import JobTile from './JobTile'
  
  export default {
    name: 'tilecontainer',
    components: {
      jobtile: JobTile
    }
  }
</script>

<style scoped>
  .columns{
    margin-right: 0rem;
    margin-top: 0rem;
  }
</style>