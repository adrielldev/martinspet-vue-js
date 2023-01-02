<template>
    <div class="container-forms p-4 mt-16 flex flex-col items-center gap-y-8 ">
        <h2 class="text-center text-3xl sm:text-4xl font-bold">Contribuir com a causa</h2>
        <div class="div-donate p-4 border rounded-lg flex flex-col gap-y-8 items-center">
            <div class="div-payments-forms flex gap-x-4 ">


                <div class="input-checkbox flex gap-x-2 items-center">
                    <button class="w-4 h-4 bg-white border rounded-full border-transparent"></button>
                    <span>pix</span>
                </div>
                <div class="input-checkbox flex gap-x-2 items-center">
                    <button class="w-4 h-4 bg-black border rounded-full border-transparent"></button>
                    <span>cartão</span>
                </div>
                <div class="input-checkbox flex gap-x-2 items-center">
                    <button class="w-4 h-4 bg-white border rounded-full border-transparent"></button>
                    <span>boleto</span>
                </div>
            </div>
            <form class="flex flex-col gap-y-8 items-center">
                <div class="label-input flex flex-col gap-y-2">
                    <label for="">Número do Cartão</label>
                    <input type="text" placeholder="XXXX-XXXX-XXXX-XXXX"
                        class=" border bg-white p-4 h-10 outline-none rounded ">
                </div>
                <div class="label-input flex flex-col gap-y-2">
                    <label for="">Nome impresso no cartão</label>
                    <input type="text" placeholder="Fulano de Tal S."
                        class=" border bg-white p-4 h-10 outline-none rounded ">
                </div>
                <div class="div-cvv-val flex w-100 gap-x-12">
                    <div class="label-input flex flex-col gap-y-2">
                        <label for="">CVV </label>
                        <input type="text" placeholder="123"
                            class=" border bg-white p-4 h-10 outline-none rounded w-28">
                    </div>
                    <div class="label-input flex flex-col gap-y-2">
                        <label for="">Validade</label>
                        <input type="text" placeholder="02/29"
                            class=" border bg-white p-4 h-10 outline-none rounded w-28">
                    </div>

                </div>
                <div class="label-input flex flex-col gap-y-2">
                    <label for="">CPF/CNPJ Titular</label>
                    <input type="text" placeholder="123-456-789.20"
                        class=" border bg-white p-4 h-10 outline-none rounded ">
                </div>
                <div class="label-input flex flex-col gap-y-2">
                    <label for="">Valor</label>
                    <input type="text" placeholder="R$ 100" class=" border bg-white p-4 h-10 outline-none rounded ">
                </div>

                <input class="button-submit w-fit border-transparent p-2 border rounded-lg text-white" type="submit"
                    value="Enviar" @click="(e) => { e.preventDefault() }">
            </form>

        </div>
        <h2 class="text-center text-3xl sm:text-4xl font-bold w-3/4 sm:1/2">Não pode mais cuidar do seu pet?
            Preencha o formulário abaixo para doá-lo</h2>
        <div class="div-address-infos p-4  rounded flex flex-col gap-y-8">
            <h2 class="text-center text-2xl sm:text-3xl font-medium text-white">ENDEREÇO</h2>
            <form class="flex flex-col gap-y-4 ">
                <div class="state-city flex flex-col lg:flex-row gap-y-4 gap-x-8">
                    <div class="label-input flex flex-col gap-y-2">
                    <label for="">Estado</label>
                    <input type="text" placeholder="Pernambuco"
                        class=" border bg-white p-4 h-10 outline-none rounded ">
                        
                </div>
                <div class="label-input flex flex-col gap-y-2">
                    <label for="">Cidade</label>
                    <input type="text" placeholder="Olinda"
                        class=" border bg-white p-4 h-10 outline-none rounded ">
                        
                </div>

                </div>
                <div class="state-city flex flex-col lg:flex-row gap-y-4 gap-x-8">
                    <div class="label-input flex flex-col gap-y-2">
                    <label for="">Endereço</label>
                    <input type="text" placeholder="Bairro X, rua Y"
                        class=" border bg-white p-4 h-10 outline-none rounded ">
                        
                </div>
                <div class="label-input flex flex-col gap-y-2">
                    <label for="">Número</label>
                    <input type="text" placeholder="123"
                        class=" border bg-white p-4 h-10 outline-none rounded ">
                        
                </div>

                </div>
                <div class="ref-none">
                    <div class="label-input flex flex-col gap-y-2">
                    <label for="">Ponto de referência</label>
                    <textarea class=" border bg-white p-2 w-1/2 outline-none rounded ">

                    </textarea>
                        
                </div>
                <div>

                </div>

                </div>
            
            </form>
           <h2 class="text-center text-2xl sm:text-3xl font-medium text-white">INFORMAÇÕES </h2>
            <form  class="flex flex-col gap-y-4 ">
                 <div class="state-city flex flex-col lg:flex-row gap-y-4 gap-x-8">
                    <div class="label-input flex flex-col gap-y-2">
                    <label for="">Nome Dono(a)</label>
                    <input type="text" placeholder="Fulano"
                        class=" border bg-white p-4 h-10 outline-none rounded ">
                        
                </div>
                <div class="label-input flex flex-col gap-y-2">
                    <label for="">Sobrenome</label>
                    <input type="text" placeholder="De tal"
                        class=" border bg-white p-4 h-10 outline-none rounded ">
                        
                </div>

                </div>
                 <div class="state-city flex flex-col lg:flex-row gap-y-4 gap-x-8">
                    <div class="label-input flex flex-col gap-y-2">
                    <label for="">Nome do pet</label>
                    <input type="text" placeholder="Luke"
                        class=" border bg-white p-4 h-10 outline-none rounded ">
                        
                </div>
                <div class="label-input flex flex-col gap-y-2">
                    <label for="">Idade do pet</label>
                    <input type="number" placeholder="3"
                        class=" border bg-white p-4 h-10 outline-none rounded ">
                        
                </div>

                </div>
                 <div class="state-city flex flex-col lg:flex-row gap-y-4 gap-x-8">
                    <div class="label-input flex flex-col gap-y-2">
                    <label for="">Peso do pet (kg)</label>
                    <input type="number" placeholder="20"
                        class=" border bg-white p-4 h-10 outline-none rounded ">
                        
                </div>
                <div class="label-input flex flex-col gap-y-2">
                    <label for="">Sexo do pet</label>
                    <select value="macho" name="sexos"
                        class=" border bg-white h-10 p-2 outline-none rounded ">
                        <option value="macho">macho</option>
                        <option value="femea">femea</option>
                    </select>
                    
                        
                </div>

                </div>
                <div class="file-button flex flex-col lg:flex-row gap-y-4 gap-x-8">
                    <div class="label-input flex flex-col gap-y-2">
                    <label for="">Imagem do pet </label>
                    <input type="file" placeholder="Luke"
                        class="">
                        
                </div>

                </div>
                <div class="label-input flex flex-col gap-y-2 mr-10 justify-center items-center sm:items-start">
                    <input type="submit" placeholder="3" value="Enviar"
                        class="button-submit border border-transparent mt-2 bg-white outline-none rounded p-2 text-white">
                        
                </div>


            </form>
            <p class="text-left sm:text-center text-gray-300">
                Obrigado pela doação! 
Lembre-se abandono é crime. Em breve uma van de nossa instituição irá resgatar o pet!
O $nomeDoPet em breve terá um novo lar :)

            </p>
        </div>

    </div>


</template>

<script setup>
import { ref } from 'vue'



</script>


<style scoped>
.div-donate {
    background-color: #1F5F3E;
}

.button-submit {
    background-color: #33845B;
}

.label-input label {
    color: #A3A3A3;

}

.div-address-infos {
    background-color: #1F5F3E;

}
</style>