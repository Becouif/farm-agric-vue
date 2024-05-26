<template>
  
  <section id="about" class="bg-green-800" >
        <div class="text-center w-1/4  text-gray-50 m-auto inside-about ">
            <h1 class="h1 font-bold text-3xl">Eat to Live</h1>
            <p class="font-medium message text-xl leading-8"> We are an agro industrial company that produces and
                manufactures
                food, edibles.
                We have a strong entrepreneurial culture and we continuously work towards improving every aspect of
                our operations.</p>
        </div>
    </section>
</template>

<style scoped>
#about {
    padding: 7rem;
    /* padding: 10%; */
    /* color: black; */
}

h1.h1 {
    font-family: 'Vollkorn SC', serif;
    text-decoration: underline;
}

p.message {
    font-family: 'Alegreya Sans', sans-serif;
}
@media(max-width:640px){
    #about{
        padding:6.1rem;
        /* margin: 100%; */
        /* width: 25rem; */
        height:30rem;
    }
    .inside-about {
        margin: auto;
        width: 90%;
    }
    p.message{
        width: auto;
    }
    h1.h1 {
        margin-bottom: 1rem;
        text-decoration: underline;
    }
}
</style>