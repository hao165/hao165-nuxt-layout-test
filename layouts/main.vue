<template>
    <div>
        <nav>main</nav>
        <slot name="content" />
        <div>Sidebar</div>
        <slot name="footer" />
    </div>
</template>

<script setup>
console.log('setup')
onMounted(() => {
    console.log('main')
})
</script>