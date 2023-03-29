<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import '../src/assets/web-content/bootstrap-5.3.0-alpha1-dist/css/bootstrap.min.css'
import 'bootstrap';
import 'jquery';
import 'popper.js';
</script>

<template>
  <header>
  <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark" style="background: rgb(47, 47, 47) !important;">
    <div class="container-fluid navCon">
      <a href="/" class="c-logo header__logo" style="gap: 22px;">
				<img src="https://www.topspeaker.ru/upload/site_options/581/58189a410b826ac866961b6ad4c44b2c.png" alt="logo">
			</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation"><span class="navbar-toggler-icon"></span></button>
      <div id="navbarCollapse" class="collapse navbar-collapse">
        <ul class="navbar-nav mb-2 mb-md-0" style="text-align: right;">
          <li class="nav-item">
            <RouterLink class="nav-link active" aria-current="page" to="/">Ссылка 1</RouterLink>
          </li>
          <li class="nav-item">
            <RouterLink class="nav-link" to="/about">Ссылка 2</RouterLink>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled">Ссылка 3</a>
          </li>
        </ul>
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search"><button class="btn btn-outline-success" type="submit">Поиск</button>
        </form>
      </div>
    </div>
  </nav>
</header>

  <RouterView />
</template>

<style scoped>

</style>
