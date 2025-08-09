<script setup>
useHead({
  title: 'Criação de Landing Pages Profissionais | Landing Pro',
  link: [
    {
      rel: 'icon',
      type: 'image/png',
      href: 'image/logo.png'
    }
  ],
  meta: [
    { 
      name: 'description', 
      content: 'Desenvolva landing pages otimizadas para conversão. Design profissional, SEO otimizado e alta performance para transformar visitantes em clientes.' 
    },
    { 
      name: 'keywords', 
      content: 'landing page, criação de landing page, páginas de conversão, web design, site responsivo' 
    }
  ],
  script: [
    {
      type: 'application/ld+json',
      children: `
      {
        "@context": "https://schema.org",
        "@type": "Organization",
        "name": "Landing Pro",
        "url": "https://landing-pro-cordeiro.netlify.app",
        "logo": "https://landing-pro-cordeiro.netlify.app/logo.png",
        "contactPoint": {
          "@type": "ContactPoint",
          "telephone": "+55-11-95966-7976",
          "contactType": "sales",
          "areaServed": "BR",
          "availableLanguage": "Portuguese"
        }
      }
      `
    }
  ]
})
</script>

<template>
  <section class="min-h-screen bg-gradient-to-b from-white to-purple-50">

    <header class="relative bg-gradient-to-br from-purple-600 to-indigo-600 py-6">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <nav class="flex items-center justify-between">
          <h1 class="text-xl font-bold text-white">
            Criação de Landing Pages | <span class="text-purple-300">Landing Pro</span>
          </h1>
          <div class="hidden md:flex items-center gap-6">
            <span class="text-sm text-purple-200 font-bold"><a href="#como-funciona">Como funciona?</a></span>
            <span class="text-sm text-purple-200 font-bold"><a href="#por-que-escolher">Por que escolher a gente?</a></span>
            <span class="text-sm text-purple-200 font-bold"><a href="#depoimentos">Depoimentos</a></span>
          </div>
          
          <u-button 
            class="bg-white text-purple-600 px-4 py-2 rounded-full text-sm font-medium hover:bg-purple-50 hover:scale-105 transition-all duration-300 shadow-lg"
            to="https://wa.me/5511959667976?text=Olá!%20Gostaria%20de%20falar%20com%20vocês%20sobre%20os%20serviços.%20Podem%20me%20atender?"            
            target="_blank">
            Fale Conosco
          </u-button>
        </nav>
      </div>
    </header>

    <div class="max-w-6xl mx-auto px-4 py-14 flex flex-col md:flex-row items-center justify-between">
  <div class="md:w-1/2 mb-8 md:mb-0">
    <h2 class="text-4xl font-bold text-purple-800 mb-4">Landing Pages que <span class="text-indigo-600">Convertem</span></h2>
    <p class="text-gray-600 text-lg mb-6">Transforme visitantes em clientes com páginas otimizadas e de alta performance.</p>
    <u-button 
      class="bg-purple-600 text-white px-8 py-3 rounded-xl hover:bg-purple-700 transition-all"
      to="https://wa.me/5511959667976?text=Oi!%20Estou%20pronto%20para%20começar%20meu%20projeto%20e%20gostaria%20de%20conversar%20com%20vocês%20hoje."      
      target="_blank">
      Começar Agora
    </u-button>
  </div>
  <div class="md:w-1/2">
    <img 
      src=/image/undraw_screening-resumes_dh9s.svg
      alt="Landing Page Illustration" 
      class="w-full max-w-lg mx-auto animate-float"
    /> 
  </div>
