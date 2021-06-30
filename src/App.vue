<template>
  <div id="app">
    <nav class="bg-green-500 p-6 text-lg font-medium text-white">
      <div class="flex justify-center gap-2">
        <router-link to="/" exact exact-active-class="border-b-2 border-black"
          >About Me</router-link
        >
        |
        <router-link
          to="/portfolio"
          exact
          exact-active-class="border-b-2 border-black"
          >Portfolio</router-link
        >
        |
        <router-link
          to="/blog"
          exact
          exact-active-class="border-b-2 border-black"
          >Blog</router-link
        >
      </div>
    </nav>
    <router-view />
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
