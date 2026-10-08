# Repositório — Programação Web (Fatec Ipiranga)

Este repositório contém os códigos e projetos desenvolvidos durante as aulas da disciplina de **PWEB** (Programação Web) na **Fatec Ipiranga** (Semestre 2025/2).  
O foco principal deste projeto é o estudo prático e a criação de aplicações web modernas, abordando desde os fundamentos de estruturação e estilização até o desenvolvimento de rotas backend, manipulação de formulários e integração com serviços web.

---

## Funcionalidades e Tópicos Abordados

* **Estruturação e Estilização Web:** Desenvolvimento de interfaces semânticas utilizando HTML5, CSS3 responsivo e layouts modernos (Flexbox e Grid).
* **Manipulação do DOM e JavaScript:** Criação de dinamismo do lado do cliente (*client-side*), validação de formulários e manipulação de eventos em tempo real.
* **Desenvolvimento de Servidores Web:** Criação de servidores e APIs RESTful com Node.js e Express para gerenciamento de requisições e rotas.
* **Consumo de APIs e Requisições Assíncronas:** Comunicação assíncrona entre cliente e servidor através de `fetch` e `axios` (AJAX/Promises).
* **Persistência de Dados e Sessões:** Introdução ao armazenamento local no navegador (LocalStorage/SessionStorage) e gestão de dados em formulários.

---

## Arquitetura e Estrutura dos Arquivos

O repositório está dividido conceitualmente entre as camadas de apresentação, lógica do servidor e arquivos estáticos:

| Arquivo / Diretório | Descrição |
| :--- | :--- |
| `public/` | Arquivos estáticos da aplicação (HTML, CSS, imagens e scripts do lado do cliente). |
| `src/routes/` | Definição das rotas e endpoints da aplicação web. |
| `src/controllers/` | Lógica de processamento das requisições web e renderização de respostas. |
| `package.json` | Arquivo de manifesto do Node.js contendo as dependências do projeto e scripts de execução. |
| `.env` | (Omitido do controle de versão) Arquivo de parametrização para portas do servidor e chaves de configuração. |

---

## Aprendizado Progressivo de Conceitos

Através do desenvolvimento dos módulos e exercícios práticos, foi possível consolidar uma evolução clara de conceitos essenciais para o ecossistema Web Fullstack:

### 1. Interfaces Responsivas e Semântica
* **Semântica HTML5 e CSS:** Compreensão da estrutura acessível e estilização responsiva adaptável a múltiplos tamanhos de dispositivos.
* **Componentização e Reutilização:** Organização de elementos visuais e scripts para garantir facilidade de manutenção.

### 2. Fluxo Cliente-Servidor
* **O Problema (Páginas Estáticas):** A limitação em criar experiências dinâmicas e persistir dados apenas no lado do cliente sem comunicação com um backend.
* **A Solução (Servidores Express e APIs):** Construção de endpoints no Node.js/Express para receber dados do cliente, processar regras de negócio e devolver respostas estruturadas em JSON ou HTML.

### 3. Integração Assíncrona e Segurança
* **Requisições HTTP Assíncronas:** Uso de Promises e `async/await` para buscar e enviar dados sem interromper a navegação do usuário.
* **Variáveis de Ambiente (`dotenv`):** Isolamento de portas e configurações de servidor via `process.env`, prevenindo a exposição de dados sensíveis no repositório através do `.gitignore`.

---

## Como Executar o Projeto de PWEB

### Pré-requisitos
* **Node.js** instalado na máquina.
* Navegador web moderno (Chrome, Firefox, Edge).

### Passos para configuração e execução:

1. **Acesse o diretório do projeto:**
   ```bash
   cd 20252_fatec_ipi_pweb

2. **Instale as dependências do pacote:**
   ```bash
   npm install

3. **Configure as Variáveis de Ambiente:**

   Crie um arquivo chamado .env na raiz do projeto e preencha com as suas configurações:
   ```bash
   PORT=3000
   NODE_ENV=development


4. **Execute a aplicação:**

   
   ```bash
   Para rodar com monitoramento contínuo (modo dev):
   npm run dev

   Para rodar no modo padrão:
   npm start

