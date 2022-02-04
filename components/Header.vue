<template>
    <div>
        <div class="container mx-auto ">
            <div class="py-6 flex justify-between">
                <Logo/>
                <div class="w-96 items-center pt-4">
                    <div class="border border-gray-100 p-1 flex rounded-full items-center">
                        <div class="min-w-max px-3">
                            <img src="~/assets/img/search.png" alt="">
                        </div>
                    
                    <input class="w-full p-3 py-1 focus:outline-none" type="search" placeholder="Search here ...">
                    <button class="hb-gray-backgrund px-6 rounded-full py-2 text-white">Search</button>
                    </div>
                </div>
                
                <div class="min-w-max flex items-center">
                    <nuxt-link to="/"><span class="hb-icon-box rounded-full hover:bg-gray-200 inline-block flex items-center justify-center "><img src="~/assets/img/heart.png" alt=""></span></nuxt-link>
                    <nuxt-link to="/" class="relative m-3"><span class="hb-icon-box rounded-full hover:bg-gray-200 inline-block flex items-center justify-center"><img src="~/assets/img/shop.png" alt=""></span><span class="absolute bg-red-600 w-4 h-4 top-0 right-0 rounded-full text-xs flex justify-center items-center">0</span></nuxt-link>
                    <nuxt-link to="/" class="flex items-center"><span class="hb-icon-box rounded-full hover:bg-gray-200 inline-block flex items-center justify-center"><img src="~/assets/img/man.png" alt=""></span><span>account</span></nuxt-link>
                </div>
            </div>
            <div class="flex">
                <div class="w-96">
                    <div class="hb-green-background flex rounded-full px-4 py-2 cursor-pointer">
                        <div class="min-w-max">
                            <img src="~/assets/img/menu-right.png" alt="">
                        </div>
                        <div class="w-full text-white text-center px-6">
                            All Categories
                        </div>
                        <div class="min-w-max">
                            <img src="~/assets/img/chevron-down.png" alt="">
                        </div>
                    </div>
                </div>
                <div class="w-full items-center">
                    <ul class="flex justify-center">
                        <li><nuxt-link to="/" class="p-4">Home</nuxt-link></li>
                        <li><nuxt-link to="/" class="p-4">Shop</nuxt-link></li>
                        <li><nuxt-link to="/" class="p-4">Pages</nuxt-link></li>
                        <li><nuxt-link to="/" class="p-4">Blogs</nuxt-link></li>
                        <li><nuxt-link to="/" class="p-4">Contact</nuxt-link></li>
                        <li><nuxt-link to="/" class="p-4">Track Order</nuxt-link></li>
                    </ul>
                </div>
                <div class="min-w-max">
                    <nuxt-link to="/" class="hb-orange-color flex">
                        <img class="mr-3" src="~/assets/img/u_percentage.png" alt=""> Special Offers!
                    </nuxt-link>
                </div>
                


            </div>
        </div>
    </div>
</template>

<script>
import Logo from './Logo.vue'
    export default {
        components: { Logo },
        name:"Header"
    }
</script>

<style lang="scss" scoped>

</style>