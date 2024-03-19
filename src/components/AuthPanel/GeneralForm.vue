<template>
<div class="login-form">
    <div class="form-left">
        <div class="header">
            <FormHeader/>
        </div>
        <div class="form">
            <FormInput :show="showInputs"/>
            <FormButton :toggle="changeInputs" :change="showButtons"/>
        </div>
    </div>
    <div class="form-right">
        <img src="../../../public/img/login.jpg" alt="Descripción de la imagen">
    </div>
</div>    
</template>
  
<script lang="ts" setup>
import { ref } from 'vue';
import FormHeader from './FormHeader.vue'
import FormButton from './FormButton.vue'
import FormInput from './FormInput.vue'

const showInputs = ref(true);
const showButtons = ref(true);

const changeInputs = () => {
    showInputs.value = !showInputs.value;
    showButtons.value = !showButtons.value;
} 
</script> 

<style scoped>

.login-form{
    margin: 0;
    display: flex;
    gap: 0;
    height: 500px;
    width: 900px;
    background-color: #ffffff;
    border-radius: 20px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

.form-left{
    display: flex;
    flex-direction: column;
    justify-content: center;
    height: auto;
    width: 470px;
    padding-right: 55px;
    padding-left: 55px;
}

.header{
    width: auto;
    height: 100px;
}

.form{
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 20px;
    align-items: center;
}

.login-form h1, .login-form h3 {
    margin: 0;
}

.form-right{
    height: 500px;
    width: 430px;
}

.form-right img{
  width: 100%;
  height: 100%;
  border-radius: 0 20px 20px 0;
}
</style>