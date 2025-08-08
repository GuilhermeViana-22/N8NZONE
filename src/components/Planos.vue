<template>
  
    <!-- Pricing Section -->
    <section id="pricing" class="py-20 px-4 bg-gradient-to-b from-black/50 to-[#0e0e10]">
      <div class="max-w-7xl mx-auto">
        <div class="text-center mb-16">
          <h2 class="text-3xl md:text-4xl font-bold mb-4 text-led">Planos de <span class="highlight-text">Automação</span></h2>
          <p class="text-gray-300 max-w-2xl mx-auto">Escolha o plano ideal para automatizar seus processos com n8n.</p>
        </div>
        
        <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
          <!-- Free Plan -->
          <div class="glass-card pricing-card rounded-xl p-8 flex flex-col">
            <h3 class="text-xl font-semibold mb-2">Básico</h3>
            <p class="text-gray-300 mb-6">Ideal para pequenas empresas começando com automação</p>
            <div class="mb-6">
              <span class="text-4xl font-bold">R$ 297</span>
              <span class="text-gray-300">/mês</span>
            </div>
            <a href="#" class="mt-auto rounded-full border border-white/20 px-6 py-2 text-center font-medium text-sm hover:bg-white/10 transition led-glow">Contratar</a>
            <div class="mt-8 space-y-3">
              <div class="flex items-center">
                <svg class="w-5 h-5 text-accent mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                <span>Até 5 fluxos automatizados</span>
              </div>
              <div class="flex items-center">
                <svg class="w-5 h-5 text-accent mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                <span>Suporte via WhatsApp</span>
              </div>
              <div class="flex items-center">
                <svg class="w-5 h-5 text-accent mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                <span>Configuração inicial inclusa</span>
              </div>
            </div>
          </div>
          
          <!-- Pro Plan (Popular) -->
          <div class="glass-card pricing-card popular rounded-xl p-8 flex flex-col relative glow-effect">
            <div class="absolute top-0 right-0 bg-accent text-black text-xs font-bold px-3 py-1 rounded-bl-lg rounded-tr-lg">POPULAR</div>
            <h3 class="text-xl font-semibold mb-2">Profissional</h3>
            <p class="text-gray-300 mb-6">Para empresas que precisam de automações mais complexas</p>
            <div class="mb-6">
              <span class="text-4xl font-bold">R$ 597</span>
              <span class="text-gray-300">/mês</span>
            </div>
            <a href="#" class="mt-auto rounded-full btn-led text-black px-6 py-2 text-center font-medium text-sm">Contratar</a>
            <div class="mt-8 space-y-3">
              <div class="flex items-center">
                <svg class="w-5 h-5 text-accent mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                <span>Até 15 fluxos automatizados</span>
              </div>
              <div class="flex items-center">
                <svg class="w-5 h-5 text-accent mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                <span>Integrações avançadas</span>
              </div>
              <div class="flex items-center">
                <svg class="w-5 h-5 text-accent mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                <span>Suporte prioritário</span>
              </div>
              <div class="flex items-center">
                <svg class="w-5 h-5 text-accent mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                <span>Treinamento da equipe</span>
              </div>
            </div>
          </div>
          
          <!-- Enterprise Plan -->
          <div class="glass-card pricing-card rounded-xl p-8 flex flex-col">
            <h3 class="text-xl font-semibold mb-2">Empresarial</h3>
            <p class="text-gray-300 mb-6">Para grandes empresas com necessidades complexas</p>
            <div class="mb-6">
              <span class="text-4xl font-bold">R$ 1.297</span>
              <span class="text-gray-300">/mês</span>
            </div>
            <a href="#" class="mt-auto rounded-full border border-white/20 px-6 py-2 text-center font-medium text-sm hover:bg-white/10 transition led-glow">Falar com Vendas</a>
            <div class="mt-8 space-y-3">
              <div class="flex items-center">
                <svg class="w-5 h-5 text-accent mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                <span>Fluxos ilimitados</span>
              </div>
              <div class="flex items-center">
                <svg class="w-5 h-5 text-accent mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                <span>Gestão de equipes</span>
              </div>
              <div class="flex items-center">
                <svg class="w-5 h-5 text-accent mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                <span>Suporte dedicado 24/7</span>
              </div>
              <div class="flex items-center">
                <svg class="w-5 h-5 text-accent mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
                </svg>
                <span>Implementação on-premise</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

</template>

<script>

</script>

<style scoped>

</style>