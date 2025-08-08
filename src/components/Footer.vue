<template>
   <!-- Footer -->
   <footer class="py-12 px-4 border-t border-white/10">
      <div class="max-w-7xl mx-auto">
        <div class="flex flex-col md:flex-row justify-between items-center">
          <div class="mb-6 md:mb-0">
            <span class="font-semibold text-white text-lg">N8N<span class="text-accent">ZONE</span></span>
            <p class="text-gray-400 text-sm mt-2">Especialistas em automação N8N</p>
          </div>
          <div class="flex flex-col sm:flex-row gap-6 text-sm text-gray-400">
            <a href="#" class="hover:text-white transition">Política de Privacidade</a>
            <a href="#" class="hover:text-white transition">Termos de Serviço</a>
            <a href="#" class="hover:text-white transition">Contato</a>
            <a href="#" class="hover:text-white transition">Documentação</a>
          </div>
        </div>
        <div class="mt-8 pt-8 border-t border-white/10 text-center text-gray-400 text-sm">
          © 2024 N8NZONE. Todos os direitos reservados.
        </div>
      </div>
    </footer>
</template>

<script setup>

</script>

<style scoped>
.footer {
  padding-top: 5rem;
  position: relative;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: 0 auto;
  position: relative;
}


@media (max-width: 768px) {
  .footer-content {
    grid-template-columns: 1fr;
    gap: 2rem;
  }
  
  .company-info {
    max-width: 100%;
  }
  
  .footer-bottom {
    flex-direction: column;
    gap: 2rem;
  }
  
  .wood-background {
    height: 24px;
  }
}

/* Efeitos de hover avançados */
.icon-container {
  position: relative;
}

.icon-container::after {
  content: '';
  position: absolute;
  width: 100%;
  height: 100%;
  border: 1px solid rgba(255, 255, 255, 0.3);
  border-radius: 50%;
  opacity: 0;
  transition: all 0.3s ease;
}

.icon-container:hover::after {
  opacity: 1;
  transform: scale(1.2);
}
</style>