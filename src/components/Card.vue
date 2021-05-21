<template>
    <section>
        <h2>{{ subtitleCard }}</h2>
        <p>{{ descriptionCard }}</p>
    </section>
</template>

<script>
export default {
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