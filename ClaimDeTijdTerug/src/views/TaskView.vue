<script setup>
import ProgressBar from "@/components/ProgressBar.vue";

</script>

<template>
<section class="top">
  <h1>Web advanced pokedex</h1>
  <section class="top-right">
    <h1>3/10</h1>
    <progress-bar/>
  </section>
</section>




<section class="subtaken">
  <h2>Subtaken</h2>
  <section  class="subtaken-middle">
    <section class="checks">
      <svg v-for="i in 3" :key="i"
           viewBox="0 0 100 100"
           width="50"
           height="50"
           xmlns="http://www.w3.org/2000/svg">

        <circle cx="50" cy="50" r="40"
                fill="none"
                stroke="black"
                stroke-width="4" />

        <path d="M30 50 L43 63 L70 36"
              fill="none"
              stroke="black"
              stroke-width="5"
              stroke-linecap="round"
              stroke-linejoin="round" />
      </svg>
      <svg viewBox="0 0 100 100" width="50" height="50" xmlns="http://www.w3.org/2000/svg">
        <circle cx="50" cy="50" r="40" fill=none stroke=black stroke-width="4" />
      </svg>
      <svg viewBox="0 0 100 100" width="50" height="50" xmlns="http://www.w3.org/2000/svg">
        <circle cx="50" cy="50" r="40" fill=none stroke=black stroke-width="4" />
      </svg>
      <svg viewBox="0 0 100 100" width="50" height="50" xmlns="http://www.w3.org/2000/svg">
        <circle cx="50" cy="50" r="40" fill=none stroke=black stroke-width="4" />
      </svg>
      <svg viewBox="0 0 100 100" width="50" height="50" xmlns="http://www.w3.org/2000/svg">
        <circle cx="50" cy="50" r="40" fill=none stroke=black stroke-width="4" />
      </svg>
      <svg viewBox="0 0 100 100" width="50" height="50" xmlns="http://www.w3.org/2000/svg">
        <circle cx="50" cy="50" r="40" fill=none stroke=black stroke-width="4" />
      </svg>
      <svg viewBox="0 0 100 100" width="50" height="50" xmlns="http://www.w3.org/2000/svg">
        <circle cx="50" cy="50" r="40" fill=none stroke=black stroke-width="4" />
      </svg>
      <svg viewBox="0 0 100 100" width="50" height="50" xmlns="http://www.w3.org/2000/svg">
        <circle cx="50" cy="50" r="40" fill=none stroke=black stroke-width="4" />
      </svg>
    </section>
    <section class="teksten">
      <h2>Maken van HomeView</h2>
      <h2>Hardcoden 1 pokemon</h2>
      <h2>Designen van hardcoded DetailView</h2>
      <h2>Ophalen van de eerste 10 pokemons via de API</h2>
      <h2>Kleuren toevoegen van het thema van de pokemon</h2>
      <h2>Ophalen van alle andere pokemons</h2>
      <h2>Zoekfunctie integreren</h2>
      <h2>Sorteer functie integreren</h2>
      <h2>Favorieten knop implementeren</h2>
      <h2>Maken van een pokemon party</h2>
    </section>
  </section>
</section>


</template>

<style scoped>

.top{
  display: flex;
  gap: 100px;
  border: 2px solid black;
  padding: 0 10px 20px 10px;
}

.top-right{
  width: 60%;
}

.subtaken{
  border: 2px solid black;
  margin-top: 18px;
  padding: 10px;
}
.subtaken-middle{
  display: flex;
  gap: 20px;
}
.checks{
  display: flex;
  flex-direction: column;
}
.teksten h2{
  margin-bottom: 23px;
}
.teksten{
  margin-top: -10px;
}
</style>
