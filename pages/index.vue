<template>
  <div>
    Hi This is index.vue
  </div>
</template>

<script setup>
  useSeoMeta({
    title: 'Main Page',
    description: '[description]',
    ogTitle: '[og:title]',
    ogDescription: 'This is my main page',
    ogImage: '[og:image]',
    ogUrl: '[og:url]',
    twitterTitle: '[twitter:title]',
    twitterDescription: '[twitter:description]',
    twitterImage: '[twitter:image]',
    twitterCard: 'summary'
  })

  useHead({
    htmlAttrs: {
      lang: 'en'
    },
    link: [
      {
        rel: 'icon',
        type: 'image/png',
        href: '/favicon.png'
      }
    ]
  })

</script>