# Olá, sou o Caio Souza

<p align="left">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" />
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/Maestro-000000?style=for-the-badge&logo=android&logoColor=white" alt="Maestro" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
</p>

Sou estudante de Engenharia de Computação e Desenvolvedor de Software focado em arquitetura de backend, sistemas distribuídos, desenvolvimento mobile, engenharia de dados e entrega de software assistida por inteligência artificial.

Minha prática de engenharia se concentra em compreender a fundo o comportamento de sistemas complexos. Trabalho sistematicamente com fluxos modernos de engenharia com IA, utilizando ferramentas como Claude, Codex e Antigravity em ambientes orientados a especificações (Spec-Driven Development, ou SDD). Desenvolvo servidores customizados no protocolo MCP (Model Context Protocol) e arquiteturas RAG (Retrieval-Augmented Generation) para manter o código gerado por IA estritamente alinhado a contratos de sistema, especificações verificáveis e baterias de testes de regressão.

---

## Filosofia de Engenharia

- **Fronteiras bem definidas:** Desacoplar regras de domínio da infraestrutura e das camadas de apresentação, mantendo os sistemas modulares, fáceis de testar e resilientes a mudanças.
- **Rigor orientado a especificações:** Estabelecer especificações verificáveis, esquemas e contratos de interface antes da implementação, guiando ferramentas automatizadas e agentes de código com precisão.
- **Decisões orientadas por evidências:** Fundamentar escolhas arquiteturais em análise de desempenho (profiling), testes automatizados e métricas operacionais observáveis, evitando suposições.
- **Privacidade e segurança por concepção:** Integrar proteção de dados, controle de acessos e sanitização de logs como requisitos fundamentais de arquitetura desde a primeira etapa.
- **Confiabilidade e observabilidade:** Estruturar recuperação previsível de erros nos serviços e padronizar o contexto de rastreamento para tornar o diagnóstico de incidentes ágil e direto.

---

## Principais Áreas de Foco

- **Sistemas Distribuídos e Microsserviços:** Construção de pipelines assíncronos de ingestão de dados, coordenação de comunicação entre serviços e padronização de rastreamento distribuído entre fronteiras de sistemas.
- **Engenharia Mobile e Interfaces:** Desenvolvimento de aplicações móveis multiplataforma com React Native e Expo, estruturação de arquiteturas offline-first e automação de testes de ponta a ponta (E2E) com Maestro.
- **Engenharia de Dados e Análise:** Desenvolvimento de pipelines de ingestão em streaming, estruturação de análises tabulares com Pandas e NumPy, análise exploratória com Jupyter e visualização gráfica com Matplotlib.
- **Sistemas de IA e Engenharia com Agentes:** Implementação de fluxos de Spec-Driven Development (SDD), construção de servidores Model Context Protocol (MCP) e arquiteturas RAG para potencializar a entrega de software com Claude, Codex e Antigravity.
- **Privacidade de Dados e Informática em Saúde:** Proteção de dados sensíveis de usuários, adequação técnica a regulamentações como a LGPD e engenharia de pipelines de dados em streaming para processamento de grandes bases públicas.

---

## Estudos de Caso de Engenharia em Destaque

