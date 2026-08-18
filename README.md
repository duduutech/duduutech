# Portfólio

<!-- HEADER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:4c1d95,50:6366f1,100:7c3aed&height=180&section=header&text=An%C3%A1lise%20e%20Desenvolvimento%20de%20Sistemas&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=8B5CF6&center=true&vCenter=true&width=850&lines=Estudante+de+ADS+%7C+FIAP;Aprendendo+Java+%2C+Python+e+desenvolvimento+web;Construindo+projetos+reais+a+cada+semestre" alt="Animação de texto" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/2%C2%BA_semestre-4C1D95?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Back_end-6366F1?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Front_end-7C3AED?style=for-the-badge" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/duduulimatech/">
    <img src="https://img.shields.io/badge/LINKEDIN-4F46E5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:limaedu1107@gmail.com">
    <img src="https://img.shields.io/badge/EMAIL-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/duduutech">
    <img src="https://img.shields.io/badge/GITHUB-312E81?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

# Sobre

Sou estudante de Análise e Desenvolvimento de Sistemas na FIAP, no 2º semestre. Estou construindo minha base em lógica de programação, orientação a objetos (Java) e desenvolvimento web, aplicando o que aprendo em sala em projetos práticos, documentados e explicáveis.

Tenho interesse especial em:

- Desenvolvimento back-end e front-end
- Banco de dados e modelagem de sistemas
- Inteligência artificial aplicada (ainda em fase inicial de estudo)
- Boas práticas de engenharia de software

Estou no começo da jornada — cada projeto abaixo representa uma etapa real de aprendizado, não um produto pronto.

---

# Tech Stack

### Já apliquei em projetos

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,javascript,java,html,css" />
</p>

### Estudando agora

<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,react" />
</p>



---

# Projetos em Destaque

<details>
<summary><strong>Sistema Validador de Dados</strong></summary>

### Utilitário de Dados Inconsistentes

Programa em Python que resolve um problema comum em cadastros: dados inconsistentes, mal formatados ou com erro de digitação (nomes, CPFs, CNPJs, e-mails, valores monetários).

| Métrica | Detalhes |
|:---|:---|
| **Stack** | Python |
| **O que faz** | Valida CPF/CNPJ, padroniza nomes, limpa strings, valida e-mails e valores monetários |
| **Como funciona** | CLI interativa, processamento local, rodando em loop com `while True` |
| **Arquitetura** | Funções modularizadas com Type Hints |
| **O que aprendi** | Separar responsabilidades em funções puras, validação de entrada, tratamento de formatação |
| **Próximos passos** | Adicionar testes unitários e leitura/gravação em CSV |
| **Repositório** | [GitHub](https://github.com/duduutech/python-data-cleaner) |

</details>

<details>
<summary><strong>Simulador de Crédito Consignado</strong></summary>

### Simulador de Crédito Consignado CLT

Projeto individual de estudo de desenvolvimento backend — Simulação de concessão de crédito consignado para trabalhadores CLT, aplicando regras de elegibilidade bancária e cálculo financeiro.

| Métrica | Detalhes |
|:---|:---|
| **Stack** | Java 21 • Spring Boot 3/4 • Spring Data JPA • PostgreSQL • JUnit 5 |
| **Minha contribuição** | Levantamento de requisitos e regras de negócio baseados em referências públicas do mercado financeiro (Itaú Unibanco), modelagem de dados rica com JPA e implementação da arquitetura em camadas (`Controller`, `Service`, `Repository`, `Model`). |
| **O que faz** | Avalia a elegibilidade do cliente (idade, vínculo CLT, margem consignável de 35%) e simula parcelas utilizando a Tabela Price, calculando juros totais, valor máximo disponível e CET. |
| **Arquitetura** | Layered Architecture (Camadas) • RESTful API • Mapeamento Objeto-Relacional (ORM) com Hibernate • Tratamento de precisão monetária com `BigDecimal`. |
| **O que aprendi** | Mapeamento de entidades JPA/Hibernate, convenções de código para aplicações financeiras (uso de `BigDecimal` e `LocalDate`), estruturação de arquitetura desacoplada e versionamento incremental com Git. |
| **Repositório** | [GitHub](https://github.com/duduutech/simulador-credito-consignado) |
</details>

<details>
<summary><strong>Sistema de Priorização de Resgate</strong></summary>

### Site Front-End

Projeto em grupo (Global Solution FIAP) — front-end de um sistema de apoio à decisão para priorização de atendimentos em operações de resgate e emergência.

| Métrica | Detalhes |
|:---|:---|
| **Stack** | HTML5 • CSS3 • JavaScript |
| **Minha contribuição** | *[descreva aqui especificamente o que você fez no projeto, ex: "sistema de pontuação" ou "formulário de contato e validação"]* |
| **O que faz** | Interface responsiva com sistema de pontuação, FAQ interativo e formulário de contato |
| **Arquitetura** | HTML semântico • CSS com Custom Properties, Grid e Flexbox • JavaScript para interações e validações |
| **O que aprendi** | Flexbox/Grid na prática, manipulação de DOM, validação de formulário em JS |
| **Repositório** | [GitHub](https://github.com/duduutech/GlobalSolution-FrontEnd-202601) |

</details>



---

# Disciplinas cursadas

O que já vi na prática em cada uma — sem nota de proficiência, os projetos acima é que mostram o nível real:

| Disciplina | O que estudei |
|:---|:---|
| **Artificial Intelligence & Chatbot** | Configuração de chatbot com IBM Watson (Assistant, STT), integração com Telegram, Node-RED e WebChat — ferramentas low-code, ainda sem chatbot construído via código próprio |
| **Building Relational Database** | Modelagem conceitual e lógica de banco de dados, relacionamentos, cardinalidades, generalização e herança |
| **Computational Thinking Using Python** | Lógica de programação, estruturas condicionais, laços, vetores, matrizes, listas, slicing e subalgoritmos |
| **Domain Driven Design using Java** | Orientação a objetos, modificadores de acesso, encapsulamento, composição, herança, classes abstratas, interfaces e Collections |
| **Front-End Design Engineering** | Git/GitHub, HTML5 semântico, CSS3 (Flexbox, Grid, responsividade), formulários, JavaScript (eventos, validação) e prototipagem no Figma |
| **Software Engineering and Business Model** | Design Thinking, Business Model Canvas, metodologias ágeis (Scrum/Trello), requisitos e diagramas UML |

---
