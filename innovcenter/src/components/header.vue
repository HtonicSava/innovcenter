<template>
  <div class="header">
      <div class="header__container">
          <div class="header__logo">
              <img src="../assets/img/logo.png" alt="">
          </div>
          <div class="header__menu">
              <div v-for="item in items" :key="item" class="header__item">
                  <p>{{item}}</p>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "cus-header",
    data: function () {
        return {
            items: [
                'Главная',
                'Сервисы',
                'Проекты',
                'О центре', 
                'Партнеры', 
                'Контакты'
            ]
        }
    }
}
</script>

<style lang="sass" scoped>
    .header
        background: linear-gradient(209deg, rgba(41,78,128,1) 0%, rgba(0,139,160,1) 100%)
        font-family: "Gotham Pro"
        font-weight: bold
        color: #ffffff
        
    .header__container
        max-width: 1220px 
        width: 100%
        padding: 0px 10px
        margin: auto
        display: flex
        align-items: center
        justify-content: space-between
        height: 60px
    .header__logo
        width: 150px
        display: flex
        align-items: center  
        img
            max-width: 100%
            width: auto

    .header__menu
        display: flex

    .header__item
        position: relative
        cursor: pointer
        margin-right: 15px
        &::after
            content: ''
            width: 0%
            height: 4px
            background-color: #ffffff
            position: absolute
            bottom: -2px
            transition: 0.2s
        &:hover
            &::after
                width: 100%
                        
        &:last-child
            margin-right: 0px
        p
            margin-bottom: 0px

</style>