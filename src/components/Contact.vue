<template>
    <div class="container-contact p-4 mt-16 flex flex-col justify-center items-center gap-y-4 bg-green-800">
        <h2 class="text-3xl sm:text-4xl font-medium text-center sm:text-left text-white">CONTATE-NOS</h2>
        <form class="flex flex-col gap-y-4 w-100">
                <div class="state-city flex justify-between flex-col lg:flex-row gap-y-4 gap-x-32">
                    <div class="label-input flex flex-col gap-y-2">
                    <label for="" class="text-white">Nome</label>
                    <input type="text" placeholder="Fulano"
                        class=" border bg-white p-4 h-10 outline-none rounded ">
                        
                </div>
                <div class="label-input flex flex-col gap-y-2">
                    <label for="" class="text-white">Sobrenome</label>
                    <input type="text" placeholder="de Tal"
                        class=" border bg-white p-4 h-10 outline-none rounded ">
                        
                </div>

                </div>
                <div class="state-city flex justify-between flex-col lg:flex-row gap-y-4 gap-x-32">
                    <div class="label-input flex flex-col gap-y-2">
                    <label for="" class="text-white">Email</label>
                    <input type="text" placeholder="fulano@gmail.com"
                        class=" border bg-white p-4 h-10 outline-none rounded ">
                        
                </div>
                <div class="label-input flex flex-col gap-y-2">
                    <label for="" class="text-white">Telefone</label>
                    <input type="text" placeholder="(xx) 9xxxx-xxxx"
                        class=" border bg-white p-4 h-10 outline-none rounded ">
                        
                </div>

                </div>
                <div class="state-city flex justify-between flex-col lg:flex-row gap-y-4 gap-x-32">
                    <div class="label-input flex flex-col gap-y-2">
                    <label for="" class="text-white">Mensagem</label>
                    <textarea type="text" placeholder="Fulano"
                        class=" border bg-white p-2  outline-none rounded "></textarea>
                        
                </div>
               
                <div class="label-input flex items-center gap-x-4 justify-start  mr-4 p-4 gap-y-2">
                    <label for="" class="text-white">Receber notificações</label>
                    <input type="checkbox" placeholder="de Tal"
                        class=" border bg-white p-4 h-4 w-4 outline-none rounded ">
                        <button class="bg-white text-green-900 p-2 rounded ">enviar</button>
                </div>

                </div>
            </form>
            
    </div>



</template>


<script setup>


</script>


<style scoped>
.container-contact h2{
    font-family:'Alegreya', serif
}



</style>