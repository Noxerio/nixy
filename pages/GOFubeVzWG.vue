<script setup>

</script>
<template>
    <div class="grid grid-cols-2 items-center justify-center place-content-center h-screen container mx-auto">
        <div class="w-full flex justify-center items-center">
            <div class="flex flex-col gap-8 mx-auto">
                <img src="/img/Vector.svg" class="drop-shadow-xl w-48">

                <div>
                    <p class="opacity-70">Aktuální předplatné:</p>
                    <p class="text-xl font-bold">Zkušební verze</p>
                </div>
                <div>
                    <p class="opacity-70">Platnost:</p>
                    <p class="text-xl font-bold">7 dní</p>
                </div>
                <div>
                    <p class="opacity-70">Unikátní klíč:</p>
                    <p class="text-xl font-bold">GOFubeVzWG</p>
                </div>
                <div>
                    <p class="opacity-70">URL adresa:</p>
                    <p class="text-xl font-bold">www.postavgril.cz</p>
                </div>
            </div>
        </div>
        
        
        <div class="flex flex-col gap-8 items-center justify-center ">
            <div class="flex gap-8 justify-center items-center bg-white px-5 rounded-xl drop-shadow-xl">
                <iframe class="p-5 w-48 bg-white rounded-xl" src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://play.google.com/store/apps/details?id=com.viwi.viwi"></iframe>
                <div>
                    <h3 class="text-2xl font-bold">Stáhněte si aplikaci pro Android</h3>
                    <p>Naskentujte QR kód nebo klikněte na odkaz níže</p>
                </div>
            </div>
          
           
            <div class="flex gap-8 items-center justify-center">
                <div class="bg-white rounded-xl drop-shadow-xl">
                    <iframe class="p-5 w-48 bg-white rounded-xl" src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=GOFubeVzWG"></iframe>
                    <p class="text-center opacity-60">1. Krok</p>
                    <h3 class="text-center font-bold mb-5">Přístupový token</h3>
                </div>

                <div class="bg-white rounded-xl drop-shadow-xl">
                    <iframe class="p-5 w-48 bg-white rounded-xl" src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=http://RB8VE36M6V6IGUUAB9J9URTZ9HQQDXBL:@www.postavgril.cz"></iframe>
                    <p class="text-center opacity-60">2. Krok</p>
                    <h3 class="text-center font-bold mb-5">URL adresa</h3>
                </div>
            </div>
        </div>
    </div>
</template>