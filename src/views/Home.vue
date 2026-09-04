<script setup>
import Projects from '@/components/Projects.vue';
import TheWelcome from '@/components/TheWelcome.vue';

</script>

<template>
  <nav class="navbar_custom navbar fixed-top navbar-expand-lg border-bottom border-2 fs-5">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Daniel Vieira da Costa</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav d-flex ms-auto gap-2">
          <a class="nav-link" href="#projetos">Projetos</a>
          <a class="nav-link" href="#">Sobre</a>
          <a class="nav-link" href="#">Contato</a>
        </div>
      </div>
    </div>
  </nav>
  <main class="container">
    <TheWelcome />
    <Projects />
  </main>
</template>