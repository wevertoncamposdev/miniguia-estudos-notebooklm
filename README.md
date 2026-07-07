# Miniguia de Estudos: Currículo de Referência em Tecnologia e Computação

Este repositório foi desenvolvido como parte de um desafio prático da **DIO (Digital Innovation One)**, com o objetivo de criar um **Caderno Temático** utilizando o **NotebookLM** do Google. A proposta é aliar curadoria de conteúdo de qualidade, pensamento crítico e engenharia de prompts para construir uma ferramenta de aprendizado ativa e estruturada.

---

## 🎯 1. Contexto e Objetivos

### Escolha do Tema
*   **Tema Escolhido:** Currículo de Referência em Tecnologia e Computação
*   **Por que este tema?** Este tema é vital pois capacita o professor a transformar alunos de consumidores passivos em criadores ativos de tecnologia
. O currículo oferece base prática para um futuro onde 60% das profissões ainda não existem e a IA já impacta 30% dos trabalhadores brasileiros
. Além disso, garante o alinhamento com a BNCC e as competências digitais essenciais.
.

### Objetivos de Estudo
1.  Compreender os fundamentos teóricos do Currículo de Referência em Tecnologia e Computação através de fontes confiáveis.
2.  Estruturar um guia prático para referência rápida no dia a dia.
3.  Experimentar e documentar o comportamento da IA (NotebookLM) ao interagir com diferentes tipos de prompts.

---

## 📚 2. Curadoria de Fontes

Para alimentar o NotebookLM e garantir respostas de alta qualidade técnica, foram selecionadas e carregadas as seguintes fontes abertas (PDFs e artigos):

1.  **[Currículo de Referência em Tecnologia e Computação](https://www.cieb.net.br/wp-content/uploads/2019/09/Curr%C3%ADculo-CIEB-2019.pdf)** - *CIEB*
    *   **Descrição:** Foca nos conceitos iniciais e no publico do ensino infatil e fundamental
2.  **[Itinerário Formativo](https://cieb.net.br/wp-content/uploads/2020/07/ITINERARIO-FORMATIVO-CIEB.pdf)** - *CIEB*
    *   **Descrição:** Com o objetivo de preparar o egresso para o mercado de trabalho e para o ensino superior, promovendo o uso crítico e responsável das tecnologias

---

## 🧠 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Esta seção documenta a jornada de refinamento da interação com o NotebookLM. Veja como os prompts evoluíram para extrair respostas mais precisas e como os problemas de resposta foram resolvidos.

### 🔄 Evolução do Prompt

#### Tentativa 1 (Prompt Simples)
> **Prompt:** "Do que se trata o Currículo de Referência em Tecnologia e Computação?"
*   **Resposta da IA:** Uma resposta genérica e sem profundidade, basicamente copiando o que estava na fonte
*   **Problema Encontrado:** Faltou direcionamento sobre a intenção de aplicação do conhecimento

#### Tentativa 2 (Prompt Refinado - Engenharia de Prompt)
> **Prompt:** "Agindo como um especialista em Educação em Tecnologia e Computação, analise os documentos carregados e explique as diretrizes práticas para a implementação de itinerários formativos em escolas públicas e privadas. Com os conteúdos estruturados em três eixos fundamentais: Cultura Digital, Pensamento Computacional e Tecnologia Digital. Foque nas aplicações práticas apresentadas na Fonte 2 e forneça a explicação em tópicos."
*   **Resposta da IA:** Resposta detalhada, estruturada em tópicos e citando as páginas/documentos corretos, e aplicações prática.

### 🩹 Cicatrizes (Troubleshooting e Desafios)
*   **Desafio de Alucinação/Imprecisão:** No início, a IA mesclava conceitos de fora das fontes enviadas.
    *   *Como resolvi:* Adicionei a restrição explícita: `"Responda APENAS com base nos documentos fornecidos. Se a informação não estiver neles, diga que não sabe."`
*   **Desafio de Contexto:** Conteúdo de uma unica fonte
    * Dado que as fontes pertencem à mesma instituição de ensino, faltou mais contexto; diferentes currículos de referência poderiam trazer mais dinamismo ao tema e, assim, estimular a criação de novos conceitos a partir de perspectivas variadas.

---

## 📖 4. Miniguia de Estudo (Entrega Final)

Esta é a consolidação do conhecimento gerado pelo NotebookLM e revisado ativamente.

### 📝 Resumos Estruturados

#### Tópico A: [Currículo de Referência em Tecnologia e Computação]
Este documento do CIEB complementa a BNCC para transformar estudantes em criadores ativos de tecnologia, combatendo o consumo passivo de recursos digitais.
Sua estrutura é dividida nos eixos Cultura Digital, Tecnologia Digital e Pensamento Computacional, totalizando 10 conceitos e 26 unidades curriculares.
Oferece um guia prático com 112 habilidades, indicadores de avaliação e sugestões de atividades plugadas e desplugadas para apoiar o docente.

#### Tópico B: [Itinerário Formativo]
É a parte flexível do Novo Ensino Médio que permite ao estudante escolher áreas de aprofundamento conforme seus interesses e projeto de vida.
O itinerário de tecnologia soma até 1.440 horas, organizadas em módulos básico, intermediário e avançado com unidades essenciais e eletivas.
Visa garantir a fluência tecnológica necessária para o mercado de trabalho atual e para o exercício da cidadania contemporânea.

