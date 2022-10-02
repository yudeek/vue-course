<template>
  <h1>Vue Course</h1>
  <!-- передача строки! -->
  <State number="123" @changeUserName="log" />
</template>

<script setup>
  import State from '@/components/State.vue';

  const log = d => console.log({emit: d});
</script>
