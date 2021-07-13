<template>
  <div class="partners">
      <div class="partners__content">
          <div class="partners__title">
              <h2>
                  Партнёры
              </h2>
          </div>
          <div class="partners__body">
              <div class="partners__item">
              </div>
              <div class="partners__item">
              </div>
              <div class="partners__item">
              </div>
              <div class="partners__item">
              </div>
              <div class="partners__item">
              </div>
          </div>

      </div>
  </div>
</template>

<script>
export default {
    name: "partners"
}
</script>

<style lang="sass" scoped>

.partners
    padding: 20px 0px
    font-family: "Gotham Pro"
    background-color: #CCDFF8 

.partners__content
    max-width: 1220px
    padding: 0px 10px
    margin: auto

.partners__title
    font-weight: bold
    font-size: 24px
    color: #233A60
    text-align: center
    margin-bottom: 8px

.partners__body
    display: flex
    justify-content: space-evenly
    flex-wrap: wrap 

.partners__item
    width: 150px
    height: 150px
    background-color: #4E8CE1
    border-radius: 10px
    margin: 20px
    position: relative
    &::before
        content: "Лого"
        position: absolute
        top: 50%
        left: 50%
        color: #ffffff
        font-size: 20px
        transform: translate(-50%, -50%)

</style>