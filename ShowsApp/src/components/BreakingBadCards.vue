<script setup>
import axios from "axios";

const response = await axios.get(
  "https://www.breakingbadapi.com/api/characters"
);
</script>

<template>
  <div>
    <h1>Breaking Bad Cards</h1>
    <h1>{{ response }}</h1>
  </div>
</template>
