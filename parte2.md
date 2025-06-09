## 🧭 Parte 2: Modelos de Processo de Software

### 🔄 O que são modelos de processo?

Um modelo de processo define a **forma como o software será desenvolvido**: as etapas, a ordem delas, e como elas se conectam. Ele serve como um **guia** para organizar o trabalho da equipe de desenvolvimento.

Existem vários modelos de processo, cada um com suas vantagens e desvantagens. Vamos ver os principais:

---

### 📏 1. Modelo Cascata (ou Sequencial)

#### Como funciona?

É o mais tradicional. As etapas seguem uma ordem linear:

> Requisitos → Análise → Projeto → Codificação → Testes → Entrega

Cada fase só começa depois que a anterior termina. É como construir uma casa por etapas fixas.

#### Vantagens:

* Fácil de entender e organizar.
* Boa documentação.

#### Desvantagens:

* Pouca flexibilidade.
* Dificuldade em lidar com mudanças nos requisitos.
* Só se vê o produto no final.

> ⚠️ Esse modelo é útil quando os requisitos estão muito bem definidos desde o início, o que é raro.

---

### 🌀 2. Modelo Espiral

#### Como funciona?

Combina **planejamento e prototipação iterativa**. O projeto evolui em ciclos, e a cada volta da espiral, o software é refinado e ganha novas versões.

> Etapas em cada ciclo: Planejamento → Análise de riscos → Engenharia → Avaliação

#### Vantagens:

* Foco em riscos e feedback contínuo.
* Flexível e iterativo.

#### Desvantagens:

* Mais complexo de gerenciar.
* Pode ser custoso se mal aplicado.

> ✅ Ideal para projetos grandes e com requisitos que podem mudar.

---

### 🧱 3. Processo Unificado (RUP)

#### Como funciona?

Segue uma abordagem **incremental e iterativa**. O desenvolvimento ocorre em fases (Iniciação, Elaboração, Construção e Transição), com entregas parciais do produto em cada ciclo.

#### Características:

* Baseado em **casos de uso**.
* Divide o sistema em módulos reutilizáveis.
* Boa documentação, mas flexível.

> 🔄 É um meio-termo entre a rigidez do Cascata e a flexibilidade do Ágil.

---

### ⚡ 4. Desenvolvimento Ágil

#### O que é?

É um conjunto de métodos com foco em **entregar valor rápido ao cliente**, adaptando-se facilmente às mudanças.

> O Manifesto Ágil (2001) prioriza:

* Pessoas e interações mais que ferramentas e processos.
* Software funcional mais que documentação.
* Colaboração com o cliente mais que contrato.
* Responder a mudanças mais que seguir um plano.

#### Princípios principais:

* O cliente deve estar satisfeito desde cedo.
* Equipes devem ser motivadas, auto-organizadas e colaborativas.
* Requisitos mudam? Tudo bem! O time se adapta.
* Entregas frequentes, feedback rápido.

---

### 🚀 Métodos Ágeis mais usados:

#### ✅ Scrum

* Equipe pequena e auto-organizada.
* Trabalho em **sprints** de 2 a 4 semanas.
* Funções: Product Owner (prioriza tarefas), Scrum Master (remove impedimentos), Equipe de Dev.
* Artefatos: Product Backlog, Sprint Backlog, Incremento.

#### ✅ XP (Extreme Programming)

* Foco na qualidade e colaboração.
* Práticas: programação em par, testes automatizados, design simples, pequenas entregas frequentes.

#### ✅ Kanban

* Fluxo contínuo, visualizado em cartões.
* Foco em **gestão de tarefas** e **limite de trabalho em andamento (WIP)**.
* Equipes monitoram e adaptam o fluxo de trabalho.

#### ✅ DevOps

* Integra **desenvolvimento + operações**.
* Foco em automação de testes, entrega contínua, integração contínua.
* Aumenta a agilidade e a confiança nas entregas.

---

### 🔑 Comparando os modelos

| Modelo             | Ideal para                       | Pontos fortes                      | Limitações                            |
| ------------------ | -------------------------------- | ---------------------------------- | ------------------------------------- |
| Cascata            | Requisitos bem definidos         | Clareza e organização              | Rígido e pouco flexível               |
| Espiral            | Projetos grandes e complexos     | Gerenciamento de riscos e iteração | Requer mais tempo e análise           |
| Processo Unificado | Projetos bem estruturados        | Modularidade e equilíbrio          | Exige mais documentação               |
| Ágil (Scrum, XP)   | Projetos com requisitos mutáveis | Flexível, colaborativo e rápido    | Requer forte disciplina e comunicação |

