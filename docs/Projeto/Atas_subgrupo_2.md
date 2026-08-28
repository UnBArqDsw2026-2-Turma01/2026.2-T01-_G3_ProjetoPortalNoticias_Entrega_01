# Ata subgrupo 2

# **REUNIÃO 24/08 - Desenho de Software (Entrega 01)**////////

**Data:** 24/08/2026
**Hora:** 21h08
**Local:** [Chamada Online](https://unbbr-my.sharepoint.com/:v:/g/personal/241011401_aluno_unb_br/IQA1vulGmUsrSJLco6KN9g4OASIz_lUTv3haiqHMj0CS9yY?e=Wjt694&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
**Membros Presentes:**
Luís Felipe Parreira Cunha, André Henrique De Souza Belarmino e Matheus Eiki Kimura Rezende.

### **Pauta**

> 1. Revisão comparativa dos Diagramas de Estimativas elaborados individualmente por cada membro do Subgrupo 2 (histórias de dados do projeto, restrições, recursos e estimativas de custo/prazo).
> 2. Alinhamento do cronograma metodológico com base no Design Sprint.
> 3. Revisão do SIG / NFR Framework (URPS+), construído a partir da Engenharia Reversa do Forem/dev.to.
> 4. Revisão dos modelos BPMN individuais (publicação de artigo, seguir tag e uso geral da plataforma).
> 5. Definição do fluxo de organização de branches e commits para consolidação dos artefatos do subgrupo.

### **Discussões Realizadas**

A reunião teve início com Luís apresentando seu Diagrama de Estimativas, construído a partir da Engenharia Reversa do Forem/dev.to: histórico de tecnologias (Ruby, biblioteca leve de React, SendGrid, base SQL), requisitos funcionais e não funcionais (dark mode, busca instantânea via Algolia/IA, proteção contra cross-site scripting), restrições do projeto (até 90 mil acessos simultâneos, cerca de 9 milhões de acessos mensais), estimativa de tamanho (200 a 250 mil linhas de código), cobertura de testes (49% no front-end e cerca de 81% no projeto como um todo) e uma calculadora de custo baseada em COCOMO. Luís destacou ter utilizado IA generativa para organizar e interpretar parte dessas informações. Em seguida, André apresentou sua versão, reaproveitando os requisitos não funcionais de Luís e acrescentando funcionalidades como feed de artigos mais engajados, seguir tags, salvar para ler depois e recomendação de publicações; seu diagrama estimou o esforço por funcionalidade completa (front e back integrados) usando story points, chegando a aproximadamente 1450 horas totais. Matheus apresentou sua própria versão, organizada por módulos (interface front-end, conteúdo gerado pelo usuário, infraestrutura/back-end), também com story points, chegando a 250 pontos (≈1000 horas, ou 100 horas por pessoa ao longo do semestre), além de uma referência salarial de desenvolvedor júnior obtida no Glassdoor. O grupo comparou as diferenças entre as três abordagens de estimativa — sobretudo a divergência entre separar front-end/back-end (Matheus) ou tratar cada funcionalidade de forma integrada (André) — e decidiu adotar a divisão por funcionalidade completa, alinhada à natureza incremental do Design Sprint. Também revisaram uma proposta inicial de cronograma (estudo de caso → brainstorming → planejamento 5W3H → prototipação → desenvolvimento/testes → deploy).

Na sequência, o grupo revisou o SIG/NFR Framework. Luís apresentou sua proposta organizando os requisitos não funcionais em cinco categorias baseadas em URPS+ (desempenho, segurança, usabilidade, funcionalidade e escalabilidade), com apoio de IA generativa para abstrair e detalhar os pontos. André confirmou ter reaproveitado os mesmos requisitos não funcionais por considerá-los suficientes, adicionando apenas alguns requisitos funcionais extras identificados no dev.to. O grupo alinhou a cobertura de testes de referência da estimativa em torno de 70%.

Por fim, o grupo revisou os modelos BPMN: Luís apresentou o fluxo de **publicação de um artigo**, dividido em três raias (autor/usuário, aplicação principal/Ruby on Rails e background jobs), cobrindo edição em markdown, validação no backend (incluindo verificação contra cross-site scripting), persistência, atualização de cache, notificação de seguidores por e-mail e cross-posting em outras redes; André apresentou o fluxo de **seguir uma tag** (verificação de autenticação, criação do follow e atualização do feed); e Matheus apresentou o fluxo de **uso geral da plataforma** (navegação, visualização de notícias e interação via comentário/curtida/compartilhamento, condicionada à autenticação). O grupo discutiu como organizar os três fluxos individuais dentro do artefato do subgrupo (cada versão individual seguida da versão consolidada) e encerrou com uma discussão sobre o fluxo de trabalho no Git: cada integrante trabalharia em uma branch própria antes de consolidar no Subgrupo 2, avaliando também uma convenção de commits referenciando o número de versão (em vez de mensagens descritivas), embora tenham reconhecido o risco de conflitos quando mais de uma pessoa atualiza a mesma versão simultaneamente.

### **Decisões Tomadas**

> * **Diagrama de Estimativas:** manter no artefato principal apenas uma visão genérica organizada por módulo, movendo o detalhamento de custo/prazo (COCOMO e story points) para uma página separada no Figma/Pages.
> * **Metodologia de Estimativa:** complementar o diagrama de André com a calculadora COCOMO de Luís, como um complemento, e adotar a divisão do cronograma por funcionalidade completa (não separando front-end e back-end), alinhada à abordagem incremental do Design Sprint.
> * **Cobertura de Testes de Referência:** definida em aproximadamente 70% para fins da estimativa.
> * **SIG/NFR Framework:** manter as cinco categorias definidas por Luís (desempenho, segurança, usabilidade, funcionalidade e escalabilidade) como base do subgrupo.
> * **Estrutura do BPMN:** o artefato do subgrupo reunirá os três fluxos individuais (publicação de artigo, seguir tag e uso geral da plataforma) seguidos de uma versão consolidada.
> * **Workflow de Git:** cada integrante do subgrupo trabalha em uma branch própria antes de consolidar na branch/pasta do Subgrupo 2.

### **Próximos Passos**

> * **Consolidação Individual:** André finalizar sua branch/consolidação, adiada para o dia seguinte.
> * **Alinhamento com o Time Completo:** verificar com o restante da equipe como o dev.to trata conteúdo em Markdown, em comparação com G1 e UnB Notícias, dado o impacto nos requisitos de formatação de conteúdo.
> * **Padronização Visual:** Luís ajustar cores e formatação do Diagrama de Estimativas após a reunião.
> * **Consolidação dos Artefatos:** unificar as três versões individuais (estimativas, SIG/NFR e BPMN) em uma versão única do Subgrupo 2.
> * **Convenção de Versionamento:** definir com a equipe completa a convenção final de commits/versões, evitando conflitos entre integrantes que atualizem a mesma versão simultaneamente.

**Observação:** A reunião contou com gravação e transcrição gerada automaticamente.

### **Histórico de Versões**

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :---- | :---- | :---- | :---- | :---- |
| **0.1** | 27/08/2026 | Criação da Ata da Reunião do Subgrupo 2 (Entrega 01) a partir da transcrição da chamada | Luís Felipe Parreira Cunha | — |