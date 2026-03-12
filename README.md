AI Copilots System

Um sistema de copilotos de inteligência artificial especializados, criado para auxiliar desenvolvedores em diferentes etapas do desenvolvimento de software: aprendizado, planejamento, análise de código e execução de tarefas.

O projeto implementa diferentes modos de assistência, onde cada copiloto possui um comportamento específico para tornar a interação com IA mais organizada e eficiente.

📚 Sobre o Projeto

Durante o desenvolvimento de software, usamos IA para várias tarefas diferentes:

aprender conceitos

planejar arquitetura

resolver bugs

gerar código

Normalmente tudo acontece no mesmo chat, o que pode gerar respostas confusas.

Este projeto resolve esse problema criando copilotos especializados, cada um com uma função clara.

Assim, o desenvolvedor pode escolher qual tipo de ajuda precisa no momento.

🧠 Copilotos Disponíveis
🔎 ASK Mode — Technical Consultant

Modo focado em análise e explicação.

O copiloto funciona como um consultor técnico, ajudando a entender código e resolver dúvidas.

Funções:

explicar código

diagnosticar erros

sugerir melhorias

responder dúvidas técnicas

⚠️ Não altera código automaticamente.

⚙️ Agent Mode — Development Assistant

Modo voltado para execução e criação de código.

O copiloto atua como um assistente de desenvolvimento, ajudando a implementar funcionalidades.

Funções:

gerar código

sugerir implementações

criar estruturas de projeto

auxiliar no desenvolvimento de features

📖 Study Mode — Learning Assistant

Modo focado em aprendizado técnico.

O copiloto explica conceitos de forma didática para ajudar desenvolvedores a evoluírem suas habilidades.

Funções:

explicar conceitos de programação

ensinar segurança da informação

explicar frameworks e tecnologias

fornecer exemplos práticos

🧩 Plan Mode — Project Planner

Modo dedicado ao planejamento de projetos e arquitetura.

Ajuda a estruturar projetos antes da implementação.

Funções:

criar roadmap de desenvolvimento

planejar arquitetura de software

dividir tarefas em etapas

organizar backlog

🏗 Arquitetura do Projeto

Estrutura sugerida do projeto:

ai-copilots-system
│
├── prompts
│   ├── ask.md
│   ├── agent.md
│   ├── study.md
│   └── plan.md
│
├── src
│   ├── index.js
│   └── config.js
│
├── docs
│   └── architecture.md
│
└── README.md

Cada copiloto possui instruções próprias, permitindo comportamentos diferentes da IA.

💻 Tecnologias Utilizadas

JavaScript

Node.js

HTML

CSS

APIs de Inteligência Artificial
