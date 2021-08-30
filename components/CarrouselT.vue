<template>
   <div>
      <div id="carrousel" class="w-800 h-500 overflow-hidden">
         <div id="carrousel-itens" class="flex ">
            <!-- Inicio dos botões-->
            <!-- Vai precisar ser mudado mais tarde para se adequar ao numero de slides-->
            <input type="radio" name="btn-radio" id="radio1">
            <input type="radio" name="btn-radio" id="radio2">
            <input type="radio" name="btn-radio" id="radio3">
            <input type="radio" name="btn-radio" id="radio4">

            <div id="div-img" class="first">
               <img class="w-full h-full object-cover"  src="https://images.unsplash.com/photo-1422303289886-00d1f7710118?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1052&q=80" alt="">
            </div>
            <div id="div-img">
               <img class="w-full h-full object-cover"  src="https://images.unsplash.com/photo-1422112528461-3186878f87dc?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=967&q=80" alt="">
            </div>
            <div id="div-img">
               <img class="w-full h-full object-cover"  src="https://images.unsplash.com/photo-1592337283075-215253227066?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" alt="">
            </div>
            <div id="div-img">
               <img class="w-full h-full object-cover"  src="https://images.unsplash.com/photo-1598624669900-ee1be9f81e23?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1065&q=80" alt="">
            </div>

            <!-- Navegacao automata-->
            <div id="btn-auto1"></div>
            <div id="btn-auto2"></div>
            <div id="btn-auto3"></div>
            <div id="btn-auto4"></div>

            <!-- Navegacao manuel-->  
         </div> 

         <div id="nav-manuel" class="flex absolute">
            <label for="radio1" id="btn-manuel"></label>
            <label for="radio2" id="btn-manuel"></label>
            <label for="radio3" id="btn-manuel"></label>
            <label for="radio4" id="btn-manuel"></label>
         </div>
      </div>
   </div>
      
</template>
<style>
   #carrousel-itens{
      width: 500%;
      height: 500px;  
   }

   #carrousel-itens input{
      display: none;
   }

   #div-img{
      width: 20%;
      transition: 0.8s;
   }

   #nav-manuel{
      width:800px;
      margin-top:-40px;
      justify-content: center;
   }

   #btn-manuel{
      border: 2px solid white; 
      padding: 5px; 
      border-radius: 10px;
      transition: 0.2s; 
   }

   #btn-manuel:not(:last-child){
      margin-right: 40px
   }

   #btn-manuel:hover{
      background: white;
   }

   #radio1:checked ~ .first{
      margin-left: 0;
   }

   #radio2:checked ~ .first{
      margin-left: -20%;
   }

   #radio3:checked ~ .first{
      margin-left: -40%;
   }

   #radio4:checked ~ .first{
      margin-left: -60%;
   }

</style>
