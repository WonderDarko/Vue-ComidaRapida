<template>
    <div class="card mar" style="width: 18rem;">
        <Img>
            <img v-bind:src="url" class="card-img-top">
        </Img>
        <div class="card-body">
            <h5 class="card-title">{{nombre}}</h5>
            <p class="card-text">{{descripcion}}</p>
            <p class="card-text">Costo: {{costo}}</p>
        </div>
    </div>
</template>

<script>
import Img from "./Img.vue";
        export default{
    props: {
        nombre: {
            String
        },
        descripcion: {
            String
        },
        costo: {
            Number,
        },
        url: {
            String,
        }
    },
    components: { Img }
}
</script>

<!-- <style scoped>
    .mar{
        margin: 10px;
        display: inline-block;
    }
</style> -->