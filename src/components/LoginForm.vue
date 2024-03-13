<template>
<div class="login-form">
    <div class="login-form-left">
    <LoginHeader/>
    <LoginInput/>
    <LoginButton/>
    </div>
    <div class="login-form-right">
        <img src="../../public/img/login.jpg" alt="Descripción de la imagen">
    </div>
    </div>    
</template>
  
<script lang="ts" setup>
import LoginHeader from './LoginHeader.vue';
import LoginButton from './LoginButton.vue'
import LoginInput from './LoginInput.vue'
</script>
  
<style scoped>
.login-form{
    display: flex;
    gap: 0;
    height: 500px;
    width: 900px;
    background-color: #ffffff;
    border-radius: 20px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

.login-form-left{
    height: auto;
    width: 435px;
    padding-right: 55px;
    padding-left: 55px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 20px;
    align-items: center;
    background-color: #ffffff;
}

.login-form h1, .login-form h3 {
    margin: 0;
}

.login-form-right{
    height: 500px;
    width: 425px;
    background-color: aqua;
}

.login-form-right img{
  width: 100%;
  height: 500px;
}
</style>