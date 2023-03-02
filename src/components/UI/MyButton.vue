
<template>
  <button class="btn" >
    <slot></slot>
  </button>
</template>

<script>
export default {
  name: "my-button"
}
</script>

<style scoped>
.btn {
  align-self: flex-end;
  padding: 10px 15px;
  background: none;
  color: purple;
  border: 1px solid purple;
}

.btn:hover {
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.075) inset, 0 0 8px purple;
}  
</style>