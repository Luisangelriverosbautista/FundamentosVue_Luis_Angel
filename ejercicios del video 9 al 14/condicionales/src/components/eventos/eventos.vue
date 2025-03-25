<template>
    <div class="container">
        <div class="row mt-4">
            <div class="div">
                <h4>evento click</h4>
                <button @click="clic" class="btn btn-danger" type="button">dale click</button>
                <button @click="soyBoton" class="btn btn-warning mx-2" type="button">dale click 2</button>
            </div>
            <div class="div">
                <h4>evento change</h4>


                <label class="input-group-text">ingrese tu nombre</label>
                <input class="form-control mt-2" type="text" id="nombre" @change="nombreE">
                <p>el nombre ingresado es: <strong>{{ nombre }}</strong></p>

            </div>
            <div>
                <h3>envento de mouseenter y mouseleave</h3>
               <div style="width: 300px;height: 200px;background-color: black; text-align: center;padding: 15px;border-radius: 14px;"
                @mouseenter="mostrarMensaje" @mouseleave="ocultarMensaje">
             <p>pase el muse</p>
            <p class="text-white">{{ mensaje }}</p>
            </div> 
            </div>
            
           
        </div>
    </div>

</template>
<script>
export default {
    data() {
        return {
            nombre: '',
            mensaje: ''
        }
    },
    methods: {
        clic() {
            alert("gracias por darle click")
        },
        soyBoton() {
            alert("soy un boton")
        },
        nombreE(event) {
            this.nombre = event.target.value

        },
        mostrarMensaje() {
            this.mensaje = "el mouse esta dentro del rectangulo"
        },
        ocultarMensaje() {
            this.mensaje = "el mouse esta fuera del rectangulo"
        }
    }
}
</script>
<style></style>