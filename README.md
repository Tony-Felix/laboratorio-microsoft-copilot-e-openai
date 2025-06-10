# laboratorio-microsoft-copilot-e-openai

# 💡 Exploração do Microsoft Copilot (Bing)

Este repositório faz parte do desafio da DIO sobre IA Generativa com foco no uso do **Microsoft Copilot**, acessado via [https://copilot.microsoft.com](https://copilot.microsoft.com).

---

## 🔹 1. Acesso à Plataforma

- Acesse o site: [https://copilot.microsoft.com](https://copilot.microsoft.com)
- Fiz login com minha conta Microsoft para desbloquear recursos completos, como histórico de chat e geração de imagens

---

## 🔹 2. Primeira Interação – Previsão do Tempo

**Prompt usado:**
Qual é a previsão do tempo para Rio de Janeiro na próxima semana?

**Resposta:**
> “A previsão para São Paulo inclui temperaturas entre 18°C e 27°C, com chuvas entre quarta e sexta-feira. Segunda e terça serão ensolaradas...”

**Observação:**
Resposta clara, baseada em fontes confiáveis, útil para planejamento semanal.

## 🔹 3. Segunda Interação – Apoio Acadêmico

**Prompt usado:**
Resuma os principais conceitos sobre aprendizado de máquina supervisionado para um trabalho da faculdade.


**Resposta:**
> “Aprendizado supervisionado é um tipo de machine learning onde o modelo é treinado com dados rotulados. Os algoritmos mais comuns incluem regressão linear, árvores de decisão e SVM...”

**Observação:**
Utilizei a resposta como base para um trecho do meu trabalho acadêmico sobre IA.

---

## 🔹 4. Terceira Interação – Geração de Imagem

**Prompt usado:**
Crie uma imagem de um estudante estudando programação à noite com um notebook e livros ao redor.

**Resposta:**
Imagem gerada por IA com estilo digital, mostrando um estudante concentrado, notebook iluminado e livros empilhados.

**Uso prático:**
Utilizei a imagem como ilustração de capa para meu relatório acadêmico sobre "IA Generativa na Educação".

# Uso do Azure AI Foundry

### ✅ Etapas Realizadas

#### 🔹 1. Acesso ao Portal
- Acessei: [https://ai.azure.com](https://ai.azure.com)
- Realizei login com minha conta da Microsoft.
- Fechei os painéis de ajuda e naveguei até a tela inicial clicando no logotipo **Azure AI Foundry**.

---

#### 🔹 2. Criação de Projeto com o GPT-4o
- Na seção **"Explore models and capabilities"**, pesquisei por `gpt-4o`.
- Cliquei em **Use this model**.
- Criei um novo projeto com as seguintes configurações:
  - **Nome do projeto**: `HistoryGPT`
  - **Azure AI Foundry resource**: `HistoryGPT-resource`
  - **Subscription**: conta gratuita do Azure
  - **Resource group**: `history-ai`
  - **Region**: `East US`
- Cliquei em **Create** e aguardei a criação do projeto e deployment do modelo.

---

#### 🔹 3. Playground: Primeiro Teste com IA
O **Chat Playground** foi aberto automaticamente.

- No campo de instruções do modelo, configurei:

You are a history teacher who can answer questions about past events all around the world.

- Enviei o prompt:
> What are the key events in the history of Scotland?

- A resposta incluiu eventos como:
- As guerras de independência da Escócia
- O reinado de Mary, Queen of Scots
- A união dos reinos em 1707

---

#### 🔹 4. Exploração dos Recursos do Projeto
- Acesse a aba **Overview** para ver os detalhes do projeto, como endpoints e chaves de API.
- Acesse o **Management Center** para visualizar recursos e permissões.
- Cliquei no link do **Resource Group** e visualizei os recursos criados diretamente no portal do Azure.

---

# Content Filters no Azure AI Foundry

Explicação:
Não foi possível acessar os filtros de conteúdo conforme descrito na atividade, pois essa funcionalidade é restrita a contas corporativas. Usuários individuais não têm permissão para criar ou editar filtros personalizados no Azure AI Foundry, o que inviabiliza a execução completa da simulação.
