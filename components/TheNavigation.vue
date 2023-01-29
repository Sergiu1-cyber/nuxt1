<template>
  <div class="bg-cyan-500">
    <TheSaidebar />
    <div class="flex justify-between p-2">
      <h3 
         class="ml-4 font-bold text-2xl" 
         @click="visibleSaidbar = false">
      &equiv;
      </h3>
      <h1 class="font-bold text-2xl w-2/3 text-left">Saidebar</h1>
    </div>
  </div>
</template>

<script >
  export default {

  }
</script>

<script setup> 
  const visibleSaidbar = useVisibleSaidebar()
</script>
