<template>
  <div class="team">
      <div class="team__content">
          <div class="team__title">
              <h2>
                  Команда
              </h2>
          </div>
          <div class="team__body">
              <div class="team__item">
                 <div class="team__avatar">
                     <div class="team__photo"></div>
                 </div>
                 <div class="team__description">
                     <div class="team__name">
                         <h4>
                             Имя Фамилия
                         </h4>
                     </div>
                     <div class="team__post">
                         <h4>
                             Занимая должность
                         </h4>
                     </div>
                     <div class="team__text">
                         Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed rerum repudiandae voluptatem maiores nostrum ducimus illo, amet fugit dignissimos tempore at suscipit.
                     </div>
                 </div>
              </div>
              <div class="team__item">
                 <div class="team__avatar">
                     <div class="team__photo"></div>
                 </div>
                 <div class="team__description">
                     <div class="team__name">
                         <h4>
                             Имя Фамилия
                         </h4>
                     </div>
                     <div class="team__post">
                         <h4>
                             Занимая должность
                         </h4>
                     </div>
                     <div class="team__text">
                         Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed rerum repudiandae voluptatem maiores nostrum ducimus illo, amet fugit dignissimos tempore at suscipit.
                     </div>
                 </div>
              </div>
              <div class="team__item">
                 <div class="team__avatar">
                     <div class="team__photo"></div>
                 </div>
                 <div class="team__description">
                     <div class="team__name">
                         <h4>
                             Имя Фамилия
                         </h4>
                     </div>
                     <div class="team__post">
                         <h4>
                             Занимая должность
                         </h4>
                     </div>
                     <div class="team__text">
                         Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed rerum repudiandae voluptatem maiores nostrum ducimus illo, amet fugit dignissimos tempore at suscipit.
                     </div>
                 </div>
              </div>
              <div class="team__item">
                 <div class="team__avatar">
                     <div class="team__photo"></div>
                 </div>
                 <div class="team__description">
                     <div class="team__name">
                         <h4>
                             Имя Фамилия
                         </h4>
                     </div>
                     <div class="team__post">
                         <h4>
                             Занимая должность
                         </h4>
                     </div>
                     <div class="team__text">
                         Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed rerum repudiandae voluptatem maiores nostrum ducimus illo, amet fugit dignissimos tempore at suscipit.
                     </div>
                 </div>
              </div>
              <div class="team__item">
                 <div class="team__avatar">
                     <div class="team__photo"></div>
                 </div>
                 <div class="team__description">
                     <div class="team__name">
                         <h4>
                             Имя Фамилия
                         </h4>
                     </div>
                     <div class="team__post">
                         <h4>
                             Занимая должность
                         </h4>
                     </div>
                     <div class="team__text">
                         Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed rerum repudiandae voluptatem maiores nostrum ducimus illo, amet fugit dignissimos tempore at suscipit.
                     </div>
                 </div>
              </div>
              <div class="team__item">
                 <div class="team__avatar">
                     <div class="team__photo"></div>
                 </div>
                 <div class="team__description">
                     <div class="team__name">
                         <h4>
                             Имя Фамилия
                         </h4>
                     </div>
                     <div class="team__post">
                         <h4>
                             Занимая должность
                         </h4>
                     </div>
                     <div class="team__text">
                         Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sed rerum repudiandae voluptatem maiores nostrum ducimus illo, amet fugit dignissimos tempore at suscipit.
                     </div>
                 </div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "team",
    
    
}
</script>

<style lang="sass" scoped>

.team
    padding: 20px 0px
    font-family: "Gotham Pro"
    background-color: #CCDFF8 

.team__content
    max-width: 1220px
    padding: 0px 10px
    margin: auto

.team__title
    font-weight: bold
    font-size: 24px
    color: #233A60
    text-align: center
    margin-bottom: 8px

.team__body
    padding-top: 20px
    display: flex
    justify-content: space-evenly
    flex-wrap: wrap

.team__item
    flex-basis: 200px
    position: relative
    margin: 60px 60px 20px 60px

.team__avatar
    position: absolute
    width: 80px
    height: 80px
    border-radius: 50%
    border: 4px solid rgba(41,78,128,1)
    z-index: 1
    overflow: hidden
    transform: translate(-50%, -50%)
    left: 50%

.team__photo
    width: 100%
    height: 100%
    background-color: #4E8CE1
    position: absolute
    z-index: 2
    &::before
        content: "A"
        position: absolute
        top: 50%
        left: 50%
        color: #ffffff
        font-size: 20px
        transform: translate(-50%, -50%)

.team__description
    position: relative
    background: linear-gradient(rgba(41,78,128,1) , rgba(0,139,160,1) ) 
    padding-top: 40px
    border-radius: 10px
    padding: 40px 20px 20px 20px
    color: #ffffff
    z-index: 0

.team__name
    text-align: center
     

.team__post
    text-align: center 
    margin-bottom: 16px

.team__text
    color: #fffc
</style>