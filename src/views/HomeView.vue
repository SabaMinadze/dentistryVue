<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import head1 from '../components/head1.vue'
import head2 from '../components/head2.vue'
import head3 from "../components/head3.vue"
import cards from "../components/cards.vue"
import residency from "../components/residency.vue"
import achivements from "../components/achivements.vue"
import dentists from "../components/dentists.vue"
import footer1 from "../components/footer.vue"
</script>

<template>
  <div>
    <head1/>
    <head2/>
    <head3/>
    <cards class="cards"/>
    <residency class="residency"/>
    <achivements/>
    <dentists/>
    <footer1/>
  </div>
</template>


<style scoped>
.cards{
  display: grid;
  place-items: center;
  height: 100vh; /* or any height you prefer */
}

.residency{
  display: grid;
  place-items: center;
  height: 100vh;
}
</style>