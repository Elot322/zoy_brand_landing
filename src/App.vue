<template>
  <div class="app">
    <h1 style="color:white; margin-bottom: 10px">ZOYBRAND</h1>
    <div class="action-container">
      <ActionContainer/>
    </div>
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

@media (min-width: 576px) {
  .app {
    text-align: center;
    align-items: center;     
    margin-top: 55%;             
  }
}

@media (min-width: 1200px) {
  .app {
    text-align: center;
    align-items: center;     
    margin-top: 20%;             
  }
}

.action-container {
  vertical-align: center;
  align-items: center;
  padding: 3px;
  justify-content: center;
  display: inline-block;
}
</style>