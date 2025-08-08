<script setup>
import Navbar from '@/components/Navbar.vue';
import Banner from '@/components/Banner.vue';
import Intrudocao from '@/components/Intrudocao.vue';
import Fundamentos from '@/components/Planos.vue';
// import Servicos from '@/components/Servicos.vue';

import Footer from '@/components/Footer.vue';

import WhatsAppButton from '@/components/WhatsAppButton.vue';
import Embesed from '@/components/embesed/cta.vue';

import Servicos2 from '@/components/Testemunhas.vue';
</script>
<template>
  <div class="relative">
 
     <Navbar />
    <Banner />
    
    <div class="relative z-10">
      <Intrudocao />
   
      <Fundamentos />
      <!-- <Servicos /> -->
      <Servicos2 />
   
      <Embesed />

    </div>
    
    <WhatsAppButton />
    <Footer />
  </div>
</template>
