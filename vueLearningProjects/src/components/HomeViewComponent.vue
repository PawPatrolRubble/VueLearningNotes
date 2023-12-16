<template>
    <h1>home</h1>


    <input v-model="Message">

    <div>{{ defaultValue }}</div>
    <slot> default content</slot>


</template>

<script setup>
import { ref } from 'vue';

defineProps({
    defaultValue:Number
})

defineEmits(['update:defaultValue'])

const Message = ref('input')

</script>