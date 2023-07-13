<script>
export default {
  name: 'BVGridComponent',
  setup() {
    return {}
  }
}
</script>
<template>
  <b-row>
    <h6 class="rowheader">Row 1</h6>
    <b-col cols="4" class="light-border">
      <h6>Column 1</h6>

      <b-placeholder-card></b-placeholder-card>
    </b-col>
    <b-col cols="4" class="light-border">
      <h6>Column 2</h6>

      <b-placeholder-card></b-placeholder-card>
    </b-col>
    <b-col cols="4" class="light-border">
      <h6>Column 3</h6>
      <b-placeholder-card></b-placeholder-card>
    </b-col>
  </b-row>
  <b-row>
    <h6 class="rowheader">Row 2</h6>
    <b-col cols="4" class="light-border">
      <h6>Column 1</h6>

      <b-placeholder-card></b-placeholder-card>
    </b-col>
    <b-col cols="4" class="light-border">
      <h6>Column 2</h6>

      <b-placeholder-card></b-placeholder-card>
    </b-col>
    <b-col cols="4" class="light-border">
      <h6>Column 3</h6>
      <b-placeholder-card></b-placeholder-card>
    </b-col>
  </b-row>
</template>

<style scoped>
.light-border {
  border-width: 10px;
  border-color: gold;
}
.rowheader {
  margin-top: 1em;
  background-color: lightcoral;
}
</style>
