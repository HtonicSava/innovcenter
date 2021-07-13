<template>
  <div class="news">
      <div class="news__content">
          <div class="news__title">
              <h2>
                  Новости
              </h2>
          </div>
          <v-slide-group
            center-active
            show-arrows
        >
            <v-slide-item
            v-for="n in 8"
            :key="n"
            v-slot="{ toggle }"
            >
                <v-card
                    class="ma-4 card"
                    height="300"
                    width="400"
                    @click="toggle"
                >
                        <v-card-text>
                            <h4 class="card__title"> Заголовок новости </h4>
                            <p class="card__text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi inventore eaque aut ullam itaque ipsum dignissimos quisquam dolore sequi quaerat, suscipit, officiis vitae natus sint doloribus quia porro incidunt distinctio?</p>
                        </v-card-text>
                </v-card>
            </v-slide-item>
        </v-slide-group>
      </div>
  </div>
</template>

<script>
export default {
    name: "news",
    data () {
        return {
        
        }
    }
}
</script>

<style lang="sass" scoped>
    .news
        padding: 20px 0px
        font-family: "Gotham Pro"
        background-color: #CCDFF8
        
    .news__content
        max-width: 1220px
        width: 100%
        margin: auto

    .news__title
        font-weight: bold
        font-size: 24px
        color: #233A60
        text-align: center

    .card 
        padding: 20px

    .card__title
        font-size: 18px
        color: #233A60
        margin-bottom: 8px

        
</style>