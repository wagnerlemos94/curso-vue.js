<template>
  <login-template>
    <publicar-conteudo-vue />
    <h2>Login</h2>
    <input type="text" placeholder="E-mail" />
    <input type="text" placeholder="Senha" />
    <button type="button" class="btn">Entrar</button>
  </login-template>
</template>

<script>
import LoginTemplate from "@/templates/LoginTemplate";
import CardConteudoVue from "@/components/social/CardConteudoVue";
import CardDetalheVue from "@/components/social/CardDetalheVue";
import PublicarConteudoVue from "@/components/social/PublicarConteudoVue";
export default {
  name: "Login",
  data() {
    return {};
  },
  components: {
    LoginTemplate,
    CardConteudoVue,
    CardDetalheVue,
    PublicarConteudoVue
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
