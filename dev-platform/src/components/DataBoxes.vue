<script setup>
const covidQuebec = [
  {
    cases: 55
  }
]
</script>

<template>
    <div class="databoxes">
    <div class="container text-center">
  <div class="row">
    <div class="col">
      <div v-for="CovidQuebec in CovidQuebec" :key="CovidQuebec" class="data">
        {{ CovidQuebec }}
      </div>
    </div>
    <div class="col">
      <div class="data">
    hello
      </div>
    </div>
    <div class="col">
      <div class="data">
     hello
      </div>
    </div>
  </div>
</div>
    </div>
</template>



<style>
 * {
    padding: 0;
    margin: 0;
 }
 .data {
    border: black solid 2px;
    padding: 35px;
    border-radius: 15px;
 }
</style> -->