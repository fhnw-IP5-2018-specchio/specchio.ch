<template>
  <div class="layout layout-default">

    <section class="hero is-dark is-medium is-bold heading-hero">
      <div class="hero-head">

          <navbar/>
          
      </div>    
    </section>

    <!-- CTA -->
    <cta-box/>

    <!-- Content -->
    <div class="container content-container">
      <Content/>
    </div>

    <!-- Footer -->
    <page-footer/>

  </div>
</template>

<script>
import CtaBox from '../components/CtaBox.vue'
import Navbar from '../components/Navbar.vue'
import PageFooter from '../components/PageFooter.vue'

export default {
    components: { CtaBox, Navbar, PageFooter }
}
</script>

<style src="../styles/theme.scss" lang="scss"></style>