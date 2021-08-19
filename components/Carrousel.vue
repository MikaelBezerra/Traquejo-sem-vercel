<template>
   <div class=" w-full pl-3 pb-3">
      <div id="item" class="rounded-lg flex overflow-x-auto ">
         <div id="div-img" class="flex-none w-full ">
            <img  class="w-full h-full object-cover" src="https://images.unsplash.com/photo-1422303289886-00d1f7710118?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1052&q=80" alt="">
         </div>
         <div id="div-img" class="flex-none w-full ">
            <img  class="w-full h-full object-cover" src="https://images.unsplash.com/photo-1422112528461-3186878f87dc?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=967&q=80" alt="">
         </div>
         <div id="div-img" class="flex-none w-full ">
            <img  class="w-full h-full object-cover" src="https://images.unsplash.com/photo-1592337283075-215253227066?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80" alt="">
         </div>
         <div id="div-img" class="flex-none w-full ">
            <img  class="w-full h-full object-cover" src="https://images.unsplash.com/photo-1598624669900-ee1be9f81e23?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1065&q=80" alt="">
         </div>
      </div>
   </div>
</template>

<style scoped>
   #item {
      scroll-snap-type: x mandatory;
      -webkit-overflow-scrolling: touch; 
   }
   #div-img{
      scroll-snap-align: start;
   }
</style>
