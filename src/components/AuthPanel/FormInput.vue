<template>
<div v-if="show" class="form-input-1">
    <div class="header-form-1">
        <span class="highlight-word-1">Inicio de Sesión</span>
    </div>
    <label class="login-label-1">Usuario</label>
    <input class="login-input-1">
    <label class="login-label-1">Contraseña</label>
    <input class="login-input-1" type="password">
</div>
<div v-if="!show" class="form-input-2">
    <div class="header-form-2">
        <span class="highlight-word-1">Crear una cuenta</span>
    </div>
    <div class="input-general">
        <div class="col1">
            <label class="login-label-2">Usuario</label>
            <input class="login-input-2"> 
        </div>
        <div class="col2">
            <label class="login-label-2">Contraseña</label>
            <input class="login-input-2" type="password"> 
        </div>
    </div> 
</div>

</template>
  
<script lang="ts" setup>
import { defineProps } from 'vue';

defineProps({
    show: Boolean,
});
</script>
  
<style scoped>
.highlight-word-1{
    margin: 0;
    font-weight: 800;
    font-size: 200%;
}

.form-input-1{
    margin: 0;
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.login-label-1{
    margin: 0;
    font-family: "Red Hat Display", sans-serif;
    font-weight:500;
    font-size: medium;
    color: #88B88D;
}

.login-input-1{
    margin: 0;
    height: 35px;
    width: 350px;
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

.login-input-1:hover{
    background-color: #ffffff;
    box-shadow: 0px 0px 8px rgba(136, 184, 141, 0.1);
    border: 10px;
    border-color: #3D767D;
}


.input-general{
    margin: 0;
    width: auto;
    display: flex;
}

.col1{
    margin: 0;
    display: flex;
    flex-direction: column;
    flex-grow: 1;
}

.col2{
    margin: 0;
    display: flex;
    flex-direction: column;
    flex-grow: 1;
}

.highlight-word-2{
    margin: 0;
    font-weight: 800;
    font-size: 200%;
}

.form-input-2{
    margin: 0;
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.login-label-2{
    margin: 0;
    font-family: "Red Hat Display", sans-serif;
    font-weight:500;
    font-size: medium;
    color: #88B88D;
}

.login-input-2{
    margin: 0;
    height: 35px;
    width: 150px;
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

.login-input-2:hover{
    background-color: #ffffff;
    box-shadow: 0px 0px 8px rgba(136, 184, 141, 0.1);
    border: 10px;
    border-color: #3D767D;
}
</style>./LoginButton.vue