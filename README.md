### Sexto Semestre (2025-1)

# Plataforma de Treinamento de IA — Comparação e Avaliação de LLMs com Feedback Humano

## Descrição do Projeto
**Semestre:** Sexto Semestre – 2025-1  
**Empresa Parceira:** Dom Rock  
**Área de Atuação:** A Dom Rock oferece serviços ágeis de diagnóstico e análise na implementação de soluções e agentes de IA de acordo com as estratégias e demandas das áreas de negócio.  
**Professor responsável:** **José Walmir Gonçalves Duque** (P2)  
**Contato do Parceiro:** Andre F. de Almeida

---

### ![Problem Icon](https://img.shields.io/badge/-Problema-E74C3C?style=flat&logo=issue-tracking&logoColor=white)

Com a crescente adoção de modelos de linguagem (LLMs) em setores como saúde, jurídico e análise de risco, empresas como a Dom Rock enfrentam o desafio de garantir que esses modelos entreguem respostas coerentes, confiáveis e adaptadas ao seu contexto de atuação.

Entretanto, a simples integração de modelos genéricos não supre essa necessidade, visto que muitos desses LLMs apresentam limitações de veracidade, imparcialidade e naturalidade, impactando negativamente a credibilidade das análises geradas e a experiência do usuário final.

Além disso, sem mecanismos estruturados de coleta de feedback humano, torna-se inviável realizar ajustes finos nos modelos por meio de técnicas como RLHF (Reinforcement Learning with Human Feedback), o que compromete a evolução contínua dessas soluções.

---

### ![Solution Icon](https://img.shields.io/badge/-Solução-27AE60?style=flat&logo=solution&logoColor=white)

A equipe desenvolveu uma **Plataforma de Treinamento de IA**, que permite:

- Comparação entre respostas geradas por diferentes LLMs (como OpenAI, Gemini, DeepSeek, Grog).
- Avaliação das respostas com base em critérios definidos (ex: coerência, naturalidade, veracidade).
- Registro e análise de feedback humano, com uso de RLHF (Reinforcement Learning with Human Feedback).
- Interface responsiva e acessível desenvolvida com Vue.js e prototipada no Figma.
- Backend robusto em FastAPI, com Langchain e integração com banco vetorizado.


### **Imagens do Sistema**
#### **[Demonstração do projeto em execução]**

<p align="center">
  <img src="https://github.com/tsilvadev89/Portfolio/blob/API6S/img/RespostaLLMsAPI6s.jpg" alt="Interface da Plataforma" width="800" height="400">
  <br>
</p>

---

### **Link do Repositório Git**  
<a href="https://github.com/FATEC-FULLSTACK/API6" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white&style=flat-square" alt="GitHub link">
</a>

---

### ![Tech Icon](https://img.shields.io/badge/-Tecnologias%20Utilizadas-3498DB?style=flat&logo=stackshare&logoColor=white)

- ![Vue.js](https://img.shields.io/badge/-Vue.js-42b883?logo=vue.js&logoColor=white&style=flat) **Vue.js**: Desenvolvimento da interface frontend com foco em responsividade.
- ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white&style=flat) **FastAPI**: Backend ágil com endpoints assíncronos e integrados ao Langchain.
- ![Langchain](https://img.shields.io/badge/-Langchain-3eaf7c?logo=openai&logoColor=white&style=flat) **Langchain**: Orquestração das respostas LLMs e integração com sistemas RAG.
- ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white&style=flat) **MongoDB**: Armazenamento NoSQL das avaliações e logs de uso.
- ![Figma](https://img.shields.io/badge/-Figma-F24E1E?logo=figma&logoColor=white&style=flat) **Figma**: Protótipos e validação de usabilidade.
- ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat) **Python**: Linguagem base do backend e lógica de avaliação de feedback.

---

### ![Contribution Icon](https://img.shields.io/badge/-Contribuições%20Pessoais-F39C12?style=flat&logo=contribution&logoColor=white)

