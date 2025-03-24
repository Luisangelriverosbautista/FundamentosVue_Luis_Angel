<script>
export default{
    data() {
        return {
            alumnos: [
                        {id:1234, nombre_completo: 'luis angel riveros', gusto: 'le gusta la musica como el rok y estilos parecidos,ect.'},
                        {id:1234, nombre_completo : 'mari gonzlez', gusto: 'le gusta las flores como los girasoles'},
                        {id:1234, nombre_completo : 'gera martinez', gusto: 'le gusta ver series en sus tiempos libres'},
                        {id:1234, nombre_completo : 'alison vazquez', gusto: 'le guta el deporte'}

                    ]       
        }
    }
}
</script>
<template>
<div class="container">
    <h3 class="mt-4 ">lista de alumnos</h3>
    <ul>
        <li v-for=" alumno in alumnos" :key="alumno.id">
            <strong>{{ alumno.nombre_completo }} </strong>-
            <strong>{{ alumno.gusto }} </strong>
        </li>
    </ul>
</div>
</template>
<style>
h3{
    text-align: center;
    font-family:'Courier New', Courier, monospace;
    color: rgb(0, 0, 0);
    background-color: rgb(247, 110, 179);
    border-radius: 15px;
    padding: 10px;
}
ul{
    list-style-type: none;
    padding: 0%;
    text-align: justify;
    text-align: center;
}
li{
    font-family:'Courier New', Courier, monospace;
    background-color: rgb(219, 255, 250);
    border-radius: 15px;
    padding: 10px;
    margin: 10px;
    color: rgb(0, 0, 0);
}
</style>