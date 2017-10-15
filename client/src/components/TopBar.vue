<template>
  <nav class="navbar is-transparent" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a class="navbar-item" href="http://bulma.io">
        <img src="http://bulma.io/images/bulma-logo.png" alt="Bulma: a modern CSS framework based on Flexbox" width="112" height="28">
      </a>

      <button class="button navbar-burger">
        <span></span>
        <span></span>
        <span></span>
      </button>
    </div>
    <div class="navbar-menu">
      <div class="navbar-start">
        
      </div>
      <div class="navbar-end">
        <a class="navbar-item" href="#">
          <span>
            CONTACT
          </span>
        </a>
        <a class="navbar-item" href="#">
          <span>
            Follow us
          </span>
        </a>
        <a class="navbar-item" href="https://twitter.com/jgthms" target="_blank">
          <span class="icon" style="color: #3b5998;">
            <i class="fa fa-lg fa-facebook-square"></i>
          </span>
        </a>
        <a class="navbar-item" href="https://twitter.com/jgthms" target="_blank">
          <span class="icon" style="color: #55acee;">
            <i class="fa fa-lg fa-twitter"></i>
          </span>
        </a>
        <a class="navbar-item" href="https://twitter.com/jgthms" target="_blank">
          <span class="icon" style="color: #0077B5">
            <i class="fa fa-lg fa-linkedin"></i>
          </span>
        </a>
        <a class="navbar-item" href="https://twitter.com/jgthms" target="_blank">
          <span class="icon" style="color: #d34836">
            <i class="fa fa-lg fa-google-plus"></i>
          </span>
        </a>
      </div>
    </div>
  </nav>  
</template>

<script>
  export default{
    name: 'topbar'
  }
</script>


<style scoped>
  
  .container{
    background-color: white;
    margin-left: 0px !important;
    padding-left: 20px !important
  }
  .site-title{
    padding: 12px;
    font-weight: 600;
    font-size: 18px;
    font-family: 'Nova Slim', cursive;
  }

  .contact{
    padding-left: 13px;
    padding-top: 12px; 
  }
  a {
    color: black;
    font-size: 13px;
  }

  a:hover{
    text-decoration: none;
  }    
</style>