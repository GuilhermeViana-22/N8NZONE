<template>
  <!-- Testimonials Section - Horizontal Layout -->
  <section id="testimonials" class="testimonials-section py-12 px-4 w-full overflow-x-auto">
    <div class="text-center mb-12">
      <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">O que Nossos <span class="highlight-text">Clientes Dizem</span></h2>
      <p class="text-gray-300 max-w-2xl mx-auto">Junte-se a centenas de empresas que transformaram seus processos com N8N</p>
    </div>
    
    <div class="flex flex-nowrap gap-8 pb-6 w-max mx-auto">
      <!-- Testimonial 1 -->
      <div class="led-border flex-shrink-0 w-80">
        <div class="testimonial-card inner-card rounded-xl p-6 h-full">
          <div class="flex items-center mb-4">
            <div class="avatar-glow w-10 h-10 rounded-full mr-4"></div>
            <div>
              <h4 class="font-semibold">Maria Silva</h4>
              <p class="text-sm text-gray-400">Diretora de TI</p>
            </div>
          </div>
          <p class="testimonial-text text-gray-300">"O N8NZONE automatizou nossos processos de vendas e reduziu nossa carga de trabalho manual em 70%. Excelente suporte!"</p>
          <div class="star-rating flex mt-4">
            <svg v-for="star in 5" :key="star" class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
              <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
            </svg>
          </div>
        </div>
      </div>
      
      <!-- Testimonial 2 -->
      <div class="led-border flex-shrink-0 w-80">
        <div class="testimonial-card inner-card rounded-xl p-6 h-full">
          <div class="flex items-center mb-4">
            <div class="avatar-glow w-10 h-10 rounded-full mr-4"></div>
            <div>
              <h4 class="font-semibold">João Santos</h4>
              <p class="text-sm text-gray-400">CEO, LogiTech</p>
            </div>
          </div>
          <p class="testimonial-text text-gray-300">"Integramos mais de 15 sistemas diferentes em nossa empresa. As automações do N8N nos poupam 20 horas de trabalho por semana."</p>
          <div class="star-rating flex mt-4">
            <svg v-for="star in 5" :key="star" class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
              <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
            </svg>
          </div>
        </div>
      </div>
      
      <!-- Testimonial 3 -->
      <div class="led-border flex-shrink-0 w-80">
        <div class="testimonial-card inner-card rounded-xl p-6 h-full">
          <div class="flex items-center mb-4">
            <div class="avatar-glow w-10 h-10 rounded-full mr-4"></div>
            <div>
              <h4 class="font-semibold">Ana Costa</h4>
              <p class="text-sm text-gray-400">Gerente de Operações</p>
            </div>
          </div>
          <p class="testimonial-text text-gray-300">"Como pequena empresa, o N8NZONE nos deu superpoderes de automação. Nossos processos ficaram mais eficientes e confiáveis."</p>
          <div class="star-rating flex mt-4">
            <svg v-for="star in 5" :key="star" class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
              <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
            </svg>
          </div>
        </div>
      </div>
      
      <!-- Adicione mais depoimentos se necessário -->
      <div class="led-border flex-shrink-0 w-80">
        <div class="testimonial-card inner-card rounded-xl p-6 h-full">
          <div class="flex items-center mb-4">
            <div class="avatar-glow w-10 h-10 rounded-full mr-4"></div>
            <div>
              <h4 class="font-semibold">Carlos Mendes</h4>
              <p class="text-sm text-gray-400">CTO, TechSolutions</p>
            </div>
          </div>
          <p class="testimonial-text text-gray-300">"Implementamos o N8NZONE em toda nossa infraestrutura e os resultados foram impressionantes. ROI em menos de 3 meses."</p>
          <div class="star-rating flex mt-4">
            <svg v-for="star in 5" :key="star" class="w-5 h-5 text-yellow-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
              <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"></path>
            </svg>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'TestimonialsHorizontal'
}
</script>

<style scoped>
/* Efeitos LED e melhorias visuais */
.testimonial-card {
  position: relative;
  overflow: hidden;
  background: linear-gradient(135deg, rgba(138, 184, 173, 0.1), rgba(255, 255, 255, 0.05));
  border: 1px solid rgba(138, 184, 173, 0.3);
  transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
}

.testimonial-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, 
    transparent, 
    rgba(138, 184, 173, 0.2), 
    transparent
  );
  transition: left 0.8s ease;
}

.testimonial-card:hover::before {
  left: 100%;
}

.testimonial-card:hover {
  transform: translateY(-8px) scale(1.02);
  box-shadow: 
    0 20px 40px rgba(138, 184, 173, 0.2),
    0 0 30px rgba(138, 184, 173, 0.3),
    inset 0 1px 0 rgba(255, 255, 255, 0.2);
  border-color: rgba(138, 184, 173, 0.6);
}

.avatar-glow {
  position: relative;
  background: linear-gradient(135deg, #8ab8ad, #6a9b8e);
  box-shadow: 0 0 20px rgba(138, 184, 173, 0.4);
  animation: pulse-glow 2s ease-in-out infinite alternate;
}

@keyframes pulse-glow {
  from {
    box-shadow: 0 0 20px rgba(138, 184, 173, 0.4);
  }
  to {
    box-shadow: 0 0 30px rgba(138, 184, 173, 0.7);
  }
}

.star-rating {
  filter: drop-shadow(0 0 8px rgba(255, 193, 7, 0.5));
}

.testimonial-text {
  position: relative;
  z-index: 2;
}

.section-title {
  text-shadow: 0 0 20px rgba(138, 184, 173, 0.5);
}

.led-border {
  position: relative;
  padding: 2px;
  background: linear-gradient(45deg, 
    #8ab8ad, 
    #6a9b8e, 
    #8ab8ad, 
    #6a9b8e
  );
  background-size: 400% 400%;
  animation: led-flow 3s ease-in-out infinite;
  border-radius: 12px;
}

@keyframes led-flow {
  0%, 100% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
}

.inner-card {
  background: rgba(14, 14, 16, 0.9);
  border-radius: 10px;
  height: 100%;
}

/* Efeito de partículas LED */
.testimonials-section {
  position: relative;
  overflow: hidden;
}

.testimonials-section::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-image: 
    radial-gradient(circle at 20% 20%, rgba(138, 184, 173, 0.1) 1px, transparent 1px),
    radial-gradient(circle at 80% 80%, rgba(138, 184, 173, 0.1) 1px, transparent 1px),
    radial-gradient(circle at 40% 60%, rgba(138, 184, 173, 0.05) 1px, transparent 1px);
  background-size: 50px 50px, 60px 60px, 40px 40px;
  animation: float-particles 20s ease-in-out infinite;
  pointer-events: none;
}

@keyframes float-particles {
  0%, 100% {
    transform: translate(0, 0);
  }
  33% {
    transform: translate(10px, -10px);
  }
  66% {
    transform: translate(-5px, 5px);
  }
}

/* Scrollbar personalizada para navegadores WebKit */
.testimonials-section::-webkit-scrollbar {
  height: 8px;
}

.testimonials-section::-webkit-scrollbar-track {
  background: rgba(138, 184, 173, 0.1);
  border-radius: 10px;
}

.testimonials-section::-webkit-scrollbar-thumb {
  background: linear-gradient(45deg, #8ab8ad, #6a9b8e);
  border-radius: 10px;
}

.testimonials-section::-webkit-scrollbar-thumb:hover {
  background: #6a9b8e;
}
</style>