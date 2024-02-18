<template>
  <div>
    
  <h1>
    Info personal: {{ info }}
  </h1>
  <p>{{ Nombre }}</p>
  <p>{{ Matricula }}</p>
  <p>{{ Grupo }}</p>
  <img :src="require('@/assets/Espada.jpg')" />
  </div>
</template>

<script>
  export default{
    data(){
       return{
        info: "",
        Nombre: "Alexis Eduardo Aguilar Zacarias",
        Matricula: "20962",
        Grupo: "5A"
       }
    }
  }
</script>