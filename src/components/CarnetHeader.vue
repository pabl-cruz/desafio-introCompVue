<script>
import { defineComponent } from 'vue';
export default defineComponent({
    name: 'CarnetHeader',
})
</script>

<template>
    <header>
          <p>REPUBLICA DE CHILE</p>
          <span>SERVICIO DE REGISTRO CIVIL E IDENTIFICACIÓN</span>
        </header>
</template>

<style scoped>
    main header p {
        font-size: 20px;
        margin: 0;
        font-weight: bold;
        color: #0235a4;
      }

    main header span {
        font-size: 8px;
        color: #399be1;
      }
</style>