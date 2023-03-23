<!-- Create un nuovo progetto utilizzando Vite: aiutatevi con le slide per ripercorrere i vari passaggi dell'installazione come visti a lezione.
Create e utilizzate un componente AppTitle, il quale contiene un titolo che recita "La mia prima app con Vite!" -->


<script>

  import Titolo from './components/Apptitle.vue';
  import Immagine from './components/AppHero.vue'

  export default{
    data(){
      return{

      }
    },
    components:{
      Titolo,
      Immagine
    },

    methods:{

    },
  }




</script>

<template>
  <div>

    <div class="container">

      <Titolo></Titolo>

    <Immagine></Immagine>

    </div>
    

  </div>
</template>

<style lang="css">

  .container{
    text-align: center;

    padding: 2rem;

    max-width: 1200px;
    margin: 0 auto;
    background-color: brown;
    border-radius: 30px;

    box-shadow: 1px 1px 5px black;
  }

</style>