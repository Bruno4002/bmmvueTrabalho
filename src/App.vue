<script setup>
import { ref } from 'vue'

const nome = ref('')
const idade = ref('')
</script>

<template>
    <div class="container">
<div>
    <label>Nome:</label>
     <input type="text " v-model="nome">
     <label>Idade</label>
    <input type="number" v-model="idade">
</div>

    








    </div>
</template>

<style scoped>

</style>
