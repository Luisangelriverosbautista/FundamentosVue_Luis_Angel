<script>
export default{
    data() {
        return {
            alumnos: [
                        {nc:1234, nombre : 'luis', carrera: 'ISC'},
                        {nc:1234, nombre : 'mari', carrera: 'veterinaria'},
                        {nc:1234, nombre : 'gera', carrera: 'ENFERMERA'},
                        {nc:1234, nombre : 'gera', carrera: 'ENFERMERA'}

                    ]       
        }
    }
}
</script>
<template>
<div class="container">
    <h3 class="">lista de alumnos</h3>
    <ul>
        <li v-for=" alumno in alumnos" :key="alumno.nc">
            <strong>{{ alumno.nombre }} </strong>-
            <strong>{{ alumno.carrera }} </strong>
        </li>
    </ul>
</div>
</template>
<style>
h3{
    color: rgb(255, 255, 255);
    background-color: rgb(247, 110, 179);
    border-radius: 15px;
    padding: 10px;
}
ul{
    list-style-type: none;
    padding: 0%;
}
li{
    background-color: black;
    border-radius: 15px;
    padding: 10px;
    margin: 10px;
    color: rgb(255, 255, 255);
}
</style>