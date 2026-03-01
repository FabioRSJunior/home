<!DOCTYPE html>
<html lang="pt-BR" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fabio Romero - Portfólio de IA & Engenharia</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
    </style>
</head>
<body class="bg-slate-900 text-slate-300 antialiased selection:bg-teal-300 selection:text-slate-900">

    <header class="min-h-screen flex flex-col justify-center items-center text-center px-4 sm:px-6 lg:px-8">
        <div class="max-w-3xl">
            <h1 class="text-5xl sm:text-7xl font-bold text-slate-100 tracking-tight mb-4">
                Fabio Romero
            </h1>
            <h2 class="text-xl sm:text-2xl text-teal-400 font-medium mb-6">
                Engenheiro de Computação | Pesquisador em IA & Dados
            </h2>
            <p class="text-lg text-slate-400 mb-8 max-w-2xl mx-auto leading-relaxed">
                Especialista em criar soluções inovadoras utilizando Inteligência Artificial, Machine Learning e Deep Reinforcement Learning. Unindo rigor acadêmico e visão de negócios através do Mestrado em Engenharia Elétrica (UFU) e MBA em Data Science e Analytics (USP/Esalq).
            </p>
            
            <div class="flex justify-center space-x-4 mb-12">
                <a href="https://github.com/FabioRSJunior" target="_blank" class="px-5 py-2.5 bg-slate-800 hover:bg-slate-700 text-white rounded-lg transition-colors border border-slate-700">GitHub</a>
                <a href="https://www.linkedin.com/in/fabioromerosjunior/" target="_blank" class="px-5 py-2.5 bg-slate-800 hover:bg-slate-700 text-white rounded-lg transition-colors border border-slate-700">LinkedIn</a>
                <a href="https://www.kaggle.com/fabiorsjunior" target="_blank" class="px-5 py-2.5 bg-slate-800 hover:bg-slate-700 text-white rounded-lg transition-colors border border-slate-700">Kaggle</a>
                <a href="http://lattes.cnpq.br/3976533093866468" target="_blank" class="px-5 py-2.5 bg-slate-800 hover:bg-slate-700 text-white rounded-lg transition-colors border border-slate-700">Lattes</a>
            </div>
            
            <a href="#projetos" class="text-teal-400 hover:text-teal-300 animate-bounce block">
                <svg class="w-6 h-6 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"></path></svg>
            </a>
        </div>
    </header>

    <section id="projetos" class="py-20 px-4 sm:px-6 lg:px-8 max-w-5xl mx-auto border-t border-slate-800">
        <h3 class="text-3xl font-bold text-slate-100 mb-10 flex items-center">
            <span class="bg-teal-400 w-8 h-1 mr-3 rounded-full"></span>
            Projetos em Destaque
        </h3>

        <div class="grid grid-cols-1 gap-8">
            <div class="bg-slate-800/50 border border-slate-700 rounded-xl p-6 md:p-8 hover:border-teal-400 transition-colors group">
                <h4 class="text-2xl font-semibold text-slate-100 mb-3 group-hover:text-teal-400 transition-colors">
                    🔹 Analisador Inteligente de PDFs com LLM
                </h4>
                <p class="text-slate-400 mb-6 leading-relaxed">
                    Automação de análise documental com IA generativa. Desenvolvimento de aplicação web capaz de processar múltiplos PDFs utilizando LLMs locais (Ollama) ou em nuvem (Groq), com pipeline completo de extração de texto, chunking, geração de JSON estruturado via engenharia de prompts e persistência em SQLite.
                </p>
                
                <div class="flex flex-wrap gap-2 mb-6">
                    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
                    <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask">
                    <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
                    <img src="https://img.shields.io/badge/LLM-Generative_AI-blue?style=for-the-badge" alt="LLM">
                    <img src="https://img.shields.io/badge/Ollama-Local_Model-black?style=for-the-badge" alt="Ollama">
                    <img src="https://img.shields.io/badge/Groq-Cloud_Inference-orange?style=for-the-badge" alt="Groq">
                </div>

                <div class="flex space-x-4">
                    <a href="#" class="text-sm font-medium text-teal-400 hover:text-teal-300">Visualizar Código no GitHub →</a>
                </div>
            </div>
        </div>
    </section>

    <section class="py-20 px-4 sm:px-6 lg:px-8 max-w-5xl mx-auto border-t border-slate-800">
        <h3 class="text-3xl font-bold text-slate-100 mb-10 flex items-center">
            <span class="bg-teal-400 w-8 h-1 mr-3 rounded-full"></span>
            Experiência Profissional
        </h3>

        <div class="space-y-12 border-l-2 border-slate-700 ml-3 pl-6 md:pl-8">
            <div class="relative">
                <div class="absolute w-4 h-4 bg-teal-400 rounded-full -left-[1.90rem] md:-left-[2.40rem] top-1.5 ring-4 ring-slate-900"></div>
                <h4 class="text-xl font-bold text-slate-100">Pesquisador/Programador P&D</h4>
                <p class="text-teal-400 font-medium mb-1">Laboratório de Redes Inteligentes (LRI-UFU) | Fev 2023 - Fev 2024</p>
                <p class="text-slate-400 mb-3">P&D ANEEL nº 00393-0015/2022 e P&D Petrobras ANEEL nº PD-00553-0071/2021</p>
                <ul class="list-disc list-inside text-slate-400 space-y-2">
                    <li>Desenvolvimento e manutenção de aplicações utilizando Python, C#, PostgreSQL, MongoDB e GIS.</li>
                    <li>Implantação de rotinas em Docker e CI/CD com Jenkins.</li>
                    <li>Integração de sistemas com APIs e bibliotecas de geoprocessamento.</li>
                </ul>
            </div>

            <div class="relative">
                <div class="absolute w-4 h-4 bg-slate-600 rounded-full -left-[1.90rem] md:-left-[2.40rem] top-1.5 ring-4 ring-slate-900"></div>
                <h4 class="text-xl font-bold text-slate-100">Estagiário de Cognitive Computing (AWS)</h4>
                <p class="text-slate-300 font-medium mb-1">UOL Compass | Mar 2023 - Set 2023</p>
                <ul class="list-disc list-inside text-slate-400 space-y-2 mt-3">
                    <li>Aprofundamento em AWS e modelos de Machine Learning utilizando Amazon SageMaker.</li>
                    <li>Processamento de linguagem natural (NLP) com Amazon Comprehend, Kendra e Lex.</li>
                    <li>Análise de imagens com Amazon Rekognition e tecnologias de voz (Polly, Alexa Skill Kit).</li>
                </ul>
            </div>
        </div>
    </section>

    <section class="py-20 px-4 sm:px-6 lg:px-8 max-w-5xl mx-auto border-t border-slate-800">
        <h3 class="text-3xl font-bold text-slate-100 mb-10 flex items-center">
            <span class="bg-teal-400 w-8 h-1 mr-3 rounded-full"></span>
            Formação Acadêmica
        </h3>

        <div class="space-y-12 border-l-2 border-slate-700 ml-3 pl-6 md:pl-8">
            <div class="relative">
                <div class="absolute w-4 h-4 bg-teal-400 rounded-full -left-[1.90rem] md:-left-[2.40rem] top-1.5 ring-4 ring-slate-900"></div>
                <h4 class="text-xl font-bold text-slate-100">MBA em Data Science e Analytics</h4>
                <p class="text-teal-400 font-medium mb-1">USP/Esalq | 2024 - 2025</p>
            </div>

            <div class="relative">
                <div class="absolute w-4 h-4 bg-slate-600 rounded-full -left-[1.90rem] md:-left-[2.40rem] top-1.5 ring-4 ring-slate-900"></div>
                <h4 class="text-xl font-bold text-slate-100">Mestrado em Engenharia Elétrica</h4>
                <p class="text-slate-300 font-medium mb-1">Universidade Federal de Uberlândia (UFU) | 2024 - 2025</p>
                <p class="text-slate-400 text-sm mt-2">Foco em Processamento Digital de Sinais e Redes de Comunicação.</p>
            </div>

            <div class="relative">
                <div class="absolute w-4 h-4 bg-slate-600 rounded-full -left-[1.90rem] md:-left-[2.40rem] top-1.5 ring-4 ring-slate-900"></div>
                <h4 class="text-xl font-bold text-slate-100">Graduação em Engenharia de Computação</h4>
                <p class="text-slate-300 font-medium mb-1">Universidade Federal de Uberlândia (UFU) | 2020 - 2023</p>
            </div>

            <div class="relative">
                <div class="absolute w-4 h-4 bg-slate-600 rounded-full -left-[1.90rem] md:-left-[2.40rem] top-1.5 ring-4 ring-slate-900"></div>
                <h4 class="text-xl font-bold text-slate-100">Curso Técnico em Eletrônica</h4>
                <p class="text-slate-300 font-medium mb-1">Centro Federal de Educação Tecnológica de Minas Gerais (CEFET-MG) | 2014 - 2015</p>
            </div>
        </div>
    </section>

    <section class="py-20 px-4 sm:px-6 lg:px-8 max-w-5xl mx-auto border-t border-slate-800">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
            
            <div>
                <h3 class="text-2xl font-bold text-slate-100 mb-6 flex items-center">
                    <span class="bg-teal-400 w-6 h-1 mr-3 rounded-full"></span>
                    Iniciação Científica
                </h3>
                <div class="bg-slate-800/50 border border-slate-700 rounded-xl p-6 hover:border-teal-400/50 transition-colors">
                    <h4 class="text-lg font-bold text-slate-100 mb-2">Controle de Tráfego em Smart Cities</h4>
                    <span class="inline-block px-3 py-1 bg-slate-700 text-slate-300 text-xs font-semibold rounded-full mb-3">2018</span>
                    <p class="text-slate-400 text-sm leading-relaxed">
                        Desenvolvimento de um protótipo para controle de tráfego em Smart Cities, utilizando a plataforma de prototipagem eletrônica Arduino, linguagem de programação Python e a biblioteca de visão computacional OpenCV.
                    </p>
                </div>
            </div>

            <div>
                <h3 class="text-2xl font-bold text-slate-100 mb-6 flex items-center">
                    <span class="bg-teal-400 w-6 h-1 mr-3 rounded-full"></span>
                    Certificações
                </h3>
                <ul class="space-y-4">
                    <li class="flex items-center text-slate-300 bg-slate-800/30 p-4 rounded-lg border border-slate-700/50 hover:bg-slate-800/80 transition-colors">
                        <svg class="w-6 h-6 text-teal-400 mr-4 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        <span class="font-medium">Cognizant Cloud Data Engineer</span>
                    </li>
                    <li class="flex items-center text-slate-300 bg-slate-800/30 p-4 rounded-lg border border-slate-700/50 hover:bg-slate-800/80 transition-colors">
                        <svg class="w-6 h-6 text-teal-400 mr-4 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        <span class="font-medium">Banco Carrefour Data Engineer</span>
                    </li>
                </ul>
            </div>

        </div>
    </section>

    <footer class="py-8 text-center text-slate-500 border-t border-slate-800 mt-10">
        <p>© 2026 Fabio Romero. Desenvolvido para a Web.</p>
    </footer>

</body>
</html>
