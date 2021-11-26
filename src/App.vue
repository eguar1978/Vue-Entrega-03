<template>
  <div id="app">
    <ContainerCP 
      :titulo="titulo"
      :items="items" 
    />
  </div>
</template>

<script>
import ContainerCP from "./components/ContainerCP.vue"

export default {
  name: 'App',
  components: {
    ContainerCP,
  },
    data: () => ({
      titulo: "Comidas WEB",
      items:    [{
                    id: 1,
                    titulo: "Anana",
                    costo: 51,
                    imagen: "images/fyv/anana.jpeg",
                    descripcion: "There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomise",
                    tipo: "fyv",
                    promocionado: true
                }, {
                    id: 2,
                    titulo: "Arandano",
                    costo: 35,
                    imagen: "images/fyv/arandano.jpeg",
                    descripcion: "There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomise",
                    tipo: "fyv",
                    promocionado: true
                }, {
                    id: 3,
                    titulo: "Frutilla",
                    costo: 50,
                    imagen: "images/fyv/frutilla.jpeg",
                    descripcion: "There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomise",
                    tipo: "fyv",
                    promocionado: false
                }, {
                    id: 4,
                    titulo: "Higo",
                    costo: 35,
                    imagen: "images/fyv/higo.jpeg",
                    descripcion: "There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomise",
                    tipo: "fyv",
                    promocionado: true
                }, {
                    id: 5,
                    titulo: "Limon",
                    costo: 50,
                    imagen: "images/fyv/limon.jpeg",
                    descripcion: "There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomise",
                    tipo: "fyv",
                    promocionado: false
                }, {
                    id: 6,
                    titulo: "Manzana",
                    costo: 35,
                    imagen: "images/fyv/manzana.jpeg",
                    descripcion: "There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomise",
                    tipo: "fyv",
                    promocionado: false
                }, {
                    id: 7,
                    titulo: "Naranja",
                    costo: 50,
                    imagen: "images/fyv/naranja.jpeg",
                    descripcion: "There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomise",
                    tipo: "fyv",
                    promocionado: true
                }, {
                    id: 8,
                    titulo: "Pera",
                    costo: 35,
                    imagen: "images/fyv/pera.jpeg",
                    descripcion: "There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomise",
                    tipo: "fyv",
                    promocionado: true
                }, {
                    id: 9,
                    titulo: "Remolacha",
                    costo: 50,
                    imagen: "images/fyv/remolacha.jpeg",
                    descripcion: "There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomise",
                    tipo: "fyv",
                    promocionado: false
                }, {
                    id: 10,
                    titulo: "Zanahoria",
                    costo: 35,
                    imagen: "images/fyv/zanahoria.jpeg",
                    descripcion: "There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomise",
                    tipo: "fyv",
                    promocionado: false
                }]
            })
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
