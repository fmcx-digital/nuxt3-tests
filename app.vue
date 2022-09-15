<script lang="ts" setup>
const { data } = await useFetch('https://worldtimeapi.org/api/timezone/America/Sao_Paulo');
</script>

<template>
  <div>
    <div>{{ data.datetime }}</div>
  </div>
</template>
