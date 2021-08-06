<template>
  <header class="header">
    <a href="/">
      <img class="header__logo" src="/cujaneway.co.uk/assets/logo.png">
    </a>
    <div class="header__mobile-menu desktop-hide" id="mobile-menu">
      <hr class="header__burger-line">
      <hr class="header__burger-line color-japanese-laurel" id="mobile-menu-middle">
      <hr class="header__burger-line">
    </div>
    <nav class="header__desktop-menu desktop-show">
      <router-link class="header__link" href="/">Home</router-link>
      <router-link class="header__link" href="/">Blog</router-link>
      <router-link class="header__link" href="/">Work</router-link>
      <router-link class="header__link" href="/">Contact</router-link>
    </nav>
  </header>
</template>

<script>
export default {

}
</script>

<style>

</style>