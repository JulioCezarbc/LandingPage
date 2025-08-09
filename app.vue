<script setup>
useHead({
  title: 'Landing Page Profissional - Criação de Landing Pages | Landing Pro',
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
      content: 'Landing page profissional para aumentar conversões. Desenvolva landing pages otimizadas para SEO, design responsivo e alta performance para transformar visitantes em clientes.' 
    },
    { 
      name: 'keywords', 
      content: 'landing page, landing page profissional, criação de landing page, páginas de conversão, web design, site responsivo' 
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
            Landing Page Profissional | <span class="text-purple-300">Landing Pro</span>
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
    <h2 class="text-4xl font-bold text-purple-800 mb-4">Landing Page que <span class="text-indigo-600">Convertem</span></h2>
    <p class="text-gray-600 text-lg mb-6">Transforme visitantes em clientes com uma landing page profissional, otimizada e de alta performance. Nossa especialidade é criar landing pages que realmente geram resultados para seu negócio.</p>
    <u-button 
      class="bg-purple-600 text-white px-8 py-3 rounded-xl hover:bg-purple-700 transition-all"
      to="https://wa.me/5511959667976?text=Oi!%20Estou%20pronto%20para%20começar%20meu%20projeto%20e%20gostaria%20de%20conversar%20com%20vocês%20hoje."      
      target="_blank">
      Começar Agora
    </u-button>
  </div>
  <div class="md:w-1/2">
    <img 
      src="/image/undraw_screening-resumes_dh9s.svg"
      alt="Landing page profissional - Criação de páginas otimizadas para conversão" 
      class="w-full max-w-lg mx-auto animate-float"
    /> 
  </div>
</div>

    <div class="bg-gradient-to-r from-purple-600 to-indigo-600 py-16 px-4 text-center text-white">
      <h2 class="text-3xl font-bold mb-4">Pronto para aumentar suas conversões?</h2>
      <p class="mb-8 text-purple-100">Comece agora e tenha sua landing page profissional em 5 dias!</p>
      <u-button 
            class="bg-white text-purple-600 px-4 py-2 rounded-full text-sm font-medium hover:bg-purple-50 hover:scale-105 transition-all duration-300 shadow-lg"
            to="https://wa.me/5511959667976?text=Olá!%20Gostaria%20de%20solicitar%20um%20orçamento%.%20Podem%20me%20ajudar?"            
            target="_blank">
            Solicitar Orçamento
          </u-button>
    </div>

    <div class="max-w-4xl mx-auto py-16 px-8" id="como-funciona">
      <h2 class="text-3xl font-bold text-center mb-12 text-purple-800">Como Criamos Sua Landing Page Profissional?</h2>
      <div class="grid md:grid-cols-4 gap-8 text-center">
        <div class="group hover:scale-105 transition-transform">
          <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center text-2xl text-purple-600 mx-auto mb-4 group-hover:bg-purple-200 transition-colors">1</div>
          <h3 class="font-semibold mb-2">Briefing Detalhado</h3>
          <p class="text-gray-600">Entendemos suas necessidades específicas e objetivos de conversão para sua landing page. Analisamos seu público-alvo e concorrência.</p>
        </div>
        <div class="group hover:scale-105 transition-transform">
          <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center text-2xl text-purple-600 mx-auto mb-4 group-hover:bg-purple-200 transition-colors">2</div>
          <h3 class="font-semibold mb-2">Design Persuasivo</h3>
          <p class="text-gray-600">Criamos o layout perfeito utilizando princípios de UX/UI para maximizar conversões em sua landing page profissional.</p>
        </div>
        <div class="group hover:scale-105 transition-transform">
          <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center text-2xl text-purple-600 mx-auto mb-4 group-hover:bg-purple-200 transition-colors">3</div>
          <h3 class="font-semibold mb-2">Desenvolvimento Otimizado</h3>
          <p class="text-gray-600">Codificamos sua landing page com foco em performance, SEO e responsividade para todos os dispositivos.</p>
        </div>
        <div class="group hover:scale-105 transition-transform">
          <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center text-2xl text-purple-600 mx-auto mb-4 group-hover:bg-purple-200 transition-colors">4</div>
          <h3 class="font-semibold mb-2">Entrega e Suporte</h3>
          <p class="text-gray-600">Sua landing page profissional no ar com suporte contínuo e hospedagem gratuita incluída!</p>
        </div>
      </div>
    </div>

    <div class="max-w-4xl mx-auto py-16 px-4" id="por-que-escolher">
      <h2 class="text-3xl font-bold text-center mb-12 text-purple-800">Por que Escolher Nossa Landing Page Profissional?</h2>
      
      <!-- Hero text with gradient background -->
      <div class="bg-gradient-to-br from-purple-50 to-indigo-50 p-8 rounded-2xl mb-12">
        <div class="max-w-3xl mx-auto space-y-6">
          <p class="text-lg text-gray-700 leading-relaxed">
            Uma landing page profissional é a <span class="text-purple-700 font-semibold">ferramenta mais eficaz</span> para converter visitantes em clientes. Nossa abordagem é estrategicamente desenvolvida para maximizar suas conversões.
          </p>
          
          <div class="flex items-center gap-4 p-4 bg-white rounded-xl shadow-sm">
            <div class="bg-purple-100 p-2 rounded-lg">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
              </svg>
            </div>
            <p class="text-gray-700">Equipe especializada em marketing digital e desenvolvimento web</p>
          </div>
          
          <div class="flex items-center gap-4 p-4 bg-white rounded-xl shadow-sm">
            <div class="bg-purple-100 p-2 rounded-lg">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
              </svg>
            </div>
            <p class="text-gray-700">Testes rigorosos de usabilidade e performance</p>
          </div>
        </div>
      </div>

      <!-- Features Grid -->
      <div class="grid md:grid-cols-2 gap-8">
        <div class="group bg-white rounded-xl hover:shadow-lg transition-all duration-300 overflow-hidden">
          <div class="p-6">
            <div class="flex items-start space-x-4">
              <div class="bg-purple-100 p-3 rounded-xl group-hover:bg-purple-200 transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6" />
                </svg>
              </div>
              <div>
                <h3 class="font-semibold text-xl mb-2 text-purple-800">SEO Otimizado</h3>
                <p class="text-gray-600">Cuidamos de cada detalhe técnico e estrutural da sua landing page para garantir o melhor desempenho nos mecanismos de busca. Isso inclui a escolha estratégica de palavras-chave, otimização de títulos e descrições (meta tags).</p>
              </div>
            </div>
          </div>
          <div class="bg-purple-50 px-6 py-3 text-sm text-purple-600 ">
            Inclui otimização de títulos, meta tags e estrutura
          </div>
        </div>

        <div class="group bg-white rounded-xl hover:shadow-lg transition-all duration-300 overflow-hidden">
          <div class="p-6">
            <div class="flex items-start space-x-4">
              <div class="bg-purple-100 p-3 rounded-xl group-hover:bg-purple-200 transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
                </svg>
              </div>
              <div>
                <h3 class="font-semibold text-xl mb-2 text-purple-800">Alta Performance</h3>
                <p class="text-gray-600">Desenvolvemos landing pages com carregamento ultra-rápido e interface otimizada. Nossa tecnologia garante que sua landing page profissional ofereça a melhor experiência possível, resultando em maiores taxas de conversão.</p>
              </div>
            </div>
          </div>
          <div class="bg-purple-50 px-6 py-3 text-sm text-purple-600">
            Foco em velocidade e experiência do usuário
          </div>
        </div>

        <div class="group bg-white rounded-xl hover:shadow-lg transition-all duration-300 overflow-hidden">
          <div class="p-6">
            <div class="flex items-start space-x-4">
              <div class="bg-purple-100 p-3 rounded-xl group-hover:bg-purple-200 transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              </div>
              <div>
                <h3 class="font-semibold text-xl mb-2 text-purple-800">Design Responsivo</h3>
                <p class="text-gray-600">Sua landing page funcionará perfeitamente em todos os dispositivos: desktop, tablet e smartphones. Garantimos uma experiência consistente e otimizada para qualquer tela, maximizando o alcance da sua campanha.</p>
              </div>
            </div>
          </div>
          <div class="bg-purple-50 px-6 py-3 text-sm text-purple-600">
            Compatível com todos os dispositivos e tamanhos de tela
          </div>
        </div>

        <div class="group bg-white rounded-xl hover:shadow-lg transition-all duration-300 overflow-hidden">
          <div class="p-6">
            <div class="flex items-start space-x-4">
              <div class="bg-purple-100 p-3 rounded-xl group-hover:bg-purple-200 transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                </svg>
              </div>
              <div>
                <h3 class="font-semibold text-xl mb-2 text-purple-800">Integração Completa</h3>
                <p class="text-gray-600">Integramos sua landing page com ferramentas de análise, CRM, e-mail marketing e automações. Acompanhe métricas detalhadas e otimize continuamente seus resultados de conversão.</p>
              </div>
            </div>
          </div>
          <div class="bg-purple-50 px-6 py-3 text-sm text-purple-600">
            Conexão com as principais ferramentas do mercado
          </div>
        </div>
      </div>
    </div>
    
    <div class="bg-gray-50 py-16">
      <div class="max-w-4xl mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-12 text-purple-800">Benefícios de Uma Landing Page Profissional</h2>
        
        <div class="grid md:grid-cols-2 gap-8">
      <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition-all">
        <div class="flex items-center gap-4 mb-4">
          <div class="bg-purple-100 p-2 rounded-lg">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6" />
            </svg>
          </div>
          <h3 class="font-semibold text-lg text-purple-800">Aumento de Conversões</h3>
        </div>
        <p class="text-gray-600">
          Empresas que utilizam landing pages dedicadas aumentam suas conversões em até 40% comparado a páginas genéricas.
        </p>
      </div>

      <div class="bg-white p-6 rounded-xl shadow-sm hover:shadow-md transition-all">
        <div class="flex items-center gap-4 mb-4">
          <div class="bg-purple-100 p-2 rounded-lg">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
            </svg>
          </div>
          <h3 class="font-semibold text-lg text-purple-800">Análise Detalhada</h3>
        </div>
        <p class="text-gray-600">
          Acompanhe métricas importantes como taxa de conversão, tempo na página e origem do tráfego em tempo real.
        </p>
      </div>
    </div>

    <div class="mt-12 bg-white p-8 rounded-xl shadow-sm">
      <p class="text-lg text-gray-700 leading-relaxed">
        Nossa abordagem combina <span class="text-purple-700 font-semibold">design atrativo</span> com 
        <span class="text-purple-700 font-semibold">estratégia de marketing digital</span>. 
        Utilizamos técnicas avançadas de neuromarketing e psicologia das cores para criar uma experiência 
        que naturalmente guia o visitante à conversão.
      </p>
    </div>
      </div>
    </div>
    
    <div class="max-w-5xl mx-auto py-16 px-4" id="depoimentos">
      

      <div class="max-w-4xl mx-auto py-12 px-8 bg-white rounded-xl shadow-sm">
        <h2 class="text-3xl font-bold text-center text-purple-800 mb-12">Metodologia Para Landing Page de Alta Conversão</h2>
        
        <div class="space-y-8 text-gray-600">
          <p class="text-lg">
            Nossa metodologia para criação de landing page profissional é baseada em anos de experiência e centenas de projetos bem-sucedidos. Seguimos um processo estruturado que combina pesquisa de mercado, análise de concorrência e testes A/B para garantir os melhores resultados.
          </p>
          
          <div class="bg-purple-50/50 p-6 rounded-xl">
            <p class="text-lg font-medium text-purple-800 mb-6">Nossa landing page profissional é desenvolvida seguindo três pilares fundamentais:</p>
            
            <div class="grid md:grid-cols-3 gap-6">
              <div class="bg-white p-6 rounded-xl hover:shadow-md transition-shadow">
                <div class="bg-purple-100 p-3 rounded-xl w-12 h-12 flex items-center justify-center mb-4">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 5a1 1 0 011-1h14a1 1 0 011 1v2a1 1 0 01-1 1H5a1 1 0 01-1-1V5zM4 13a1 1 0 011-1h6a1 1 0 011 1v6a1 1 0 01-1 1H5a1 1 0 01-1-1v-6zM16 13a1 1 0 011-1h2a1 1 0 011 1v6a1 1 0 01-1 1h-2a1 1 0 01-1-1v-6z" />
                  </svg>
                </div>
                <h3 class="font-semibold text-xl mb-2 text-purple-800">Design Persuasivo</h3>
                <p>Utilizamos princípios de psicologia e UX para criar layouts que guiam naturalmente o visitante à ação desejada. Cada elemento visual é estrategicamente posicionado para maximizar conversões.</p>
              </div>

              <div class="bg-white p-6 rounded-xl hover:shadow-md transition-shadow">
                <div class="bg-purple-100 p-3 rounded-xl w-12 h-12 flex items-center justify-center mb-4">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
                  </svg>
                </div>
                <h3 class="font-semibold text-xl mb-2 text-purple-800">Performance Otimizada</h3>
                <p>Desenvolvemos com tecnologias modernas que garantem carregamento rápido e experiência fluida. Nossa landing page profissional mantém alta performance em todos os dispositivos.</p>
              </div>

              <div class="bg-white p-6 rounded-xl hover:shadow-md transition-shadow">
                <div class="bg-purple-100 p-3 rounded-xl w-12 h-12 flex items-center justify-center mb-4">
                  <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-purple-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                  </svg>
                </div>
                <h3 class="font-semibold text-xl mb-2 text-purple-800">Credibilidade e Confiança</h3>
                <p>Incorporamos provas sociais, depoimentos autênticos e elementos de segurança que reforçam a confiança do visitante, aumentando significativamente as taxas de conversão da sua landing page.</p>
              </div>
            </div>
          </div>
          
          <p class="text-lg text-center">
            Cada landing page profissional é desenvolvida considerando seu público-alvo específico e objetivos de negócio. Trabalhamos com análise de dados para identificar os melhores elementos e estruturas que maximizam suas taxas de conversão, garantindo retorno sobre investimento.
          </p>
        </div>
      </div>

      <h2 class="text-3xl font-bold text-center mb-12 text-purple-800 mt-8">Depoimentos de Clientes Satisfeitos</h2>
      <div class="grid md:grid-cols-2 gap-8">
        <div class="bg-white p-6 rounded-xl shadow-sm">
          <p class="text-gray-600 mb-4">"A landing page profissional superou nossas expectativas. As conversões aumentaram em 40% logo no primeiro mês! O investimento se pagou rapidamente."</p>
          <div class="flex items-center">
            <div>
              <h4 class="font-semibold">João Silva</h4>
              <p class="text-gray-500 text-sm">CEO, Empresa X</p>
            </div>
          </div>
        </div>
        
        <div class="bg-white p-6 rounded-xl shadow-sm">
          <p class="text-gray-600 mb-4">"Excelente trabalho! A landing page ficou exatamente como imaginávamos. Design moderno, carregamento rápido e resultados incríveis."</p>
          <div class="flex items-center">
            <div>
              <h4 class="font-semibold">Maria Santos</h4>
              <p class="text-gray-500 text-sm">Diretora de Marketing, Startup Y</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="max-w-2xl mx-auto py-12 px-8">
      <h2 class="text-3xl font-bold text-center mb-8 text-purple-800">Perguntas Frequentes Sobre Landing Page</h2>
      <div class="space-y-4">
        <details class="bg-white p-4 rounded-xl shadow-sm">
          <summary class="font-semibold cursor-pointer text-purple-700">Quanto tempo leva para criar uma landing page profissional?</summary>
          <p class="mt-2 text-gray-600">Em média, entregamos sua landing page profissional otimizada em 5 dias úteis. Este prazo inclui briefing, design, desenvolvimento e testes de qualidade.</p>
        </details>
        <details class="bg-white p-4 rounded-xl shadow-sm">
          <summary class="font-semibold cursor-pointer text-purple-700">Posso personalizar completamente o design da minha landing page?</summary>
          <p class="mt-2 text-gray-600">Sim! Trabalhamos com você para criar um design único e personalizado que reflita sua marca. Cada landing page é desenvolvida do zero, seguindo suas especificações e objetivos.</p>
        </details>
        <details class="bg-white p-4 rounded-xl shadow-sm">
          <summary class="font-semibold cursor-pointer text-purple-700">Quais formas de pagamento vocês aceitam?</summary>
          <p class="mt-2 text-gray-600">Aceitamos pagamento via Pix para maior agilidade e conveniência. Oferecemos condições flexíveis para projetos maiores.</p>
        </details>
        <details class="bg-white p-4 rounded-xl shadow-sm">
          <summary class="font-semibold cursor-pointer text-purple-700">Preciso contratar hospedagem separadamente?</summary>
          <p class="mt-2 text-gray-600">Não! Oferecemos hospedagem gratuita e de alta performance para todas as landing pages que desenvolvemos. Sua página ficará sempre online e rápida.</p>
        </details>
        <details class="bg-white p-4 rounded-xl shadow-sm">
          <summary class="font-semibold cursor-pointer text-purple-700">A landing page será otimizada para dispositivos móveis?</summary>
          <p class="mt-2 text-gray-600">Absolutamente! Toda landing page profissional que criamos é totalmente responsiva, garantindo experiência perfeita em smartphones, tablets e desktops.</p>
        </details>
      </div>
    </div>

    <div class="text-center py-16">
      <h2 class="text-2xl font-bold mb-2">Pronto para Ter Sua Landing Page Profissional?</h2>
      <p class="text-gray-600 mb-8">Transforme seu negócio com uma landing page de alta conversão desenvolvida por especialistas</p>
      <u-button 
        class="bg-purple-600 text-white px-8 py-3 rounded-xl hover:bg-purple-700 hover:scale-105 transition-all duration-300 shadow-lg"
        to="https://wa.me/5511959667976?text=Olá!%20Gostaria%20de%20tirar%20algumas%20dúvidas%20sobre%20os%20serviços."        
        target="_blank">
        Falar no WhatsApp
      </u-button>
    </div>

    <footer class="text-center text-gray-600 mt-16 bg-white/80 py-8">
      <p class="text-sm">© 2025 Landing Pro. Todos os direitos reservados.</p>
      <p class="text-sm">Especialistas em landing page profissional e otimização de conversão.</p>
      <p class="text-sm">Feito com ❤️ por <a href="https://www.linkedin.com/in/juliobcordeiro/" target="_blank">Júlio Cordeiro</a></p>
    </footer>

  </section>
</template>