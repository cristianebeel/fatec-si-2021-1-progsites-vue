<template>
  <div class="about">
    <h1>Sobre mim</h1>
    <h2>{{ author }}</h2>
    <p>Estudante de Sistemas para Internet. Este projeto foi criado para a aula de Programação de Sites.</p>
    <div>
      <p>Gostaria que você fosse o autor?</p>
      <input placeholder="Informe seu nome" v-model="author">
    </div>
  </div>
</template>

<script>
export default{
  data(){
    return{
      author: 'Belle Santos'
    }
  }
}
</script>

<style scoped lang="scss">
  $cor-principal: rgb(153,51,148);
  
  p{
    color: $cor-principal;
  }

  h1{
    background: $cor-principal;
    color: white;
    padding: 1rem;
    text-align: center;
  }
</style>