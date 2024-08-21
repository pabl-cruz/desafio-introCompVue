<script>
import { defineComponent } from 'vue';
export default defineComponent({
    name: 'CarnetAside',
    
    data(){
        return{
            bandera: '/img/chile_bandera.png',
            foto: '/img/foto_elon.jpg',
            rut: '22.222.222-2',
        }
    }
})
</script>

<template>
    <aside>
        <div>
          <span>CEDULA DE IDENTIDAD</span>
          <img width="40" :src="bandera" alt="Bandera de Chile"/>
        </div>

        <img :src="foto" alt="Elon Musk" />
        <p>RUN {{ rut }}</p>
    </aside>
        
</template>

<style scoped>
    aside div {
        display: flex;
      }

      aside > img {
        margin-top: 15px;
        width: 100%;
      }

      aside p {
        text-align: center;
        font-size: 12px;
        font-weight: bold;
      }
</style>