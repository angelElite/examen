<template>
    <grid>
      <div class="card" style="width: 18rem;">
        <img v-bind:src="url" :alt="nombre" class="card-img-top">
        <div class="card-body">
          <h5 class="card-title">{{ nombre }}</h5>
          <p class="card-text">{{ descripcion }} <ul>${{ costo }}</ul></p>
          <a href="#" class="btn btn-primary">Leer mas....</a>
        </div>
      </div>
    </grid>
</template>

<script>
import Grid from "./Grid.vue";
    export default {
    props: {
        url: { String },
        nombre: { String },
        descripcion: { String},
        costo: { String }
    },
    components: { Grid }
};
</script>

<style scoped>
   
    img {
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 60%;
        background-color: snow;
    }

</style>
