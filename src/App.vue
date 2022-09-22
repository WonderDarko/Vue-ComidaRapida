<template>
  <div>
    <div class="container">
      <div class="row">
        <div class="col-12">
          <h1 class="text-center">Comidas del dia</h1>
        </div>
      </div>
      <div class="row p-3">
      <div class="col-4">
        <card nombre="Tacos al pastor" descripcion="Platillo recomendado para comenzar el dia." costo="20" url="https://assets.unileversolutions.com/recipes-v2/236509.jpg"/>
      </div>
      <div class="col-4">
        <card nombre="Tortas" descripcion="Platillo recomendado para comenzar el dia." costo="40" url="https://www.poblanerias.com/wp-content/archivos/2021/01/rayito-1000x666.jpg"/>
      </div>
      <div class="col-4">
        <card nombre="Enchiladas" descripcion="Platillo recomendado para comenzar el dia." costo="60" url="https://www.mexicoenmicocina.com/wp-content/uploads/2013/11/Enchiladas-rojas-2.jpg"/>
      </div>
    </div>
    <div class="row p-3">
      <div class="col-4">
        <card nombre="Tostadas" descripcion="Platillo recomendado para comenzar el dia." costo="35" url="https://i.blogs.es/70730e/tostadas-h/450_1000.jpg"/>
      </div>
      <div class="col-4">
        <card nombre="Quesadillas" descripcion="Platillo recomendado para comenzar el dia." costo="25" url="https://www.vvsupremo.com/wp-content/uploads/2015/11/900X570_Two-Cheese-Quesadillas.jpg"/>
      </div>
      <div class="col-4">
        <card nombre="Albondigas" descripcion="Platillo recomendado para comenzar el dia." costo="40" url="https://www.lavanguardia.com/files/og_thumbnail/uploads/2018/07/17/5e997a42b5463.jpeg"/>
      </div>
    </div>
    </div>
    
  </div>
</template>

<script>
  import Card from "./components/Card.vue";
  export default{
    components: { Card },
    
  };
</script>

