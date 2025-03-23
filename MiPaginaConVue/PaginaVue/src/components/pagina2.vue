<script>
import icono from '../assets/icono.png';
import album1 from '../assets/twenty.webp';
import album2 from '../assets/regional.jpg';
import album3 from '../assets/vessel.jpg';
import album4 from '../assets/blurry.png';
import album5 from '../assets/threc.jpg';
import album6 from '../assets/scaled.jpg';
import album7 from '../assets/clancy.jpeg';
import presentacion from '../assets/presentacion.jpg';

export default {
    data() {
        return {
            icono,album1,album2,album3,album4,album5,album6,album7,presentacion
        }
    },
}

</script>
<template>
   <div class="container">
        <nav class="navbar navbar-expand-lg bg-body-tertiary bg-dark" data-bs-theme="dark" style="background: linear-gradient(to right, #000000, #931414f5);">
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
                 <a href="index.html"><img :src="icono" alt="Icono"
                  width="100" height="100" style="text-align: center;">
                    
                </a>
                
            </div>
        </nav>
       
        
        
    </div>
    <br>
    <br>
    <br><br>
    <div class="container">
            <!-- Álbum 1: Izquierda -->
            <div class="row justify-content-center">
                <div class="col-md-8">
                    <div class="card mt-3 shadow-lg">
                        <div class="card-header text-center text-white" style="background: linear-gradient(to right, #000000, #1563a7f5);">
                            <h5>El Lore de DEMA: La Historia Oculta de Twenty One Pilots</h5>
                        </div>
                        <div class="card-body text-center" style="background: linear-gradient(to right, #1563a7, #da1dbe); height: auto;">
                            <img :src="presentacion"
                                alt="Twenty One Pilots album" class="img-fluid rounded" width="400" height="400">
                            
                            <hr>
                            <p class="text-start" style="color: white;">
                                <strong>📜 ¿Qué es DEMA?</strong><br>
                                DEMA es una ciudad metafórica y distópica controlada por los <strong>Nueve Obispos</strong>, quienes representan la opresión, la ansiedad y la depresión. 
                                <br><br>
                                <strong>📖 Origen del Nombre:</strong> Se cree que proviene de "Dema y los Fariseos", un término que aparece en una carta escrita en <em>Trench</em>, sugiriendo un sistema opresivo.
                                <br><br>
                                <strong>📍 Localización de DEMA:</strong> Es una ciudad amurallada y aislada. En la portada de <em>Trench</em>, se pueden ver ruinas y un túnel, posiblemente la única vía de escape.
                            </p>
                            <hr>
                            <p class="text-start" style="color: white;">
                                <strong>🕵️‍♂️ Los Nueve Obispos – Controladores de DEMA</strong><br>
                                Cada Obispo representa una emoción negativa:
                                <ul style="text-align: start;color: white;" >
                                    <li><strong>Nico (Nicholas Bourbaki)</strong> - Líder de los Obispos, vinculado con <em>Blurryface</em>.</li>
                                    <li>Lisden</li>
                                    <li>Keons</li>
                                    <li>Reisdro</li>
                                    <li>Salinger</li>
                                    <li>Vetomo</li>
                                    <li>Sacuar</li>
                                    <li>Andre</li>
                                    <li>Norlim</li>
                                </ul>
                                <strong style="color: white; text-align: start;">💡 Dato Curioso:</strong> <p style="color: white;text-align: start;">"Nicholas Bourbaki" es una referencia a un grupo de matemáticos franceses que usaban un seudónimo colectivo.</p> 
                            </p>
                            <hr>
                            <p class="text-start" style="color: white;">
                                <strong>🎭 Scaled and Icy – La Propaganda de DEMA</strong><br>
                                <em>Scaled and Icy</em> parece ser un intento de control de DEMA sobre Clancy. Curiosamente, el título es un anagrama de <strong>"Clancy is Dead"</strong>, sugiriendo la captura de Clancy.
                            </p>
                            <a href="https://www.youtube.com/watch?v=xn3Easfz_e8" target="_blank" style="text-decoration: none;">
                                <button class="btn" style="background-color: black; color: white; border: none; padding: 10px 15px; cursor: pointer;">
                                   Video Explicativo <br><ion-icon name="logo-youtube" style="color: red;width: 150px;height: 150;"></ion-icon> 
                                    
                                </button>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
        <br>

</template>

<style >
    
</style>