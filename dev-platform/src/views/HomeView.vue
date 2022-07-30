<script setup>
import Header from '../components/Header.vue'
import Navbar from '../components/Navbar.vue'
import DataBoxes from '../components/DataBoxes.vue'
</script>

<template>
  <div class="home">
    <Navbar></Navbar>
    <Header></Header>
    <div class="backdrop">
       <h2>How We Get Our Data</h2>
       <p>The data on this site is, for the most part, entirely manually compiled from a huge variety of government and news media sources in near real-time as information is announced. The variety of sources is used to ensure that an accurate and complete dataset is available. For every case, a source URL is provided. For reference, a list of links to the common sources for each province is found below. Do note that data from this site is largely updated by the live press briefings, and the sources below are usually delayed.</p>
    </div>
    <br>
    <DataBoxes></DataBoxes>
  </div>
</template>

<style>
 .backdrop {
  background-color: rgb(62, 102, 135);
  padding: 150px;
 }
 .backdrop h2 {
  color: white;
  font-family: sans-serif;
  text-align: center;
 }
 .backdrop p {
  color: white;
  font-family: sans-serif;
 }
</style>