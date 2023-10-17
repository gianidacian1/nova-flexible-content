<template>
    <p class="text-80 grow px-4">
        <span class="mr-3 font-semibold">#{{ index + 1 }}</span>
        {{ group.title }}
    </p>
</template>

<script>
export default {
    props: {
        index: null,
        group: {}
    }
}
</script>
