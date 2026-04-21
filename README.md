# Caderno Temático: O Ecossistema de Agentes de IA 🤖

## 📝 Contexto e Objetivos
Este repositório foi criado como parte de um desafio de projeto para a **DIO (Digital Innovation One)**. O foco central deste estudo é a exploração de **Agentes de Inteligência Artificial**, indo além dos modelos de chat tradicionais para entender sistemas autônomos que planejam, executam ferramentas e tomam decisões para atingir objetivos complexos usando a ferramenta NotebookLm da Google, que garante que a Inteligência Artificial não gere respostas inventadas.

**Objetivos de estudo:**
* Compreender a arquitetura fundamental de um agente de IA (Raciocínio, Memória e Ferramentas).
* Analisar as principais frameworks de desenvolvimento (como LangChain, CrewAI ou n8n).
* Explorar casos de uso práticos para automação de fluxos de trabalho.
* Verificar se a IA consegue ajudar pessoas leigas

## 📚 Curadoria de Fontes
Para alimentar o NotebookLM e garantir a base do conhecimento, foram selecionadas as seguintes fontes de alta qualidade:

1. **Youtube** - Build AI Agents with GPT-5 (No Code Required!) - [[Link ou Referência]](https://www.youtube.com/watch?v=kIw8eur4kK4)
2. **Youtube** - STOP Building Dumb AI Agents – Do This Instead - [[Link ou Referência]](https://www.youtube.com/watch?v=KHc0ClOIv0A)
3. **Codeloom Technologies** - AI Agents for Business Automation in 2025: Use Cases, Stack, and ROI - [[Link ou Referência]](https://codeloomtechnologies.com/blogs/ai-agents-business-automation-2025/)
4. **Pe Collective** - AI Agent Frameworks 2026 - LangChain, CrewAI & AutoGen Compared - [[Link ou Referência](https://pecollective.com/blog/ai-agent-frameworks-compared/)]

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Nesta seção, documento o raciocínio utilizado para interagir com a IA e extrair as melhores respostas.

### Prompts Testados:
* **Tentativa 1 (Básico):** "Como posso fazer meu primeiro agente de IA"
    * *Resultado:* IA responde bem dando dicas sobre como construir o primeiro agente, semrpe referenciando onde buscou as informações:
      <img width="956" height="648" alt="image" src="https://github.com/user-attachments/assets/f28c58f1-90e1-40b0-b221-d985cc9852c4" />
      <img width="956" height="661" alt="image" src="https://github.com/user-attachments/assets/2ee591e1-9470-4b4f-a8c0-2db6a20968b1" />
      <img width="956" height="415" alt="image" src="https://github.com/user-attachments/assets/7b9f0144-568a-4c6c-a11b-9d52704d86f1" />

* **Tentativa 2 (Estratégico):** "Atue como um Arquiteto de Soluções. Com base nas fontes de dados fornecidas, explique a diferença técnica entre um chatbot RAG simples e um Agente de IA capaz de usar ferramentas (Tool Use)."
    * *Resultado:* IA respondeu de uma forma bem estruturada e didática, trouxe detalhes sobre o loop de raciocínio (Reasoning Loop).
      <img width="956" height="647" alt="image" src="https://github.com/user-attachments/assets/5b37a46f-45da-4dd9-aa55-d86dddc512c0" />
      <img width="956" height="647" alt="image" src="https://github.com/user-attachments/assets/f9b7add1-6e99-485b-b87d-10d270b71d6b" />
      <img width="956" height="647" alt="image" src="https://github.com/user-attachments/assets/1cac237a-e6d4-4f73-975b-8a5aa9f9d504" />


### Dificuldades Encontradas ("Cicatrizes"):
* **Alucinação de Contexto:** Em certos momentos, a IA não estava se comunicando como um instrutor. O papel desse notebook é justamente ajudar pessoas com dificuldade em IA e tecnologia entenderem melhor sobre o assunto e aplicarem. 
* **Solução:** Incluí uma fonte de dados em texto com um prompt ajustando o comportamento dela, tanto nas explicações, quanto na organização da repsosta.
* **Refinamento:** Percebi que detalhar o comportamento da IA mudou drasticamente a profundidade técnica das respostas.

## 📖 Miniguia de Estudo (Entrega Final)

### Resumo Estruturado
Os Agentes de IA representam a evolução da IA Generativa. Enquanto um LLM comum apenas processa texto, um Agente possui:
* **Planejamento:** Capacidade de quebrar tarefas grandes em subtarefas.
* **Memória:** Uso de histórico de curto prazo e bases de vetores para longo prazo.
* **Uso de Ferramentas:** Capacidade de chamar APIs, fazer buscas na web ou executar código.

Isso ajuda muito interna e externamente. Agente podem automatizar tarefas que exigem muito tempo e que são repetitivas. Um bom exemplo é solicitar relatórios, conferindo os dados para verificar se estão certos, ou até mesmo apresentações, vídeos, entre outros. No meu notebook utilizei as ferramentas de Studio e fiquei impressionada com a qualidade. Também ajuda aos clientes, usuários comuns, não só no aprendizado, mas gerando também preferência por empresas que se adaptam ao mercado atual, aproveitando os benefícios que esse agentes trazem.

### Glossário de Conceitos Aprendidos
* **Reasoning (Raciocínio):** O processo da IA para decidir o próximo passo (ex: Chain of Thought).
* **Orquestração:** Gerenciamento de múltiplos agentes trabalhando juntos.
* **Autonomia:** O grau em que o agente pode operar sem intervenção humana constante.

### Prompts Reutilizáveis para Revisão
> *"O que é um agente de IA?"*
> *"Crie um checklist de automatizações para um agente de suporte técnico baseado nas fontes estudadas."*
> *"Gere um relatório com as principais ferramentas de criação de agentes de IA atuais."*



✨ **Projeto desenvolvido por [Daniela Thais] para a comunidade DIO.**
[Confira o Notebook aqui](https://notebooklm.google.com/notebook/01e597f2-ac8c-42f5-be72-22efc370a86b)

Aqui deixo um vídeo mostrando brevemente o Notebook.
https://youtu.be/G-yW7MyWd7E
