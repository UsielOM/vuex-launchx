<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">

 <Intento/>
 <Cuadrado/>
 <Botonescont/>

    </div>
 
</template>



<script>
import Intento from "../components/Intento.vue";
import Cuadrado from "../components/Cuadrado.vue";
import Botonescont from "../components/Botonescont.vue";

export default {
  name: 'HomeView',

  components:{
    Intento,
    Cuadrado,
    Botonescont
    
  }
  
}
</script>




<style>
.contador{
  font-size: 80px;
}
div{
  margin-bottom: 10px;
}


.cuadrado{
  font-size: 25px;
}


</style>
