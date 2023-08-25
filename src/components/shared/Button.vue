<template>
    <button class="rounded-full px-16 py-2" :class=variant>{{title}}</button>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({

    props: { 
        variant: {
            required: true,
            default: 'white',
            type: String,
        },
        title: {
            type: String,
            required: true,
        },
    }
})

</script>