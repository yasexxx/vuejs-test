<script lang="ts">
import { defineComponent } from 'vue';
import Header from './Header.vue';

    export default defineComponent({
    methods: {},
    components: { Header }
})
</script>

<template>
    <Header />
    <slot></slot>
</template>