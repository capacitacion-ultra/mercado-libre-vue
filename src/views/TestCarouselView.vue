<template>
    <div class="container">
        <div class="row">
            <div class="col d-md-flex align-items-center">
                <CarouselComponent class="ajusta" 
                    :img=imagenes 
                    :baseUrl=url 
                />
            </div>
        </div>
    </div>
</template>

<script>
    import CarouselComponent from '@/components/CarouselComponent'
    import info from './ProductoView.json';

    export default {
        components: {
            'CarouselComponent': CarouselComponent
        },
        data: function () {
            return { 
                imagenes: info.dimg,
                url: 'http://127.0.0.1/'
            }
        }
    }
</script>

<style scaoped>
    .ajusta {
        width: 400px;
    }
</style>