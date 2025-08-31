<script setup>
import Footer from '~/components/global/Footer.vue';
useHead({
  htmlAttrs: {
    lang: 'en',
  },
  meta: [
    { property: 'og:title', content: `Jadoo` },
    { name: 'description', content: 'Jadoo is a travel agency landing page built with TailwindCSS and Nuxt.' },
    { property: 'og:description', content: 'Jadoo is a travel agency landing page built with Nuxt 3 and TailwindCSS.' },
    { property: 'og:url', content: 'https://jadoo-sandy.vercel.app/' },
    { name: 'twitter:title', content: 'Jadoo' },
    { name: 'twitter:description', content: 'Jadoo is a travel agency landing page built with TailwindCSS and Nuxt.' },
    { name: 'twitter:site', content: 'https://jadoo-sandy.vercel.app/' }
  ],
  title: `Jadoo`,
})
</script>

<template>
  <main class="max-w-8xl">
    <slot/>
    <Footer />
  </main>
</template>
