<template>
<div class="header-form">
    <div class="header-form-1">
        <span class="highlight-word-1">PRESAD</span>
    </div>
    <div class="header-form-2">
        <span class="highlight-word-2">Inicio de Sesión</span>
    </div>
</div>
</template>
      
<script lang="ts" setup>
</script>
      
<style scoped>
.header-form{
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 50px;
    width: 100%;
}

.header-form-1{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: left;
    width: 100%;
}

.header-form-2{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: left;
    width: 100%;
    height: auto;
}

.highlight-word-1{
    font-weight: 900;
    font-size: 100%;
}

.highlight-word-2{
    font-weight: 800;
    font-size: 200%;
}
</style>