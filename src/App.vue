<script setup lang="ts">
import Layout from "@/layout/index.vue";

function foo() {
	console.log("test");
}

onMounted(() => {
	foo();
});
</script>

<template>
	<Layout />
</template>

<style lang="scss" scoped>
h3 {
  @apply hover:bg-red-400;
}
</style>
