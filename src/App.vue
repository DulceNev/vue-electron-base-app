<template>
  <div class="min-h-screen flex items-center justify-center">
    <div class="card w-96 border border-white/15 bg-white/10 backdrop-blur-md shadow-xl">
      <div class="card-body items-center text-center">
        <h2 class="card-title text-2xl text-white">Vue + Electron</h2>
        <p class="text-white/70">Tailwind CSS + DaisyUI + Acrylic Glass</p>
        <div class="card-actions mt-4">
          <button class="btn btn-primary" @click="count++">
            Clicks: {{ count }}
          </button>
          <button class="btn btn-secondary" @click="count = 0">
            Reset
          </button>
        </div>
        <div class="badge badge-accent mt-4">DaisyUI v5</div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref } from 'vue';

const count = ref(0);
</script>
