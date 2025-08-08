<template>
  <!-- Container principal -->
  <div class="fixed w-full z-50 top-0 flex justify-center px-4 mt-4">
    <!-- Navbar com efeito vidro -->
    <nav class="bg-white/5 backdrop-blur-md text-white shadow-lg rounded-b-xl border-b border-white/10 max-w-7xl w-full transition-all duration-300 hover:bg-white/10 px-6 py-3">
      <div class="flex justify-between items-center">
        <!-- Logo -->
        <div class="logo">
          <span class="font-semibold text-white text-lg">N8N<span class="text-accent">ZONE</span></span>
        </div>

        <!-- Itens do menu desktop -->
        <div class="hidden md:flex items-center gap-6 text-sm text-gray-300">
          <a href="#features" class="hover:text-white transition">Automações</a>
          <a href="#pricing" class="hover:text-white transition">Preços</a>
          <a href="#testimonials" class="hover:text-white transition">Depoimentos</a>
        </div>

        <!-- Botão CTA Desktop -->
        <a href="#pricing" target="_blank"
          class="hidden md:flex items-center btn-led text-black px-5 py-2 rounded-full text-sm font-medium">
          Começar Agora
        </a>

        <!-- Botão Mobile -->
        <button @click="toggleMenu" class="md:hidden text-white focus:outline-none p-2">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path v-if="!isMenuOpen" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
            <path v-else stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
          </svg>
        </button>
      </div>

      <!-- Menu Mobile -->
      <div v-show="isMenuOpen" class="md:hidden mt-3 rounded-lg px-4 py-4 transition-all duration-300 ease-in-out bg-white/5 backdrop-blur-md">
        <ul class="space-y-3">
          <li v-for="item in menuItems" :key="item.text">
            <a
              :href="item.href"
              class="block py-2 px-3 rounded hover:bg-white/10 transition"
              @click="closeMenu"
            >
              {{ item.text }}
            </a>
          </li>
          <li class="pt-3">
            <a href="#pricing"
              class="flex justify-center items-center btn-led text-black py-3 px-5 rounded-full">
              Começar Agora
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
import { ref } from 'vue';

export default {
  setup() {
    const isMenuOpen = ref(false);
    
    const menuItems = [
      { text: "Automações", href: "#features" },
      { text: "Preços", href: "#pricing" },
      { text: "Depoimentos", href: "#testimonials" },
    ];

    const toggleMenu = () => {
      isMenuOpen.value = !isMenuOpen.value;
    };

    const closeMenu = () => {
      isMenuOpen.value = false;
    };

    return {
      isMenuOpen,
      menuItems,
      toggleMenu,
      closeMenu
    };
  }
};
</script>

<style scoped>
.text-accent {
  color: #8ab8ad;
}

.bg-accent {
  background-color: #8ab8ad;
}

.glow-effect {
  box-shadow: 0 0 15px rgba(138, 184, 173, 0.5);
}

.transition {
  transition: all 0.3s ease;
}
</style>