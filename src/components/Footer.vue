<script setup>
import { Icon } from '@iconify/vue';
</script>

<template>
  <footer id="contact">
    <h2>
      <strong>
        Contact Us Via:
      </strong>
    </h2>
    <section class="icon-section">
      <a href="https://www.instagram.com/pillzen_pvt.ltd._/" target="_blank" class="icon-link">
        <Icon icon="fa6-brands:instagram" class="custom-icon" />
      </a>
      <a href="https://api.whatsapp.com/send?phone=918075817184" target="_blank" class="icon-link">
        <Icon icon="fa6-brands:whatsapp" class="custom-icon" />
      </a>
      <a href="mailto:abhishekbiju1920@gmail.com" class="icon-link">
        <Icon icon="cib:gmail" class="custom-icon" />
      </a>
      <a href="tel:+91 8075817184" class="icon-link">
        <Icon icon="material-symbols:call-outline" class="custom-icon" />
      </a>
    </section>
    <p>All Right Reserved @Pillzen</p>
  </footer>
</template>

<style scoped>
h2 {
  margin-top: 20px;
  margin-bottom: 20px;
}

h2 {
  line-height: 20px;
  text-decoration: underline;
  padding-bottom: 5px;
}

section.icon-section {
  display: flex;
  justify-content: center;
  margin: 10px;
}

section a {
  margin: 0 10px;
  color: #000;
  font-size: 32px;
}

.custom-icon {
  margin: 0 5px;
}

footer {
  margin-top: 60px;
  margin-bottom: 10px;
  text-align: center;
}

p {
  margin-top: 20px;
}

a {
  text-decoration: none;
}
</style>
