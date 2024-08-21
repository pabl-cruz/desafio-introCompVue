<script>
import { defineComponent } from 'vue';
export default defineComponent({
    name: 'CarnetDatos',
    data(){
        return{
            nombres: 'ELON REEVE',
            apellidos: 'MUSK',
            nacionalidad: 'SUDAFRICANO',
            sexo: 'M',
            fechaNacimiento: '28 JUN 1971',
            numDocumento: '222.222.222',
            fechaEmision: '01 ENE 2025',
            fechaVencimiento: '01 ENE 2030',
            firmaTitular: 'X Æ A-12',
        }
    }
})
</script>

<template>
    <section>
          <article>
            <header>APELLIDOS</header>
            <span>{{ apellidos }}</span>
          </article>
          <article>
            <header>NOMBRES</header>
            <span>{{ nombres }}</span>
          </article>

          <div class="grid-2-colums">
            <article>
              <header>NACIONALIDAD</header>
              <span>{{ nacionalidad }}</span>
            </article>
            <article>
              <header>SEXO</header>
              <span>{{ sexo }}</span>
            </article>
          </div>
          <div class="grid-2-colums">
            <article>
              <header>FECHA DE NACIMIENTO</header>
              <span>{{ fechaNacimiento }}</span>
            </article>
            <article>
              <header>NÙMERO DOCUMENTO</header>
              <span>{{ numDocumento }}</span>
            </article>
          </div>
          <div class="grid-2-colums">
            <article>
              <header>FECHA DE EMISIÒN</header>
              <span>{{ fechaEmision }}</span>
            </article>
            <article>
              <header>FECHA DE VENCIMIENTO</header>
              <span>{{ fechaVencimiento }}</span>
            </article>
          </div>
          <article>
            <header>FIRMA DEL TITULAR</header>
            <span>{{ firmaTitular }}</span>
          </article>
        </section>
</template>

<style scoped>
    main article header {
        font-weight: bold;
        color: #0235a4;
        font-size: 8px;
      }

      main article {
        margin: 4px 0px;
      }

      main section {
        margin-top: 10px;
      }

      main section article span {
        font-size: 13px;
        font-weight: 600;
      }
</style>