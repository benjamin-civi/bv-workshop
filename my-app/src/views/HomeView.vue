<script setup>

import HelloWorldComponent from "@/components/HelloWorldComponent.vue"
import BVFormComponent from "@/components/bv-example/BVFormComponent.vue";
import BVGridComponent from "@/components/bv-example/BVGridComponent.vue";
import BVCardComponent from "@/components/bv-example/BVCardComponent.vue";
</script>

<template>
  <b-card border-variant="primary">
  <b-row>
  <b-col cols="auto">
    <HelloWorldComponent/>
  </b-col>
  <b-col cols="auto">
  <BVGridComponent/>
  </b-col>
  <b-col cols="auto">
    <BVCardComponent/>
  </b-col>
  <b-col cols="auto">
  <BVFormComponent/>
  </b-col>
  </b-row>
</b-card>

</template>
