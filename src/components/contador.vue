

<template>
  <h1>fredy Orellana</h1>
<p>{{ contador }}</p>
<button @click="incrementar">evelin</button>
<button @click="decrementar">Decrementar</button>
</template>

<script setup>
import { ref} from 'vue';
const contador = ref(0);
const incrementar = () => {
contador.value++;

}
const decrementar =()=>{
  contador.value--;
}




</script>

<style scoped>
p {
  color: rgb(221, 21, 161);
}


</style>
