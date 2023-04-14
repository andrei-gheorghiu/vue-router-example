<script setup>
import { useRoute } from "vue-router";
</script>
<template>
  <pre v-text="JSON.stringify(useRoute().params, null, 2)" />
</template>
