<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfólio Profissional</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
      html {
        scroll-behavior: smooth;
      }
    </style>
  </head>
  <body class="bg-gradient-to-b from-purple-900 to-purple-700 text-white font-sans">
    <!-- Cabeçalho -->
    <header class="sticky top-0 z-50 bg-purple-950 bg-opacity-90 p-4 flex justify-between items-center shadow-lg">
      <h1 class="text-2xl font-bold">Portfólio Profissional</h1>
      <nav class="space-x-4">
        <a href="#servicos" class="hover:text-purple-300">Serviços</a>
        <a href="#seguranca" class="hover:text-purple-300">Segurança</a>
        <a href="#contato" class="hover:text-purple-300">Contato</a>
      </nav>
    </header>

    <!-- Banner Principal -->
    <section class="flex flex-col items-center text-center py-10 px-4">
      <img src="WhatsApp Image 2025-04-10 at 18.16.59.jpeg" alt="Imagem de perfil" class="rounded-full w-40 h-40 object-cover border-4 border-purple-400 shadow-md" />
      <h2 class="text-3xl mt-4 font-semibold">Bem-vindo(a) ao meu espaço de trabalho!</h2>
      <p class="mt-2 text-purple-200">Conheça meus serviços, minha metodologia e entre em contato.</p>
    </section>

    <!-- Aba Serviços -->
    <section id="servicos" class="px-6 py-10 bg-purple-800 rounded-t-3xl shadow-inner">
      <h2 class="text-2xl font-bold text-center mb-8">Serviços</h2>
      <div class="grid md:grid-cols-3 gap-6">
        <!-- Cada serviço é um botão clicável -->
        <div class="bg-purple-900 p-4 rounded-2xl shadow hover:bg-purple-700 transition cursor-pointer" onclick="toggleDescricao('servico1')">
          <h3 class="font-semibold text-xl">Artigos Científicos</h3>
          <p id="servico1" class="mt-2 hidden">Criação e formatação de artigos conforme ABNT, com linguagem humanizada e autores reais. Ideal para trabalhos acadêmicos, TCCs e publicações.</p>
        </div>
        <div class="bg-purple-900 p-4 rounded-2xl shadow hover:bg-purple-700 transition cursor-pointer" onclick="toggleDescricao('servico2')">
          <h3 class="font-semibold text-xl">Projetos Acadêmicos</h3>
          <p id="servico2" class="mt-2 hidden">Desenvolvimento de projetos interdisciplinares, TCCs e relatórios com cronograma, justificativa e metodologia sob medida.</p>
        </div>
        <div class="bg-purple-900 p-4 rounded-2xl shadow hover:bg-purple-700 transition cursor-pointer" onclick="toggleDescricao('servico3')">
          <h3 class="font-semibold text-xl">Slides e Apresentações</h3>
          <p id="servico3" class="mt-2 hidden">Apresentações completas com design profissional, narração embutida e roteiro de fala para congressos e defesas.</p>
        </div>
        <div class="bg-purple-900 p-4 rounded-2xl shadow hover:bg-purple-700 transition cursor-pointer" onclick="toggleDescricao('servico4')">
          <h3 class="font-semibold text-xl">Portfólios e Relatórios</h3>
          <p id="servico4" class="mt-2 hidden">Organização e escrita de relatórios técnicos, portfólios e fichas de estágio com linguagem clara e objetiva.</p>
        </div>
        <div class="bg-purple-900 p-4 rounded-2xl shadow hover:bg-purple-700 transition cursor-pointer" onclick="toggleDescricao('servico5')">
          <h3 class="font-semibold text-xl">Correções e Reformulações</h3>
          <p id="servico5" class="mt-2 hidden">Revisão textual, correção ortográfica, reestruturação de ideias e adequação às normas acadêmicas.</p>
        </div>
        <div class="bg-purple-900 p-4 rounded-2xl shadow hover:bg-purple-700 transition cursor-pointer" onclick="toggleDescricao('servico6')">
          <h3 class="font-semibold text-xl">Consultoria Personalizada</h3>
          <p id="servico6" class="mt-2 hidden">Atendimento individualizado para orientar seu projeto do início ao fim, com dicas, sugestões e acompanhamento.</p>
        </div>
      </div>
    </section>

    <!-- Aba Segurança -->
    <section id="seguranca" class="px-6 py-10 bg-purple-900">
      <h2 class="text-2xl font-bold text-center mb-6">Segurança e Sigilo</h2>
      <p class="text-center max-w-3xl mx-auto text-purple-200">
        Todos os trabalhos são realizados com ética, profissionalismo e absoluto sigilo. Seus dados e conteúdos não são compartilhados com terceiros. Os arquivos finais são entregues com exclusividade e você acompanha cada etapa do processo.
      </p>
    </section>

    <!-- Aba Contato -->
    <section id="contato" class="px-6 py-10 bg-purple-800">
      <h2 class="text-2xl font-bold text-center mb-6">Contato</h2>
      <div class="text-center space-y-4">
        <p>Para orçamentos, dúvidas ou agendamentos, envie uma mensagem:</p>
        <a href="https://www.instagram.com/tcctrabalhosuniversitarios" target="_blank" class="bg-purple-600 px-4 py-2 rounded-full hover:bg-purple-500 transition inline-block">Instagram: @tcctrabalhosuniversitarios</a>
      </div>
    </section>

    <!-- Botão Voltar ao Topo -->
    <button onclick="window.scrollTo({ top: 0, behavior: 'smooth' })" class="fixed bottom-5 right-5 bg-purple-700 hover:bg-purple-500 p-3 rounded-full shadow-lg">
      ⬆️
    </button>

    <!-- Script para alternar serviços -->
    <script>
      function toggleDescricao(id) {
        const el = document.getElementById(id);
        el.classList.toggle('hidden');
      }
    </script>
  </body>
</html>
