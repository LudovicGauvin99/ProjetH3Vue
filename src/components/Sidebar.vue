<template>
  <div class="d-flex flex-column flex-shrink-0 p-3 bg-light" style="width: 10%;">
    <ul class="nav nav-pills flex-column mb-auto">
      <li class="nav-item">
        <RouterLink :to="{name:'home'}" class="nav-link active">
          <svg class="bi me-2" width="16" height="16"><use xlink:href="#home"></use></svg>
          Home
        </RouterLink>
      </li>
    </ul>
    <hr>
    <div class="dropdown">
      <a href="#" class="d-flex align-items-center link-dark text-decoration-none dropdown-toggle" id="dropdownUser2" data-bs-toggle="dropdown" aria-expanded="false">
        <img src="https://images.pexels.com/photos/220453/pexels-photo-220453.jpeg" alt="" width="32" height="32" class="rounded-circle me-2">
        <strong>mdo</strong>
      </a>
      <ul class="dropdown-menu text-small shadow" aria-labelledby="dropdownUser2">
        <li><a class="dropdown-item" href="#">Nouveau projet</a></li>
        <li><a class="dropdown-item" href="#">Options</a></li>
        <li><a class="dropdown-item" href="#">Profile</a></li>
        <li><hr class="dropdown-divider"></li>
        <li><a class="dropdown-item" href="#">Deconnexion</a></li>
      </ul>
    </div>
  </div>
</template>

<script setup>
import { RouterLink } from "vue-router"

</script>