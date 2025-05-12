<template>
  <div>
    <provet-button variant="primary" @click="count++"> Count is: {{ count }}</provet-button>
    <NuxtPage />
    <NuxtRouteAnnouncer />
  </div>
</template>

<script setup>
import "@provetcloud/css";
import "@provetcloud/web-components";
import "./styles/_override.css";
import "./styles/_theme.css";

const count = ref(0);
</script>
