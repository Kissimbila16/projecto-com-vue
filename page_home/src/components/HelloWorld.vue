<style scoped>
    a{
    color:white;
   text-decoration: none;
   font-weight:500;
   margin-left: 15px;
   font-size:20px;
    }

    ol{
          display: flex;
          justify-content: center;
          margin-left: -10%;
      
    }

.title{

  font-family: 'poppins';
  font-size: 30px;
  font-weight: 600;
  text-align: left;
  margin-left:10% ;
 

}


#fundo{
 
    height:100%;
    height: 100%;
    border-radius: 15px;

}


.body{
  display: grid;
  justify-content: top;
  margin-bottom:45%;
}

</style>


<template >

<div class="d-grid  fundo row-4 w-50" id="fundo" style="background-color:rgb(131, 38, 131);">

  <div class="row" style="color:white;padding-top: 5px;">
 <div class="col">
  <h2 class="title" >XBOX</h2>
 </div>


 <div class="col">

  <div class="row" >
  <ol  class="" style="list-style: none;text-decoration: none; color:white;align-items: center;">
<li><a href="inicio">Home</a></li>
<li><a href="about">About</a></li>
<li><a href="contacto">Contact</a></li>
<li><a href="suporte">Suporte</a></li>

<li>

 <div class="d-flex row-12">
  &nbsp;  <input type="text" name="nome" class="col-8 rounded-3 border-2 border-dark"  style="border:solid 1px black;height:30px;margin-top: 6px;" placeholder="Qual é o nome do jogo">
<button class="col-2" style="background-color: transparent;border: none;">  <i class="bi bi-search text-light" style="font-size: 20px;"></i></button>
<button class="col-2" style="background-color: transparent;border: none;"> <i class="bi bi-cart4 text-light" style="font-size: 20px;"></i></button>
<button class="col-2" style="background-color: transparent;border: none;"> <i class="bi bi-circle-fill text-light" style="font-size: 20px;"></i></button>


 </div>
</li>
  </ol>
  </div>
 </div>
</div>
<ConteudoVer/>
<br>
</div>




</template>


<script>
import ConteudoVer from './ConteudoVer.vue';
export default{
name:"helloWord",
components:{
  ConteudoVer
},
data(){

}



}
</script>