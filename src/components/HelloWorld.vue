<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      L'abbreviazione di
      <a href="https://it.wikipedia.org/wiki/Meteorologia" target="_blank" rel="noopener">meteorologia</a>, il ramo delle scienze dell'atmosfera e della Terra che studia i fenomeni fisici che avvengono nell'atmosfera terrestre (troposfera) e responsabili del 
      <a href="https://it.wikipedia.org/wiki/Tempo_(meteorologia)" target="_blank" rel="noopener">tempo atmosferico</a>.
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
