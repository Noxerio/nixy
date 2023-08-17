<script setup>

</script>
<template>
    <div class="flex items-center justify-center h-screen flex-col gap-8">
        <img src="/img/Vector.svg" class="drop-shadow-xl">
        <div class="flex gap-8">
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
</template>