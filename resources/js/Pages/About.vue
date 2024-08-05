<script setup>
defineProps({
    user: String,
});
</script>
<template>
    <div>
        <h1>About Page</h1>
        <p>Hello {{ user }}</p>
    </div>
</template>
