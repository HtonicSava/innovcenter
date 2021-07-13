<template>
  <div class="contacts">
      <div class="contacts__content">
          <div class="contacts__body">
              <div class="contacts__item">
                  <div class="contacts__name">
                      <h4>
                          Наш адрес 
                      </h4>
                  </div>
                  <div class="contacts__description">
                      <p>
                          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sapiente quia magni perspiciatis beatae quaerat. 
                      </p>
                  </div>
                  <div class="contacts__name">
                      <h4>
                          Наш телефон 
                      </h4>
                  </div>
                  <div class="contacts__description">
                      <p>
                          Lorem ipsum dolore 
                      </p>
                  </div>
              </div>
              <div class="contacts__item">
                  <div class="contacts__map"></div>
              </div>
          </div>

      </div>
  </div>
</template>

<script>
export default {
    name: "contacts",
    data: function () {
        return {
            
        }
    }
    
}
</script>

<style lang="sass" scoped>

.contacts
    padding: 20px 0px
    font-family: "Gotham Pro"

.contacts__content
    max-width: 1220px
    padding: 0px 10px
    margin: auto

.contacts__body
    display: flex

.contacts__item
    flex-basis: 50%
    padding: 16px 

.contacts__name 
    margin-bottom: 16px
    font-size: 20px
    color: #233A60
.contacts__description
    margin-bottom: 60px

.contacts__map
    width: 100%
    height: 500px
    background-color: #4E8CE1
    position: relative
    border-radius: 10px
    &::before
        content: "Карта"
        position: absolute
        top: 50%
        left: 50%
        color: #ffffff
        font-size: 20px
        transform: translate(-50%, -50%)


</style>