  <style>
  .btns{
   width: 100%;
margin-left: 10%;

  }


  div.row button{

     height:40px;
     font-size:12px;

  }

  .h4{
     font-size: 14px;
     text-align: left;
     font-weight: 500;
     margin-left: 3%;
       


  }


.body{
    height:300px;
}

.img{
height: 85%;
border-radius: 20px;
margin-top: 0.3%;
margin-right:2%;
}

.sub-title{
animation-name:cor;
animation-duration: 3s;
animation-iteration-count: infinite;
animation-direction: normal;
  
}



@keyframes cor{

0%{color:red;}
50%{color:orange;}
70%{color:black;}
100%{color:aqua;}


}



</style>

<template>
    



    <div class="row">
  <div class="col">
  <div class="d-grid">
    <h2 class="sub-title" style="font-size: 120px;color:white;text-align: left;margin-left: 5%;">XBOX</h2>
<h3 style="font-size:30px;font-weight: 400; text-align:left;margin-left:5%;padding-top:-80px;color: white;">Wireless Controller</h3>
    <div class="row-8">
<h4 class="d-flex h4 text-light">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius sunt expedita, eveniet cumque repellat animi dolores temporibus sed perspiciatis minima neque perferendis, blanditiis esse quisquam illum facere, atque obcaecati alias?
Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius sunt expedita, eveniet cumque repellat animi dolores temporibus sed perspiciatis minima neque perferendis, blanditiis esse quisquam illum facere, atque obcaecati alias?</h4>

<div class="row d-flex w-100 btns" >
    <button class="w-25 btn-lg btn bg-dark text-light " style="margin-left: 5px;">Add Card</button>
    <button class="w-25 btn-lg btn bg-dark text-light " style="margin-left: 5px;">Add to wishlist</button>
</div>
    </div>


  </div>
  </div>


  <div class="col">
<div class="row img">
<img src="../assets/gamer.jpg" alt="gamer-control" class="rounded-5">
</div>

<div class="row w-100 d-flex justify-content-center ">
    <button class="d-flex justify-content-center border-none bg-transparent" style="height:40px;border-color:transparent;width:auto;border-radius: 5px;margin-top: 5px;"><i class="bi bi-circle-fill text-danger" style="font-size: 30px;"></i></button>
    <button class="d-flex justify-content-center border-none bg-transparent" style="height:40px;border-color:transparent;width:auto;border-radius: 5px;margin-top: 5px;"><i class="bi bi-circle-fill text-warning" style="font-size: 30px;"></i></button>
    <button class="d-flex justify-content-center border-none bg-transparent" style="height:40px;border-color:transparent;width:auto;border-radius: 5px;margin-top: 5px;"><i class="bi bi-circle-fill text-info" style="font-size: 30px;"></i></button>
    <button class="d-flex justify-content-center border-none bg-transparent" style="height:40px;border-color:transparent;width:auto;border-radius: 5px;margin-top: 5px;"><i class="bi bi-circle-fill text-sucess" style="font-size: 30px;"></i></button>
</div>

  </div>


    </div>
<div class="d-grid" style="margin-top: 100px;height:100%;">
<BodyVer/>
<br>
<BodyVer/>
<br>
<footerVer/>
</div>




</template>



<script>
import BodyVer from './BodyVer.vue'
import footerVer from './footerVer.vue'
  export default{

name:"ConteudoVer"
,
components:{
BodyVer,
footerVer
},
data(){


return{}

}

  }
</script>