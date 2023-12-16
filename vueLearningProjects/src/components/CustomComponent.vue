<template>

<div>

    <div>first name: {{ firstName }}</div>
    <div>last name :{{ lastName }}</div>
    
</div>

</template>

<script setup>

    defineProps({
        firstName:String,
        lastName:String
    })

    defineEmits(['update:firstName','update:lastName'])

    //using props to pass parameters from parents to child

</script>