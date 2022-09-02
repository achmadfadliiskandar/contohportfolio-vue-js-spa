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
    <template #heading>Perkenalan Singkat</template>
    <p>Assalamualaikum wr wb nama saya muhammad fadlan iskandar saya lahir di jakarta dan besar di depok</p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Organisasi</template>
    <ol>
      <li>Beko Fc (2014,2016)</li>
      <li>Gloria Bc (2019,sekarang)</li>
      <li>Beji Putra (2013,2016)</li>
    </ol>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Latar Pendidikan</template>
    <ol>
      <li>Sdit Mutiara Islam (2014,2020)</li>
      <li>Smps Taruna Bhakti (2020,2023)</li>
      <!-- calon anak smansa <li>Sman Negri 1 Depok (2023,2026)</li> -->
    </ol>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Me</template>
    Silahkan Ke Halaman : 
    <RouterLink to="/contact">Contact</RouterLink>
    untuk melihat sosial media saya dan menghubungi Saya
  </WelcomeItem>
</template>