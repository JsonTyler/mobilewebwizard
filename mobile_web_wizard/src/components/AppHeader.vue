<template>
  <header>
    <nav class="navbar navbar-expand-lg navbar-light fixed-top">
      <a class="navbar-brand" href="#">
        <img src="../assets/mobilewebwizardwatermarkyoutube.jpg" class="logo" alt="Mobile Web Wizard logo" title="Mobile Web Wizard" />
      </a>
      <div class="contact-icons-header d-flex d-lg-none">
        <!-- <a href="https://www.youtube.com/@mobilewebwizard" target="_blank" rel="noopener noreferrer" aria-label="YouTube">
          <i class="fab fa-youtube fa-2x"></i>
        </a> -->
        <a href="https://www.linkedin.com/in/jason-tyler-rodriguez/" target="_blank" rel="noopener noreferrer" aria-label="LinkedIn">
          <i class="fab fa-linkedin fa-2x"></i>
        </a>
        <a href="mailto:info@mobilewebwizard.com" aria-label="Email">
          <i class="fas fa-envelope fa-2x"></i>
        </a>
      </div>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link font-weight-bold" href="#services" title="What we do">Our Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about" title="Who We Are">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact" title="How To Reach Us">Contact Us</a>
          </li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
    name: 'AppHeader',
}
</script>

<style scoped>
/* Component-specific styles here */
</style>
