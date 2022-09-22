<template>
  <div>
    <h1>Componentes en Vue</h1>
    <hr/>
    <div class="container">
      <div class="row">
      <div class="col-4">
        <card nombre="Sopa" descripcion="Prueba de descripcion" costo="20" url="https://images.vexels.com/media/users/3/141250/isolated/preview/3740af73cfd1da1211270e8a402ef284-sopa-en-un-bol.png"/>
      </div>
      <div class="col-4">
        <card nombre="Sopa" descripcion="Prueba de descripcion" costo="20" url="https://images.vexels.com/media/users/3/141250/isolated/preview/3740af73cfd1da1211270e8a402ef284-sopa-en-un-bol.png"/>
      </div>
      <div class="col-4">
        <card nombre="Sopa" descripcion="Prueba de descripcion" costo="20" url="https://images.vexels.com/media/users/3/141250/isolated/preview/3740af73cfd1da1211270e8a402ef284-sopa-en-un-bol.png"/>
      </div>
    </div>
    <div class="row">
      <div class="col-4">
        <card nombre="Sopa" descripcion="Prueba de descripcion" costo="20" url="https://images.vexels.com/media/users/3/141250/isolated/preview/3740af73cfd1da1211270e8a402ef284-sopa-en-un-bol.png"/>
      </div>
      <div class="col-4">
        <card nombre="Sopa" descripcion="Prueba de descripcion" costo="20" url="https://images.vexels.com/media/users/3/141250/isolated/preview/3740af73cfd1da1211270e8a402ef284-sopa-en-un-bol.png"/>
      </div>
      <div class="col-4">
        <card nombre="Sopa" descripcion="Prueba de descripcion" costo="20" url="https://images.vexels.com/media/users/3/141250/isolated/preview/3740af73cfd1da1211270e8a402ef284-sopa-en-un-bol.png"/>
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

