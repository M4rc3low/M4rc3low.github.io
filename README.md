# M4rc3low.github.io
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Marcelo • Portfólio</title>
  <meta name="description" content="Portfólio de Marcelo – ADS, IA, Engenharia de Software, Cloud, Big Data, ABAP e Linux." />
  <meta name="theme-color" content="#0ea5e9" />
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html { scroll-behavior: smooth; }
    .glass { backdrop-filter: blur(10px); background: rgba(255,255,255,0.7); }
    .dark .glass { background: rgba(15,23,42,0.6); }
  </style>
  <!-- SEO / Schema.org -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Marcelo",
    "jobTitle": "Estudante de ADS e Tecnologia em IA",
    "sameAs": [
      "https://github.com/M4rc3low",
      "[https://www.linkedin.com/in/marcelo-s-gomes-019792389/)
    ],
    "url": "https://M4rc3low.github.io"
  }
  </script>
</head>
<body class="min-h-screen bg-slate-50 text-slate-800 dark:bg-slate-900 dark:text-slate-100">
  <!-- Topbar -->
  <header class="sticky top-0 z-50 border-b border-slate-200 dark:border-slate-800 bg-white/70 dark:bg-slate-900/60 glass">
    <div class="max-w-6xl mx-auto px-4 py-3 flex items-center justify-between">
      <a href="#home" class="font-semibold tracking-tight text-slate-800 dark:text-white">Marcelo</a>
      <nav class="hidden md:flex items-center gap-6 text-sm">
        <a class="hover:text-sky-600" href="#sobre">Sobre</a>
        <a class="hover:text-sky-600" href="#habilidades">Habilidades</a>
        <a class="hover:text-sky-600" href="#projetos">Projetos</a>
        <a class="hover:text-sky-600" href="#certificacoes">Certificações</a>
        <a class="hover:text-sky-600" href="#contato">Contato</a>
      </nav>
      <div class="flex items-center gap-2">
        <button id="themeToggle" class="rounded-xl px-3 py-1.5 text-xs border border-slate-300 dark:border-slate-700 hover:bg-slate-100 dark:hover:bg-slate-800">🌙/☀️</button>
        <a target="_blank" rel="noopener" href="https://github.com/M4rc3low" class="rounded-xl px-3 py-1.5 text-xs border border-slate-300 dark:border-slate-700 hover:bg-slate-100 dark:hover:bg-slate-800">GitHub</a>
      </div>
    </div>
  </header>

  <!-- Hero -->
  <section id="home" class="relative overflow-hidden">
    <div class="absolute inset-0 bg-gradient-to-b from-sky-100/60 via-transparent to-transparent dark:from-sky-900/20"></div>
    <div class="max-w-6xl mx-auto px-4 pt-16 pb-10">
      <div class="grid md:grid-cols-2 items-center gap-10">
        <div>
          <p class="text-sky-600 font-medium">Portfólio</p>
          <h1 class="mt-2 text-3xl md:text-5xl font-extrabold tracking-tight">Marcelo — ADS • IA • Engenharia de Software</h1>
          <p class="mt-4 text-slate-600 dark:text-slate-300 leading-relaxed">Foco em Cloud (AWS/GCP), Big Data (Hadoop/Spark/MLlib), NoSQL (MongoDB/Redis), ABAP (SAP) e Linux. Busco oportunidades para estágio ou júnior, com projetos práticos e evolução contínua.</p>
          <div class="mt-6 flex flex-wrap gap-3">
            <a href="#projetos" class="inline-flex items-center gap-2 rounded-2xl px-4 py-2 bg-sky-600 text-white shadow hover:bg-sky-700">Ver Projetos</a>
            <a href="#contato" class="inline-flex items-center gap-2 rounded-2xl px-4 py-2 border border-slate-300 dark:border-slate-700 hover:bg-slate-100 dark:hover:bg-slate-800">Falar comigo</a>
          </div>
        </div>
        <div class="md:justify-self-end">
          <div class="w-full md:w-[420px] rounded-3xl p-6 glass shadow-xl">
            <h3 class="font-semibold mb-3">Disponível para</h3>
            <ul class="space-y-2 text-sm">
              <li>• Estágio / Dev Júnior (Java/Python)</li>
              <li>• Dados & Big Data (Spark, MLlib, SQL)</li>
              <li>• Cloud (AWS / Google Cloud)</li>
              <li>• Automação Linux & DevOps básico</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Sobre -->
  <section id="sobre" class="py-16 border-t border-slate-200 dark:border-slate-800">
    <div class="max-w-6xl mx-auto px-4 grid md:grid-cols-3 gap-10">
      <div class="md:col-span-2">
        <h2 class="text-2xl font-bold">Sobre mim</h2>
        <p class="mt-4 leading-relaxed text-slate-700 dark:text-slate-300">Sou estudante de <strong>Análise e Desenvolvimento de Sistemas</strong> e de <strong>Tecnologia em Inteligência Artificial</strong>. Tenho perfil prático, gosto de aprender construindo projetos e estou montando carreira em <strong>engenharia de software</strong>, <strong>dados</strong> e <strong>cloud</strong>. Também estudo <strong>ABAP</strong> para o ecossistema SAP e utilizo <strong>Linux</strong> diariamente.</p>
        <p class="mt-4 leading-relaxed text-slate-700 dark:text-slate-300">Objetivo: entrar em uma equipe onde eu possa contribuir desde o dia 1 e evoluir rápido, com mentoria e desafios reais.</p>
      </div>
      <aside class="space-y-2">
        <div class="text-sm">📍 São Paulo, SP</div>
        <div class="text-sm">🎓 ADS + IA (cursando)</div>
        <div class="text-sm">🕒 Disponibilidade: meio período/manhã</div>
      </aside>
    </div>
  </section>

  <!-- Habilidades -->
  <section id="habilidades" class="py-16 border-t border-slate-200 dark:border-slate-800">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-2xl font-bold">Habilidades</h2>
      <div class="mt-6 grid sm:grid-cols-2 lg:grid-cols-3 gap-4">
        <div class="rounded-2xl p-4 border border-slate-200 dark:border-slate-800">
          <h3 class="font-semibold">Linguagens & Core</h3>
          <p class="mt-2 text-sm text-slate-600 dark:text-slate-300">Java, Python, Bash, ABAP (iniciante)</p>
        </div>
        <div class="rounded-2xl p-4 border border-slate-200 dark:border-slate-800">
          <h3 class="font-semibold">Dados & Big Data</h3>
          <p class="mt-2 text-sm">SQL, NoSQL (MongoDB/Redis), Hadoop, Spark, MLlib</p>
        </div>
        <div class="rounded-2xl p-4 border border-slate-200 dark:border-slate-800">
          <h3 class="font-semibold">Cloud & DevOps</h3>
          <p class="mt-2 text-sm">AWS, Google Cloud, Git/GitHub, Docker (básico), Linux</p>
        </div>
        <div class="rounded-2xl p-4 border border-slate-200 dark:border-slate-800">
          <h3 class="font-semibold">Engenharia de Software</h3>
          <p class="mt-2 text-sm">POO, UML, Arquitetura em camadas, Testes (TDD)</p>
        </div>
        <div class="rounded-2xl p-4 border border-slate-200 dark:border-slate-800">
          <h3 class="font-semibold">IA & Analytics</h3>
          <p class="mt-2 text-sm">Pandas/NumPy, Scikit-learn, Visualização</p>
        </div>
        <div class="rounded-2xl p-4 border border-slate-200 dark:border-slate-800">
          <h3 class="font-semibold">Soft Skills</h3>
          <p class="mt-2 text-sm">Comunicação, trabalho em equipe, foco em resultado</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Projetos -->
  <section id="projetos" class="py-16 border-t border-slate-200 dark:border-slate-800">
    <div class="max-w-6xl mx-auto px-4">
      <div class="flex items-end justify-between gap-4">
        <h2 class="text-2xl font-bold">Projetos em Destaque</h2>
        <a target="_blank" rel="noopener" href="https://github.com/SEU_USUARIO" class="text-sm underline underline-offset-4 hover:text-sky-600">Ver GitHub →</a>
      </div>

      <div class="mt-6 grid md:grid-cols-2 xl:grid-cols-3 gap-6">
        <!-- Card 1 -->
        <article class="rounded-2xl border border-slate-200 dark:border-slate-800 p-5 hover:shadow-lg transition">
          <h3 class="font-semibold">CRUD Java + MongoDB</h3>
          <p class="mt-2 text-sm text-slate-600 dark:text-slate-300">Aplicativo simples em Java SE com persistência em MongoDB (CRUD, camadas, boas práticas).
          </p>
          <ul class="mt-3 text-xs list-disc pl-5 space-y-1">
            <li>Java, MongoDB, Maven</li>
            <li>Arquitetura em camadas + testes</li>
          </ul>
          <div class="mt-4 flex gap-3">
            <a target="_blank" rel="noopener" href="https://github.com/SEU_USUARIO/crud-java-mongodb" class="text-sm rounded-xl px-3 py-1.5 border border-slate-300 dark:border-slate-700">Código</a>
          </div>
        </article>
        <!-- Card 2 -->
        <article class="rounded-2xl border border-slate-200 dark:border-slate-800 p-5 hover:shadow-lg transition">
          <h3 class="font-semibold">Automação Linux – Backup & Logs</h3>
          <p class="mt-2 text-sm">Scripts Bash para backup comprimido, limpeza de logs antigos e relatório do sistema.</p>
          <ul class="mt-3 text-xs list-disc pl-5 space-y-1">
            <li>Bash, cron, tar/gzip</li>
            <li>Execução em Ubuntu/WSL e EC2</li>
          </ul>
          <div class="mt-4 flex gap-3">
            <a target="_blank" rel="noopener" href="https://github.com/SEU_USUARIO/linux-automations" class="text-sm rounded-xl px-3 py-1.5 border border-slate-300 dark:border-slate-700">Código</a>
          </div>
        </article>
        <!-- Card 3 -->
        <article class="rounded-2xl border border-slate-200 dark:border-slate-800 p-5 hover:shadow-lg transition">
          <h3 class="font-semibold">Análise de Dados com Spark</h3>
          <p class="mt-2 text-sm">Pipeline de leitura de CSV, limpeza e agregações em Spark; exporta relatório final.</p>
          <ul class="mt-3 text-xs list-disc pl-5 space-y-1">
            <li>Apache Spark, DataFrames, SparkSQL</li>
            <li>Dataset público (vendas)</li>
          </ul>
          <div class="mt-4 flex gap-3">
            <a target="_blank" rel="noopener" href="https://github.com/SEU_USUARIO/spark-analytics" class="text-sm rounded-xl px-3 py-1.5 border border-slate-300 dark:border-slate-700">Código</a>
          </div>
        </article>
        <!-- Card 4 -->
        <article class="rounded-2xl border border-slate-200 dark:border-slate-800 p-5 hover:shadow-lg transition">
          <h3 class="font-semibold">Modelo ML (Scikit-learn ou MLlib)</h3>
          <p class="mt-2 text-sm">Classificador de churn com métricas de acurácia, precisão e recall, comparando modelos.</p>
          <ul class="mt-3 text-xs list-disc pl-5 space-y-1">
            <li>Python/Scikit-learn ou Spark MLlib</li>
            <li>Notebook e README explicativo</li>
          </ul>
          <div class="mt-4 flex gap-3">
            <a target="_blank" rel="noopener" href="https://github.com/SEU_USUARIO/ml-churn" class="text-sm rounded-xl px-3 py-1.5 border border-slate-300 dark:border-slate-700">Código</a>
          </div>
        </article>
        <!-- Card 5 -->
        <article class="rounded-2xl border border-slate-200 dark:border-slate-800 p-5 hover:shadow-lg transition">
          <h3 class="font-semibold">ABAP – Relatório KNA1</h3>
          <p class="mt-2 text-sm">Programa ABAP que lista clientes (KNA1) com filtros e exportação para CSV (exercício acadêmico).</p>
          <ul class="mt-3 text-xs list-disc pl-5 space-y-1">
            <li>ABAP básico + tabelas internas</li>
            <li>WRITE/SELECT/LOOP AT</li>
          </ul>
          <div class="mt-4 flex gap-3">
            <a target="_blank" rel="noopener" href="https://github.com/SEU_USUARIO/abap-exercicios" class="text-sm rounded-xl px-3 py-1.5 border border-slate-300 dark:border-slate-700">Código</a>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- Certificações -->
  <section id="certificacoes" class="py-16 border-t border-slate-200 dark:border-slate-800">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-2xl font-bold">Certificações (alvo)</h2>
      <ul class="mt-4 grid md:grid-cols-2 gap-3 text-sm">
        <li class="rounded-xl p-3 border border-slate-200 dark:border-slate-800">AWS Cloud Practitioner</li>
        <li class="rounded-xl p-3 border border-slate-200 dark:border-slate-800">Google Cloud Digital Leader</li>
        <li class="rounded-xl p-3 border border-slate-200 dark:border-slate-800">Linux Essentials</li>
        <li class="rounded-xl p-3 border border-slate-200 dark:border-slate-800">AZ-900 (opcional)</li>
      </ul>
    </div>
  </section>

  <!-- Contato -->
  <section id="contato" class="py-16 border-t border-slate-200 dark:border-slate-800">
    <div class="max-w-6xl mx-auto px-4">
      <h2 class="text-2xl font-bold">Contato</h2>
      <p class="mt-2 text-slate-600 dark:text-slate-300">Estou aberto a oportunidades de estágio e posições júnior. Vamos conversar!</p>
      <div class="mt-6 grid sm:grid-cols-2 lg:grid-cols-3 gap-4 text-sm">
        <a class="rounded-2xl p-4 border border-slate-200 dark:border-slate-800 hover:bg-slate-100 dark:hover:bg-slate-800" target="_blank" rel="noopener" href="mailto:mg.anjos1991@gmail.com">📧 E-mail</a>
        <a class="rounded-2xl p-4 border border-slate-200 dark:border-slate-800 hover:bg-slate-100 dark:hover:bg-slate-800" target="_blank" rel="noopener" href="[https://www.linkedin.com/in/SEU_LINKEDIN](https://www.linkedin.com/in/marcelo-s-gomes-019792389/)">🔗 LinkedIn</a>
        <a class="rounded-2xl p-4 border border-slate-200 dark:border-slate-800 hover:bg-slate-100 dark:hover:bg-slate-800" target="_blank" rel="noopener" href="https://github.com/M4rc3low">🐙 GitHub</a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="py-10 border-t border-slate-200 dark:border-slate-800">
    <div class="max-w-6xl mx-auto px-4 text-sm flex flex-col md:flex-row items-center justify-between gap-2">
      <p>© <span id="year"></span> Marcelo — Portfólio</p>
      <p class="text-slate-500">Feito com HTML + TailwindCSS. Publicado no GitHub Pages.</p>
    </div>
  </footer>

  <script>
    // Ano automático
    document.getElementById('year').textContent = new Date().getFullYear();
    // Tema claro/escuro
    const btn = document.getElementById('themeToggle');
    const root = document.documentElement;
    const setTheme = (dark) => {
      if(dark){ root.classList.add('dark'); localStorage.setItem('theme','dark'); }
      else { root.classList.remove('dark'); localStorage.setItem('theme','light'); }
    }
    setTheme(localStorage.getItem('theme') === 'dark');
    btn.addEventListener('click', ()=> setTheme(!root.classList.contains('dark')));
  </script>
</body>
</html>
