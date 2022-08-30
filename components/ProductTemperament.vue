<script setup>
defineProps({
  temperament: String,
});
</script>
<template>
  <span>
    {{ temperament ? temperament : "" }}
  </span>
</template>