</div>

    <div class="bg-gradient-to-r from-purple-600 to-indigo-600 py-16 px-4 text-center text-white">
      <h2 class="text-3xl font-bold mb-4">Pronto para aumentar suas conversões?</h2>
      <p class="mb-8 text-purple-100">Comece agora e tenha sua landing page em 5 dias!</p>
      <u-button 
            class="bg-white text-purple-600 px-4 py-2 rounded-full text-sm font-medium hover:bg-purple-50 hover:scale-105 transition-all duration-300 shadow-lg"
            to="https://wa.me/5511959667976?text=Olá!%20Gostaria%20de%20solicitar%20um%20orçamento%.%20Podem%20me%20ajudar?"            
            target="_blank">
            Solicitar Orçamento
          </u-button>
    </div>
    <div class="max-w-4xl mx-auto py-12 px-4">

  </div >
    <div class="max-w-4xl mx-auto py-16 px-8" id="como-funciona">
      <h2 class="text-3xl font-bold text-center mb-12 text-purple-800">Como funciona?</h2>
      <div class="grid md:grid-cols-4 gap-8 text-center">
        <div class="group hover:scale-105 transition-transform">
          <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center text-2xl text-purple-600 mx-auto mb-4 group-hover:bg-purple-200 transition-colors">1</div>
          <h3 class="font-semibold mb-2">Briefing</h3>
          <p class="text-gray-600">Entendemos suas necessidades e objetivos</p>
        </div>
        <div class="group hover:scale-105 transition-transform">
          <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center text-2xl text-purple-600 mx-auto mb-4 group-hover:bg-purple-200 transition-colors">2</div>
          <h3 class="font-semibold mb-2">Design</h3>
          <p class="text-gray-600">Criamos o layout perfeito</p>
        </div>
        <div class="group hover:scale-105 transition-transform">
          <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center text-2xl text-purple-600 mx-auto mb-4 group-hover:bg-purple-200 transition-colors">3</div>
          <h3 class="font-semibold mb-2">Desenvolvimento</h3>
          <p class="text-gray-600">Codificamos sua landing</p>
        </div>
        <div class="group hover:scale-105 transition-transform">
          <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center text-2xl text-purple-600 mx-auto mb-4 group-hover:bg-purple-200 transition-colors">4</div>
          <h3 class="font-semibold mb-2">Entrega</h3>
          <p class="text-gray-600">Seu site no ar!</p>
        </div>
      </div>
    </div>

    <div class="max-w-4xl mx-auto py-16 px-4" id="por-que-escolher">
      <h2 class="text-3xl font-bold text-center mb-12 text-purple-800">Por que escolher nossa solução?</h2>
      <div class="grid md:grid-cols-2 gap-8">
        <div class="flex items-start space-x-4 p-6 bg-white rounded-xl hover:shadow-lg transition-shadow">
          <div class="bg-purple-100 p-3 rounded-xl">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6" />
            </svg>
          </div>
          <div>
            <h3 class="font-semibold text-xl mb-2">SEO Otimizado</h3>
            <p class="text-gray-600">Páginas otimizadas para mecanismos de busca, garantindo maior visibilidade.</p>
          </div>
        </div>

        <div class="flex items-start space-x-4 p-6 bg-white rounded-xl hover:shadow-lg transition-shadow">
          <div class="bg-purple-100 p-3 rounded-xl">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
            </svg>
          </div>
          <div>
            <h3 class="font-semibold text-xl mb-2">Alta Performance</h3>
            <p class="text-gray-600">Sites rápidos e otimizados para melhor experiência do usuário.</p>
          </div>
        </div>
      </div>
    </div>
    
    <div class="max-w-5xl mx-auto py-16 px-4" id="depoimentos">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4 md:gap-8 max-w-3xl mx-auto mb-16 text-center">
        <div class="bg-white p-6 rounded-xl shadow-sm">
          <h3 class="text-3xl font-bold text-purple-800 mb-2">24/7</h3>
          <p class="text-gray-600">Suporte Exclusivo</p>
        </div>
        <div class="bg-white p-6 rounded-xl shadow-sm">
          <h3 class="text-3xl font-bold text-purple-800 mb-2">40%</h3>
          <p class="text-gray-600">Média de Conversão</p>
        </div>
        <div class="bg-white p-6 rounded-xl shadow-sm">
          <h3 class="text-3xl font-bold text-purple-800 mb-2">5 dias</h3>
          <p class="text-gray-600">Prazo de Entrega</p>
        </div>
      </div>

      
    
    <div class="max-w-4xl mx-auto py-12 px-8 bg-white rounded-xl shadow-sm">
      <h2 class="text-3xl font-bold text-center text-purple-800 mb-12">Por que sua empresa precisa de uma Landing Page?</h2>
      
      <div class="space-y-8 text-gray-600">
        <p class="text-lg">
          Uma landing page bem construída é essencial para qualquer estratégia de marketing digital moderna. Diferente de um site tradicional, landing pages são páginas focadas em conversão, projetadas especificamente para transformar visitantes em leads ou clientes.
        </p>
        
        <div class="bg-purple-50/50 p-6 rounded-xl">
          <p class="text-lg font-medium text-purple-800 mb-6">Nossas landing pages são desenvolvidas com foco em três pilares fundamentais:</p>
          
          <div class="grid md:grid-cols-3 gap-6">
            <div class="bg-white p-6 rounded-xl hover:shadow-md transition-shadow">
              <div class="bg-purple-100 p-3 rounded-xl w-12 h-12 flex items-center justify-center mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 5a1 1 0 011-1h14a1 1 0 011 1v2a1 1 0 01-1 1H5a1 1 0 01-1-1V5zM4 13a1 1 0 011-1h6a1 1 0 011 1v6a1 1 0 01-1 1H5a1 1 0 01-1-1v-6zM16 13a1 1 0 011-1h2a1 1 0 011 1v6a1 1 0 01-1 1h-2a1 1 0 01-1-1v-6z" />
                </svg>
              </div>
              <h3 class="font-semibold text-xl mb-2 text-purple-800">Design Persuasivo</h3>
              <p>Utilizamos princípios de psicologia e UX para criar layouts que guiam naturalmente o visitante à ação desejada.</p>
            </div>

            <div class="bg-white p-6 rounded-xl hover:shadow-md transition-shadow">
              <div class="bg-purple-100 p-3 rounded-xl w-12 h-12 flex items-center justify-center mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
                </svg>
              </div>
              <h3 class="font-semibold text-xl mb-2 text-purple-800">Escalabilidade sob Medida</h3>
              <p>Desenvolvemos com tecnologias modernas que permitem evoluções rápidas.</p>
            </div>

            <div class="bg-white p-6 rounded-xl hover:shadow-md transition-shadow">
              <div class="bg-purple-100 p-3 rounded-xl w-12 h-12 flex items-center justify-center mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                </svg>
              </div>
              <h3 class="font-semibold text-xl mb-2 text-purple-800">Credibilidade e Confiança</h3>
              <p>Utilizamos provas sociais, depoimentos e selos que reforçam a confiança e aumentam suas conversões.</p>
            </div>
          </div>
        </div>
        
        <p class="text-lg text-center">
          Cada landing page é desenvolvida considerando seu público-alvo específico e objetivos de negócio. Trabalhamos com análise de dados para identificar os melhores elementos e estruturas que maximizam suas taxas de conversão.
        </p>
      </div>
    </div>

      <h2 class="text-3xl font-bold text-center mb-12 text-purple-800 mt-8">O que nossos clientes dizem</h2>
      <div class="grid md:grid-cols-2 gap-8">
        <div class="bg-white p-6 rounded-xl shadow-sm">
          <p class="text-gray-600 mb-4">"A landing page superou nossas expectativas. As conversões aumentaram em 40%!"</p>
          <div class="flex items-center">
            <div>
              <h4 class="font-semibold">João Silva</h4>
              <p class="text-gray-500 text-sm">CEO, Empresa X</p>
            </div>
          </div>
        </div>
        <!-- Add more testimonials -->
      </div>
    </div>

    <div class="max-w-2xl mx-auto py-12 px-8">
      <h2 class="text-3xl font-bold text-center mb-8 text-purple-800">Perguntas Frequentes</h2>
      <div class="space-y-4">
        <details class="bg-white p-4 rounded-xl shadow-sm">
          <summary class="font-semibold cursor-pointer text-purple-700">Quanto tempo leva para criar?</summary>
          <p class="mt-2 text-gray-600">Em média, entregamos sua landing page em 5 dias úteis.</p>
        </details>
        <details class="bg-white p-4 rounded-xl shadow-sm">
          <summary class="font-semibold cursor-pointer text-purple-700">Posso personalizar o design?</summary>
          <p class="mt-2 text-gray-600">Sim! Trabalhamos com você para criar um design único e personalizado.</p>
        </details>
        <details class="bg-white p-4 rounded-xl shadow-sm">
          <summary class="font-semibold cursor-pointer text-purple-700">Quais formas de pagamento aceitam?</summary>
          <p class="mt-2 text-gray-600">Aceitamos Pix.</p>
        </details>
        <details class="bg-white p-4 rounded-xl shadow-sm">
          <summary class="font-semibold cursor-pointer text-purple-700">Preciso de hospedagem?</summary>
          <p class="mt-2 text-gray-600">Não! Oferecemos hospedagem gratuita para todas as landing pages.</p>
        </details>
      </div>
    </div>


    <div class="text-center py-16">
      <h2 class="text-2xl font-bold mb-2">Pronto para começar?</h2>
      <p class="text-gray-600 mb-8">Transforme seu negócio com uma landing page de alta conversão</p>
      <u-button 
        class="bg-purple-600 text-white px-8 py-3 rounded-xl hover:bg-purple-700 hover:scale-105 transition-all duration-300 shadow-lg"
        to="https://wa.me/5511959667976?text=Olá!%20Gostaria%20de%20tirar%20algumas%20dúvidas%20sobre%20os%20serviços."        
        target="_blank">
        Falar no WhatsApp
      </u-button>
    </div>

    <footer class="text-center text-gray-600 mt-16 bg-white/80 py-8">
      <p class="text-sm">© 2025. Todos os direitos reservados.</p>
      <p class="text-sm">Feito com ❤️ por <a href="https://www.linkedin.com/in/juliobcordeiro/" target="_blank">Júlio Cordeiro</a></p>
    </footer>

  </section>
</template>
