<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
<script setup lang="ts">

useSeoMeta({
  title: 'Fluxo - Sistema de gestão financeira pessoal ',
  // description: 'Portfólio de Darlan, desenvolvedor fullstack especializado em Nuxt3, Vue3, Typescript e Tailwind. Confira meus projetos e experiência.',
  // ogTitle: 'Darlan Prado - Desenvolvedor Fullstack',
  // ogDescription: 'Explore o portfólio de Darlan, onde apresento meus projetos, habilidades e experiência como desenvolvedor.',
  // ogImage: '/avatar.png',
  // twitterTitle: 'Darlan Prado - Desenvolvedor Fullstack',
  // twitterDescription: 'Veja meu portfólio e conheça meus projetos e habilidades.',
  // twitterImage: '/avatar.png',
  // twitterCard: 'summary'
})


useHead({
  bodyAttrs: {
    class: 'bg-gray-300 dark:bg-gray-600'
  },
  htmlAttrs: {
    lang: 'pt-br',
    // class: 'font-mukta overflow-y-auto snap-y snap-mandatory h-screen '
  },
  // link: [
  //   {
  //     rel: 'icon',
  //     type: 'image/png',
  //     href: '/avatar.png'
  //   }
  // ]
})
</script>
