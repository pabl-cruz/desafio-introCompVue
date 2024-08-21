<script setup>
import CarnetAside from './components/CarnetAside.vue';
import CarnetHeader from './components/CarnetHeader.vue';
import CarnetDatos from './components/CarnetDatos.vue';
</script>

<template>
 <div class="carnet">
    <CarnetAside></CarnetAside>
    <main>
    <CarnetHeader></CarnetHeader>
    <CarnetDatos></CarnetDatos>
  </main>
 </div>
</template>

<style scoped>
main {
  padding: 0px 14px;
}

main article {
  margin: 4px 0px;
}

main section {
  margin-top: 10px;
}
</style>
