<template>
    <div class="container">
        <h3 class=" mt-4" style="color:white;">horario</h3>
        <table class="table ">
            
            <thead>
                <tr class="table-primary">
                    <th scope="col">lunes</th>
                    <th scope="col">martes</th>
                    <th scope="col">miercoles</th>
                    <th scope="col">jueves</th>
                    <th scope="col">viernes</th>
                </tr>
            </thead>
            <tbody class=" table-success ">
                <tr v-for="(row, index) in horario" :key="index">
                    <td>{{ row.lunes }}</td>
                    <td>{{ row.martes }}</td>
                    <td>{{ row.miercoles }}</td>
                    <td>{{ row.jueves }}</td>
                    <td>{{ row.viernes }}</td>
                </tr>
            </tbody>
        </table>
    </div>


</template>
<style>
td {
    white-space: pre-line;
    /* Permite saltos de línea con \n */
    padding: 8px;
    text-align: center;
    
}

td{
    border: none;
}
</style>
<script setup>
import { ref } from 'vue';
const horario = ref([

    {
        lunes: " 11:00-13:00 \n Redes de Computadoras \n aula:RDS/Profesor:garcia hernandez astrid mildred",
        martes: "12:00-14:00 \nlenguje y automatas I \n aula:ACS/Profesor:acevedo bautista ivor" ,
        miercoles: "11:00-13:00  \n Redes de Computadoras \n aula:RDS/Profesor:garcia hernandez astrid mildred",
        jueves: "11:00-13:00 \nlenguje y automatas I \n aula:ACS/Profesor:acevedo bautista ivortomatas I", 
        viernes: "12:00-13:00 \nlenguje y automatas I \n aula:ACS/Profesor:acevedo bautista ivor"
    },
    {
    lunes: "13:00-15:00 \n ingenieria de software \n aula:RDS/Profesor:roman cruz jose alfredo", 
    martes: "15:00-17:00 \n sistemas operativos \n aula:ACS/Profesor:cruz perez jorge",
    miercoles: "13:00-15:00 \n programacion web \n aula:RDS/Profesor:vasquez martinez josue israel", 
    jueves: "13:00-15:00 \n administracion de base de datos  \n aula:RDS/Profesor:solano hernandez miguel angel", 
    viernes: "13:00-14:00  \n Redes de Computadoras \n aula:RDS/Profesor:garcia hernandez astrid mildred" },
    {
        lunes: " 15:00-17:00 \n programacion web \n aula:RDS/Profesor:vasquez martinez josue israel",
        martes: "17:00-19:00 \nlengujes de interfaz \n aula:LDS/Profesor:sanchez vasquez lucia" ,
        miercoles: "15:00-17:00 \n ingenieria de software \n aula:ACS/Profesor:roman cruz jose alfredo",
        jueves: "15:00-17:00 \n sistemas operativos \n aula:ACS/Profesor:cruz perez jorge", 
        viernes: "14:00-15:00 \n ingenieria de software \n aula:RDS/Profesor:roman cruz jose alfredo"
    },
    {
        lunes: "17:00-19:00 \n administracion de base de datos  \n aula:RDS/Profesor:solano hernandez miguel angel",
        
        jueves: "15:00-17:00 \nlengujes de interfaz \n aula:LDS/Profesor:sanchez vasquez lucia", 
        viernes: "15:00-16:00 \n programacion web \n aula:LDS/Profesor:vasquez martinez josue israel"
    },
    {
        viernes: "16:00-17:00 \n administracion de base de datos  \n aula:RDS/Profesor:solano hernandez miguel angel",
        
        
    },
])  
</script>