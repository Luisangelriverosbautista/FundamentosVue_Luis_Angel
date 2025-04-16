<script>
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
            icono, album1, album2, album3, album4, album5, album6, album7
        }
    },
}

</script>
<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary bg-dark" data-bs-theme="dark"
        style="background: linear-gradient(to right, #000000, #931414f5);">
        <div class="container-fluid">

            <a class="navbar-brand" href="index.html">TWENTY ONE PILOTS</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="index.html">inicio</a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link" href="index2.html">lore</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="index2.html">acerca de</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link ">comentario</a>

                    </li>
                </ul>

            </div>
            <a href="#"><img :src="icono" alt="Icono" width="100" height="100" style="text-align: center;">

            </a>

        </div>
    </nav>
</template>