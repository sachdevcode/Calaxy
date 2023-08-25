<template>
    <h1 class="text-white text-3xl">{{ heading }}</h1>
    <p class="mt-3 text-white text-sm">{{ description }}</p>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

    export default defineComponent({
        props: {
            description: {
                type: String,
                required: true,
                default: 'lorem ipsum'
            },
            heading: {
                type: String,
                required: true,
                default: 'lorem ipsum33'
            }
        }
    })
</script>