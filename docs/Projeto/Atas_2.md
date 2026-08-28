# Ata reunião 2

# **REUNIÃO 25/08 - Estrutura do Protótipo e Regras de Negócio**

**Data:** 25/08/2026  
**Hora:** 20h02  
**Local:** Chamada Online  
**Membros Presentes:**  
André Henrique, Davi L, Giovanna Felipe, Giovanna Aguiar, João Pedro Lopes da Cruz, Johnnatan Salles, Júlia Gabriella, Luís Felipe Parreira Cunha, Matheus Eiki, Pedro Henrique Ferreira Xavier.

### **Pauta**

> 1. Apresentação da estrutura do protótipo inicial (navegação, comunidades e regionalismo).
> 2. Definição da experiência de usuários logados em contrapartida a visitantes sem cadastro.
> 3. Apresentação de estimativas de projeto, tecnologias e requisitos não funcionais.
> 4. Análise de diagramas BPMN para submissão de publicações, validação e uso geral.
> 5. Deliberação sobre a arquitetura de conteúdo (tópicos fixos institucionais versus tags e comunidades soltas).

### 

### **Discussões Realizadas**

A reunião iniciou com a apresentação do protótipo desenvolvido pelo Johnnatan, o qual demonstrou uma navegabilidade centrada em comunidades e uma proposta de filtro regional. Discutiu-se amplamente o fluxo do primeiro acesso, chegando ao consenso de que visitantes sem cadastro poderão consumir notícias livremente, enquanto engajamentos mais profundos, como seguir comunidades e receber notificações, exigirão autenticação. O debate sobre a inclusão de funcionalidades de comentários levou à sua remoção temporária, citando complexidades de moderação e riscos à segurança, como ataques de negação de serviço. Além disso, foram apresentados os requisitos não funcionais, destacando desempenho, escalabilidade, segurança e acessibilidade, com ênfase na inclusão de suporte a leitores de tela e alternância de temas (claro e escuro). Por fim, o grupo ponderou sobre a organização estrutural do portal. Para evitar uma complexidade similar à do Reddit e facilitar a usabilidade de um portal de notícias, concluiu-se que as categorias seriam baseadas em tópicos fixos pré-definidos na página inicial, complementados pelo uso de tags, levando ao descarte da regionalidade como filtro estrutural primário.

### 

### **Decisões Tomadas**

> * **Escopo e Modelo da Plataforma:** Adoção de um escopo geral, customizável através de comunidades, sem restrição a contextos específicos.  
> * **Acesso e Autenticação:** Permissão de leitura pública para visitantes; funcionalidades interativas, como seguir comunidades e receber notificações, ficam restritas a usuários logados.  
> * **Interações de Usuário:** Descarte temporário da funcionalidade de comentários nas publicações visando simplificar a moderação e segurança.  
> * **Estrutura de Conteúdo:** Abandono do modelo puramente focado em comunidades independentes em favor de categorias institucionais de tópicos fixos associados a tags para pesquisa refinada.  
> * **Regionalidade:** Remoção da funcionalidade de regionalismo estrutural; os agrupamentos se darão primordialmente via temas e comunidades fixas.  
> * **Acessibilidade Inclusiva:** Incorporação de controles para tema (claro/escuro) e ajustes de usabilidade diretamente no protótipo.

### 

### **Próximos Passos**

> * **Atualização de Interface:** Ajustar o protótipo para incluir visão de visitante (botão de login no lugar de perfil), suporte a temas, ícones de acessibilidade e seção de calendário de eventos.  
> * **Alinhamento de Processos:** Formalizar as regras de negócio sobre fluxo de permissões de acesso, acompanhamento de comunidades e notificações.  
> * **Definição Categórica:** Mapear e estabelecer os tópicos fixos institucionais (áreas temáticas) que guiarão a página inicial e a distribuição de conteúdo do portal.

**Observação:** A reunião contou com gravação e transcrição. Segue abaixo os links para verificação

- [Transcrição](https://docs.google.com/document/d/1AWpu1-p7XLbrZXXtFa48FE2jbQAgcsA6pBOov7PA4V4/edit?usp=sharing): https://docs.google.com/document/d/1AWpu1-p7XLbrZXXtFa48FE2jbQAgcsA6pBOov7PA4V4/edit?usp=sharing

- [Gravação](https://drive.google.com/file/d/1cOMzntQl6ct4_4mmiOLpnkfF-ZN8XW4p/view?usp=sharing): https://drive.google.com/file/d/1cOMzntQl6ct4_4mmiOLpnkfF-ZN8XW4p/view?usp=sharing

### 

### **Histórico de Versões**

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :---- | :---- | :---- | :---- | :---- |
| **0.1** | 27/08/2026 | Criação da Ata da Reunião 2 a partir das anotações e transcrição | João Pedro Lopes da Cruz |  |
