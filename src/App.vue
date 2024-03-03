<template>
  <div id="app">
    <MainPage /> <!-- Здесь используем компонент Page -->
  </div>
</template>

<script>
import MainPage from './view/MainPage.vue'; // Импорт компонента Page.vue

export default {
  name: 'App',
  components: {
    MainPage, // Регистрация компонента Page
  },
};
</script>

<style>
/* Стили для корневого компонента приложения */
</style>