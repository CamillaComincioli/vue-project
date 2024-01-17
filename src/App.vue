<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'

const items = [
  {icon: "test.svg", title: "test1"},
  {icon: "test.svg", title: "test2"},
  {icon: "test.svg", title: "test3"},
]

</script>



<template>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="Il meteo in Vue" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main> -->
  <h1>my website</h1>
  <ul>
    <li v-for="item in items">
      <img :src="item.icon" alt="">
      {{ item.title }}
    </li>
  </ul>

</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
