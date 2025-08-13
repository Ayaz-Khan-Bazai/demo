<script setup>
import { ref } from 'vue'

const showModal = ref(false)
</script>

<template>
    <div @mouseenter="showModal = true" @mouseleave="showModal = false"
        class="relative w-64 p-4 bg-white rounded-xl shadow hover:shadow-lg transition">
        <h2 class="text-lg font-bold">Hover Me</h2>
        <p class="text-gray-500">Sponsor Name</p>

        <!-- Hover Modal -->
        <div v-if="showModal" class="absolute top-full left-0 mt-2 w-64 bg-blue-600 text-white p-4 rounded shadow-lg z-10">
            <p class="font-semibold">Sponsor Details</p>
            <p class="text-sm mt-1">This sponsor supports our local football team. Thank you!</p>
        </div>
    </div>
</template>
