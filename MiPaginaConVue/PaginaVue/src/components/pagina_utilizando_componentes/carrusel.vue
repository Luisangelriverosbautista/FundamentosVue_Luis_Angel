<script >
import icono from '../../assets/icono.png';
import album1 from '../../assets/twenty.webp';
import album2 from '../../assets/regional.jpg';
import album3 from '../../assets/vessel.jpg';
import album4 from '../../assets/twenty_one_pilots_blurryface-portada.jpg';
import album5 from '../../assets/threc.jpg';
import album6 from '../../assets/scaled.jpg';
import album7 from '../../assets/clancy.jpeg';


export default {
    data() {
        return {
            icono,album1,album2,album3,album4,album5,album6,album7
        }
    },
}

</script>
<template>
    <div id="carouselExample" class="carousel slide">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img :src="album1" class="d-block w-100 tamaño" alt="Twenty_One_Pilots_album">"
                        
                </div>
                <div class="carousel-item">
                    <img :src="album2" class="d-block w-100 tamaño" alt="regional at best" >
                </div>
                <div class="carousel-item">
                    <img :src="album3" class="d-block w-100 tamaño" alt="vessel" >
                </div>
                <div class="carousel-item">
                    <img :src="album4" class="d-block w-100 tamaño" alt="vessel" >
                </div>
                <div class="carousel-item">
                    <img :src="album5" class="d-block w-100 tamaño" alt="vessel" >
                </div>
                <div class="carousel-item">
                    <img :src="album6" class="d-block w-100 tamaño" alt="vessel" >
                </div>
                <div class="carousel-item">
                    <img :src="album7" class="d-block w-100 tamaño" alt="vessel" >
                </div>
            </div>
            <button class="carousel-control-prev btn_carrucel_tam" type="button" data-bs-target="#carouselExample" data-bs-slide="prev"
                style="background-color: rgba(0, 0, 0, 0.706);">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next btn_carrucel_tam" type="button" data-bs-target="#carouselExample" data-bs-slide="next"
                style="background-color: rgba(0, 0, 0, 0.706);">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
</template>

<style>
.tamaño {
    width: 100;
    height: 700px;
    
}
.btn_carrucel_tam {
    width: 100px;
    height: 100px;
    background-color: rgba(0, 0, 0, 0.706);
     border-radius: 50%;
    margin-top: 300px; 
}
</style>