<template>
  <div>
    <NavbarComponent />
  </div>
  <router-view />
</template>
<script>
import NavbarComponent from './components/NavbarComponent.vue'
import 'bootstrap/dist/css/bootstrap.min.css'
export default {
  components: {
    NavbarComponent,
  },
}
</script>
<style lang="scss"></style>
