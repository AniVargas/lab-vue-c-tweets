<script setup>

const props = defineProps({
 message: String,
});

</script>


<template>
    <p class="message">{{tweets[0].message}}</p>
</template>