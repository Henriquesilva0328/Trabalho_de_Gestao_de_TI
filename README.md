# COBIT — Governança de Tecnologia da Informação

Projeto acadêmico desenvolvido no contexto da disciplina de **Gestão de Tecnologia da Informação**, com foco na aplicação de conceitos de **Governança de TI e COBIT**, aliados às boas práticas de desenvolvimento de interfaces web.

O repositório acadêmico é destinado ao desenvolvimento, documentação e controle de
versão das entregas **P1 e P2** da disciplina de **Gestão de Tecnologia da
Informação**.

A **P1 — Projeto COBIT** contempla o desenvolvimento de uma interface web no
lado cliente, aplicando conceitos de estruturação semântica, responsividade,
acessibilidade e boas práticas de CSS.

A **P2** dará continuidade à solução desenvolvida na P1, incorporando
comportamento dinâmico, validações no lado do cliente e comunicação assíncrona.

---

## Visão do Projeto

O projeto utiliza práticas de engenharia de software e controle de versão para
manter as entregas acadêmicas organizadas, rastreáveis e evolutivas.

O repositório concentra:

- código-fonte;
- documentação técnica;
- artefatos das entregas;
- histórico de alterações;
- branches de desenvolvimento;
- versões integradas;
- versão estável destinada à entrega.

### Entregas

| Etapa | Escopo principal | Status |
|---|---|---|
| **P1 — Projeto COBIT** | HTML5, CSS3, semântica, acessibilidade e responsividade | Em desenvolvimento |
| **P2** | JavaScript, validações e requisições assíncronas | Planejada |

---

# P1 — Projeto COBIT

## Objetivo

Desenvolver uma **interface gráfica do usuário (GUI) semântica, responsiva e
acessível** para o front-end de uma aplicação web.

A aplicação deverá ser construída no lado cliente utilizando **HTML5 e CSS3**,
permitindo o **cadastro e a visualização de dados de um sistema de gestão**.

---

## Requisitos da P1

A implementação deverá contemplar:

- estrutura em HTML5;
- estilização com CSS3;
- utilização adequada de elementos semânticos;
- formulário para cadastro de dados;
- visualização estruturada dos registros;
- responsividade;
- acessibilidade;
- compatibilidade com navegadores modernos;
- separação entre estrutura e apresentação;
- organização e legibilidade do código-fonte.

---

## Fundamentação Bibliográfica da P1

A fundamentação técnica da primeira entrega utiliza a obra indicada no
enunciado da atividade:

> **FREEMAN, Elisabeth; FREEMAN, Eric. _Use a Cabeça! HTML com CSS e XHTML_.  
> 2. ed. Rio de Janeiro: Alta Books, 2008. 580 p. ISBN 978-85-7608-218-7.**

O enunciado orienta a consulta aos capítulos introdutórios relacionados à
**estrutura de páginas web** e às **boas práticas de utilização de CSS**.

A obra apresenta progressivamente conceitos relevantes para a implementação
da P1, entre eles:

| Conteúdo da obra | Aplicação no projeto |
|---|---|
| Linguagem e estrutura HTML | Organização estrutural da página |
| Construção de páginas web | Hierarquia e composição dos elementos |
| Padrões HTML | Construção de documentos consistentes |
| CSS | Separação entre conteúdo e apresentação |
| Seletores e classes | Organização das regras de estilo |
| Herança e cascata | Controle e reutilização de estilos |
| Modelo de caixa | Espaçamento e dimensionamento |
| Estruturação de regiões da página | Organização visual do conteúdo |
| Layout e posicionamento | Construção da interface |
| Tabelas | Visualização estruturada de dados |
| Formulários | Entrada e cadastro de informações |

---

## Entregáveis da P1

A primeira entrega deverá conter:

```text
Código-fonte da interface
HTML5
CSS3
Relatório técnico
Repositório Git/GitHub
```

### Relatório técnico

