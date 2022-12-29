<script setup>
import logoImg from '../assets/logomartinspet.svg'
import {ref} from 'vue'
const showMenu = ref(false)
const displayMenu = () => {
    showMenu.value = !showMenu.value;
    
}

</script>


<template>
    <div class="header w-100 flex items-center justify-around px-3">
        <div class="flex items-center ">
            <img :src="logoImg" class=""/>
    <h1>
        Martinspets
    </h1>
        </div>
        <div class="menu-desktop hidden mr-30 gap-x-5 sm:flex items-center mt-0.5">
            <h4>quem somos</h4>
            <h4>nossos animais</h4>
            <h4>contato</h4>
        </div>
        <button class="menu-desktop-button hidden sm:flex mt-2 p-2 rounded items-center justify-center ">doar</button>
    <div class="sm:hidden">

    
    <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"  @click="displayMenu">
    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
</svg>


</div>

    </div>
     <div class="menu-mobile container w-100 flex justify-end pr-5 mt-2" v-if="showMenu">
        <div class="menu-mobile-list flex flex-col gap-y-2">
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
    font-weight: 600;
    font-size: 28px;
    font-family: 'Alegreya', serif;
    color: #E0E0E0;
}
.menu-desktop h4{
    font-size: 16px;
    font-family: 'Roboto',sans-serif;
    font-weight: 400;
    color: #E0E0E0;
}
.menu-desktop-button{
    font-weight: 600;
    font-family: 'Robot',sans-serif;
    color: #0B4829;
    background-color: #fff;
    
}
.menu-mobile{
    position: absolute;
    
}
.menu-mobile-list {
    background-color: #E0E0E0;
    padding: 30px;
    width: 30vw;
    border-radius: 8px;
}
.menu-mobile h4{
    font-size: 14px;
    padding: 4px;
    transition: .5s;
    border-bottom: 1px solid #0B4829;
}
.menu-mobile h4:hover{
    color:#0B4829;

}


</style>