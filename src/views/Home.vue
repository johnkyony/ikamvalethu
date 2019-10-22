<template>
 <body id="page-top">
   <Navigation></Navigation>
   <Header></Header>
   <Services></Services>
   <!-- <PortfolioGrid></PortfolioGrid> -->
   <About></About>
   <Team></Team>
   <!-- <Clients></Clients> -->
   <Contact></Contact>
   <Footer></Footer>
   <Modal></Modal>
 </body>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Navigation from '@/components/Navigation.vue'
import About from '@/components/About.vue'
import Clients from '@/components/Clients.vue'
import Header from '@/components/Header.vue'
import Services from '@/components/Services.vue'
import Team from '@/components/Team.vue'
import Contact from '@/components/Contact.vue'
import Modal from '@/components/Modals.vue'
import PortfolioGrid from '@/components/PortfolioGrid.vue'
export default {
  name: 'home',
  components: {
    Navigation,
    About , 
    Clients , 
    Header , 
    Services,
    Team , 
    Contact , 
    Modal , 
    PortfolioGrid
  }
}
</script>
