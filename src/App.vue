<template>
  <LoginForm />
</template>

<script lang="ts" setup>
  import LoginForm from '../src/components/AuthPanel/GeneralForm.vue'
</script>

<style>
#app{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  font-family: "Red Hat Display", sans-serif;
  font-optical-sizing: auto;
  font-style: normal;
  font-size: larger;
  color: #000000;
  background-color: #ffffff;
  height: 100vh;
}
</style>
