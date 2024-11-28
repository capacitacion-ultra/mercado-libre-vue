<template>
    <div class="container mb-4">
        <div class="row"> <!-- Raiting y fecha -->
            <div class="d-flex mb-3">
                <div class="me-auto">
                    <RaitingComponent :percentage=percentage class="fs-6 mt-0" />
                </div>
                <div class="texto-gris"> {{ date }}</div>
            </div>
        </div>

        <div class="row"> <!-- Comentario -->
            <p class="text-start">
                {{ comment }}
            </p>
        </div>

        <div class="row"><!-- Botones like y dislike -->
            <button type="button" class="btn btn-outline-secondary w-auto ms-2">
                Es útil <i class="fa-regular fa-thumbs-up"></i> {{ quantityLike }}
            </button>
            <button type="button" class="btn btn-outline-secondary w-auto ms-3 rounded-circle">
                <i class="fa-regular fa-thumbs-down"></i>
            </button>
        </div>

        <hr>
    </div>
</template>

<script>
    import RaitingComponent from './RaitingComponent.vue';

    export default {
        props: ['percentage', 'date', 'comment', 'quantityLike'],
        name: 'CommentComponent',
        components : {
            'RaitingComponent' : RaitingComponent
        }
    }
</script>