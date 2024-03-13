<template>
<div class="form-input">
    <label class="login-label">Usuario</label>
    <input class="login-input">
    <label class="login-label">Contraseña</label>
    <input class="login-input" type="password">
</div>
</template>
  
<script lang="ts">
</script>
  
<style scoped>
.form-input{
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.login-label{
    font-family: "Red Hat Display", sans-serif;
    font-weight:500;
    font-size: medium;
    color: #88B88D;
}

.login-input{
    height: 35px;
    width: 400px;
    padding-top: 5px;
    padding-bottom: 5px;
    padding-left: 10px;
    padding-right: 10px;
    background-color: #eff8f8;
    color: #000000;
    border: 0;
    border-radius: 10px;
    outline: 0;
    font-family: "Red Hat Display", sans-serif;
    font-weight:800;
    font-size: medium;
}

.login-input:hover{
    background-color: #ffffff;
    box-shadow: 0px 0px 8px rgba(136, 184, 141, 0.1);
    border: 10px;
    border-color: #3D767D;
}

</style>./LoginButton.vue