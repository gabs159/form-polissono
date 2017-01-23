  <!--
  Colocar mascara nos campos, data de nascimento, estatura, peso, telefones.
   -->
<template>
<div id=app>



  <div id=form>

    <p>Nome Completo: <input v-model="name"><br>
      <p>
        <p>Data de Nascimento: <input v-model="message" placeholder="__/__/__"></p>
        <p>
          <form id="gender">
            Sexo:
            <input type="radio" id="f" value="F" v-model="picked" v-bind:false-value="a">
            <label for="F">F</label>

            <input type="radio" id="m" value="M" v-model="picked" v-bind:false-value="b">
            <label for="M">M</label>
            <br>
          </form>
        </p>
        <p>Peso: <input v-model="peso"><br></p>
        <p>Estatura: <input v-model="estatura"></p>
        <p>Telefones para contato: <input type=text></p>
        <p>Medicamentos que faz uso regular:</p>
        <textarea v-model="medicamentos" placeholder="Medicamentos que faz uso regular."></textarea>

  </div>

</div>
</template>

<script>
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#form {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  font-size: 20px;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
