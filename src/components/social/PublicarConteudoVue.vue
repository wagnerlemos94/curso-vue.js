<template>
  <div class="row">
      <grid-vue class="input-field" tamanho="12">
        <textarea v-model="conteudo" id="conteudoId" class="materialize-textarea"></textarea>
        <label for="conteudoId">O que está acontecendo?</label>
      </grid-vue>
      <p>
        <grid-vue v-if="conteudo" class="btn waves-effect waves-light" tamanho="2 offset-s10">Publicar</grid-vue>
      </p>
    </div>
</template>

<script>
import GridVue from "@/components/layouts/GridVue";

export default {
  name: "PublicarConteudoVue",
  props: ["perfil", "nome", "data"],
  data() {
    return {
      conteudo:''
    };
  },
  components: {
    GridVue,
  },
};
</script>

<style>
</style>