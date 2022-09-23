<template>
  <hr />
  <card 
  url= "https://cdn.pixabay.com/photo/2017/12/09/08/18/pizza-3007395__340.jpg" 
  nombre="Pizza"
  descripcion="Especie de torta de harina amasada , encima de la cual se pone queso , tomate frito y otros ingredientes , y que se cuece en el horno ."
  costo="135"
  />
  <card url="https://media.istockphoto.com/photos/milanese-cutlet-picture-id1370911251?b=1&k=20&m=1370911251&s=170667a&w=0&h=lE5H_uxFWN5Ddg-FTjZnJWqdO0gLNWODDe9Kw8QreOw=" 
  nombre="Milanesas de pollo"
  descripcion="Son hechas con pan molido, fritas. Se pueden rellenar con queso y jamon"
  costo="50"
  />
  <card url="https://cdn.pixabay.com/photo/2021/01/16/09/05/meal-5921491__340.jpg" 
  nombre="Arroz a la jardinera"
  descripcion="Platillo con verdura incluida, puede tener zanahoria, chicharro y elotito"
  costo="70"
  />
  <card url="https://cdn.pixabay.com/photo/2020/05/12/23/55/sushi-5165271__340.jpg" 
  nombre="Spaghetti verde "
  descripcion="Pasta hecha a base de escencias verdes, chile poblano, cilindro, crema y queso"
  costo="65"
  />
  <card url="https://cdn.pixabay.com/photo/2014/10/09/20/02/tomato-soup-482403__340.jpg" 
  nombre="Salsa de chipotle con chuletas y piña"
  descripcion="El elemento principal es la piña ya que el sabor es el más pronunciado, excelente para paladares exigentes"
  costo="75"
  />
  <card url="https://cdn.pixabay.com/photo/2019/09/28/21/04/meatballs-4511773__340.jpg" 
  nombre="Albondigas"
  descripcion="Bolitas de carne molida de cerdo"
  costo="35"
  />
  <card url="https://media.istockphoto.com/photos/rolled-tacos-guatemala-typical-food-picture-id516461671?b=1&k=20&m=516461671&s=170667a&w=0&h=6BI4FMfKQQMk4waRwABp5Cveiz_H8_0IXcE6KxCnGuM=" 
  nombre="Tacos dorados de pollo"
  descripcion="Tortilla rellena con pollo. Después de ser frita se sirve con lechuga, queso, crema y salsa al gusto"
  costo="15"
  />
  <hr />
</template>

<script>
  import Card from "./components/Card.vue";
  
  export default {
    components: { Card },
  };
</script>