<template>
  <TheNavigation />
  <div 
    class="bg-cyan-100 h-screen w-screen"
    @click="visibleSaidbar = true">
      <slot />
  </div>
</template>

<script setup> 
  const visibleSaidbar = useVisibleSaidebar()
</script>
