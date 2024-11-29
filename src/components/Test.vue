<script setup>
defineProps({
    mytestmsg: {
        type: String,
        required: true,
    },
})
</script>
<template>
    <div class="greetings">
        <h1 class="green">{{ mytestmsg }}</h1>
    </div>
</template>