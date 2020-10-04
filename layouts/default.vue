<template>
  <div>
    <div class="cabeca1">
    <Header />
  
      <b-navbar>
        <template slot="brand">
          <n-link to="/" no-prefetch>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img
                    src="https://upload.wikimedia.org/wikipedia/commons/d/d4/IGN_Logo.png"
                    alt="LOGO IGN"
                >
            </b-navbar-item>
            </n-link>
        </template>
        <template slot="start">
          <nuxt-link to="/">
            <b-navbar-item >
                Home
            </b-navbar-item>
            </nuxt-link>

            <nuxt-link to="/PaginasDosCards/publicar">
            <b-navbar-item>
                Publicar
            </b-navbar-item>
            </nuxt-link>
        </template>
        
    </b-navbar>
    </div>
    <Nuxt />
    <Footer />
  </div>
  
</template>

<script>
import Header from '../components/Header'
import Footer from '../components/Footer'

export default {
  components: {
    Header,
    Footer,
  },
  data() {
    return {
      items: [
        {
          title: 'Home',
          icon: 'home',
          to: { name: 'index' },
        },
        {
          title: 'Inspire',
          icon: 'lightbulb',
          to: { name: 'inspire' },
        },
      ],
    }
  },
}
</script>

<style>
.cabeca1{
  padding-bottom: 1%;
  
}
</style>
