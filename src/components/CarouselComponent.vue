<template>
    <!-- Carousel wrapper -->
    <div id="carouselMDExample" class="carousel slide carousel-fade w-100" data-bs-interval="false"> <!-- w-75 se cambio a w-100-->
        <!-- Slides -->
        <div class="carousel-inner mb-0 shadow-1-strong rounded-3 ">
            <div :class=selecciona(index) v-for="(elemento,index) in img" v-bind:key="index" class="align-self-center imagenpadre">
                <div v-if=pinta(elemento)>
                    <img :src=baseUrl+elemento class="img-fluid imgsizehead m-auto" alt="..." />
                </div>
                <div v-else>
                    <a href="#" class="sombra">
                        <video 
                            id="videoElement" 
                            ref="videoElement"
                            @click="toogle" 
                            class="img-fluid imgsizehead m-auto" 
                            :controls="false" 
                            :poster=poster()>
                            <source :src=baseUrl+elemento type="video/mp4" />
                            Your browser does not support the video tag.
                        </video> 
                    </a>
                </div>
            </div>
        </div>
        <!-- Slides -->

        <!-- Controls -->
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselMDExample" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="false"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselMDExample" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="false"></span>
            <span class="visually-hidden">Next</span>
        </button>
        <!-- Controls -->

        <!-- Thumbnails -->
        <div class="row w-100 d-flex justify-content-start">
            <div class="ajusta" style="margin-bottom: -20px;">
                <span v-for="(miniatura,index) in img" v-bind:key="index" class="text-center">
                    <button 
                        class="boton-tumb"
                        data-bs-target="#carouselMDExample" 
                        aria-current="true" 
                        aria-label="Slide 1"
                        :data-bs-slide-to=index >
                        <img :src=coloca(miniatura) class="imgsize"/>
                    </button>
                </span>
            </div>
        </div>
        <!-- Thumbnails -->
    </div>
</template>

<script>
    export default {
        props: ['img', 'baseUrl'],
        name: "CarouselComponent",
        data() {
            return {
                caruselActivo: "carousel-item active",
                caruselInactivo: "carousel-item",
            }
        },
        methods: {
            selecciona: function(index) {
                return (index==0)?this.caruselActivo:this.caruselInactivo
            },
            pinta: function(elemento) {
                return !elemento.endsWith('.mp4');
            },
            poster: function() {
                return this.baseUrl+'play-movie3.jpg'
            },
            coloca: function(miniatura) {
                if(miniatura.endsWith('.mp4')) {
                    return this.baseUrl+'amlo.jpg'
                }
                return this.baseUrl+miniatura
            },
            toogle: function() {
                const video = this.$refs.videoElement[0];
                if(video.paused) {
                    video.play()
                } else {
                    video.pause()
                }  
            }
        }
    }
</script>

<style scoped>
    .imgsize {
        width: 110px;
        height: 80px;
        object-fit: contain;
    }
    .imgsizehead {
        width: 80%;
        height: 80%;
        object-fit: contain;
    }
    .imagenpadre {  /** 300px cambio a 400px */
        height: 400px;
    }
    .boton-tumb {
        background-color: white;
        border: 0;
        display: contents;
    }
    .ajusta {
        height: 100px;
        display: flex;
        overflow-x: scroll;
        scrollbar-color: rgba(8, 8, 66, 0.877) rgba(255, 255, 0, 0.534);
    }/*
    .carousel-control-next-icon {
        background-image: url('https://gitlab.qbits.mx/D-2.jpg');
    }
    .carousel-control-prev-icon {
        background-image: url('https://gitlab.qbits.mx/D-2.jpg');
    }*/
    .sombra:hover {
        background-color: #BB0000;
    }
</style>