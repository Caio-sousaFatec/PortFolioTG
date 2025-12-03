# **Agile Assessment**
---

![alt text](Assets/VisionLogo.png)

### **1º Semestre • Projeto Integrador Fatec-SJC**  
#### **Cliente interno:** Lucas Gonçalves Nadalete

> Aplicação Web de avaliação 360° baseada na Escala Likert, permitindo avaliações internas entre membros de equipes Scrum, líderes e professores.

---

## Problema Proposto

O cliente possuía a necessidade de uma solução que permitisse realizar avaliações internas entre membros de equipes utilizando a **Escala Likert**, de forma organizada, acessível e com registros estruturados.  
Também era necessário suportar diferentes tipos de usuários, gerenciar permissões e possibilitar o acompanhamento do desempenho dos avaliados ao longo das sprints.

---

## Solução apresentada
---

Foi entregue uma aplicação Web funcional, construída com Python e Flask, capaz de registrar avaliações, controlar perfis de usuários e gerar dashboards de acompanhamento.  
A solução atendeu aos requisitos do cliente, oferecendo uma interface simples e acessível, além de armazenamento local com TinyDB.

### **Requisitos funcionais concluídos**

- Realizar avaliações utilizando perguntas baseadas na Escala Likert.  
- Diferenciar perfis de usuários (aluno, professor, administrador).  
- Implementar login com autenticação simples.  
- Armazenar avaliações em banco de dados local (TinyDB).  
- Gerar dashboards consolidados com os resultados.  
- Acompanhar o progresso de membros em diferentes sprints.

### **Requisitos não funcionais**

- Interface simples e intuitiva.  
- Armazenamento local eficiente utilizando TinyDB.  
- Organização visual agradável, baseada no protótipo Figma.  
- Performance satisfatória para o volume de dados proposto.  
- Ausência de informações adicionais.

---

## Tecnologias Utilizadas

| Tecnologia | Motivo de uso |
|-----------|----------------|
| ![Python](https://img.shields.io/badge/python-purple?logo=python&logoColor=white) | Linguagem principal no backend, com uso de Pandas e TinyDB. |
| ![Flask](https://img.shields.io/badge/flask-purple?logo=flask&logoColor=white) | Microframework utilizado para construção da API e das rotas da aplicação. |
| ![HTML5](https://img.shields.io/badge/HTML5-purple?logo=html5&logoColor=white) | Construção da interface do usuário. |
| ![CSS3](https://img.shields.io/badge/CSS3-purple?logo=css3&logoColor=white) | Estilização e layout da aplicação. |
| ![TinyDB](https://img.shields.io/badge/TinyDB-purple) | Armazenamento local em formato NoSQL simples. |
| ![Figma](https://img.shields.io/badge/Figma-purple?logo=figma&logoColor=white) | Protótipo visual das telas. |

---

<details>
<summary><strong>VER MAIS DETALHES</strong></summary>

---

## Minhas Contribuições

> **Função:** Product Owner (PO) – primeira experiência na função.  
> Foco em organização do backlog, comunicação com o cliente e alinhamento dos requisitos.

---

### **1. Organização do Backlog**

- Criação e priorização de histórias de usuário.  
- Definição dos requisitos funcionais com base nas necessidades do cliente.  

<details>
<summary><strong>Evidências</strong></summary>

| Sprint | Descrição | User Storie | Prioridade |
|--------|-----------|--------------|-------------|
| 01 | Haverá um painel mostrando todas perguntas e possibilidades de avaliação, com 5 botões de avaliação | Eu como aluno quero poder realizar minhas avaliações para manter uma informação sobre o desempenho do time | Imprescindível |
| 01 | Haverá um painel com dados da sprint | Eu como aluno quero poder acessar minhas informações de sprint para melhor gerenciamento | Importante |
| 01 | Haverá uma base de dados para avaliações | Eu como PBLTeX quero ter as avaliações armazenadas para não perder os dados de avaliações realizadas | Imprescindível |
| 01 | Haverá uma base de dados para login | Eu como PBLTeX quero ter uma tela de autenticação para conseguir entrar em determinados perfis | Imprescindível |
| 02 | Haverá uma diferenciação de times no cadastro | Eu como aluno quero ter minhas informações de grupo para melhor controle de qual é meu grupo e suas qualidades | Importante |
| 02 | Haverá uma diferenciação entre aluno e professor | Eu como cliente quero que haja uma diferenciação entre aluno e orientador para melhor diferenciação de dados | Importante |
| 02 | Haverá uma tela de admin | Eu como PBLTeX quero que haja um perfil administrador para cadastrar ou retirar cadastro dos usuários | Imprescindível |
| 03 | Haverá uma tela de avaliação ao ScrumMaster | Eu como líder técnico quero poder avaliar meu aluno líder técnico para manter um bom rendimento de atividades | Importante |
| 03 | Haverá uma tela de avaliação ao PO | Eu como fake client quero avaliar meu aluno PO para manter bom rendimento e alterar pontos fracos | Imprescindível |
| 03 | Haverá um sistema de profiles | Eu como administrador quero atribuir um perfil específico a cada usuário cadastrado para que eu possa utilizar esse dado sistemicamente após sua autenticação | Imprescindível |
| 04 | Haverão telas de demonstração de pontuação | Eu como usuário quero que os dados sejam demonstrados de forma direta e prática para facilitação de entendimento | Importante |
| 04 | Haverá uma visualização de avaliação geral | Eu como instrutor quero ter acesso a avaliação de meus alunos para saber qual seu rendimento na visão do time | Imprescindível |
| 04 | Haverá um dashboard ligado às informações de time, de sprint e de avaliações de usuário | Eu como aluno quero ter um dashboard para melhor facilidade de acompanhamento | Imprescindível |

</details>

---

### **2. Validações e comunicação com o cliente**

- Condução de reuniões de validação com cliente e professor.  
- Ajuste de requisitos e verificação de aderência às necessidades reais.  

---

### **3. Criação de métricas de pontuação com Escala Likert**

---

## Conhecimentos Obtidos

Durante o projeto, obtive conhecimentos sólidos sobre:

- Responsabilidades e atuação de um **Product Owner**.  
- Estrutura e dinâmica do **Scrum**.  
- Fundamentos práticos de Python (variáveis, funções e importação de bibliotecas).  
- Noções de banco de dados com **TinyDB**.  
- Organização de backlog e priorização de histórias de usuário.

---

</details>
