<script>
// 1° importazione
  import appHeader from './components/appHeader.vue'
  import appMain from './components/appMain.vue'
  import appFooter from './components/appFooter.vue'

// 2° registrare componente
  export default{
    components: {
      appHeader,
      appMain,
      appFooter
    }
}
</script>

<!-- 3° utilizzare la componente -->
<template>
  <appHeader></appHeader>
  <appMain></appMain>
  <appFooter></appFooter>
</template>

<style>
  body{
    margin: 0;
  }
</style>