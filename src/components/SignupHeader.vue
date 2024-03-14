<template>
    <div class="header-form">
        <FormHeader />
        <div class="header-form">
            <span class="highlight-word">Crear una cuenta</span>
        </div>
    </div>
    </template>
          
<script lang="ts" setup>
import FormHeader from './FormHeader.vue';
</script>
          
<style scoped>
.header-form{
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 50px;
    width: 100%;
}

.header-form{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: left;
    width: 100%;
    height: auto;
}

.highlight-word{
    font-weight: 800;
    font-size: 200%;
}
</style>