<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
  </div>
</template>

<script lang="ts" setup>


let date = useDayjs()

console.log(date(Date.now()).format('DD.MM.YYYY'));


</script>

