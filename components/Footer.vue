<template>
    <div>
        <div class="container mx-auto">
            <div class="flex -mx-4 mb-10">
                <div class="w-1/4 px-4 flex items-center">
                    <div class="min-w-max mr-3">
                        <img width="80" src="~/assets/img/footer/call-center.png" alt="">
                    </div>
                    <div class="w-full">
                        <h3 class="text-xl font-medium mb-3">24 Customer Support</h3>
                        Contact us 24 hours
                    </div>
                </div>
                <div class="w-1/4 px-4 flex items-center">
                    <div class="min-w-max mr-3">
                        <img width="80" src="~/assets/img/footer/product.png" alt="">
                    </div>
                    <div class="w-full">
                        <h3 class="text-xl font-medium mb-3">Authentic Products</h3>
                        Contact us 24 hours
                    </div>
                </div>
                <div class="w-1/4 px-4 flex items-center">
                    <div class="min-w-max mr-3">
                        <img width="80" src="~/assets/img/footer/payment.png" alt="">
                    </div>
                    <div class="w-full">
                        <h3 class="text-xl font-medium mb-3">Secure Payment</h3>
                        Contact us 24 hours
                    </div>
                </div>
                <div class="w-1/4 px-4 flex items-center">
                    <div class="min-w-max mr-3">
                        <img width="80" src="~/assets/img/footer/offer.png" alt="">
                    </div>
                    <div class="w-full">
                        <h3 class="text-xl font-medium mb-3">Best Prices & Offers</h3>
                        Contact us 24 hours
                    </div>
                </div>
            </div>
        </div>
        <div class="bg-gray-300">
            <div class="container mx-auto py-20">
               <div class="flex">
                   <div class="w-3/5 pr-6">
                    <Logo/>
                    <p class="hb-gray-color text-base my-6 pr-16">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla diam ornare nam est gravida. Netus viverra rhoncus sit magna sapien ac eget parturient id. Est luctus dapibus quam aliquam in nisl turpis. Elit et dictum lacus morbi nec accumsan a in.</p>
                    <div class="flex">
                        <a href="#" class="mr-3"><img src="~/assets/img/footer/Apple_badge.png" alt=""></a>
                        <a href="#"><img src="~/assets/img/footer/playstore.png" alt=""></a>
                    </div>
                   </div>
                   <div class="w-1/5 pl-6">
                        <h3 class="text-2xl mb-6">About Us</h3>
                        <ul class="leading-loose">
                            <li><nuxt-link to="/">About Karte</nuxt-link></li>
                            <li><nuxt-link to="/">Contact</nuxt-link></li>
                            <li><nuxt-link to="/">Career</nuxt-link></li>
                            <li><nuxt-link to="/">Terms & Conditions</nuxt-link></li>
                            <li><nuxt-link to="/">Category</nuxt-link></li>
                        </ul>
                   </div>
                   <div class="w-1/5 pl-6">
                        <h3 class="text-2xl mb-6">Info</h3>
                        <ul class="leading-loose">
                            <li><nuxt-link to="/">information</nuxt-link></li>
                            <li><nuxt-link to="/">Shipping</nuxt-link></li>
                            <li><nuxt-link to="/">Payment</nuxt-link></li>
                            <li><nuxt-link to="/">Return</nuxt-link></li>
                            <li><nuxt-link to="/">Blog</nuxt-link></li>
                        </ul>
                   </div>
                </div> 
                <div class="flex justify-between mt-20 items-center text-xs">
                    <div class="w-1/3 px-6">
                        <a href="#"> <i class="fa fa-facebook"></i>Face</a>
                    </div>
                    <div class="w-1/3 px-6">
                        <p class="hb-gray">@2022 Copyright All Right Reserved by Bengal Shop</p>
                    </div>
                    <div class="w-1/3 px-6 flex">
                        <img class="pr-3" src="~/assets/img/footer/paypal.png" alt="">
                        <img class="pr-3" src="~/assets/img/footer/visa.png" alt="">
                        <img class="pr-3" src="~/assets/img/footer/applepay.png" alt="">
                        <img class="pr-3" src="~/assets/img/footer/gpay.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import Logo from './Logo.vue'
    export default {
  components: { Logo },
        name:"Footer"
    }
</script>

<style lang="scss" scoped>

</style>