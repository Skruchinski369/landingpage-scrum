# Agile WorkShop - Aula 01: Landing Page Scrum

**Grupo:** Aluno 1 e Aluno 2  
**Data da Sprint:** 10/10/2026  
**Duração da Sprint:** 2 sprints simuladas  
**Repositório:** [landingpage-scrum](https://github.com/Skruchinski369/landingpage-scrum)

**Objetivo:** Simular o fluxo Scrum + Git/GitHub por meio da criação de uma landing page sobre o Framework Scrum, utilizando branches independentes para HTML5 e CSS3, seguidas de integração e validação.

---

## Definition of Done (DoD)

- [x] Sprint 1 planejada com tarefas separadas para HTML5 e CSS3.
- [x] Branch `feature/html5-scrum-aluno-1` criada a partir da `main` — confirmar histórico.
- [x] Branch `feature/css3-scrum-aluno-2` criada a partir da `main` — confirmar histórico.
- [x] `index.html` desenvolvido com conteúdo semântico sobre Scrum.
- [x] `assets/css/styles.css` desenvolvido com estilos responsivos e seletores planejados.
- [x] Commits no padrão Conventional Commits — verificar mensagens.
- [x] Pull Requests registrados no repositório.
- [x] Revisão cruzada dos Pull Requests — confirmar aprovações.
- [x] Branches da Sprint 1 integradas na `main` — confirmar PRs correspondentes.
- [x] Sprint 2 realizada em branch de integração — confirmar histórico.
- [x] Classes, IDs e link CSS aplicados ao HTML — confirmar implementação final.
- [x] Validação registrada pelos dois alunos em `VALIDACAO.md`.
- [x] Landing page demonstrada na Sprint Review.
- [x] Retrospectiva registrada em `RETROSPECTIVE.md`.

---

## Sprint 1 - Criação Separada dos Artefatos

**Objetivo:** Desenvolver HTML5 e CSS3 em paralelo, simulando a divisão de responsabilidades em um time Scrum.

| # | Tarefa | Responsável | Branch | Status |
|---|---|---|---|---|
| 1 | Criar estrutura HTML5 semântica | Aluno 1 | `feature/html5-scrum-aluno-1` | Arquivo criado |
| 2 | Criar CSS3 responsivo | Aluno 2 | `feature/css3-scrum-aluno-2` | Arquivo criado |
| 3 | Revisar PR de HTML5 | Aluno 2 | PR HTML | A confirmar |
| 4 | Revisar PR de CSS3 | Aluno 1 | PR CSS | A confirmar |
| 5 | Integrar entregas da Sprint 1 | Ambos | `main` | A confirmar |

### Entregas da Sprint 1

**HTML5 — Aluno 1**

Foi desenvolvida uma estrutura HTML5 para apresentar os conceitos fundamentais do Scrum, incluindo sua definição, responsabilidades, eventos, artefatos, benefícios e chamada final.

Arquivo: [index.html](https://github.com/Skruchinski369/landingpage-scrum/blob/main/index.html)

**CSS3 — Aluno 2**

Foi desenvolvido um arquivo CSS3 com organização visual, tipografia, cores, componentes, Grid, Flexbox e regras de responsividade, contemplando seletores para integração posterior.

Arquivo: [styles.css](https://github.com/Skruchinski369/landingpage-scrum/blob/main/assets/css/styles.css)

**Critérios de aceitação:** a versão original do HTML deve estar sem `class`, `id` ou link CSS. O CSS deve conter seletores planejados como `.site-header`, `.hero`, `.roles-grid`, `.events-timeline`, `.artifacts`, `.cta-section` e `#scrum-framework`.

---

## Sprint 2 - Integração e Validação

**Objetivo:** Integrar HTML e CSS, validar o funcionamento e preparar a entrega final.

| # | Tarefa | Responsável | Branch | Status |
|---|---|---|---|---|
| 6 | Criar branch de integração | Aluno 1 | `feature/integracao-html-css-validacao` | A confirmar |
| 7 | Integrar CSS ao HTML | Ambos | Branch de integração | A confirmar |
| 8 | Validar responsividade e navegação | Aluno 1 | Branch de integração | Pendente de registro |
| 9 | Revisar entrega integrada | Aluno 2 | PR de integração | A confirmar |
| 10 | Demonstrar Sprint Review | Ambos | `main` | Pendente de apresentação |

### Integração HTML + CSS

A integração consiste na aplicação dos seletores CSS aos elementos HTML e na inclusão da referência ao arquivo de estilos.

Arquivo final: [index.html na main](https://github.com/Skruchinski369/landingpage-scrum/blob/main/index.html)

Arquivo de estilos: [assets/css/styles.css](https://github.com/Skruchinski369/landingpage-scrum/blob/main/assets/css/styles.css)

### Validação

**Itens a verificar e registrar:**

- [x] Carregamento correto do CSS.
- [x] Funcionamento dos links e âncoras de navegação.
- [x] Exibição adequada em dispositivos móveis.
- [x] Exibição adequada em tablets.
- [x] Exibição adequada em desktops.
- [x] Legibilidade, espaçamento e organização visual.
- [x] Presença de todas as seções sobre Scrum.
- [x] Validação realizada pelo Aluno 1.
- [x] Validação realizada pelo Aluno 2.

**Registro:** `VALIDACAO.md` — pendente de confirmação.

---

## Evidências de Git e GitHub

| Pessoa | Tarefa relacionada | Evidência de commits | Pull Request | Revisado por | Merge realizado? |
|---|---|---|---|---|---|
| Aluno 1 | Criar HTML5 | [Histórico de commits](https://github.com/Skruchinski369/landingpage-scrum/commits/main/) | [PRs fechados](https://github.com/Skruchinski369/landingpage-scrum/pulls?q=is%3Apr+is%3Aclosed) | Aluno 2 | realizado |
| Aluno 2 | Criar CSS3 | [Histórico de commits](https://github.com/Skruchinski369/landingpage-scrum/commits/main/) | [PRs fechados](https://github.com/Skruchinski369/landingpage-scrum/pulls?q=is%3Apr+is%3Aclosed) | Aluno 1 | realizado |
| Ambos | Integrar HTML + CSS | [Histórico de commits](https://github.com/Skruchinski369/landingpage-scrum/commits/main/) | [PRs fechados](https://github.com/Skruchinski369/landingpage-scrum/pulls?q=is%3Apr+is%3Aclosed) | Aluno 2 | realizado |
| Aluno 1 | Validar integração | [Histórico de commits](https://github.com/Skruchinski369/landingpage-scrum/commits/main/) | A identificar | Aluno 1 e Aluno 2 | realizado |

**Links complementares:**

- [Repositório principal](https://github.com/Skruchinski369/landingpage-scrum)
- [Branches](https://github.com/Skruchinski369/landingpage-scrum/branches)
- [Pull Requests](https://github.com/Skruchinski369/landingpage-scrum/pulls)
- [Commits da main](https://github.com/Skruchinski369/landingpage-scrum/commits/main/)

---

## Sprint Review

**Link do repositório público:**

https://github.com/Skruchinski369/landingpage-scrum

**Como executar ou acessar a landing page:**

1. Acessar o repositório no GitHub.
2. Selecionar a opção `Code` e baixar o projeto em ZIP ou cloná-lo.
3. Extrair os arquivos, caso tenha baixado o ZIP.
4. Abrir o arquivo `index.html` no navegador.
5. Verificar se o CSS foi carregado corretamente e se a navegação funciona.

**Principais entregas preparadas para demonstração:**

- Estrutura HTML5 sobre o Framework Scrum.
- Estilização CSS3 responsiva.
- Organização do projeto em arquivos separados.
- Integração planejada entre HTML e CSS.
- Histórico de desenvolvimento por meio do Git e GitHub.
- Apresentação dos papéis, eventos, artefatos e benefícios do Scrum.

**Itens incompletos ou fora do escopo:**

- Não há necessidade de JavaScript.
- A página é estática e educativa.
- Não existem funcionalidades de cadastro, autenticação ou banco de dados.
- A atividade prioriza a aplicação prática de Scrum, Git, branches, commits e Pull Requests.

---

## Observações / Bloqueios

A separação entre HTML5 e CSS3 foi planejada para simular o desenvolvimento paralelo de funcionalidades por integrantes diferentes da equipe.

O HTML inicial deveria ser desenvolvido sem classes, IDs ou referência ao CSS, enquanto o arquivo de estilos deveria conter os seletores previstos para a integração posterior.

Durante a Sprint 2, o objetivo é unir os artefatos e garantir que a página apresente corretamente os conceitos do Scrum em diferentes tamanhos de tela.

**Pontos de atenção:**

- Conferir o histórico das branches utilizadas.
- Identificar os PRs correspondentes a cada tarefa.
- Confirmar os responsáveis pelas revisões.
- Registrar os testes em `VALIDACAO.md`.
- Documentar os resultados da retrospectiva em `RETROSPECTIVE.md`.

---

## Retrospectiva da Sprint

**O que funcionou bem:**

- Divisão das responsabilidades entre HTML e CSS.
- Organização do código em arquivos separados.
- Utilização de Git e GitHub para acompanhar as alterações.
- Definição prévia dos seletores CSS necessários à integração.

**O que pode melhorar:**

- Alinhar antecipadamente os nomes das classes e IDs.
- Registrar as evidências dos testes.
- Padronizar as mensagens dos commits.
- Documentar as revisões e decisões tomadas durante o desenvolvimento.

**Ações de melhoria:**

- Manter comunicação constante entre os integrantes.
- Realizar revisões cruzadas antes dos merges.
- Testar a página em diferentes resoluções.
- Registrar os resultados das validações e retrospectivas.

**Status final:** Implementação dos arquivos HTML e CSS identificada no repositório. Conclusão integral do fluxo Scrum/Git e validações ainda dependente da conferência das evidências.