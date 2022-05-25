<template>
  <q-page class="flex flex-center">
    <q-img class="fixed-full" src="http://www.obraeconstrutora.com.br/bg.jpg" />
    <div>
      <q-card class="my-card text-centern">
        <q-card-section
          class="tamanho-card text-center"
          style="background: #4d606e"
        >
          <span class="text-h1 nome-obrae">OBRAÊ</span>

          <div class="q-mt-xl">
            <span>Financeiro </span>
            <span>11 99261-7283 </span>
          </div>
          <div>
            <span>Compras </span>
            <span>11 98515-0161 </span>
          </div>
          <br />
          <div>
            <span>Largo da Concórdia, 88 -</span>
            <span> Brás - São Paulo - SP </span>
          </div>

          <a
            class="link"
            target="_blank"
            href="mailto: contato@obraeconstrutora.com.br"
            >contato@obraeconstrutora.com.br</a
          >
        </q-card-section>
      </q-card>
    </div>
  </q-page>
</template>

<script>
import { defineComponent, ref } from "vue";

export default defineComponent({
  name: "IndexPage",

  setup() {
    return {
      ref,
    };
  },
});
</script>

<style>
.nome-obrae {
  font-size: 130px;
  color: #f5f6f6;
}

.tamanho-card {
  padding: 70px;
  color: #f5f6f6;
}

.link {
  text-decoration: none;
  color: #f5f6f6;
}
</style>
