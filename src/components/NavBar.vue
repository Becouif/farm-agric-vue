<template>
  <!-- this template contain the header  -->
  <section class="bg-gradient-to-r from-green-800 to-green-400 " id="home">
    <div id="heading" class="font-bold">
      <nav class=" shadow-lg sm:grid-cols-1">
            <div class="max-w-6xl mx-auto px-4">
                <div class="flex justify-between">
                    <div class="flex space-x-7">
                        <!-- Website Logo -->
                        <div class="">
                            <a href="/index" class="flex items-center py-4 px-2 ">
                                <h1 class="text-gray-50 h-15 text-7xl text-center"><i class="fas fa-leaf"></i>
                                </h1>
                            </a>
                        </div>
                        <!-- Primary Navbar items -->
                        <div class=" hidden md:flex items-center space-x-7 mynavbar  ">
                            <a href="#home"
                                class="hover:text-green-800 text-gray-50 hover:bg-gray-50 nav-link">Home</a>
                            <a href="#product"
                                class="hover:text-green-800 text-gray-50 hover:bg-gray-50 nav-link">Product</a>
                            <a href="#about"
                                class="hover:text-green-800 text-gray-50 hover:bg-gray-50 nav-link">About</a>
                            <a href="#contact"
                                class="hover:text-green-800 text-gray-50 hover:bg-gray-50 nav-link">Contact</a>
                        </div>
                    </div>
                </div>
            </div>
        </nav>
    </div>
  </section>
</template>


<style scoped>
nav {
   
    position: fixed;
    top: 0;
    left: 0;
    width:100%;
    z-index:1000;
    background: rgba(22, 101, 52, 0.7);
    /* background: rgba(0, 0, 0, 0.7) */
}
div.mynavbar {
    padding-left: 47rem;
}
a.nav-link {
    padding: 1rem;
}


@media (max-width:768px) {
    
    div.mynavbar {
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-around;
        padding-left: 0; /* Remove padding on mobile */
    }
    
    /* Ensure the nav links are displayed properly on mobile */
    a.nav-link {
        /* margin:auto; */
        padding: 0.25rem; /* Adjust padding for better fit on mobile */
        text-align: center;
    }
}

</style>