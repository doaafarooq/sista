<template>
  <div class="container py-5">
    <div class="text-center py-2">
        <h1 class="font-weight-bold">TOP <span class="theme-color">SELLERS</span></h1>
        <img src="@/assets/images/line.png" alt="">
        <p class="mt-2">Check out our weekly top sellers in all category</p>
    </div>
    
    <div class="row justify-content-center">
        <div class="col-12 col-md-5 bg-topsellers-divs rounded p-0 mb-2 mb-md-0 mr-md-2">
          <img src="../assets/images/Partners/Bexim.png" class="top-sellers-logo rounded" width="35%" alt="">
          <img src="../assets/images/topsellers1.png" alt="" class="d-flex mx-auto" width="100%">
          <div class="pl-3 py-2 bg-Midnight-Express text-white">Men's denim shirts full</div>
        </div>

        <div class="col-12 col-md-5 p-0 ml-md-2 align-self-center">
            <div class="bg-topsellers-divs mb-2">
              <img src="../assets/images/Partners/Lighton.png" class="top-sellers-logo rounded" width="35%" alt="">
              <img src="../assets/images/topsellers2.png" class="d-flex mx-auto" alt="" width="100%">
              <div class="pl-3 py-2 bg-Midnight-Express text-white">Womens's leather dag and shoe</div>
            </div>
            
            <div class="bg-topsellers-divs">
              <img src="../assets/images/Partners/Rosimo.png" class="top-sellers-logo rounded" width="35%" alt="">
              <img src="../assets/images/topsellers3.png" class="d-flex mx-auto" alt="" width="100%">
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
  .bg-topsellers-divs{
    background-color:#eee;
  }

  .top-sellers-logo{
    position: absolute;
    margin-top: 1rem;
    margin-left: 0.75rem;
    background-color: #fff;
    padding: 0.5rem;
  }
</style>