<p align="center">
    <img width="300px" src="PILHA-~1.PNG">
</p>

<p align="center">
  <h3 align="center">💰 Assistente Financeiro Inteligente – Classificação e Recomendação Personalizada</h3>
Este projeto é um desafio de Engenharia de Prompt, cujo objetivo é criar um assistente virtual capaz de identificar o perfil financeiro do usuário e oferecer orientações personalizadas de acordo com suas necessidades, objetivos, estilo de vida e momento de vida. O assistente atua como um guia financeiro digital, classificando o usuário com base em múltiplas dimensões e, a partir disso, entregando sugestões práticas e alinhadas com seu perfil.
</p>

---

## 📋 Índice

- [📝 Introdução](#-introdução)
- [💡 Resumo da Engenharia de Prompt](#-resumo-da-engenharia-de-prompt)
- [🔎 Objetivo do Projeto](#-objetivo-do-projeto)
- [🧭 Classificações Utilizadas](#-classificações-utilizadas)
  - [1️⃣ Momento de Vida](#1️⃣-momento-de-vida)
  - [2️⃣ Classificação Financeira](#2️⃣-classificação-financeira)
  - [3️⃣ Grau de Educação Financeira](#3️⃣-grau-de-educação-financeira)
  - [4️⃣ Estilo de Vida](#4️⃣-estilo-de-vida)
  - [5️⃣ Objetivos Financeiros](#5️⃣-objetivos-financeiros)
  - [6️⃣ Perfil de Investidor](#6️⃣-perfil-de-investidor)
- [⚙️ Regras de Negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)
- [👤 Autor(a)](#-autora)

---

## 📝 Introdução

A saúde financeira é um pilar essencial para uma vida estável e plena. No entanto, muitas pessoas não sabem por onde começar ou como organizar suas finanças. Este projeto visa facilitar essa jornada, oferecendo um assistente que entende quem você é e onde está na sua vida financeira, para guiar suas decisões de forma clara e personalizada.

---

## 💡 Resumo da Engenharia de Prompt

A **engenharia de prompt** é a técnica utilizada para criar interações entre o usuário e a IA de maneira eficiente, clara e personalizada. No contexto deste projeto, ela será aplicada para entender o perfil financeiro do usuário e gerar recomendações financeiras com base nas informações fornecidas.

- **Identidade**: Definimos quem é o "robô" (assistente financeiro), qual sua função (gerar recomendações financeiras) e sua tonalidade de resposta (clara, direta e personalizada de acordo com o perfil do usuário).
- **Contexto**: A IA precisará de informações sobre o negócio, objetivos do usuário, metas financeiras, e um entendimento claro da realidade financeira do usuário. Isso inclui saber onde o usuário está em sua jornada financeira e qual é o produto/serviço que ele busca.
- **Instruções Personalizadas**: A IA será orientada com instruções específicas para adaptar suas respostas às necessidades do usuário, levando em consideração o objetivo de gerar sugestões financeiras realistas e eficazes.
- **Estrutura de Tomada de Decisão**: A IA será treinada para tomar decisões com base nas classificações e dados fornecidos pelo usuário, garantindo recomendações assertivas e adequadas ao seu perfil financeiro.
- **Regras e Condicionais**: Refine as respostas da IA com base em regras específicas (como tipo de recomendação financeira), ajudando a eliminar respostas imprecisas e bloquear interações indesejadas (técnica de prompt injection).
- **Arquivos de Conhecimento:** Funcionam como uma base de dados complementar, oferecendo informações contextuais para enriquecer as respostas da IA e tornar as recomendações mais precisas e personalizadas.

---

## 🔎 Objetivo do Projeto

Criar um prompt estruturado que permita a um assistente virtual compreender o usuário em múltiplas dimensões, como renda, momento de vida, objetivos e perfil de risco e, a partir disso, gerar recomendações financeiras personalizadas e acessíveis.

---

## 🧭 Classificações Utilizadas

### 1️⃣ Momento de Vida

Ajuda a entender as prioridades e necessidades atuais do usuário.

- **Estudante**: Baixa renda, foco em aprender a poupar e formar reserva.
- **Recém-formado / Início de carreira**: Crescimento profissional e início de investimentos.
- **Casado / União estável**: Novas responsabilidades (casa, filhos), foco em segurança.
- **Com filhos**: Planejamento familiar, reserva de emergência maior.
- **Pré-aposentadoria**: Preservação de capital e renda passiva.
- **Aposentado**: Renda previsível, foco em segurança e liquidez.

---

### 2️⃣ Classificação Financeira

Retrato da situação econômica atual do usuário.

- **Baixa Renda**: Renda mensal baixa, muitas dívidas, nenhum ou poucos investimentos.
- **Renda Média**: Renda estável, algumas dívidas, início ou progresso em investimentos.
- **Renda Alta**: Alta renda mensal, poucas ou nenhuma dívida, carteira de investimentos diversificada.

---

### 3️⃣ Grau de Educação Financeira

Determina o nível de conhecimento financeiro do usuário.

- **Iniciante**: Nunca investiu, precisa de conceitos básicos.
- **Intermediário**: Já investiu em poupança, tesouro, CDB.
- **Avançado**: Já investe em ações, fundos, cripto, etc.

---

### 4️⃣ Estilo de Vida

Ajuda a entender como o usuário lida com consumo e poupança.

- **Minimalista**: Prefere simplicidade, gasta pouco.
- **Consumista**: Tem dificuldade de guardar dinheiro.
- **Equilibrado**: Gosta de gastar, mas sabe economizar.
- **Investidor nato**: Já vive pensando em oportunidades.

---

### 5️⃣ Objetivos Financeiros

Personaliza as recomendações com base em metas pessoais.

- **Reserva de emergência**
- **Viagem**
- **Compra de imóvel**
- **Aposentadoria**
- **Abrir um negócio**
- **Educação dos filhos**
- **Independência financeira**

---

### 6️⃣ Perfil de Investidor

Determina o nível de risco que o usuário está disposto a aceitar.

- **Conservador**: Baixa tolerância ao risco, foco na segurança do capital.
- **Moderado**: Aceita algum risco para buscar equilíbrio entre segurança e rentabilidade.
- **Arrojado**: Alta tolerância ao risco, busca por altos retornos no longo prazo.

---

## ⚙️ Regras de Negócio

1. **Classificar o usuário em cada uma das seis categorias** acima.
2. **Cruzar os dados entre as classificações** para entender o momento e a realidade da pessoa.
3. **Gerar recomendações realistas, com linguagem compatível com o nível de educação financeira.**
4. **Adaptar sugestões conforme o estilo de vida e objetivos de curto, médio e longo prazo.**

---

## 📖 Materiais de Apoio

- [Otimize seus Prompts e Aprenda Mais Usando IAs – Aline Antunes](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)
- [Engenharia de Prompt: O Guia Definitivo – Bruno Picinini (Notion)](https://www.notion.so/030fc2e2d1a1479ea0e8f0c25b1d537a?pvs=21)
- [Fundamentos de Engenharia de Prompt com Claude 3 – Elidiana Andrade](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Strategy: Split complex tasks into simpler subtasks – OpenAI](https://platform.openai.com/docs/guides/prompt-engineering/strategy-split-complex-tasks-into-simpler-subtasks)

---

## 🧠 Prompt de Resposta Proposto

> "Com base nas informações fornecidas pelo usuário sobre sua **renda**, **perfil de investidor** e **objetivos financeiros**, elabore uma recomendação de investimento personalizada. A recomendação deve considerar o **nível de educação financeira** do usuário, o **estilo de vida** (se ele for minimalista, consumista ou equilibrado), e sugerir um plano de ação com **tipos de investimentos** que se adequem ao seu perfil. Utilize uma linguagem simples e objetiva, adequada ao nível de entendimento do usuário."
> 

---

## 👤 Autor(a)

Este projeto foi desenvolvido por **Camila** como parte de seus estudos em Engenharia de Prompt e IA aplicada à educação financeira.
