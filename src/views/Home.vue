<template>
  <div>

<div id="nav" class="">
     <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> | -->
     
      <router-link to="/cadastro"> <b-button style="color: #FFF"  variant="link">Cadastra-se</b-button></router-link>
</div>
    <b-container class="bv-example-row">
      <b-row>
        <b-col md="4" offset-md="4">
          <b-card cols="4" title="Login" class="mb-6">
            <img src="../assets/logo.png" class="mb-6" cols="4" alt>

            <div>
              <b-input-group class="mb-3">
                <b-input-group-text slot="prepend">Email</b-input-group-text>
                <b-form-input  id="txtLogin" name="txtLogin" placeholder="E-mail"></b-form-input>
              </b-input-group>
            </div>
            
            <br>

            <div>
              <b-input-group class="mb-3">
                <b-input-group-text slot="prepend">Senha</b-input-group-text>
                <b-form-input id="txtSenha" name="txtSenha" type="password" placeholder="Confirme sua senha"></b-form-input>
              </b-input-group>
            </div>
          
          <div>
            <b-button href="#" class="mt-3" variant="success">Entrar</b-button>
          </div>

          <div>
            
          </div>

          </b-card>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
// @ is an alias to /src

/*
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}

*/
</script>

<style>
body { background-color: blueviolet;
}
</style>
