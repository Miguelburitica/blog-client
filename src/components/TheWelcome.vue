<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import JobIcon from './icons/IconJob.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import SportIcon from './icons/IconRunning.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template lang="pug">
WelcomeItem
  template(#icon)
    DocumentationIcon

  template(#heading) Personal projects

  div I want to improve my portfolio as a developer. This year, it is one of my goals and I will showcase it here. It will be amazing, I promise.

WelcomeItem
  template(#icon)
    JobIcon

  template(#heading) Job proposals

  div To advance in tech, making a positive impact is crucial. This can involve contributing to product development through understanding it.
  | I will work to solve problems based on our team's needs and I'll show you these here.
WelcomeItem
  template(#icon)
    EcosystemIcon

  template(#heading) Ecosystem

  div Get official tools and libraries for your project:
  | #[a(href="https://pinia.vuejs.org/" target="_blank" rel="noopener") Pinia],
  | #[a(href="https://router.vuejs.org/" target="_blank" rel="noopener") Vue Router],
  | #[a(href="https://test-utils.vuejs.org/" target="_blank" rel="noopener") Vue Test Utils], and
  | #[a(href="https://github.com/vuejs/devtools" target="_blank" rel="noopener") Vue Dev Tools]. If
  | you need more resources, we suggest paying
  | #[a(href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener") Awesome Vue] a visit.

WelcomeItem
  template(#icon)
    SportIcon

  template(#heading) Finding Balance

  div I am now comfortable with physical activity and use it as a way to set achievable goals. It feels great to reach them.
  | Sometimes, everyone needs space to scream, cry, reflect, or just have fun for no reason.

WelcomeItem
  template(#icon)
    SupportIcon

  template(#heading) Support Vue

  div As an independent project, Vue relies on community backing for its sustainability. You can help
  | us by #[a(href="https://vuejs.org/sponsor/" target="_blank" rel="noopener") becoming a sponsor].

</template>
