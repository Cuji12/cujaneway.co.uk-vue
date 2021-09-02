<template>
  <div>
    <div class="mobile-menu hidden bg-dark-blue h-screen w-screen z-50 px-10" id="menu">
      <div class="menu__exit transition-all" id="exit-menu" @click="closeMenu">
      </div>
      <ul class="text-white flex flex-col items-center h-screen justify-center">
        <li class="mb-10 text-2xl font-bold" @click="closeMenu">
          <router-link class="transition-all" to="/">Home</router-link> 
        </li>
        <li class="mb-10 text-2xl font-bold" @click="closeMenu">
          <router-link class="transition-all" to="/blog">Blog</router-link>
        </li>
        <li class="mb-10 text-2xl font-bold" @click="closeMenu">
          <router-link class="transition-all" to="/work">Work</router-link> 
        </li>
        <li class="mb-10 text-2xl font-bold" @click="closeMenu">
          <router-link class="transition-all" to="/contact">Contact</router-link>
        </li>
        <img class="doodle doodle--menu" src="@/assets/illustrations/doodle8.png"/>
      </ul>
    </div>
    <header class="header" :class="headerColor">
      <router-link to="/">
        <img class="header__logo" src="@/assets/logo.png">
      </router-link>
    <div class="md:hidden flex flex-col w-1/12 cursor-pointer burger-menu" id="burger" @click="openMenu">
        <hr class="mb-2">
        <hr class="mb-2">
        <hr class="">
      </div>
      <nav class="header__desktop-menu desktop-show">
        <router-link class="header__link" to="/">Home</router-link>
        <router-link class="header__link" to="/blog">Blog</router-link>
        <router-link class="header__link" to="/work">Work</router-link>
        <router-link class="header__link" to="/contact">Contact</router-link>
      </nav>
    </header>
  </div>
</template>

<style scoped>
  .burger-menu hr {
    border-width: 1px;
    border-radius: 2px;
    width: 30px;
  }
  .mobile-menu {
    background-color: #ffe8dc;
  }
  .mobile-menu a {
    color: #222222;
  }
  .mobile-menu a:hover {
    color: #07691c;
  }
  .menu__exit {
      position: absolute;
      top: 20px;
      right: 35px;
      color: #222222;
      font-size: 58px;
      cursor: pointer;
  }
  .menu-exit:hover {
    color: #07691c;
  }
  .menu__exit:after {
    display: inline-block;
    content: "\00d7";
  }
</style>

<script>
export default {
  props: {
    'headerColor': String
  },
  methods: {
    openMenu() {
      document.getElementById('body').setAttribute('style', 'height: 100%; overflow: hidden;');
      document.getElementById('menu').setAttribute('style', 'display: block;');
    },
    closeMenu() {
      document.getElementById('body').setAttribute('style', 'height: unset; overflow: unset;');
      document.getElementById('menu').setAttribute('style', 'display: none;');
    },
  },
}
</script>