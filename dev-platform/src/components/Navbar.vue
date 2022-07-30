<script setup>
import { RouterLink, } from 'vue-router'
</script>


<template>
    <div class="navbar">
 <ul>
    <li><router-link style="color: black; font-family: sans-serif; text-decoration: none;" to="/">Home</router-link></li>
    <li><router-link style="color: black; font-family: sans-serif; text-decoration: none;" to="/about">About</router-link></li>
 </ul>
    </div>
</template>


<style>
* {
    padding: 0;
    margin: 0;
}
.navbar {
    padding: 25px;
    background-color: whitesmoke;
}

.navbar ul {
    display: block;
}

.navbar li {
    display: inline;
    margin: 10px;
}
</style>