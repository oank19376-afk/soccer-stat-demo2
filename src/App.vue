<template>
 <div>
 <h1>{{ msg }}</h1>
 <button @click="count++">%GUF: {{ count }}</button>
 </div>
</template>
<script setup>
import { ref } from 'vue'
const msg = ref('SoccerStat =4G<=45FEO!')
const count = ref(0)
</script>
<style scoped>
h1 {
 color: #2c3e50;
}
button {
 background: #42b983;
 color: white;
 border: none;
 padding: 10px;
}
</style>