<script setup>
defineProps(['divClass', 'imageClass', 'imgSrc'])
</script>

<template>
    <div :class="divClass">
        <img :class="imageClass" :src="imgSrc" />
    </div>
</template>
