<script>

</script>

<template>
    <main class="w-1/5">
        <div class="fixed text-white flex flex-col items-center">
            <p class="self-center">MariFlores</p>
            <nav class=" flex flex-col">
                <a class="border-y-4 border-r-4 border-pink text-pink text-center font-bold hover:bg-pink hover:text-white" href="#about">Quien soy</a>
                <a class="border-y-4 border-r-4 border-yellow text-yellow text-center font-bold hover:bg-yellow hover:text-white" href="#skills">Mis Habilidades</a>
                <a class="border-y-4 border-r-4 border-green text-green text-center font-bold hover:bg-green hover:text-white" href="#projects">Mis proyectos</a>
                <a class="border-y-4 border-r-4 border-purple text-purple text-center font-bold hover:bg-purple hover:text-white" href="#contact">Contacto</a>
            </nav>
        </div>  
    </main>
</template>

<style scoped>
main{
    background-color: #331a38;

}
a{
    height: 3em;
    border-radius: 0px 50px 50px 0px;
    width: 150%;
    transition: width 1s;
}
a:hover{
    width: 200%;
}


</style>