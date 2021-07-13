<template>
  <div class="services">
      <div class="services__content">
          <div class="services__title"><h2>Сервисы</h2></div>
          <div class="services__item">
              <div class="services__img"></div>
              <div class="services__body">
                  <div class="services__body-title">Сервис 1</div>
                  <div class="services__body-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi, dicta tempore architecto ipsam quidem, quibusdam voluptatem ex totam iusto tempora nemo sed tenetur amet maxime maiores sunt ea modi in? Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid ex consectetur, rem quaerat assumenda inventore obcaecati illum in alias, provident optio sed magnam quasi placeat dolor excepturi illo, temporibus repudiandae. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsa quam fugiat similique minima, impedit ipsum ex eum ad. Maxime amet obcaecati doloribus, illo dolore adipisci repudiandae iste iure laborum animi. Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eligendi aliquam quod architecto odit, eveniet expedita beatae similique illo esse harum tempora! Voluptatum cum molestias maxime eius eum ullam, soluta distinctio.</div>
              </div>
          </div>
          <div class="services__item">
              <div class="services__img"></div>
              <div class="services__body">
                  <div class="services__body-title">Сервис 2</div>
                  <div class="services__body-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi, dicta tempore architecto ipsam quidem, quibusdam voluptatem ex totam iusto tempora nemo sed tenetur amet maxime maiores sunt ea modi in? Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid ex consectetur, rem quaerat assumenda inventore obcaecati illum in alias, provident optio sed magnam quasi placeat dolor excepturi illo, temporibus repudiandae. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsa quam fugiat similique minima, impedit ipsum ex eum ad. Maxime amet obcaecati doloribus, illo dolore adipisci repudiandae iste iure laborum animi. Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eligendi aliquam quod architecto odit, eveniet expedita beatae similique illo esse harum tempora! Voluptatum cum molestias maxime eius eum ullam, soluta distinctio.</div>
              </div>
          </div>
          <div class="services__item">
              <div class="services__img"></div>
              <div class="services__body">
                  <div class="services__body-title">Сервис 3</div>
                  <div class="services__body-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi, dicta tempore architecto ipsam quidem, quibusdam voluptatem ex totam iusto tempora nemo sed tenetur amet maxime maiores sunt ea modi in? Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid ex consectetur, rem quaerat assumenda inventore obcaecati illum in alias, provident optio sed magnam quasi placeat dolor excepturi illo, temporibus repudiandae. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsa quam fugiat similique minima, impedit ipsum ex eum ad. Maxime amet obcaecati doloribus, illo dolore adipisci repudiandae iste iure laborum animi. Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eligendi aliquam quod architecto odit, eveniet expedita beatae similique illo esse harum tempora! Voluptatum cum molestias maxime eius eum ullam, soluta distinctio.</div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "services"

}
</script>

<style lang="sass" scoped>

.services
    padding: 20px 0px
    font-family: "Gotham Pro" 

.services__content
    max-width: 1220px
    padding: 0px 10px
    margin: auto

.services__title
    font-weight: bold
    font-size: 24px
    color: #233A60
    text-align: center
    margin-bottom: 8px

.services__item
    display: flex
    justify-content: space-evenly
    flex-wrap: wrap
    margin-bottom: 8px
    &:nth-child(3n)
        flex-flow: row-reverse
        flex-wrap: wrap
  

.services__img
    position: relative
    border-radius: 5px
    // width: 100%
    // max-width: 400px

    height: 300px
    background-color: #4E8CE1
    flex-basis: 350px
    margin-bottom: 16px
    margin-right: 16px
    &::before
        content: "Фото"
        position: absolute
        top: 50%
        left: 50%
        color: #ffffff
        font-size: 20px
        transform: translate(-50%, -50%)

.services__body
    flex-basis: 65%
    min-width: 300px

.services__body-title
    margin-bottom: 16px
    font-size: 20px
    color: #233A60 

.services__body-text
    margin-bottom: 40px 


</style>