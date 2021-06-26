<template>
    <button @click="$emit('toggle-add-task',onClick)" :style="{backgroundColor: color}" class='btn'>{{text}}</button>
</template>

<script>
    export default {
        name: 'Button',
        props: ['text', 'color'],
    }
</script>