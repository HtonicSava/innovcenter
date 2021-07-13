<template>
  <div class="projects">
      <div class="projects__content">
          <div class="projects__title">
              <h2>
                  Проекты центра
              </h2>
          </div>
          <div class="projects__body">
              <div class="projects__item">
                  <div class="projects__photo"></div>
                  <div class="projects__description">
                      <div class="projects__name">Проект 1</div>
                      <div class="projects__text"> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Rerum, velit? Veniam voluptatibus in provident autem possimus quidem, blanditiis excepturi optio? Officiis sequi, tenetur possimus architecto explicabo quod officia eius. Iste.</div>
                  </div>
              </div>
              <div class="projects__item">
                  <div class="projects__photo"></div>
                  <div class="projects__description">
                      <div class="projects__name">Проект 2</div>
                      <div class="projects__text"> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Rerum, velit? Veniam voluptatibus in provident autem possimus quidem, blanditiis excepturi optio? Officiis sequi, tenetur possimus architecto explicabo quod officia eius. Iste.</div>
                  </div>
              </div>
              <div class="projects__item">
                  <div class="projects__photo"></div>
                  <div class="projects__description">
                      <div class="projects__name">Проект 3</div>
                      <div class="projects__text"> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Rerum, velit? Veniam voluptatibus in provident autem possimus quidem, blanditiis excepturi optio? Officiis sequi, tenetur possimus architecto explicabo quod officia eius. Iste.</div>
                  </div>
              </div>
              <div class="projects__item">
                  <div class="projects__photo"></div>
                  <div class="projects__description">
                      <div class="projects__name">Проект 4</div>
                      <div class="projects__text"> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Rerum, velit? Veniam voluptatibus in provident autem possimus quidem, blanditiis excepturi optio? Officiis sequi, tenetur possimus architecto explicabo quod officia eius. Iste.</div>
                  </div>
              </div>
              <div class="projects__item">
                  <div class="projects__photo"></div>
                  <div class="projects__description">
                      <div class="projects__name">Проект 5</div>
                      <div class="projects__text"> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Rerum, velit? Veniam voluptatibus in provident autem possimus quidem, blanditiis excepturi optio? Officiis sequi, tenetur possimus architecto explicabo quod officia eius. Iste.</div>
                  </div>
              </div>
              <div class="projects__item">
                  <div class="projects__photo"></div>
                  <div class="projects__description">
                      <div class="projects__name">Проект 6</div>
                      <div class="projects__text"> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Rerum, velit? Veniam voluptatibus in provident autem possimus quidem, blanditiis excepturi optio? Officiis sequi, tenetur possimus architecto explicabo quod officia eius. Iste.</div>
                  </div>
              </div>
          </div>

      </div>
  </div>
</template>

<script>
export default {
    name: "projects"
}
</script>

<style lang="sass" scoped>

.projects
    padding: 20px 0px
    font-family: "Gotham Pro"
    background-color: #CCDFF8 

.projects__content
    max-width: 1220px
    padding: 0px 10px
    margin: auto

.projects__title
    font-weight: bold
    font-size: 24px
    color: #233A60
    text-align: center
    margin-bottom: 8px

.projects__body
    display: flex
    justify-content: space-evenly
    flex-wrap: wrap 

.projects__item
    flex-basis: 280px
    height: 400px
    background-color: #ffffff
    border-radius: 10px
    margin: 20px
    box-shadow: 0px 3px 1px -2px rgb(0 0 0 / 20%), 0px 2px 2px 0px rgb(0 0 0 / 14%), 0px 1px 5px 0px rgb(0 0 0 / 12%)

.projects__photo
    position: relative
    height: 40%
    background-color: #4E8CE1 
    border-top-left-radius: 10px
    border-top-right-radius: 10px
    &::before
        content: "Фото"
        position: absolute
        top: 50%
        left: 50%
        color: #ffffff
        font-size: 20px
        transform: translate(-50%, -50%)

.projects__description 
    padding: 16px

.projects__name 
    margin-bottom: 8px
    text-align: center
    font-size: 20px
    color: #233A60 

.projects__text 



</style>