O relatório deverá justificar as escolhas de elementos semânticos utilizados
na interface.

**Extensão exigida: 1 a 2 páginas.**

O documento deverá apresentar de maneira objetiva:

1. contexto da interface;
2. estrutura semântica escolhida;
3. justificativa das principais tags;
4. decisões relacionadas ao CSS;
5. responsividade;
6. acessibilidade;
7. conclusão.

---

# P2 — Evolução da Aplicação

## Objetivo

A P2 dará continuidade à interface construída na primeira entrega,
incorporando comportamento dinâmico no lado cliente.

O desenvolvimento previsto inclui:

- JavaScript;
- manipulação do DOM;
- eventos;
- validações;
- requisições HTTP assíncronas;
- utilização de Fetch/Ajax;
- preenchimento dinâmico de informações;
- consulta automática de CEP/endereço.

---

## Relação entre P1 e P2

A P2 não representa um projeto independente.

A evolução prevista é:

```text
P1
HTML5 + CSS3
       │
       │ evolução
       ▼
P2
HTML5 + CSS3 + JavaScript
       │
       ├── Validações
       ├── Manipulação do DOM
       └── Requisições assíncronas
```
---

## Entregáveis da P2

A etapa prevê:

- arquivos JavaScript;
- HTML atualizado;
- validações no lado cliente;
- funcionalidade assíncrona;
- demonstração em vídeo.

**Duração máxima do Screen Record: 2 minutos.**

> A fundamentação bibliográfica específica da P2 será documentada quando essa
> etapa for iniciada.

---

# Stack do Projeto

| Tecnologia | Responsabilidade |
|---|---|
| **HTML5** | Estrutura e semântica |
| **CSS3** | Apresentação e responsividade |
| **JavaScript** | Comportamento da P2 |
| **DOM API** | Manipulação da interface na P2 |
| **Fetch API / Ajax** | Comunicação assíncrona na P2 |
| **Git** | Controle de versão |
| **GitHub** | Colaboração, revisão e rastreabilidade |

---

# Estrutura do Repositório

```text
gestao-ti/
│
├── docs/
│   ├── p1/
│   │   └── relatorio-semantica.pdf
│   │
│   └── p2/
│
├── src/
│   ├── css/
│   │   └── styles.css
│   │
│   ├── js/
│   │   └── main.js
│   │
│   └── index.html
│
├── .gitignore
└── README.md
```

### Responsabilidades dos diretórios

| Diretório | Responsabilidade |
|---|---|
| `src/` | Código-fonte da aplicação |
| `src/css/` | Folhas de estilo |
| `src/js/` | Scripts adicionados na P2 |
| `docs/p1/` | Documentação e relatório da P1 |
| `docs/p2/` | Documentação da P2 |

---

# Estratégia Git

O repositório utiliza branches separadas para desenvolvimento, integração e
versão estável.

```text
production
    ▲
    │
   main
    ▲
    │
    ├── integrante/nome-01
    ├── integrante/nome-02
    └── integrante/nome-03
```

## `main`

Branch de integração.

Deve conter somente alterações que passaram pelo fluxo de desenvolvimento e
estão aptas a compor a versão principal do projeto.

## `production`

Branch estável utilizada como referência para as versões destinadas à entrega.

## `integrante/*`

Branches de trabalho individuais.

Padrão:

```text
integrante/nome-sobrenome
```

Exemplo:

```text
integrante/joao-silva
```

O desenvolvimento não deverá ser concentrado diretamente na `main`.

---

# Workflow de Desenvolvimento

```text
integrante/*
      │
      ▼
    commit
      │
      ▼
Pull Request
      │
      ▼
    review
      │
      ▼
     main
      │
      ▼
  validação
      │
      ▼
 production
```

Fluxo esperado:

1. partir de uma versão atualizada da `main`;
2. desenvolver na branch individual;
3. realizar commits;
4. publicar a branch;
5. abrir Pull Request;
6. revisar a alteração;
7. integrar na `main`;
8. validar a versão integrada;
9. promover a versão aprovada para `production`.

