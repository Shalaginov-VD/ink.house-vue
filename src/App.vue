<template>
  <header-view/>
  <hero-view/>
  <catalog-nav-view/>
  <router-view/>
  <catalog-view v-if="!isCatalogView"/>
  <promo-view/>
  <team-view/>
  <footer-view/>
</template>

<script>
import Header from '@/components/Header.vue'
import Hero from '@/components/Hero.vue'
import CatalogNav from '@/components/CatalogNav.vue'
import Catalog from '@/components/Catalog.vue'
import Promo from '@/components/Promo.vue'
import Team from '@/components/Team.vue'
import Footer from '@/components/Footer.vue'

export default {
  components: {
    "header-view": Header,
    "hero-view": Hero,
    "catalog-nav-view": CatalogNav,
    "catalog-view": Catalog,
    "promo-view": Promo,
    "team-view": Team,
    "footer-view": Footer,
  },
  computed: {
    isCatalogView() {
      return this.$route.name === 'germany' || this.$route.name === 'england' || this.$route.name === 'france';
    }
  }
}
</script>

<style>
#app {
  font-family: 'Raleway';
  background-color: #F4F6F5;
}

body {
  margin: 0;
  padding: 0;
}
</style>