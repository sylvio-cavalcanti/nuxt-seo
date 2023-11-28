<template>
  <div>
    <p>SEO Debug</p>
    <Head>
      <Title>Evenyx</Title>
      <Meta name="description" hid="description" content="Evenyx description" />
      <Meta name="author" hid="author" content="Evenyx Author" />
      <Meta name="og:title" hid="og:title" content="Evenyx Title" />
      <Meta name="og:description" hid="og:description" content="Evenyx description" />
      <Meta name="og:url" hid="og:url" content="www.evenyx.com" />
      <Meta name="og:site_name" hid="og:site_name" content="Evenyx site name" />
      <Meta name="og:image" hid="og:image" content="https://evenyx.s3.amazonaws.com/mailing/images/evenyx-branco.png" />
      <Meta name="og:type" hid="og:type" content="website" />
      <Meta name="twitter:card" hid="t-type" content="https://evenyx.s3.amazonaws.com/mailing/images/evenyx-branco.png" />
    </Head>
  </div>
</template>

<script setup lang="ts">
useHead({
  htmlAttrs: {
    lang: 'en'
  },
  link: [
    {
      rel: 'icon',
      type: 'image/png',
      href: 'https://evenyx.s3.amazonaws.com/mailing/images/evenyx-branco.png'
    }
  ]
})
// useSeoMeta({
//   title: 'My Amazing Site',
//   ogTitle: 'My Amazing Site',
//   description: 'This is my amazing site, let me tell you all about it.',
//   ogDescription: 'This is my amazing site, let me tell you all about it.',
//   ogImage: 'https://evenyx.s3.amazonaws.com/mailing/images/evenyx-branco.png',
//   twitterCard: 'summary_large_image',
// })
</script>