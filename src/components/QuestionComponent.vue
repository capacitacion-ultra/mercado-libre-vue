<template>
    <div class="mt-4">
        <p class="fs-6 mb-2">{{ question }}</p>
        <p class="ms-4 mt-0 texto-gris"> {{ answer }}</p>
    </div>
</template>

<script>
    export default {
        props: ['question', 'answer'],
        name: "QuestionComponent"
    }
</script>

<style scoped>
.texto-gris {
  font-size: 0.9rem;
  color: #545B77;
}
</style>