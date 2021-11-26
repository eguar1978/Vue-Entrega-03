<template>
    <div>
        <div class="album py-1 bg-light">
            <div class="container">
                <div class="row">
                    <div class="col-12 justify-content-center container-banner">
                        <div class="container mt-3">
                            <h2>{{titulo}}</h2>
                            <table class="table table-based">
                                <thead>
                                    <tr>
                                        <th>Nombre</th>
                                        <th>Precio</th>
                                        <th>Promocionado</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <tr v-for="(item, index) in items" :key="index" :class="item.promocionado ? 'table-success' : 'table-info'">
                                        <td> {{ item.titulo }} </td>
                                        <td>$ {{ item.costo }} </td>
                                        <td v-if="item.promocionado"> 10% OFF </td>
                                        <td v-else> sin promocion </td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        props: ['titulo','items']
    }
    
</script>

<style scoped>

</style>