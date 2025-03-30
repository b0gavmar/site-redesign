<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header>
    <nav class="navbar navbar-expand-lg navbar-light bg-success">
      <div class="container-fluid">
        <a class="navbar-brand fw-bolder" to="/">GeoAgroDrone</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNavAltMarkup"
          aria-controls="navbarNavAltMarkup"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav fw-bold">
            <RouterLink class="nav-link" to="/">Főoldal</RouterLink>
            <RouterLink class="nav-link" to="/about">Rólunk</RouterLink>
            <RouterLink class="nav-link" to="/references">Referenciáink</RouterLink>
            <RouterLink class="nav-link" to="/contacts">Elérhetőségünk</RouterLink>
            <RouterLink class="nav-link" to="/services">Szolgáltatásaink</RouterLink>
          </div>
        </div>
      </div>
    </nav>
  </header>

  <RouterView />
</template>

<style scoped>
.navbar-nav .router-link-active{
  background: #00000049;
  color: white;
  border-radius: 8px;
}
.nav-link{
  color: black;
}
</style>
