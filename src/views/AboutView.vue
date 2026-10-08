<script setup>
import { useFlash } from '@/composables/useStorage.js';

let { flash } = useFlash();
</script>
<template>
  <div>
   <p>
      <button @click="flash('YAY!','It Works !', 'info')">Click me</button>
    </p>
  </div>
</template>

