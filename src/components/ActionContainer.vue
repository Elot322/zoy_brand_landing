<template>
    <div>
        <div class="row1">
            <button class="button" @click="onLookBookClick">Look Book</button>
            <button class="button right-button" @click="onSiteClick">Наш сайт</button>
        </div>
        <div>
            <button class="button" @click="onInstClick">Соц. сеть с картинками</button>
            <button class="button right-button" @click="onWhatsAppClick">What's App</button>
        </div>
    </div>
</template>

<script setup>

function onLookBookClick() {
    //TODO: Сделать презу
    window.open('./assets/zoybrand.pdf', '_blank')
}

function onSiteClick() {
    window.open('https://zoybrand.com/')
}

function onInstClick() {
    window.open('https://instagram.com/zoy_brand?igshid=YmMyMTA2M2Y=')
}

function onWhatsAppClick() {
    window.open('https://wa.me/79005745353?text=%D0%9F%D1%80%D0%B8%D0%B2%D0%B5%D1%82!%20%F0%9F%91%8B%20%D0%9C%D0%B5%D0%BD%D1%8F%20%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D0%B5%D1%81%D1%83%D0%B5%D1%82...')
}
</script>

<style>
@media screen {
    .button {
    width: 160px;
    height: 50px;
    background-color: gray;
    border-color: transparent;
    border-radius: 5px;
    color: white;
    transition: 300ms;
    border: 1px solid transparent;
}

.button:hover {
    color: black;
    border-color: black;
    transition-duration: 1000ms;
}

.right-button {
    margin-left: 10px;
}

.row1 {
    margin-bottom: 5px;
}
   
}
</style>

