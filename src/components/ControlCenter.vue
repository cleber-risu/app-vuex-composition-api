<script setup>
import { useStore } from 'vuex';

const store = useStore();

function inc() {
  store.dispatch('increment');
}
</script>

<template>
  <button @click="inc">Increment</button>
</template>
