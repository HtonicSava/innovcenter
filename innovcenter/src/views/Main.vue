<template>
    <div>
        <CusHeader/>
        <Carousel/>
        <News/>
        <Services/>
        <Projects/>
        <About/>
        <Team/>
        <History/>
        <Partners/>
        <Contacts/>
        <Footer/>
        
    </div>
</template>

<script>

import CusHeader from '../components/header.vue'
import Carousel from '../components/carousel.vue' 
import News from '../components/news.vue'
import Services from '../components/services.vue'
import Projects from '../components/projects.vue'
import About from '../components/about.vue'
import Team from '../components/team.vue'
import History from '../components/history.vue'
import Partners from '../components/partners.vue'
import Contacts from '../components/contacts.vue'
import Footer from '../components/cus-footer.vue'

export default {
    components: {
        CusHeader,
        Carousel,
        News,
        Services,
        Projects,
        About,
        Team,
        History,
        Partners,
        Contacts,
        Footer
    }
}
</script>

<style >
    @font-face {
        font-family: 'Gotham Pro Light';
        src: url('../assets/fonts/GothamPro-Light.eot');
        src: 
            url('../assets/fonts/GothamPro-Light.eot?#iefix') format('embedded-opentype'),
            url("../assets/fonts/GothamPro-Light.woff") format('woff'),
            url('../assets/fonts/GothamPro-Light.ttf') format('truetype');
        font-weight: normal;
        font-style: normal;
    }
    @font-face {
        font-family: "Gotham Pro";
        src: url("../assets/fonts/GothamPro-Medium.eot");
        src: 
            url("../assets/fonts/GothamPro-Medium.eot?#iefix") format("embedded-opentype"),
            url("../assets/fonts/GothamPro-Medium.woff") format("woff"),
            url("../assets/fonts/GothamPro-Medium.ttf") format("truetype");
        font-weight: 500;
        font-style: normal;
    }
    @font-face {
        font-family: "Gotham Pro";
        src: url("../assets/fonts/GothamPro-Bold.eot");
        src: 
            url("../assets/fonts/GothamPro-Bold.eot?#iefix") format("embedded-opentype"),
            url("../assets/fonts/GothamPro-Bold.woff") format("woff"),
            url("../assets/fonts/GothamPro-Bold.ttf") format("truetype");
        font-weight: bold;
        font-style: normal;
    }

</style>

<style lang="sass" scoped>

</style>

