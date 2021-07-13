<template>
  <div class="carousel">
      <div class="carousel__content">
        <v-carousel
        height="400"
        hide-delimiters
        show-arrows-on-hover
        >
        <v-carousel-item
            v-for="(slide, i) in slides"
            :key="i"
        >
            <v-sheet
            :color="colors[i]"
            height="100%"
            >
            <v-row
                class="fill-height"
                align="center"
                justify="center"
            >
                <div class="carousel__text">
                {{ slide }} фото/новость
                </div>
            </v-row>
            </v-sheet>
        </v-carousel-item>
        </v-carousel>
      </div>
  </div>
</template>

<script>
export default {
    name: "carousel",
    data () {
        return {
            colors: [
                'indigo',
                'warning',
                'pink darken-2',
                'red lighten-1',
                'deep-purple accent-4',
            ],
            slides: [
                'Первое',
                'Второе',
                'Третье',
                'Четвёртое',
                'Пятое',
            ],
        }
    }
}
</script>

<style lang="sass" scoped>
    .carousel
        padding: 20px 0px

        
        
    .carousel__content
        max-width: 1200px
        width: 100%
        margin: auto

    .carousel__text
        font-size: 36px
        color: #ffffff
        font-family: "Gotham Pro"

        
</style>