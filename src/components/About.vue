<template>
    <div class="container-about flex flex-col sm:flex-row">
    <div class="div-about mt-5 flex flex-col gap-y-10 p-5 sm:w-3/4">
        <h1 class="text-3xl sm:text-4xl font-bold text-center sm:text-left">
            QUEM SOMOS
        </h1>
        <div class="div-paragraphs flex flex-col gap-y-5 leading-7 text-center sm:text-left text-base sm:text-xl">
            <p>
            Somos uma organização sem fins lucrativos criada com o objetivo de dar lares e cuidar de animais que são abandonados.

        </p>
        <p>
            Você também pode fazer parte desta história, contamos com o apoio de milhares de amantes de pets. Junte-se você também e dê um pouco de amor para os nossos pequenos. <span class="cursor-pointer underline">doar</span>

        </p>

        </div>
       
    </div>
    <div class="div-achievements flex flex-col gap-y-8 sm:mt-28 p-5 sm:border-l-2">
        <h2 class="text-xl text-center font-medium sm:text-2xl">NOSSAS CONQUISTAS</h2>
        <ul class="ul-achievements flex flex-col gap-y-4">
            <li class="flex w-100 gap-x-3">
                <dog-icon fillColor="#165B38"/> 
                <span>
                    Mais de 3000 brasileiros já doaram
                </span>
                
            </li>
            <li class="flex w-100 gap-x-3">
                <dog-icon fillColor="#165B38"/>
                <span>
                    1500 pets resgatados
                </span> 
                
            </li>
            <li class="flex w-100 gap-x-3">
                <dog-icon fillColor="#165B38"/>  
                <span>
                    Pets doados para mais de 15 estados
                </span>
                
            </li>
            <li class="flex w-100 gap-x-3">
                <dog-icon fillColor="#165B38"/> 
                <span>
120 Funcionários amantes de pets na equipe.
                </span>
                
            </li>

        </ul>
    </div>
</div>
</template>

<script setup>
import DogIcon from 'vue-material-design-icons/Dog.vue';

</script>
<style scoped>
.div-about h1{
    font-family: 'Alegreya',serif;


}
.div-achievements{
    border-color: #165B38;
}
.div-achievements h2{
    font-family: 'Alegreya',serif;
    color: #165B38;
}
.ul-achievements li {
    color: #165B38;
}

.div-paragraphs{
    font-family: 'Roboto',sans-serif;
    color: #2B2B2B;
}

</style>