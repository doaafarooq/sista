<template>
  <div class="bg-subscribe">
    <div class="container">
        <div class="row">
            <div class="col ml-3 pr-5 py-5">
                <h2>SUBSCRIBE <span class="theme-color">NOW</span></h2>
                <P class="p-subscribe">Signup for awesome news about our new products and know our special discounts on products.</P>
                <div class="mt-4 d-flex p-1 rounded-pill my-subscribe-div">
                    <input type="email" placeholder="Enter email address" class="form-control border-0 ml-2 shadow-none">
                    <button class="btn bg-theme-color text-white rounded-pill my-btn-subscribe">Subscribe</button>
                </div>
            </div>
            
            <div class="d-none d-lg-block col-lg-6 chinese-silver"></div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style>
    .bg-subscribe{
        background-color: #f6f6f6;
    }

    .p-subscribe{
        font-size: 1.14rem;
    }

    .chinese-silver{
        background-color: #ccc;
    }

    .my-subscribe-div{
        background: white;
    }
</style>