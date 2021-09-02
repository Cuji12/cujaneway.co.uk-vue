<template>
  <div>
    <app-header headerColor="header--karry"></app-header>
    <section class="page-upper">
      <h1 class="page-upper__title text-2xl">Blog Posts</h1>
    </section>
    <div class="container flex flex-col items-center w-full mx-auto">
      <article class="blog-post">
        <a class="blog-post__link" href="<?= $blogPost->url;?>">
          <time class="blog-post__date desktop-hide">
            13th December 2017
          </time>
          <time class="blog-post__date desktop-show">
            Monday 13th December 2017
          </time>
          <h3 class="blog-post__title">
            This is a blog post!!!
          </h3>
          <p class="blog-post__excerpt">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
            Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi                         
          </p>
          </a>
          <div class="blog-post__tags">
            <div class="blog-post__tag">
              test
            </div>
          </div>
        <hr class="blog-post__separator">
      </article>
      <img class="doodle doodle--blog" src="@/assets/illustrations/doodle4.svg">
      <app-footer></app-footer>
    </div>
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