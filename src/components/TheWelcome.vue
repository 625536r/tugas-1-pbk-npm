<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import 'vue';
import '@fortawesome/fontawesome-free/css/all.css';
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>About Me</template>
Hi nama saya Rakhyan Naufhal Ardhana Lahir di pekanbaru 22 juni 2004
Berkuliah di Universitas Islam Riau dan seorang Mahasiswa Teknik Informatika Semeaster 4
   
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Motto Hidup</template>
 "Jangan pernah menyerah, kecuali Waktu tidur"
  

    
  </WelcomeItem>



  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>

  <div>
    <a href="https://www.instagram.com/p/C3-8fkOyWG6/?igsh=MWlhdW13eWZ4ZHk1Mw==" target="_blank">
      <i class="fab fa-instagram social-icon"></i>
    </a>
    <a href="https://api.whatsapp.com/" target="_blank">
      <i class="fab fa-whatsapp social-icon"></i>
    </a>
  </div>


</WelcomeItem>
</template>
<style scoped>
.social-icon {
  font-size: 24px; /* Sesuaikan ukuran ikon sesuai kebutuhan */
  margin-right: 10px; /* Jarak antara ikon */
}
</style>
