
<script setup lang="ts">
//import useFirstLesson from "~/composables/useFirstLesson";

const firstLesson=useFirstLesson()
</script>
<template>Hello, world!
    <NuxtLink
        class="underline font-medium"
        :href="firstLesson.path">
        Go to first lesson
    </NuxtLink>
</template>