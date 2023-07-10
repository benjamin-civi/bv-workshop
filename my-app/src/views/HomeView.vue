<script setup>

import HelloWorldComponent from "@/components/HelloWorldComponent.vue"
import BVFormComponent from "@/components/bv-example/BVFormComponent.vue";
</script>

<template>
  <b-card border-variant="primary">
  <b-row>
  <b-col cols="auto">
    <HelloWorldComponent/>
  </b-col>
  <b-col cols="auto">
  <BVFormComponent/>
  </b-col>
  </b-row>
</b-card>

</template>
