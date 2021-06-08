<template>
  <main>
      <CardInitial />
      <CardWager />
      <CardResult />
  </main>
</template>

<script>
import CardInitial from './CardInitial.vue'
import CardWager from './CardWager.vue'
import CardResult from './CardResult.vue'

export default {
    components: {
        CardInitial,
        CardResult,
        CardWager,
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

<style lang="scss">
 main {
    display: grid;
    grid-auto-flow: column;
    gap: 0.5em;

    .card {
        background-color: lightgray;
        padding: 1em;

        form {
            input, label {
                display: block;
            }
            label {
                font-size: 1em;
                font-weight: lighter;
                margin-top: 0.3em;
            }
            input {
                background-color: lightgray;
                width: 100%;
                font-size: 3em;
                border: 0;
                outline: 0;
                border-bottom: 1px solid #000;
                margin-top: 0.5em;
            }
        }

    }
 }

</style>