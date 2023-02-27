<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Contabilidad</template>

    Nos encargamos de la contabilidad de tu empresa, para que puedas enfocarte en lo que más te gusta.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Payroll</template>

    Gestionamos las nominas de tu empresa, ahorrandote tiempo y dinero.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Gestion de información</template>

    Trabajamos en 
    <a href="https://notion.so" target="_blank" rel="noopener">Notion</a> 
    permitiendo trabajar en equipo de forma colaborativa y rapida.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Predicción</template>

    Usamos la información de tu empresa para predecir el futuro de tu negocio.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Empresa familiar</template>

    Somos una familia de emprendedores que queremos trabajar juntos en los que nos gusta :)
  </WelcomeItem>
</template>
