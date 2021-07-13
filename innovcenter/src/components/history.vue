<template>
  <div class="history">
      <div class="history__content">
          <div class="history__title"><h2>История центра</h2></div>
          <v-timeline>
            <v-timeline-item
                v-for="(year, i) in years"
                :key="i"
                :color="mainColor"
                small
            >
                <template v-slot:opposite>
                <span
                    class="history__year"
                    v-text="year.year"
                ></span>
                </template>
                <div class="history__description">
                <h2 class="history__name">
                    Событие
                </h2>
                <div class="history__text">
                    Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit, an vim zril disputando voluptatibus, vix an salutandi sententiae.
                </div>
                </div>
            </v-timeline-item>
          </v-timeline>
      </div>
  </div>
</template>

<script>
export default {
    name: "history",
    data: () => ({
        mainColor: '#4E8CE1',
        years: [
        {
            year: '2016',
        },
        {
            year: '2017',
        },
        {
            year: '2018',
        },
        {
            year: '2019',
        },
        {
            year: '2020',
        },
        ],
  }),


}
</script>

<style lang="sass" scoped>

.history
    padding: 20px 0px
    font-family: "Gotham Pro" 

.history__content
    max-width: 1220px
    padding: 0px 10px
    margin: auto

.history__title
    font-weight: bold
    font-size: 24px
    color: #233A60
    text-align: center
    margin-bottom: 8px

.history__year
    text-align: center
    font-size: 20px
    color: #233A60

.history__description 

.history__name
    margin-bottom: 16px
    font-size: 20px
    color: #233A60

.history__text 


</style>