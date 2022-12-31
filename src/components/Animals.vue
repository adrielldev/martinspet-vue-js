<template>


    <div class="animals-container mt-16 flex flex-col justify-center items-center gap-y-8">
        <h1 class="text-3xl sm:text-4xl font-bold text-center sm:text-left p-4 ">NOSSOS ANIMAIS</h1>
    
        <div class="div-dogs-cats flex flex-col sm:flex-row p-4 gap-y-8 justify-between">
            <div class="dogs sm:border-l-2 sm:pl-4 ">
                <h2 class="text-2xl font-medium sm:text-3xl">CÃES</h2>
                <ul class="flex flex-row sm:flex-col gap-x-8 gap-y-4 overflow-x-auto ">
                    <li class="flex flex-col gap-y-4 p-4 rounded border-b-2 sm:border-b-0">
                        <div class="pet-img-infos flex gap-x-4">
                            <div class="div-img">
                            <img :src="PetImg"/>
                        </div>
                        <div class="div-pet-infos gap-y-2 flex flex-col pt-4">
                            <h4 class="text-base text-gray-400">Lilou, 2 anos</h4>
                        <div class="div-weight-gender flex gap-x-4">
                            <span class="text-gray-500">30kg</span>
                            <span fillColor="#f0f0f0"><GenderMaleIcon/></span>
                        </div>
                        <ul class="div-traits flex gap-x-4 flex-wrap">
                            <li class="text-gray-500">calm</li>
                            <li class="text-gray-500">courageous</li>
                        </ul>

                        </div>

                        </div>
                        
                        
                        <div class="div-buttons flex gap-x-16">
                            <button class="p-2 bg-white border rounded adopt font-bold">Adotar</button>
                            <button class="font-medium text-white">Compartilhar</button>
                        </div>

                    </li>
                    <li class="flex flex-col gap-y-4 p-4 rounded border-b-2 sm:border-b-0">
                        <div class="pet-img-infos flex gap-x-4">
                            <div class="div-img">
                            <img :src="PetImg"/>
                        </div>
                        <div class="div-pet-infos gap-y-2 flex flex-col pt-4">
                            <h4 class="text-base text-gray-400">Lilou, 2 anos</h4>
                        <div class="div-weight-gender flex gap-x-4">
                            <span class="text-gray-500">30kg</span>
                            <span fillColor="#f0f0f0"><GenderMaleIcon/></span>
                        </div>
                        <ul class="div-traits flex gap-x-4 flex-wrap">
                            <li class="text-gray-500">calm</li>
                            <li class="text-gray-500">courageous</li>
                        </ul>

                        </div>

                        </div>
                        
                        
                        <div class="div-buttons flex gap-x-16">
                            <button class="p-2 bg-white border rounded adopt font-bold">Adotar</button>
                            <button class="font-medium text-white">Compartilhar</button>
                        </div>

                    </li>
                </ul>
            </div>
            <div class="cats sm:border-l-2 sm:pl-4">
                <h2 class="text-2xl font-medium sm:text-3xl">GATOS</h2>
                <ul class="flex flex-row sm:flex-col gap-x-8 gap-y-4 overflow-x-auto ">
                    <li class="flex flex-col gap-y-4 p-4  border-b-2 sm:border-b-0">
                        <div class="pet-img-infos flex gap-x-4">
                            <div class="div-img">
                            <img :src="PetImg"/>
                        </div>
                        <div class="div-pet-infos gap-y-2 flex flex-col pt-4">
                            <h4 class="text-base text-gray-400">Lilou, 2 anos</h4>
                        <div class="div-weight-gender flex gap-x-4">
                            <span class="text-gray-500">30kg</span>
                            <span fillColor="#f0f0f0"><GenderMaleIcon/></span>
                        </div>
                        <ul class="div-traits flex gap-x-4 flex-wrap">
                            <li class="text-gray-500">calm</li>
                            <li class="text-gray-500">courageous</li>
                        </ul>

                        </div>

                        </div>
                        
                        
                        <div class="div-buttons flex gap-x-16">
                            <button class="p-2 bg-white border rounded adopt font-bold">Adotar</button>
                            <button class="font-medium text-white">Compartilhar</button>
                        </div>

                    </li>
                    <li class="flex flex-col gap-y-4 p-4  border-b-2 sm:border-b-0">
                        <div class="pet-img-infos flex gap-x-4">
                            <div class="div-img">
                            <img :src="PetImg"/>
                        </div>
                        <div class="div-pet-infos gap-y-2 flex flex-col pt-4">
                            <h4 class="text-base text-gray-400">Lilou, 2 anos</h4>
                        <div class="div-weight-gender flex gap-x-4">
                            <span class="text-gray-500">30kg</span>
                            <span fillColor="#f0f0f0"><GenderMaleIcon/></span>
                        </div>
                        <ul class="div-traits flex gap-x-4 flex-wrap">
                            <li class="text-gray-500">calm</li>
                            <li class="text-gray-500">courageous</li>
                        </ul>

                        </div>

                        </div>
                        
                        
                        <div class="div-buttons flex gap-x-16">
                            <button class="p-2 bg-white border rounded adopt font-bold">Adotar</button>
                            <button class="font-medium text-white">Compartilhar</button>
                        </div>

                    </li>
                </ul>
            </div>

        </div>
    </div>

</template>

<script setup>
import PetImg from '../assets/petimg.png'
import GenderMaleIcon from 'vue-material-design-icons/GenderMale.vue'
</script>

<style scoped>
.animals-container{
    background-color: #1F5F3E;
}
.animals-container h1{
    font-family: 'Alegreya' , serif;
    color: #fff;

}
   

.div-dogs-cats{
    width:80vw;
}
.div-dogs-cats h2{
    font-family: 'Alegreya' , serif;
    color: #fff;

}
.div-buttons .adopt{
    color: #1F5F3E;

}

.div-pet-infos {
    font-family: 'Roboto',sans-serif;
}
</style>