Atuei como **desenvolvedor full stack**, com foco em backend e integração com LLMs. Minhas principais contribuições:

- Criação da API com FastAPI, endpoints de avaliação e persistência dos dados com MongoDB.
- Integração do Langchain com múltiplos modelos (GPT-4, Gemini) e configuração do pipeline de comparação.
- Lógica de formatação e exibição de respostas comparativas, com destaque para critérios avaliativos.
- Suporte à interface Vue.js com endpoints de consulta e feedback assíncrono.
- Participação ativa na prototipagem via Figma e validação com usuários.

---

### ![Hard Skills Icon](https://img.shields.io/badge/-Hard%20Skills-2ECC71?style=flat&logo=skillshare&logoColor=white)

- ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white&style=flat) **FastAPI**: Desenvolvimento e organização de rotas backend. (Faço/uso com autonomia)
- ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white&style=flat) **MongoDB**: Estruturação de coleções e índices para feedback e sessões. (Faço/uso com ajuda)
- ![Langchain](https://img.shields.io/badge/-Langchain-3eaf7c?logo=openai&logoColor=white&style=flat) **Langchain**: Encadeamento de prompts e análise de respostas. (Faço/uso com ajuda)
- ![Vue.js](https://img.shields.io/badge/-Vue.js-42b883?logo=vue.js&logoColor=white&style=flat) **Vue.js**: Interface dinâmica para entrada de prompts e avaliação. (Faço/uso com ajuda)
- ![Figma](https://img.shields.io/badge/-Figma-F24E1E?logo=figma&logoColor=white&style=flat) **Figma**: Criação de protótipos validados em entrevistas com usuários. (Faço/uso com autonomia)

---

### ![Soft Skills Icon](https://img.shields.io/badge/-Soft%20Skills-9B59B6?style=flat&logo=meetup&logoColor=white)

- **Pensamento Crítico:** Durante o desenvolvimento, fui responsável por avaliar criticamente a metodologia inicial de comparação entre respostas dos LLMs. Propus uma reformulação nos critérios de avaliação — que antes eram subjetivos — para indicadores objetivos baseados em rubricas, o que resultou em dados mais confiáveis e reutilizáveis para futuros retreinamentos dos modelos com RLHF.
- **Resolução de Conflitos:** No momento em que a equipe se dividiu entre usar somente o modelo OpenAI ou permitir múltiplas opções, conduzi reuniões técnicas demonstrando, com dados e simulações, os benefícios de manter um pipeline modular de LLMs. Essa medida tornou o projeto multivariável no qual a resposta de cinco llms são processadas de forma sortida na qual a velocidade é primordial para exibição ao usuário final.
- **Adaptabilidade:** Ao longo do projeto, enfrentamos limitações técnicas com a API de um dos LLMs escolhidos (limite de requisições e instabilidade). Rapidamente, adaptei o backend para suportar fallback automático entre modelos, sem necessidade de reescrita da lógica principal. Essa capacidade de adaptação garantiu a continuidade dos testes e a robustez da plataforma.
- **Liderança:** Atuei como líder técnico no desenvolvimento backend, orientando colegas sobre integração de API REST e MongoDB, além de organizar as sprints usando princípios do SCRUM. Também assumi a responsabilidade de entregar a documentação técnica do backend em linha com boas práticas do mercado.
- **Resiliência:** Em fases críticas do projeto, como na homologação do sistema e resolução de bugs intermitentes nas avaliações, mantive foco e consistência, mesmo sob pressão e prazos apertados. Essa resiliência contribuiu diretamente para a entrega final estável e funcional.
---

### ![Video Icon](https://img.shields.io/badge/-Vídeo%20Tutorial-FF0000?style=flat&logo=youtube&logoColor=white)

Um vídeo tutorial foi produzido para demonstrar o uso da plataforma por usuários com ou sem familiaridade técnica. [Acesse o vídeo aqui](https://www.youtube.com/watch?v=C3ySkVufNRI).

---
