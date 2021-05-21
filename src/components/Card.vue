<template>
    <section>
        <h2>{{ subtitleCard }}</h2>
        <p>{{ descriptionCard }}</p>
        <FormInitial />
    </section>
</template>

<script>
import FormInitial from './FormInitial.vue'
export default {
    components: {
        FormInitial
    },
    props: ['dataCard'], 
    data() {
        return {
            subtitleCard: this.dataCard.subtitleCard,
            descriptionCard: this.dataCard.descriptionCard
        }
    },
}
</script>

<style>

</style>