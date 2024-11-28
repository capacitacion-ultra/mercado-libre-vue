<template>
    <div class="mb-5">
        <p class="fw-bold">{{ name }}</p>
        <table class="table table-striped fs09rem border rounded">
            <tbody>
                <tr v-for="row in rows" v-bind:key="row">
                    <th class="w-50" scope="row">{{ row.th }}</th>
                    <td>{{ row.td }}</td>
                </tr>
            </tbody>
        </table>
    </div>
</template>

<script>
    export default {
        props: ['name', 'rows'],
        name: "TableComponent"
    }
</script>

<style>
.fs09rem {
  font-size: 0.9rem;
}
</style>