<template>
  <div>
    <app-header></app-header>
    <main class="container-left">
    <div class="pink-bg pink-bg--left"></div>
    <h1 class="work-page-title">Work</h1>
    <section class="work">
      <article class="work-card work-card--1">
      </article>
      <article class="work-card work-card--2">
      </article>
      <article class="work-card work-card--3">
      </article>
      <article class="work-card work-card--4">
      </article>
      <div class="work-cards">
        <div class="work-cards__left">
          <article class="work-card work-card--5">
          </article>
        </div>
        <div class="work-cards__right">          
          <article class="work-card work-card--6">
          </article>
          <article class="work-card work-card--7">
          </article>
        </div>
      </div>
      <article class="work-card work-card--8">
      </article>
      <article class="work-card work-card--9">
      </article>
      </section>
      <app-footer></app-footer>
    </main>
  </div>
</template>

<style scoped>

</style>

<script>
import AppHeader from '@/components/HeaderComponent.vue'
import AppFooter from '@/components/FooterComponent.vue'

export default {
  components: {
    AppHeader,
    AppFooter
  }
}
</script>