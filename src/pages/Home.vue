<template>
  <div>
    <h1 class="text-4xl">Home</h1>

    <button @click="checkout"> Check Out </button>
  </div>
</template>
<script setup>
const checkout = () => {
  alert('Click Check Out Items')
}

</script>