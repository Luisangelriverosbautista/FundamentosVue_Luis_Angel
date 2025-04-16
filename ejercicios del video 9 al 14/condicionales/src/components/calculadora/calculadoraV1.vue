<script>
export default{
    data() {
        return {
            numero1:0,
            numero2:0,
            resultado:0,
        }
    },
    methods: {
        sumar(){
            this.resultado= parseInt(this.numero1) + parseInt(this.numero2);
        },
        restar(){
            this.resultado= parseInt(this.numero1) - parseInt(this.numero2);
        },
        multiplicar(){
            this.resultado= parseInt(this.numero1) * parseInt(this.numero2);
        },
        dividir(){
            this.resultado= parseInt(this.numero1) / parseInt(this.numero2);
        }

    },
}
</script>
<template>
    <div class="container mt-5">
        <div class="card shadow p-4">
            <h1 class="text-center">calculadoraV1</h1>
            <h2 class="text-center mt-4"> {{ resultado }}</h2>
            <div class="mb-3">
                <label for="">numero 1</label>
                <input type="number" class="form-control" v-model="numero1">
            </div>
            <div class="mb-3">
                <label for="">numero 2</label>
                <input type="number" class="form-control" v-model="numero2">
            </div>
            <div class="d-flex justify-content-center gap-2">
                <button @click="sumar" class="btn btn-danger"> sumar</button>
                <button @click="restar" class="btn btn-primary"> restar</button>
                <button @click="multiplicar" class="btn btn-danger"> multiplicar</button>
                <button @click="dividir" class="btn btn-primary"> dividir</button>
            </div>
           
        </div>


    </div>
</template>
<style>
h2{
    color: rgb(255, 255, 255);
    background-color: rgb(247, 110, 179);
    border-radius: 15px;
    padding: 10px;
    text-align: center;
}
</style>