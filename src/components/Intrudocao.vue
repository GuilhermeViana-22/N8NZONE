<template>

    <!-- Features Section -->
    <section id="features" class="py-20 px-4 max-w-7xl mx-auto">
      <div class="text-center mb-16">
        <h2 class="text-3xl md:text-4xl font-bold mb-4 text-led">Automações <span class="highlight-text">Inteligentes</span></h2>
        <p class="text-gray-300 max-w-2xl mx-auto">Descubra como o N8N pode transformar seus processos empresariais</p>
      </div>
      
      <div class="grid md:grid-cols-3 gap-8">
        <!-- Feature 1 -->
        <div class="glass-card rounded-xl p-6 hover:glow-effect transition led-glow">
          <div class="feature-icon w-12 h-12 rounded-lg flex items-center justify-center mb-4">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#8ab8ad" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path d="M12 2v4M12 18v4M4.93 4.93l2.83 2.83M16.24 16.24l2.83 2.83M2 12h4M18 12h4M4.93 19.07l2.83-2.83M16.24 7.76l2.83-2.83"/>
            </svg>
          </div>
          <h3 class="text-xl font-semibold mb-2">Integração de Sistemas</h3>
          <p class="text-gray-300">Conecte diferentes plataformas e APIs de forma visual, sem necessidade de programação complexa.</p>
        </div>
        
        <!-- Feature 2 -->
        <div class="glass-card rounded-xl p-6 hover:glow-effect transition led-glow">
          <div class="feature-icon w-12 h-12 rounded-lg flex items-center justify-center mb-4">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#8ab8ad" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <path d="M4 15s1-1 4-1 5 2 8 2 4-1 4-1V3s-1 1-4 1-5-2-8-2-4 1-4 1z"/><line x1="4" y1="22" x2="4" y2="15"/>
            </svg>
          </div>
          <h3 class="text-xl font-semibold mb-2">Fluxos Personalizados</h3>
          <p class="text-gray-300">Crie automações sob medida para suas necessidades específicas com nossa interface drag-and-drop.</p>
        </div>
        
        <!-- Feature 3 -->
        <div class="glass-card rounded-xl p-6 hover:glow-effect transition led-glow">
          <div class="feature-icon w-12 h-12 rounded-lg flex items-center justify-center mb-4">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#8ab8ad" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <circle cx="12" cy="12" r="10"/><path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"/><line x1="12" y1="17" x2="12.01" y2="17"/>
            </svg>
          </div>
          <h3 class="text-xl font-semibold mb-2">Monitoramento Inteligente</h3>
          <p class="text-gray-300">Acompanhe o desempenho dos seus fluxos com dashboards detalhados e alertas em tempo real.</p>
        </div>
      </div>
    </section>

</template>

<script>
export default {
  name: 'HeroSection',
  mounted() {
    // Verifica se está no lado do cliente
    if (typeof window !== 'undefined') {
      import('aos/dist/aos.css').then(() => {
        import('aos').then((AOS) => {
          AOS.init({
            once: true,
            duration: 800,
            easing: 'ease-out-quart',
          });
        });
      });
    }
  }
};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Inter:wght@400;500;600&display=swap');

/* Tipografia melhorada */
h1 {
  font-family: 'Playfair Display', serif;
}

p, a {
  font-family: 'Inter', sans-serif;
}

/* Transições suaves */
a, img {
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 300ms;
}

/* Efeito de hover no botão */
a:hover {
  box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
}
</style>