<template>
  <div class="footer">
      <div class="footer__container">
          <div class="footer__logo">
              <img src="../assets/img/logo.png" alt="">
          </div>
          <div class="footer__about">
            <p>2021</p>
            <p>copyright © all rights reserved</p>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "cus-footer",
    data: function () {
        return {

        }
    }
}
</script>

<style lang="sass" scoped>
    .footer
        background: linear-gradient(209deg, rgba(41,78,128,1) 0%, rgba(0,139,160,1) 100%)
        font-family: "Gotham Pro"
        font-weight: bold
        color: #ffffff
        
    .footer__container
        max-width: 1220px 
        width: 100%
        padding: 0px 10px
        padding-top: 16px
        margin: auto
        display: flex
        align-items: center
        justify-content: space-between
        // height: 60px
    .footer__logo
        width: 150px
        display: flex
        align-items: center  
        img
            max-width: 100%
            width: auto

    .footer__about
        text-align: end
        

</style>