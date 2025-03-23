<script >
import icono from '../assets/icono.png';
import album1 from '../assets/twenty.webp';
import album2 from '../assets/regional.jpg';
import album3 from '../assets/vessel.jpg';
import album4 from '../assets/blurry.png';
import album5 from '../assets/threc.jpg';
import album6 from '../assets/scaled.jpg';
import album7 from '../assets/clancy.jpeg';


export default {
    data() {
        return {
            icono,album1,album2,album3,album4,album5,album6,album7
        }
    },
}

</script>

<template >
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
        <!-- empieza carrucel -->
        <div id="carouselExample" class="carousel slide">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img :src="album1" class="d-block w-100" alt="Twenty_One_Pilots_album"width="50" height="600">"
                        
                </div>
                <div class="carousel-item">
                    <img :src="album2" class="d-block w-100" alt="regional at best" width="50"
                        height="600">
                </div>
                <div class="carousel-item">
                    <img :src="album3" class="d-block w-100" alt="vessel" width="50"
                        height="600">
                </div>
                <div class="carousel-item">
                    <img :src="album4" class="d-block w-100" alt="vessel" width="50"
                        height="600">
                </div>
                <div class="carousel-item">
                    <img :src="album5" class="d-block w-100" alt="vessel" width="50"
                        height="600">
                </div>
                <div class="carousel-item">
                    <img :src="album6" class="d-block w-100" alt="vessel" width="50"
                        height="600">
                </div>
                <div class="carousel-item">
                    <img :src="album7" class="d-block w-100" alt="vessel" width="50"
                        height="600">
                </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev"
                style="background-color: rgba(0, 0, 0, 0.706);">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next"
                style="background-color: rgba(0, 0, 0, 0.706);">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
        <!-- termina carrucel -->
        
    </div>
    <br>
    <br>
    <br><br>
    <div class="container">

        <!-- Álbum 1: Izquierda -->
        <div class="row justify-content-start">
            <div class="col-md-6">
                <div class="card mt-5">
                    <div class="card-header text-center" style="background: linear-gradient(to right, #000000, #1fff0ff5);">
                        <h5 style="color: white;">Twenty One Pilots</h5>
                    </div>
                    <div class="card-body text-center">
                        <img :src="album1" alt="Twenty One Pilots album"
                        class="img-fluid" style="border-radius: 10%;" width="400" height="400">
                        <p>
                            <h5>La infancia de la mente, la génesis del caos interno</h5> <br>

                            Este álbum es un grito de identidad, un intento de reconciliar la confusión juvenil con una
                            búsqueda
                            moldeada por la desesperación, pero que ya vislumbra la sombra de la duda. Es la infancia
                de significado. En sus letras se siente el eco de una mente que aún no ha sido             filosófica de la banda: preguntas sin respuesta, pensamientos en espiral y una esperanza
                            frágil que aún no ha sido puesta a prueba.
                        </p>
                        <a href="https://open.spotify.com/playlist/3tc8aLDGfRto15WXLAcEXk?si=103a9ls8TJCVGYpOIsQqWg" target="_blank" style="text-decoration: none;">
                            <button class="btn" style="background-color: black; color: white; border: none; padding: 10px 15px; cursor: pointer;">
                                <i class="bi bi-music-note-beamed"></i> Escuchar álbum
                            </button>
                        </a>
                    </div>
                </div>
            </div>
        </div>

        <!-- Álbum 2: Derecha -->
        <div class="row justify-content-end">
            <div class="col-md-6">
                <div class="card mt-3">
                    <div class="card-header text-center" style="background: linear-gradient(to right, #000000, #1563a7f5);">
                        <h5 style="color: white;">Regional at Best</h5>
                    </div>
                    <div class="card-body text-center" >
                        <img :src="album2" alt="Regional at Best album" 
                        class="img-fluid" style="border-radius: 10%;"
                            width="400" height="400">
                        <p>
                            <h5>La chispa de la transformación, el cuestionamiento del yo</h5> <br>

                            Un experimento sin límites, un salto de fe hacia lo desconocido. Aquí,
                            la música no sigue caminos definidos, sino que se desborda en múltiples direcciones,
                            reflejando una mente que intenta escapar de la monotonía de lo preestablecido. Es la batalla
                            entre el potencial
                            y la incertidumbre, entre lo que se es y lo que se podría ser.
                            Es el punto donde la creatividad encuentra su primera gran fractura: el miedo a la
                            irrelevancia.
                        </p>
                        <a href="https://open.spotify.com/intl-es/album/2pvaY5uQvitGuztVNfsRR8?si=38i09lXBQv6b7tHAYFWcTA" target="_blank" style="text-decoration: none;">
                            <button class="btn" style="background-color: black; color: white; border: none; padding: 10px 15px; cursor: pointer;">
                                <i class="bi bi-music-note-beamed"></i> Escuchar álbum
                            </button>
                        </a>
                    </div>
                </div>
            </div>
        </div>

        <!-- Álbum 3: Izquierda -->
        <div class="row justify-content-start">
            <div class="col-md-6">
                <div class="card mt-3">
                    <div class="card-header text-center" style="background: linear-gradient(to right, #000000, #fffffff5);">
                        <h5 style="color: white;" >Vessel</h5>
                    </div>
                    <div class="card-body text-center">
                        <img :src="album3" alt="Vessel album"
                        class="img-fluid" style="border-radius: 10%;" width="400" height="400">
                        <p>
                            <h5> El cuerpo como prisión, la mente como enemigo</h5> <br>

                            La lucha interna se hace presente. La mente se convierte en un campo de batalla donde la
                            esperanza
                            y la desesperación pelean por el control. Aquí, los demonios internos ya no son sombras
                            pasajeras,
                            sino habitantes permanentes de un cerebro inquieto. Cada canción es un intento de navegar
                            las turbulentas
                            aguas de la ansiedad y la depresión, de encontrar refugio en la música cuando el mundo
                            parece indiferente.
                            La juventud choca con la mortalidad y,
                            por primera vez, la risa se mezcla con el llanto.
                        </p>
                        <a href="https://open.spotify.com/intl-es/album/2r2r78NE05YjyHyVbVgqFn?si=lgz0SdAWQGeV5x1GsEKVew" target="_blank" style="text-decoration: none;">
                            <button class="btn" style="background-color: black; color: white; border: none; padding: 10px 15px; cursor: pointer;">
                                <i class="bi bi-music-note-beamed"></i> Escuchar álbum
                            </button>
                        </a>
                    </div>
                </div>
            </div>
        </div>

        <!-- Álbum 4: Derecha -->
        <div class="row justify-content-end">
            <div class="col-md-6">
                <div class="card mt-3">
                    <div class="card-header text-center" style="background: linear-gradient(to right, #000000, #d11e1e);">
                        <h5 style="color: white;">Blurryface</h5>
                    </div>
                    <div class="card-body text-center">
                        <img :src="album4" alt="Blurryface album" style="border-radius: 10%;"
                        class="img-fluid"  width="400" height="400">
                        <p>
                            <h5>El nacimiento del alter ego, la personificación de la duda</h5> <br>

                            Aquí, la inseguridad toma forma, se vuelve un personaje, un enemigo con nombre propio:
                            Blurryface.
                            Ya no es solo un sentimiento abstracto, sino una presencia tangible, una voz que susurra al
                            oído cada defecto,
                            cada miedo, cada error. Este álbum es una exploración de la autoimagen distorsionada, del
                            peso de la opinión externa
                            y de la necesidad de aceptación en un mundo donde la identidad es una máscara que nunca
                            encaja del todo.
                            Es un grito de auxilio disfrazado de revolución.
                        </p>
                        <a href="https://open.spotify.com/intl-es/album/3cQO7jp5S9qLBoIVtbkSM1?si=1YTmLUvlQPenB9Le9KJtTw" target="_blank" style="text-decoration: none;">
                            <button class="btn" style="background-color: black; color: white; border: none; padding: 10px 15px; cursor: pointer;">
                                <i class="bi bi-music-note-beamed"></i> Escuchar álbum
                            </button>
                        </a>
                    
                    </div>
                </div>
            </div>
        </div>

        <!-- Álbum 5: Izquierda -->
        <div class="row justify-content-start">
            <div class="col-md-6">
                <div class="card mt-3">
                    <div class="card-header text-center" style="background: linear-gradient(to right, #000000, #c2d11e);">
                        <h5 style="color: white;">Trench</h5>
                    </div>
                    <div class="card-body text-center">
                        <img :src="album5" alt="Trench album" style="border-radius: 10%;"
                        class="img-fluid"  width="400" height="400">
                        <p>
                            <h5>El exilio de la mente, la guerra contra el sistema</h5> <br>

                            Un mundo distópico, una metáfora de la opresión y la libertad.
                            En Trench, el viaje es literal y figurado: se huye de una estructura de control mientras se
                            busca el significado de la resistencia. Cada canción es una pieza del rompecabezas de la
                            identidad,
                            donde las cicatrices del pasado se convierten en mapas para escapar de la opresión interna y
                            externa. Aquí, la lucha ya no es solo contra el propio reflejo,
                            sino contra el mundo que impone normas invisibles para silenciar la diferencia.
                            ¿Es posible realmente huir, o la jaula está dentro de uno mismo?
                        </p>
                        <a href="https://open.spotify.com/intl-es/album/621cXqrTSSJi1WqDMSLmbL?si=lO0093WFQJqtEAh5s0CzQw" target="_blank" style="text-decoration: none;">
                            <button class="btn" style="background-color: black; color: white; border: none; padding: 10px 15px; cursor: pointer;">
                                <i class="bi bi-music-note-beamed"></i> Escuchar álbum
                            </button>
                        </a>
                    </div>
                </div>
            </div>
        </div>

        <!-- Álbum 6: Derecha -->
        <div class="row justify-content-end">
            <div class="col-md-6">
                <div class="card mt-3">
                    <div class="card-header text-center" style="background: linear-gradient(to right, #1563a7f5, #da1dbef5);">
                        <h5 style="color: white;">Scaled and Icy</h5>
                    </div>
                    <div class="card-body text-center">
                        <img :src="album6" alt="Scaled and Icy album"
                        class="img-fluid"  style="border-radius: 10%;" width="400" height="400">
                        <p>
                            <h5>La felicidad artificial, el espejismo del conformismo</h5> <br>

                            Un espejismo de felicidad, una máscara de colores vibrantes que oculta una batalla interna.
                            Scaled and Icy es la aceptación de que, a veces, la única forma de sobrellevar la vida es
                            fingiendo que todo está bien. Pero debajo de la superficie, la mente sigue en guerra. Cada
                            melodía alegre esconde una sombra, cada ritmo bailable esconde una pregunta: ¿Es esto real o
                            solo un acto de supervivencia? El conformismo se siente como una prisión cómoda, pero ¿acaso
                            no sigue siendo una prisión?
                        </p>
                        <a href="https://open.spotify.com/intl-es/album/0Q5XBpCYFgUWiG9DUWyAmJ?si=ccS7YPR2ROyDRZKgBZWoQA" target="_blank" style="text-decoration: none;">
                            <button class="btn" style="background-color: black; color: white; border: none; padding: 10px 15px; cursor: pointer;">
                                <i class="bi bi-music-note-beamed"></i> Escuchar álbum
                            </button>
                        </a>
                    </div>
                </div>
            </div>
        </div>
        <div class="row justify-content-start">
            <div class="col-md-6">
                <div class="card mt-3">
                    <div class="card-header text-center" style="background: linear-gradient(to right, #d11e1e, #d4cb1c);">
                        <h5 style="color: white;">Clancy</h5>
                    </div>
                    <div class="card-body text-center">
                        <img :src="album7" alt="Scaled and Icy album"
                        class="img-fluid"   style="border-radius: 10%;" width="400" height="400">
                        <p>
                            <h5>El regreso al laberinto, la última confrontación con la identidad</h5><br>

                            Clancy no es solo un álbum, es el cierre de un viaje, el punto donde todas las preguntas se
                            encuentran en un cruce
                            de caminos sin señales claras. Es la confrontación final con uno mismo, el regreso a la raíz
                            de todo lo que ha sido y todo lo que se ha temido. Aquí, la resistencia ya no es una huida,
                            sino una declaración: "Si este es mi destino, lo enfrentaré de frente".
                            La música se siente como páginas de un diario escrito en medio de una tormenta, donde la
                            esperanza
                            y el miedo se entrelazan en un baile caótico. Clancy es la mirada al espejo sin desviar la
                            vista,
                            la aceptación de que las sombras nunca desaparecen, pero que aprender a vivir con ellas es
                            la verdadera libertad.
                            No es el fin de la historia, pero sí el cierre de un ciclo. No se trata de ganar o perder,
                            sino de entender que el viaje en sí mismo es la respuesta.
                        </p>
                        <a href="https://open.spotify.com/intl-es/album/1KFWgQTw3EMTQebaaepVBI?si=zVVzM98KR7KvCsXNTMtGjQ" target="_blank" style="text-decoration: none;">
                            <button class="btn" style="background-color: black; color: white; border: none; padding: 10px 15px; cursor: pointer;">
                                <i class="bi bi-music-note-beamed"></i> Escuchar álbum
                            </button>
                        </a>
                        
                    </div>
                </div>
            </div>
        </div><br>

    </div>

</template>

<style scoped></style>