---

# Padrão de Commits

O projeto adota mensagens inspiradas em **Conventional Commits**.

| Tipo | Utilização |
|---|---|
| `feat` | Nova funcionalidade |
| `fix` | Correção |
| `docs` | Documentação |
| `style` | Alterações visuais/CSS |
| `refactor` | Reorganização sem alteração funcional |
| `test` | Testes |
| `chore` | Configuração e manutenção |

---

# Pull Requests

Alterações desenvolvidas nas branches individuais deverão ser integradas por
Pull Request.

Cada PR deve indicar:

- o que foi alterado;
- por que a alteração foi necessária;
- como foi validada;
- quais requisitos estão sendo atendidos;
- evidências relevantes, quando aplicável.

---

# Critérios de Qualidade

## Código

- estrutura compreensível;
- nomenclatura consistente;
- separação de responsabilidades;
- ausência de duplicação desnecessária;
- HTML válido;
- CSS organizado.

## Interface

- semântica;
- responsividade;
- acessibilidade;
- legibilidade;
- consistência;
- compatibilidade com navegadores.

## Versionamento

- utilização de branches;
- commits descritivos;
- histórico rastreável;
- integração controlada;
- `main` organizada;
- `production` estável.

## Documentação

- linguagem técnica;
- objetividade;
- ortografia;
- relação entre requisito e implementação;
- fundamentação bibliográfica;
- atualização compatível com o estado do projeto.

---

# Status

| Entrega | Item | Status |
|---|---|---|
| P1 | Estrutura do repositório | Finalizado |
| P1 | Planejamento | Finalizado |
| P1 | Interface HTML5 | Em andamento |
| P1 | CSS3 | Em andamento |
| P1 | Responsividade | Em andamento |
| P1 | Acessibilidade | Em andamento |
| P1 | Relatório de semântica | Em andamento |
| P2 | JavaScript | Não iniciado |
| P2 | Validações | Não iniciado |
| P2 | Fetch/Ajax | Não iniciado |
| P2 | Demonstração | Não iniciado |

Os status deverão representar o estado real do repositório e ser atualizados
conforme o desenvolvimento.

---

# Limitações das Entregas

| Entrega | Restrição |
|---|---|
| **P1** | Relatório de **1 a 2 páginas** |
| **P2** | Screen Record de **até 2 minutos** |

---

# Contexto Acadêmico

**Disciplina:** Gestão de Tecnologia da Informação  
**Projeto P1:** COBIT  
**Entregas documentadas:** P1 e P2  
**Ano:** 2026

**Instituição:** `FATEC Barueri`  
**Curso:** `Gestão da Tecnologia da Inforamação `  
**Professor:** `Vander Ribeiro Elme`

---

# Equipe

| Integrante | Branch |
|---|---|
| `Henrique Silva` | `integrante/henrique-silva` |
| `Melissa Victória` | `integrante/melissa-victoria` |
| `Pedro Henrique` | `integrante/pedro-henrique` |
| `Lucas Rafael` | `integrante/lucas-rafael` |

---

# Referências

## P1

FREEMAN, Elisabeth; FREEMAN, Eric. **Use a Cabeça! HTML com CSS e XHTML**.
2. ed. Rio de Janeiro: Alta Books, 2008. **580 p.**
ISBN **978-85-7608-218-7**.

### Conteúdo consultado

A referência é utilizada na P1 como fundamentação para os tópicos de:

- estrutura e construção de documentos HTML;
- padrões de marcação;
- separação entre estrutura e apresentação;
- CSS;
- seletores;
- classes;
- herança;
- cascata;
- modelo de caixa;
- organização de regiões da página;
- layouts;
- tabelas;
- formulários.

## P2

A definir.

---

## Uso

Repositório desenvolvido exclusivamente para fins acadêmicos.
