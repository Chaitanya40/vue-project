<template>
  <div class="title-banner">
    <section class="hero">
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title">WE'VE MADE YOUR JOB SEARCH EASY!</h1>
          <h2 class="subtitle">DataScienceMax curates all the job boards to get you the latest job opportunities in datascience.</h2>
        </div>    
      </div>
    </section>

      
    <div class="columns is-centered">
      <div class="column is-half">
        <div class="field is-grouped">
          <p class="control is-expanded">
            <input class="input is-medium" type="text" placeholder="Search by Skills, Company name, Location">
          </p>
          <p class="control">
            <a class="button is-primary is-medium">
            Search
            </a>
          </p>
        </div>
      </div>
      
    </div>
  </div>
</template>

<script>
  export default {
    name: 'searchcontainer'
  }
</script>

<style scoped>
  .title-banner{
    background-image: url('../assets/searchbackground.jpg');
    width: 100%;
    height: 320px;
    
  }

  input{
    border-radius: 0px !important;
  }

  .button{
    border-radius: 0px !important;
  }

  .title{
    color: white;
    line-height: 2.125;
    font-weight: 500;
  }

  .subtitle{
    color: white;
    font-size: 1.05rem;
  }

 
</style>