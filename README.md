### **Quinto Semestre (2024-2)**

# ClimaMonitor – Monitoramento Inteligente de Condições Climáticas para Produtores Rurais

## Descrição do Projeto
**Semestre:** Quinto Semestre – 2024-2  
**Empresa Parceira:** **Kersys**   
**Área de Atuação:** A Kersys é especializada em soluções tecnológicas para gestão florestal e agrícola, oferecendo sistemas informatizados e móveis para otimização de recursos e aumento da competitividade no setor.      
**Professor responsável:** **Jean Carlos**

---

### ![Problem Icon](https://img.shields.io/badge/-Problema-E74C3C?style=flat&logo=issue-tracking&logoColor=white)

O problema que motivou o desenvolvimento do **ClimaMonitor** foi a falta de uma plataforma eficiente de monitoramento climático para produtores rurais, dificultando o acompanhamento preciso das condições climáticas, especialmente em regiões com baixa conectividade. Isso prejudica o planejamento agrícola, como o controle de irrigação e a escolha de plantio e colheita, podendo resultar em perdas financeiras significativas.

---

### ![Solution Icon](https://img.shields.io/badge/-Solução-27AE60?style=flat&logo=solution&logoColor=white)

O **ClimaMonitor** é um aplicativo desenvolvido para dispositivos móveis utilizando **React Native** para garantir a compatibilidade com smartphones e tablets. O backend é implementado utilizando **Node.js** com **MongoDB** para persistência de dados. A integração com fontes externas de dados climáticos será realizada via API, com a utilização do **Power API** da NASA para obter as informações de temperatura e pluviometria. O sistema contará com gráficos interativos de monitoramento climático usando **Chart.js** e notificações de alertas utilizando **Push Notifications** para garantir que os usuários recebam atualizações em tempo real.

---

### **Imagens do Sistema**
#### **[Demonstração do projeto em execução]**

<p align="center">
  <img src="https://raw.githubusercontent.com/tsilvadev89/Portfolio/refs/heads/API5S/img/API5S.jpg" alt="Projeto CLIMA MONITOR" width="800" height="400">
  <br>
</p>

---

### **Link do Repositório Git**  
<a href="https://github.com/FATEC-FULLSTACK/BACKEND-API5S" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white&style=flat-square" alt="GitHub link">
</a>

---

### ![Tech Icon](https://img.shields.io/badge/-Tecnologias%20Utilizadas-3498DB?style=flat&logo=stackshare&logoColor=white)

- ![React Native](https://img.shields.io/badge/-React%20Native-61DAFB?logo=react&logoColor=white&style=flat) **React Native:** Framework utilizado para o desenvolvimento de aplicativos móveis, garantindo compatibilidade com Android e iOS.
- ![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=node.js&logoColor=white&style=flat) **Node.js:** Backend para gerenciamento da API e manipulação de dados em tempo real.
- ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white&style=flat) **MongoDB:** Banco de dados NoSQL utilizado para persistência dos dados climáticos.
- ![Chart.js](https://img.shields.io/badge/-Chart.js-FF6384?logo=chart.js&logoColor=white&style=flat) **Chart.js:** Biblioteca para a criação de gráficos interativos com os dados climáticos.
- ![Push Notifications](https://img.shields.io/badge/-Push%20Notifications-00C853?logo=android&logoColor=white&style=flat) **Push Notifications:** Sistema de notificação para alertar os usuários sobre eventos climáticos críticos.
- ![API Power](https://img.shields.io/badge/-Power%20API-4C9ED9?logo=nasa&logoColor=white&style=flat) **Power API:** API da NASA utilizada para obter dados climáticos precisos e em tempo real.

---

### ![Contribution Icon](https://img.shields.io/badge/-Contribuições%20Pessoais-F39C12?style=flat&logo=contribution&logoColor=white)

Atuei como **desenvolvedor Full Stack**, contribuindo tanto para o frontend quanto para o backend. Minhas principais contribuições incluem:

- Desenvolvimento da interface mobile utilizando **React Native**.
- Implementação do backend utilizando **Node.js** e integração com o banco de dados **MongoDB**.
- Criação dos gráficos interativos com **Chart.js**.
- Implementação do sistema de **Push Notifications** para alertas sobre condições climáticas críticas.
- Modelagem do banco de dados e design da estrutura da API.

---

### ![Hard Skills Icon](https://img.shields.io/badge/-Hard%20Skills-2ECC71?style=flat&logo=skillshare&logoColor=white)

- ![React Native](https://img.shields.io/badge/-React%20Native-61DAFB?logo=react&logoColor=white&style=flat) **React Native:** Desenvolvimento de aplicativos móveis. (Faço/uso com autonomia)
- ![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=node.js&logoColor=white&style=flat) **Node.js:** Desenvolvimento do backend e APIs. (Faço/uso com ajuda)
- ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?logo=mongodb&logoColor=white&style=flat) **MongoDB:** Implementação de banco de dados NoSQL. (Faço/uso com ajuda)
- ![Chart.js](https://img.shields.io/badge/-Chart.js-FF6384?logo=chart.js&logoColor=white&style=flat) **Chart.js:** Criação de gráficos para visualização dos dados climáticos. (Faço/uso com autonomia)
- ![Push Notifications](https://img.shields.io/badge/-Push%20Notifications-00C853?logo=android&logoColor=white&style=flat) **Push Notifications:** Implementação de notificações em tempo real. (Faço/uso com ajuda)

---

### ![Soft Skills Icon](https://img.shields.io/badge/-Soft%20Skills-9B59B6?style=flat&logo=meetup&logoColor=white)

- **Resolução de Problemas:** Durante o desenvolvimento do sistema, identifiquei dificuldades significativas ao utilizar o MongoDB localmente, o que estava impactando a performance do sistema. Após análise, propus a migração para uma plataforma online, o que melhorou a escalabilidade e a confiabilidade da aplicação em produção.
  
- **Adaptação Técnica:** O sistema de login original do React Native não era adequado para aplicações móveis, pois usava cookies, o que não era seguro para autenticação. Após realizar uma análise detalhada, implementei a solução correta utilizando **JSON Web Tokens (JWT)** para garantir a segurança da autenticação em dispositivos móveis, resultando em uma implementação mais robusta e escalável.
  
- **Componentização e Reutilização:** Durante a análise da arquitetura da aplicação, percebi que vários componentes poderiam ser reutilizados em diferentes pontos do sistema. Propus e implementei a componentização desses elementos, aumentando a manutenção e facilitando a expansão do sistema, ao mesmo tempo em que reduzimos o código redundante.
