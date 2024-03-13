<template>
<div class="buttons">
    <button class="login-btn">Crear Cuenta</button>
    <button class="login-btn">Iniciar Sesión</button>
</div>
</template>
  
<script lang="ts">
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

</style>./LoginButton.vue