<template>
  <div class="bg-white p-6 rounded-lg shadow-md">
    <h4 class="text-xl font-semibold mb-2">{{ title }}</h4>
    <p class="text-gray-600">{{ description }}</p>
  </div>
</template>

<script setup>
defineProps({
  title: {
    type: String,
    required: true
  },
  description: {
    type: String,
    required: true
  }
})
</script>