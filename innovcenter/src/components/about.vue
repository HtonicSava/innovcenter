<template>
  <div class="about">
      <div class="about__content">
          <div class="about__title">
              <h2>
                  О центре
              </h2>
          </div>
          <div class="about__body">
              <div class="about__item">
                  <div class="about__name">
                      <h3>Наша миссия</h3>
                  </div>
                  <div class="about__mission">
                      <p>
                          Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque quia exercitationem beatae reprehenderit ipsum odit enim odio maxime sint. Placeat cupiditate similique commodi voluptate! Commodi ea recusandae delectus eius ducimus! Lorem ipsum dolor, sit amet consectetur adipisicing elit. Culpa expedita, voluptatum autem tempore amet labore molestias corrupti! Facilis fuga enim minima expedita repellat modi facere fugit odit, debitis tempora saepe?
                      </p>
                      <p>
                          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eius recusandae perferendis mollitia iusto laudantium obcaecati commodi nostrum dolore minima. Mollitia enim incidunt alias quibusdam vitae suscipit cum error placeat Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit suscipit quidem iure consectetur enim, fugit iste? Dolore ipsum mollitia aspernatur voluptates quae eligendi, veritatis deserunt, amet modi officiis voluptatibus minima?Lorem ipsum dolor sit amet consectetur adipisicing elit. Et ullam tempora aliquam, quam eveniet quas itaque facilis accusamus illo tenetur esse fugit, nesciunt numquam, maiores aut earum. Voluptatibus, soluta modi?Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt vero iure nulla dicta beatae odit harum ex officia eligendi deserunt! Fuga ducimus officia saepe. A temporibus voluptatibus sit accusantium soluta. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima iure nobis, fugit porro eaque amet modi enim consectetur reprehenderit laudantium ex facere atque quia voluptatem magni sint. Est, voluptatum quisquam.
                      </p>
                  </div>
              </div>
              <div class="about__item">
                  <div class="about__name">
                      <h3>Наши цели</h3>
                  </div>
                  <div class="about__targets">
                      <v-expansion-panels inset>
                        <v-expansion-panel
                        v-for="(item,i) in targets"
                        :key="i"
                        >
                        <v-expansion-panel-header>{{item}}</v-expansion-panel-header>
                        <v-expansion-panel-content>
                            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
                        </v-expansion-panel-content>
                        </v-expansion-panel>
                      </v-expansion-panels>
                  </div>
              </div>
          </div>

      </div>
  </div>
</template>

<script>
export default {
    name: "about",
    data: function () {
        return {
            targets: [
                "Цель 1",
                "Цель 2",
                "Цель 3",
                "Цель 4",
                "Цель 5",
            ]
        }
    }
    
}
</script>

<style lang="sass" scoped>

.about
    padding: 20px 0px
    font-family: "Gotham Pro"

.about__content
    max-width: 1220px
    padding: 0px 10px
    margin: auto

.about__title
    font-weight: bold
    font-size: 24px
    color: #233A60
    text-align: center
    margin-bottom: 8px

.about__body
    display: flex

.about__item
    flex-basis: 50%
    padding: 16px 

.about__name 
    margin-bottom: 16px
    text-align: center
    font-size: 20px
    color: #233A60 

.about__mission 

.about__targets 




</style>