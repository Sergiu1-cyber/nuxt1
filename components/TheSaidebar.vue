<template>
  <div 
    class="absolute flex flex-col bg-cyan-400 h-screen w-2/3"
    :class="{hidden: visibleSaidbar}">
    <h1 
    @click="visibleSaidbar = true"
    class="p-2 bg-cyan-600 text-center">close</h1>
    <div class="flex flex-col pl-4 mt-2">
      <NuxtLink to="/">Home</NuxtLink>
      <NuxtLink to="/about">About</NuxtLink>
    </div>
  </div>
</template>

<script setup>
  const visibleSaidbar = useVisibleSaidebar()
</script>

