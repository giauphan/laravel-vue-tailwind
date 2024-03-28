<script setup>
import Layout from "./Layout.vue";
</script>

<script>
export default {
    layout: Layout,
};
</script>

<template>
    <Layout>
        <slot></slot>
    </Layout>
</template>
