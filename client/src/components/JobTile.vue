<template>
  <div class="column is-half">
  
    <div class="box">
      <article class="media">
        <div class="media-left">
          <figure class="image is-64x64">
            <img src="http://bulma.io/images/placeholders/128x128.png" alt="Image">
          </figure>
        </div>
        <div class="media-content">
          <div class="content">
            <p><strong>Google</strong> <small class="is-pulled-right">Posted by: Angel.co</small></p>
            <p>Business Intelligence</p>
          </div>
          <ul>
            <li><small>google.com</small></li>
            <li><small>Hyderabad</small></li>
            <li><small>15000-20000 employees</small></li>
          </ul>
          <hr>
          <p class="job-title">Data Scientist Engineering</p>
          <p class="job-description">R Studio, Python - Hyderabad, Bangalore, Pune, Mumbai - Full Time - Equity 0.1 %- 0.5 % </p>
          <hr>
          <a class="job-apply is-pulled-right" href="#">Apply Now <i class="fa  fa-chevron-right"></i></a>
        </div>
      </article>
    </div>
  </div>  
</template>


<script>
  export default{
    name: 'jobtile'
  }
</script>

<style scoped>
  .box{
    border-radius: 3px;
  }

  ul li{
    display: inline;
    font-size: 11px;
    color: #8b8f96;
    padding-right: 3px;
  }

  .content > p{
    margin-bottom: 0rem;
  }

  .job-title{
    color: #00d1b2;
    margin-bottom: 12px;
  }

  hr{
    margin: 0.5rem 0;
  }

  .job-description{
    color: #8b8f96;
    font-size: 11px;
    font-weight: 500;
  }

  .job-apply{
    color: #4259f4;
  }

</style>