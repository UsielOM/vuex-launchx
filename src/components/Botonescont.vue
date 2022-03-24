<template>

      <div class="botones">
        <button  @click="$store.dispatch('subirContador')">+</button>
        <button @click="$store.dispatch('bajarContador')">-</button>


      </div>
</template>



<script>
export default{
    name : 
    'Botonescont',
    }
</script>