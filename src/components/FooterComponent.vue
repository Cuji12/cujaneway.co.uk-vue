<template>
  <footer class="site-footer">
    <div class="site-footer__navigation">
      <router-link class="site-footer__link" to="/">Home</router-link>
      <router-link class="site-footer__link" to="/blog">Blog</router-link>
      <router-link class="site-footer__link" to="/work">Work</router-link>
      <router-link class="site-footer__link" to="/contact">Contact</router-link>
    </div>
    <div class="site-footer__socials">
      <a class="site-footer__link" href="https://www.linkedin.com/in/cu-janeway-559932120/">LinkedIn</a>
      <a class="site-footer__link" href="https://github.com/Cuji12">GitHub</a>
      <a class="site-footer__link" href="https://www.peopleperhour.com/freelancer/technology-programming/cu-janeway-full-stack-web-developer-designer-zqjnqxa">PeoplePerHour</a>
    </div>
    <router-link class="site-footer__email-desktop color-japanese-laurel" to="mailto:hello@cujaneway.co.uk">hello@cujaneway.co.uk</router-link>
    <div class="site-footer__other-info">
      <address>
        <router-link class="site-footer__email color-japanese-laurel" to="mailto:hello@cujaneway.co.uk">hello@cujaneway.co.uk</router-link>
      </address>
      <p class="site-footer__copyright">Copyright © Cu Janeway - 
        <router-link to="/about-this-site" class="site-footer__site-info desktop-show">More about this site</router-link>
      </p>
      <router-link to="/about-this-site" class="site-footer__site-info desktop-hide">More about this site</router-link>
    </div>
  </footer>
</template>

<style scoped>
  footer {
    max-width: 790px;
  }
</style>

<script>
export default {
}
</script>