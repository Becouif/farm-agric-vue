<template>
  
<section id="product">
    <!-- start of my product section html with tailwindcss -->
    <div class="p-10 grid grid-cols-2 text-gray-50 place-items-center mb-30 text-center inside-product">
        <!--Card 1-->
        <div class="each-product hover:text-gray-50 text-green-800 hover:bg-green-800 max-w-sm rounded overflow-hidden shadow-lg bg-gray-50 rounded-r-3xl	">
            <a href="">
                <img class="w-full " src="/images/ball_pepper.jpg" alt="Mountain">
                <div class="px-6 py-4">

                    <p class=" text-base font-bold text-xl mb-2 ">
                        Ball Pepper
                    </p>

                </div>
            </a>
        </div>
        <!-- end of card -->
        <!--Card 2-->
        <div class="each-product hover:text-gray-50 text-green-800 hover:bg-green-800 max-w-sm rounded overflow-hidden shadow-lg bg-gray-50 rounded-r-3xl	">
            <a href="">
                <img class="w-full" src="/images/green_chili_pepper.jpg" alt="Mountain">
                <div class="px-6 py-4">

                    <p class="text-base font-bold text-xl mb-2">
                        Green Chili Pepper
                    </p>

                </div>
            </a>
        </div>
        <!-- end of card -->
        <!--Card 3-->

        <div class="each-product hover:text-gray-50 text-green-800 hover:bg-green-800 max-w-sm rounded overflow-hidden shadow-lg bg-gray-50 rounded-r-3xl	">
            <a href="">
                <img class="w-full" src="/images/red_chili.jpg" alt="Mountain">
                <div class="px-6 py-4">

                    <p class="text-base font-bold text-xl mb-2">
                        Red Chili Pepper
                    </p>


                </div>
            </a>
        </div>
        <!-- end of card -->
        <!--Card 4-->

        <div class="each-product hover:text-gray-50 text-green-800 hover:bg-green-800 max-w-sm rounded overflow-hidden shadow-lg bg-gray-50 rounded-r-3xl	">
            <a href="">
                <img class="w-full" src="/images/onion2.jpg" alt="Mountain">
                <div class="px-6 py-4">
                    <p class="text-base font-bold text-xl mb-2">
                        Onion
                    </p>


                </div>
            </a>
        </div>
        <!-- end of card -->
    </div>

</section>
</template>


<style scoped>
section#product {
    /* margin-top: -13rem; */
}
.inside-product {
    padding: 1rem;
    margin: 1rem;
}
.each-product {
    /* padding: 2px; */
    margin:0px 0px 5px 5px;
    height: 250px;
    /* border-radius: 9%; */
}
.each-product img {
width: 100%;
height: 185px;
}
.each-product p {
    width:auto;
    margin: auto;
    font-size: 0.9rem;
}
</style>