<template>
<div class="fundo">
<homeView/>
</div>
</template>

<style>
:root{
--verde:rgb(15, 93, 15);
--azul_bota:rgb(86, 103, 171);
--violeta:rgb(164, 44, 164);
--preto:black;
--branco:white;
--agua:transparent;
--opaco:opacity:0.7;
--primary:rgb(20, 20, 120);
--second:#ccc;

}







#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}



.fundo{
  width:100%;
  height: 100vh;
  margin: auto;
  

}



@media(max-width:500px){
  
}









</style>
<script>
   import HomeView from './views/HomeView.vue';


export default{
 nome:"app",
   components:{
HomeView
   },
 
 data(){


 }


}
</script>