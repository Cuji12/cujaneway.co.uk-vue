<template>
  <div>
    <app-header></app-header>
    <main class="container-right">
      <div class="pink-bg pink-bg--right"></div>
      <h1 class="me__page-title-desktop desktop-show bold">Cu Janeway</h1>
      <section class="me">
        <h1 class="me__page-title desktop-hide bold">Cu Janeway</h1>
        <img class="me__image" src="@/assets/me.webp">
        <p class="me__subtitle color-japanese-laurel semi-bold"><span>Web Development</span></p>
        <p class="me__description">Hey there, I'm a Web Developer from Manchester. Why don't you check out some of my work and doodles across the site.</p>
      </section>
      <section class="recent-posts">
        <h2 class="recent-posts__title">Recent Posts</h2>
        <ul class="recent-posts__list">
          <li class="recent-posts__list-item"> Lorum ipsum dulce et decorum est dulce et decorum est</li>
          <li class="recent-posts__list-item"> Lorum ipsum dulce et decorum est</li>
          <li class="recent-posts__list-item"> Lorum ipsum dulce et decorum est</li>
          <li class="recent-posts__list-item"> Lorum ipsum dulce et decorum est</li>
        </ul>
      </section>
      <img class="doodle doodle--home" src="@/assets/illustrations/doodle1.svg">
      <app-footer></app-footer>
    </main>
  </div>
</template>

<script>
import AppHeader from '@/components/HeaderComponent.vue'
import AppFooter from '@/components/FooterComponent.vue'

export default {
  name: 'Home',
  data: function () {
    return {
      headerColor: ''
    }
  },
  components: {
    AppHeader,
    AppFooter
  }
}
</script>
