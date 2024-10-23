<script setup lang="ts"></script>

<template>
  <nav class="navbar navbar-expand-lg bd-navbar sticky-top navbar-dark bg-dark">
    <div class="container-fluid">
      <Router-Link to="/" class="navbar-brand">Leonardo Villanueva</Router-Link>
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
        <div class="navbar-nav">
          <Router-Link to="/" class="nav-link active">Home</Router-Link>
          <Router-Link to="/about" class="nav-link">About</Router-Link>
          <Router-Link to="/projects" class="nav-link">Projects</Router-Link>
          <Router-Link to="/resume" class="nav-link">Resume</Router-Link>
          <Router-Link to="/contact" class="nav-link">Contact</Router-Link>
        </div>
      </div>
    </div>
  </nav>
</template>

<style scoped></style>
