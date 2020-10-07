<template>
    <div class="border-bottom">
        <div class="container py-4">
            <div class="row">

                <div class="col-5 col-lg-3 d-flex align-items-center order-lg-1">
                    <a href="#" class=""><img src="@/assets/images/Logo.png" alt="" class="ml-2"></a>
                </div>

                <div class="col-12 mt-2 mt-lg-0 col-lg-6 order-lg-2 order-3">
                    <div class="input-group">
                        <input type="search" class="form-control my-input-text shadow-none" placeholder="Search products...">
                        <div class="input-group-append">
                            <button class="rounded-0 btn border dropdown-toggle shadow-none" type="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Categories </button>
                            <div class="dropdown-menu">
                                <a class="dropdown-item" href="#">Categories 1</a>
                                <a class="dropdown-item" href="#">Categories 2</a>
                                <a class="dropdown-item" href="#">Categories 3</a>
                                <a class="dropdown-item" href="#">Categories 4</a>
                                <a class="dropdown-item" href="#">Categories 5</a>
                                <a class="dropdown-item" href="#">Categories 6</a>
                            </div>
                            <button class="btn border my-btn-search shadow-none"><i class="fas fa-search"></i></button>
                        </div>
                    </div>
                </div>

                <div class="col-7 col-lg-3 order-lg-3 text-right">
                    <button class="btn mr-1 shadow-none"><img src="@/assets/images/buttons/User icon.png" width="16px" alt=""> <img src="@/assets/images/buttons/MyAccount.png" alt="" width="66px"></button>
                    <button class="btn mx-2 p-0 shadow-none"><img src="@/assets/images/buttons/HeartIcon.png" alt="" width="18px"></button>
                    <button class="btn mr-2 p-0 shadow-none"><img src="@/assets/images/buttons/CompareIcon.png" alt="" width="18px"></button>
                    <button class="btn mr-2 p-0 shadow-none"><img src="@/assets/images/buttons/BagIcon.png" alt="" width="18px"></button>
                    <button class="btn p-0 shadow-none d-none d-lg-inline-block">$0.00</button>
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
    .my-input-text{
        border-radius: 25px 0px 0px 25px ;
    }

    .my-btn-search{
        background-color: #20D3C2;
        color: #fff;
        border-radius: 0px 25px 25px 0px ;
    }
</style>