<template>
  <div class="navbar1">
    <div class="container d-flex justify-content-between">
      <div class="d-flex">
        <div class="dropdown">
          <button class="my-btn btn shadow-none dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            ENG
          </button>
          <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
            <a class="dropdown-item" href="#">SWE</a>
            <a class="dropdown-item" href="#">ARABIC</a>
          </div>
        </div>

        <div class="dropdown">
          <button class="my-btn btn shadow-none right-border dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            USD
          </button>
          <div class="dropdown-menu navbar1" aria-labelledby="dropdownMenuButton">
            <a class="dropdown-item" href="#">EUR</a>
            <a class="dropdown-item" href="#">Real</a>
          </div>
        </div>
      </div>
      <div class="d-flex">
        <div class="d-none d-md-block">
          <button class="my-btn btn shadow-none right-border">Newsletter</button>
          <button class="my-btn btn shadow-none right-border">Contact us</button>
          <button class="my-btn btn shadow-none right-border">FAQs</button>
        </div>
        <div class="d-flex align-items-center">
          <a href="#"><i class="fab fa-facebook-f text-white ml-2"></i></a>
          <a href="#"><i class="fab fa-twitter text-white ml-2"></i></a>
          <a href="#"><i class="fab fa-instagram text-white ml-2"></i></a>
          <a href="#"><i class="fab fa-youtube text-white ml-2"></i></a>
          <a href="#"><i class="fab fa-google-plus-g text-white ml-2"></i></a>
        </div>
      </div>
    </div>
  </div>  
</template>

<script>
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  .navbar1{
    background-color: #20D3C2;
  }

  .my-btn{
    color: #fff;
  }

  .right-border{
    border-radius: 0;
    border-right-width: 1px;
    border-right-color:white;
  }
</style>
