<template>
    <h1>{{ name }}</h1>
</template>

<script setup>
import { ref } from "vue"

const name = ref("elvis");
</script>

<script>

import MainLayout from '@/Layouts/MainLayout.vue';

export default {
    layout: MainLayout
}
</script>