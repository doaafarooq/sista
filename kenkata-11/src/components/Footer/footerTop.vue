<template>
  <div class="bg-top-footer">
    <a href="#"><div class="d-none d-lg-block float-right m-3 py-2 px-3 rounded bg-theme-color"><i class="far fa-arrow-up text-white"></i></div></a>
    <div class="container">
      <div class="row py-5">
        <div class="col-6 col-md-4 col-lg-3 mt-2">
          <a href="#"><img class="mb-2" src="@/assets/images/Logo-white.png" alt=""></a>
          <p class="mt-4 text-white my-p-footer">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Praesent enim quam, ullamcorper vel tellus vitae, tempus fringilla lectus. Donec maximus justo eu nisl convallis iaculis. Aenean laoreet.</p>
          <p class="text-white mt-5">Follow us:</p>
          <a href="#"><i class="fab fa-facebook-f theme-color mr-3"></i></a>
          <a href="#"><i class="fab fa-twitter theme-color mr-3"></i></a>
          <a href="#"><i class="fab fa-instagram theme-color mr-3"></i></a>
          <a href="#"><i class="fab fa-youtube theme-color mr-3"></i></a>
          <a href="#"><i class="fab fa-google-plus-g theme-color"></i></a>
        </div>

        <div class="col-6 col-md-4 col-lg-3 mt-2">
          <h5 class="theme-color">CONTACT INFO</h5>
          <p class="mt-4 theme-color">Address:</p>
          <p class="text-white">Solna Business Park <br> Feni-2500, Stockholm</p>
          <p class="theme-color">Phone:</p>
          <p class="text-white">+08-123456789 <br> +08-123456789</p>
          <p class="theme-color">Emil:</p>
          <p class="text-white">support@website.se <br> info@website.se</p>
        </div>

        <div class="col-6 col-md-4 col-lg-3 mt-2">
          <h5 class="theme-color">USEFUL LINKS</h5>
          <a href="#" class="text-white text-decoration-none"><p class="mt-4">Privacy Policy</p></a>
          <a href="#" class="theme-color"><p>Terms &amp; Conditions</p></a>
          <a href="#" class="text-white text-decoration-none"><p>Contact Us</p></a>
          <a href="#" class="text-white text-decoration-none"><p>Our Sitemap</p></a>
          <a href="#" class="text-white text-decoration-none"><p>Latest News</p></a>
          <a href="#" class="text-white text-decoration-none"><h6>Returns</h6></a>
        </div>
        <div class="d-none d-lg-block col-lg-3 mt-2">
          <h5 class="theme-color">RECENT INSTAGRAM</h5>
          <div class="mt-4">
            <div class="d-flex justify-content-between">
              <div class=" rounded bg-insta"></div>
              <div class=" rounded bg-insta"></div>
              <div class=" rounded bg-insta"></div>
            </div>

            <div class="d-flex justify-content-between my-3">
              <div class=" rounded bg-insta"></div>
              <div class=" rounded bg-insta-theme"></div>
              <div class=" rounded bg-insta"></div>
            </div>
            
            <div class="d-flex justify-content-between">
              <div class=" rounded bg-insta"></div>
              <div class=" rounded bg-insta"></div>
              <div class=" rounded bg-insta"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
  .bg-theme-color{
    background-color: #20D3C2 ; 
  }

  .theme-color{
    color:#20D3C2;
  }

  .my-p-footer{
    font-size: 0.92rem;
  }

  .bg-top-footer{
    background-color: #0E153D;
    border-top:5px solid #20D3C2;
  }

  .bg-insta{
    background-color:#e3e3e3;
    width: 75px;
    height: 75px;
  }

  .bg-insta-theme{
    background-color:#20D3C2;
    width: 75px;
    height: 75px;
  }
</style>