Estudos arquiteturais detalhados categorizados por trilhas técnicas no repositório [**`case-studies`**](https://github.com/Fcsscoder/case-studies):

### [1. Motor Gráfico de Matrizes Curriculares e Quadro Branco Colaborativo](https://github.com/Fcsscoder/case-studies/tree/main/fullstack-and-monorepos/academic-curriculum-dag-whiteboard)
*TypeScript, React 19, Express, Prisma, PostgreSQL, MinIO, Docker, Zod*
- Estruturação de monorepo TypeScript que modela matrizes curriculares acadêmicas como grafos acíclicos dirigidos (DAGs) interativos.
- Implementação de pipeline idempotente de ingestão de analytics com travas de concorrência em banco de dados e relatórios de coorte.
- Concepção de fila write-behind com escritor único para quadro branco colaborativo, desacoplando a renderização de traços da persistência no banco de dados para garantir taxa contínua de 60 FPS de desenho.

### [2. Biblioteca de Rastreamento Distribuído e Logs Estruturados para Node.js](https://github.com/Fcsscoder/case-studies/tree/main/backend-and-distributed-systems/distributed-observability-lib)
*TypeScript, Node.js, Pino, Axios, AsyncLocalStorage*
- Autoria de biblioteca leve de observabilidade distribuída para padronizar registros de log em microsserviços internos.
- Propagação de cabeçalhos de correlação (`X-Correlation-Id`, `X-Installation-Id`) através de callbacks assíncronos e chamadas de clientes HTTP.
- Engenharia de filtragem inteligente de health checks que silencia sondagens rotineiras 200 OK enquanto preserva a telemetria diagnóstica completa diante de serviços com degradação.

### [3. Ingestão Escalável de Prontuários Clínicos e Sanitização de Dados Sensíveis (PII)](https://github.com/Fcsscoder/case-studies/tree/main/data-engineering-and-privacy/clinical-record-pii-sanitization)
*Python, Flask, PostgreSQL, Docker, Nginx*
- Refatoração de pipelines de saúde para expurgar dados de identificação pessoal (PII) de rotas, parâmetros de consulta e logs de acesso de servidores web.
- Engenharia de pipeline de ingestão de arquivos CSV em streaming baseada em geradores, processando cadastros volumosos com consumo de memória plano e previsível para evitar sobrecarga.
- Otimização de consultas relacionais por meio de índices compostos, identificadores normalizados e rotinas automatizadas de estratificação de risco clínico.

### [4. Microsserviço de Gestão de Identidade e Acesso com Arquitetura Hexagonal](https://github.com/Fcsscoder/case-studies/tree/main/backend-and-distributed-systems/hexagonal-auth-service)
*TypeScript, Node.js, Express, PostgreSQL, JWT, Mutation Testing*
- Arquitetura de microsserviço de IAM adotando o padrão Hexagonal (Ports and Adapters), mantendo as regras de negócio puras e isoladas de frameworks web e clientes de banco.
- Tratamento de condições de corrida na invalidação de sessões durante renovações concorrentes de tokens, aplicando travas de sincronização na rotação de refresh tokens.
- Validação de regras de autorização e barreiras de controle multi-inquilino (multi-tenant) com baterias de testes de mutação para certificar a integridade de fluxos condicionais.

### [5. Pipeline Tolerante a Falhas para Ingestão de Documentos e Gateway Blindado](https://github.com/Fcsscoder/case-studies/tree/main/backend-and-distributed-systems/fault-tolerant-ingestion-gateway)
*Python 3, PyPDF, Node.js, Express, Docker Compose, Nginx, MongoDB*
- Desenvolvimento de rotina de extração acompanhada por 31 testes de regressão automatizados para interpretar tabelas e layouts complexos em documentos PDF de várias colunas.
- Definição de contratos de posse exclusiva para impedir que sincronizações automatizadas sobreponham correções manuais efetuadas pela equipe técnica.
- Blindagem de gateway reverso com controle de picos de tráfego (burst limits), restrições de concorrência e proteção em nível de rota contra tráfego anômalo.

### [6. Aplicativo Mobile de Rastreamento de Frotas com Preservação de Privacidade](https://github.com/Fcsscoder/case-studies/tree/main/mobile-engineering/campus-mobility-transit-app)
*React Native, Expo, TypeScript, NativeWind, Android Exact Alarms*
- Desenvolvimento de aplicativo mobile multiplataforma voltado ao acompanhamento em tempo real e roteirização de linhas de transporte coletivo.
- Construção de indicador visual vetorial (SVG) com animação pulsante suave na origem, projetado com respeito às configurações de acessibilidade de movimento reduzido do sistema operacional.
- Criação de barreira técnica de consentimento que restringe chamadas de rede e telemetria em segundo plano até a confirmação formal do usuário.

---

## Stack Técnica

| Domínio | Tecnologias e Ferramentas |
|---|---|
| **Linguagens e Ambientes** | TypeScript, JavaScript, Python 3, C++ (Embarcados/Arduino), SQL |
| **Backend e Microsserviços** | Node.js, Express.js, Flask, Prisma ORM, Hexagonal Architecture, Zod, APIs RESTful |
| **Frontend e Mobile** | React, React Native, Expo, Next.js (App Router), Tailwind CSS, NativeWind, TanStack Query |
| **Dados e Armazenamento** | Pandas, NumPy, Matplotlib, Jupyter, PostgreSQL, MongoDB, SQLite, Turso (libSQL), MinIO |
| **IA e Engenharia com Agentes** | Spec-Driven Development (SDD), Model Context Protocol (MCP), RAG, Claude, Codex, Antigravity |
| **Testes e Qualidade** | Maestro (Mobile E2E), Playwright, Jest, Vitest, Pytest, Testes de Mutação |
| **DevOps e Infraestrutura** | Docker, Docker Compose, Nginx, GitHub Actions, GHCR, VPS Linux, Cosign, Trivy, Git |
| **Mensageria e Telemetria** | MQTT (Mosquitto), Socket.IO (WebSockets), Server-Sent Events (SSE), Pino |

---

## Navegue pelos Estudos de Caso por Trilha

Explore os estudos de caso técnicos no repositório [**`Fcsscoder/case-studies`**](https://github.com/Fcsscoder/case-studies):

- [**Backend e Sistemas Distribuídos**](https://github.com/Fcsscoder/case-studies/tree/main/backend-and-distributed-systems)
- [**Engenharia Mobile**](https://github.com/Fcsscoder/case-studies/tree/main/mobile-engineering)
- [**Frontend e Aplicações Web**](https://github.com/Fcsscoder/case-studies/tree/main/frontend-and-web-apps)
- [**Engenharia de Dados e Privacidade**](https://github.com/Fcsscoder/case-studies/tree/main/data-engineering-and-privacy)
- [**Full-Stack e Monorepos**](https://github.com/Fcsscoder/case-studies/tree/main/fullstack-and-monorepos)
- [**Sistemas Embarcados e IoT**](https://github.com/Fcsscoder/case-studies/tree/main/embedded-systems-and-iot)

---

## Contato

- GitHub: [@Fcsscoder](https://github.com/Fcsscoder)
- Email: [caiotosousa43@gmail.com](mailto:caiotosousa43@gmail.com)
