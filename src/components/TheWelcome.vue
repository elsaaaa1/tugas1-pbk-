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
    <template #heading>Pendidikan</template>
    SDN 019 Tambusai Utara, SMPN 12 Tambusai Utara, SMK YAPIM Tambusai Utara, Universitas Islam Riau
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Hobi</template>

    Hobi saya Membaca dan Mendengarkan Musik

    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Tempat Tanggal Lahir</template>

    Jati Sari, 22 Januari 2003
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Alamat</template>

    Desa Rantau Sakti Kecamatan Tambusai Utara
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Tentang Saya</template>

    Saya suka pedas tidak suka manis, saya punya kucing 5 namanya Tumil, Tompel, Mika, Miko, Miki.
    saya memiliki satu adik laki-laki. tinggi saya hanya sekitar 148 saya termasuk kedalam manusia
    mini. sekian terimakasih
  </WelcomeItem>
</template>
