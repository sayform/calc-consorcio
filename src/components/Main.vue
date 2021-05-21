<template>
  <main>
      <!-- <template v-for="(card, i) in cards">
          <Card :key="card.id" :dataCard="cards[i]"/>
      </template> -->
      <Card :dataCard="cards[0]"></Card>
      <Footer />
      <FormInitial />
  </main>
</template>

<script>
import Card from './Card.vue'
import FormInitial from './FormInitial.vue'
import Footer from './Footer.vue'

export default {
    components: {
        Card,
        Footer,
        FormInitial
    },
    data() {
        return {
            cards: [
                {
                    id: 1,
                    subtitleCard: 'Subtítulo 1',
                    descriptionCard: 'la lalal alla alalla lalal'
                },
                {
                    id: 2,
                    subtitleCard: 'Subtítulo 2',
                    descriptionCard: 'la lalal alla alalla lalal gdfhh fgds fdsff sfsdf sdfs'
                },
                {
                    id: 3,
                    subtitleCard: 'Subtítulo 3',
                    descriptionCard: 'la lalal alla alalla lalal'
                },
                {
                    id: 4,
                    subtitleCard: 'Subtítulo 4',
                    descriptionCard: 'la lalal alla alalla lalal gdfhh fgds fdsff sfsdf sdfs'
                }
            ]
        }
    }
}
</script>

<style>

</style>