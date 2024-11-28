<template>
    <p v-if="title != null" class="texto-gris fs-5 mt-4 my-0">
        {{ title }}
    </p>
    <p class="texto-gris fs-5">
        {{ description }}
    </p>
</template>

<script>
    export default {
        props: ['title', 'description'],
        name: "DescriptionComponent"
    }
</script>