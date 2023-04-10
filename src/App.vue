<template>
  <div class="app">
    <h1 style="color:white; margin-bottom: 10px">ZOYBRAND</h1>
    <div class="action-container">
      <ActionContainer/>
    </div>
    <marquee style="margin-top: 10px; color:white; line-height: 150%;"><h4>Подпишишсь на нас и получи скидку на первую покупку! Подпишишсь на нас и получи скидку на первую покупку! Подпишишсь на нас и получи скидку на первую покупку! Подпишишсь на нас и получи скидку на первую покупку!</h4></marquee>

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

.app {
  text-align: center;
  align-items: center;     
  position: absolute;
  top: 45%;             
}


.action-container {
  vertical-align: center;
  align-items: center;
  padding: 3px;
  justify-content: center;
  display: flex;
}
</style>