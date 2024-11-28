<template>
    <div class="ratings">
        <i :class="star(i, percentage)" v-for="i in 5" v-bind:key="i"></i>
    </div>
</template>

<script>
    export default {
        props: ['percentage'],
        name: 'RaitingComponent',
        data() {
            return {
                starActive: 'fa fa-star text-primary',
                starInactive: 'fa fa-star rating-inactive'
            }
        },
        methods: {
            star: function(index, percentage) {
                console.log('Entra')
                if (percentage <= 20)
                    return (index == 1) ? this.starActive : this.starInactive;
                else if (percentage <= 40)
                    return (index <= 2) ? this.starActive : this.starInactive;
                else if (percentage <= 60)
                    return (index <= 3) ? this.starActive : this.starInactive;
                else if (percentage <= 80)
                    return (index <= 4) ? this.starActive : this.starInactive;
                else
                    return (index <= 5) ? this.starActive : this.starInactive;
                
            }
        }
    }
</script>

<style>
.rating-inactive{
    stroke: rgba(0, 0, 0, .25);
}
</style>