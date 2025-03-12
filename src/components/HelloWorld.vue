<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
  </div>
</template>

<script lang="ts">
export default {
  name: 'HelloWorld',
}
</script>

<style>
  .greetings {
    display: flex;
    align-items: start;
    background-color: blue;
  }
</style>
