<template>
  <div class="container">
      <NavBar/>
      <Header>
        <h1 class="title is-2 is-size-3-mobile has-text-centered has-text-weight-light">
          Ciao sono <span class="has-text-weight-semibold">Alex Pagnotta</span> e questo è il mio sito
        </h1>
      </Header>
      <Divider/>
      <MediumArticlesContainer/>
      <GithubProjectsContainer/>
  </div>
  <Panel 
    imageSrc= "profile.jpg"
    name= "Alex Pagnotta"
    subTitle= "Vai al mio Linkedin"
    subTitleLink= "https://www.linkedin.com/in/alex-pagnotta/?originalSubdomain=it"
    >
      <div class="columns is-variable is-8">
        <div class="column">
          <p class="title is-4 mt-6">
            Chi Sono?
          </p> 
          <p class="is-size-6 mt-3">
            Sono Alex Pagnotta, ho 22 anni, e sin da piccolo ho sempre avuto una grande passione per tutto quello che riguarda l'informatica e la programmazione, passione che da qualche anno è diventato il mio lavoro.
          </p>     
        </div>
        <div class="column">
          <p class="title is-4 mt-4">
            Cosa Faccio?
          </p> 
          <p class="is-size-6 mt-3">
            In questi anni ho principalmente lavorato in ambiente .Net, utilizzando .Net Core e approfondendo Azure e il cloud in generale, mentre nel tempo libero mi sono interessato anche allo sviluppo Frontend e Mobile, utilizzando varie tecnologie, tra cui React e React Native. 
          </p>     
        </div>
      </div>  
  </Panel>
  <Footer>
    <p class="is-6">
        Sito sviluppato da <span class="has-text-weight-semibold">Alex Pagnotta</span>, con Vue.js, Bulma.io
    </p>
  </Footer>
</template>

<script>

import NavBar from './components/NavBar.vue'
import Header from './components/Header.vue'
import Divider from './components/Divider.vue'
import Panel from './components/Panel.vue'
import Footer from './components/Footer.vue'
import GithubProjectsContainer from './components/GithubProjectsContainer.vue'
import MediumArticlesContainer from './components/MediumArticlesContainer.vue'

export default {
  name: 'App',
  components: {
    NavBar, Header, Divider, GithubProjectsContainer, MediumArticlesContainer, Panel, Footer
  }
}

</script>

