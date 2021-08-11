<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-dark">
    <div class="container-fluid justify-content-center">
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse d-flex justify-content-end" id="navbarNav">
        <ul class="navbar-nav ">
          <li class="nav-item">
            <router-link class="nav-link text-white" to="/">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link text-white" to="/about">
              Nicolas
            </router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link text-white" to="/PortafolioTomas">
              Tomas
            </router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
import 'bootstrap/js/dist/collapse'
export default {
  name: 'NavbarComponent',
}
</script>

<style lang="scss" scoped></style>
