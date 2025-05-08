<script setup>
import DefaultTheme from 'vitepress/theme'

const { Layout } = DefaultTheme
</script>

<template>
  <Layout>
    <template #home-hero-image>
        <img src="/assets/images/zubalis_logo_dark.png" alt="Zubalis Logo" style="max-width: 315px; display: block;" class="dark-only">
        <img src="/assets/images/zubalis_logo_light.png" alt="Zubalis Logo" style="max-width: 315px; display: block;" class="light-only">
    </template>
  </Layout>
</template>