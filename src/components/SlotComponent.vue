<template>
  <div>
    <h2>Slot Component</h2>
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'SlotComponent'
}
</script>

<style scoped>
h2 {
  color: #eff0ef;
}
</style>