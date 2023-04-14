<template>
  <div class="app">
    <h1 style="color:white; margin-bottom: 10px">ZOYBRAND</h1>
    <div class="action-container">
      <ActionContainer/>
    </div>
    <h4 style="margin-top: 10px;">Говорят, если стать нашим подписчиком и отправить в директ сообщение «20%», в ответ придёт промокод на скидку</h4>

  </div>
</template>
<script setup>
import ActionContainer from './components/ActionContainer.vue';
</script>
<style>
*,
*::before,
*::after { 
    margin: 0; 
    padding: 0; 
    box-sizing: border-box; 
}

html {
  background-image: url(./assets/zoy_background.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-attachment: fixed;
  background-size: cover;
}

body{width:100%; overflow-x:hidden; color:white}

.app {
  text-align: center;
  align-items: center;     
  margin-top: 55%;             
}

.run-text {
  margin-top: 10px;
  color:white;
}

.action-container {
  vertical-align: center;
  align-items: center;
  padding: 3px;
  justify-content: center;
  display: inline-block;
}
</style>