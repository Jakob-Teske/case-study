<script setup lang="ts">

import { ref } from 'vue'

// Fetch nuxt events from Github API

var events = ref([])

</script>
<template>
    <h1>Events</h1>
    <ul>
        <li v-for="event in events" :key="event.id">
            <p> {{  event.id }}</p>
        </li>
    </ul>
</template>