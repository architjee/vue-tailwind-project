<script>
import { RouterView } from 'vue-router';
import Navbar from './components/Navbar.vue'
export default {
  components: {
    'custom-navbar': Navbar
  }
}
</script>

<template>


<div class="my-app">
    <section class="hero is-link is-fullheight">
      <div class="hero-head">
        <slot name="mynavbarslot">
          fallback
        </slot>
        

      </div>
      <div class="hero-body">
        <div class="custom-wrapper">
          <p class="title">
            Fullheight navbar
          </p>
          <p class="subtitle">
            Half height subtitle
          </p>
        </div>
      </div>
    </section>
  </div>


  <RouterView>
    <template #mynavbarslot>
      <custom-navbar></custom-navbar>
    </template>
  </RouterView>
</template>

<style scoped>

</style>
