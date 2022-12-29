<script setup>
import logoImg from '../assets/logomartinspet.svg'
import {ref} from 'vue'
const showMenu = ref(false)
const displayMenu = () => {
    showMenu.value = !showMenu.value;
    
}

</script>


<template>
    <div class="header w-100 flex items-center justify-between px-3">
        <div class="container flex items-center ">
            <img :src="logoImg" class=""/>
    <h1>
        Martinspets
    </h1>
        </div>
    <div class="sm:hidden">

    
    <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"  @click="displayMenu">
    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
</svg>


</div>

    </div>
     <div class="menu-mobile container w-100 flex justify-end pr-4 mt-2" v-if="showMenu">
        <div class="flex flex-col gap-y-2">
            <h4 class="text-center">quem somos</h4>
            <h4 class="text-center">nossos animais</h4>
            <h4 class="text-center">contato</h4>
            <h4 class="text-center underline">doar</h4>
        </div>
        
     </div>


    
    


</template>

<style scoped>
.header{
    background-color: #165B38;
}
.hamburguer{
    background-color: #0D0D0D;
}
img{
    width: 80px;
    height: 80px;
}
h1{
    font-size: 28px;
    font-family: 'Alegreya', serif;
    color: #E0E0E0;
}


</style>