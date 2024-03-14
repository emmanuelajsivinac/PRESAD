<template>
<div class="buttons">
    <button class="login-btn" @click="selectButton('login')">Iniciar Sesión</button>
    <button class="login-btn" @click="selectButton('signup')">Crear Cuenta</button>
</div>
</template>
  
<script lang="ts" setup>
import { ref } from 'vue';

const activeButton = ref('');

const selectButton = (button: string) => {
  activeButton.value = button;
  console.log(activeButton.value);
};

</script>
  
<style scoped>
.buttons{
    display: flex;
    gap: 20px;
}

.login-btn{
    padding: 15px;
    background-color: #529B9B;
    font-family: "Red Hat Display", sans-serif;
    font-weight:500;
    font-size: small;
    color: #ffffff;
    border: 0;
    width: 175px;
    border-radius: 50px;
}

.login-btn:hover{
    background-color: #eff8f8;
    color: #529B9B;
}

.active {
  background-color: #eff8f8;
  color: #529B9B;
}

</style>./LoginButton.vue