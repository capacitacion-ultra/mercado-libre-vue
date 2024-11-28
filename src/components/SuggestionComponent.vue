<template>
    <div :class="sizeClass(size)"> <!-- Sugerencia -->
        <a class="link sugestion-link" href="#">
            <div class="card border-gris m-2">
                <div class="d-flex justify-content-center"> <!-- Imagen sugerencia -->
                    <img class="img-fluid sugestion-image" :src=photo>
                </div>
                <hr class="texto-gris w-100">
                <div class="card-body text-start"> <!-- Detalles de una sugerencia -->
                    <p v-if="originalPrice != null" class="fs09rem texto-gris text-decoration-line-through my-0">${{ originalPrice }}</p>
                    <div class="d-flex">
                        <h4 class="card-title my-auto">${{ offerPrice }}</h4>
                        <p class="text-success fs09rem ms-1 my-auto">{{ discount }}% OFF</p>
                    </div>
                    <p v-if="monthsOffer != null" class="card-text text-success my-0 fs09rem">{{ monthsOffer }} x ${{ monthlyOffer }} sin interés</p>
                    <p v-if="full" class="card-text text-success my-0 fs09rem fw-bold">
                        <span v-if="freeShipping">Envío gratis</span>
                        <span class="text-uppercasefst-italic"><i class="fa-solid fa-bolt"></i>Full</span>
                    </p>
                    <p class="card-text my-0 fs09rem">{{ months }} x ${{ monthlyPayment }}</p>
                    <p class="card-text my-0 fs09rem lh-1">{{ name }}
                        Mini</p>
                </div>
            </div>
        </a>
    </div>
</template>

<script>
    export default {
        props: ['size', 'id', 'photo', 'originalPrice', 'offerPrice', 'discount', 'freeShipping', 'full', 'monthsOffer', 'monthlyOffer', 'months', 'monthlyPayment', 'name'],
        name: "SuggestionComponent",
        data() {
            return {
                size3: 'col-md-3 mb-3',
                size4: 'col-md-4 mb-3',
                size12: 'col-md-12 mb-3',
            }
        },
        methods: {
            sizeClass: function(size) {
                if (size == 3)
                    return this.size3;
                else if (size == 4)
                    return this.size4;
                else
                    return this.size12;
            }
        }
    }
</script>

<style>
.link {
  text-decoration: none;
}

.link:hover {
  color: #30A2FF;
}

.sugestion-image {
  height: 190px;
  width: 190px;
}

.sugestion-link:hover {
  box-shadow: 0 0 20px #4f9;
}

.border-gris {
  border-color: #EDEDED;
}

.border-gris:hover {
  -webkit-box-shadow: 0px 0px 5px 5px rgba(209, 201, 209, 1);
  -moz-box-shadow: 0px 0px 5px 5px rgba(209, 201, 209, 1);
  box-shadow: 0px 0px 5px 5px rgba(209, 201, 209, 1);
}

.fs09rem {
  font-size: 0.9rem;
}

.texto-gris {
  font-size: 0.9rem;
  color: #545B77;
}
</style>