## 🧱 Parte 4: Projeto de Software

### 🧭 O que é o projeto de software?

É a **fase central da engenharia de software**. Aqui, os requisitos coletados são transformados em uma **“planta técnica”**, ou seja, um conjunto de decisões e representações que orientam a construção do sistema.

> Sem um bom projeto, corremos o risco de criar software confuso, instável e difícil de manter.

---

### 🎯 Objetivos do projeto de software

* **Incorporar qualidade** desde o início.
* **Organizar** o sistema em partes (módulos).
* **Planejar** como os dados serão usados.
* **Facilitar testes, manutenção e evolução** do software.

---

### 🧠 Conceitos essenciais do projeto

1. **Abstração**
   Focar no essencial, deixando os detalhes para mais tarde.

2. **Arquitetura**
   Organização geral do sistema: componentes, relacionamentos e padrões.

3. **Padrões de projeto**
   Soluções reutilizáveis para problemas comuns.

4. **Separação por interesses**
   Dividir o sistema em partes independentes e especializadas.

5. **Modularidade**
   Criar componentes separados, com responsabilidades claras.

6. **Encapsulamento**
   Esconder detalhes internos e mostrar apenas o necessário.

7. **Independência funcional**
   Cada módulo deve fazer bem uma coisa e depender o mínimo de outros.

8. **Refinamento gradual**
   Começar do geral e ir detalhando aos poucos.

9. **Refatoração**
   Melhorar a estrutura do código/projeto sem mudar seu funcionamento.

---

### 🗂 Modelos do projeto

Para organizar tudo isso, usamos **modelos**. Cada modelo foca em uma parte do sistema:

| Modelo                       | O que representa                                                   |
| ---------------------------- | ------------------------------------------------------------------ |
| **Dados**                    | Como os dados são estruturados, armazenados e acessados.           |
| **Arquitetura**              | Como os módulos se conectam.                                       |
| **Interface (UI e sistema)** | Como o usuário interage com o sistema e como os módulos conversam. |
| **Componentes**              | Como cada parte funciona por dentro.                               |
| **Implantação**              | Como o sistema será instalado e executado nos dispositivos reais.  |

---

### 📐 Diretrizes para um bom projeto

* Use **padrões reconhecidos** de arquitetura.
* Organize o sistema de forma **modular**.
* Crie **interfaces simples e coesas**.
* Escolha **estruturas de dados adequadas**.
* Construa com base em **requisitos bem definidos**.
* Faça projetos **rastreáveis** (ligados aos requisitos).
* Use **notações compreensíveis** (UML, diagramas simples).
* Desenvolva de forma **iterativa**, refinando a cada ciclo.

---

### 🏛 Estilos e padrões de arquitetura

#### Estilos de arquitetura:

| Estilo                    | Características                                               |
| ------------------------- | ------------------------------------------------------------- |
| **Centralizado em dados** | Tudo gira em torno de um banco de dados central.              |
| **Fluxo de dados**        | Os dados passam por etapas até gerar um resultado.            |
| **Chamada e retorno**     | Uso de funções e procedimentos em sequência.                  |
| **Orientado a objetos**   | Tudo é estruturado em objetos com atributos e comportamentos. |

#### Padrões de arquitetura:

* **Economia**: foco no essencial, evitando excessos.
* **Visibilidade**: decisões do projeto devem ser fáceis de entender.
* **Espaçamento**: separar as partes sem perder a coesão.
* **Simetria**: consistência entre os componentes.
* **Emersão**: comportamentos emergem da boa organização e integração.

---

### 🔩 Projeto de Componentes

Um componente é uma **parte reutilizável e substituível** do sistema. Pode representar um módulo, uma classe ou uma função.

#### Princípios importantes:

* **OCP – Aberto para extensão, fechado para modificação**
* **LSP – Substituição de Liskov**: classes filhas devem funcionar onde se usa a classe mãe.
* **DIP – Inversão de dependência**: dependa de abstrações, não de implementações concretas.
* **ISP – Segregação de interfaces**: melhor ter várias interfaces específicas que uma genérica.
* **REP/CRP/CCP**: princípios para organizar pacotes e facilitar a reutilização e manutenção.

> A ideia é construir software que seja **modular, adaptável, reutilizável e com baixo acoplamento**.

---

### 🧑‍💻 Desenvolvimento baseado em componentes

Ao invés de programar tudo do zero, usamos **componentes prontos** (bibliotecas, APIs, etc.) e integramos com os nossos.

**Vantagens**:

* Menor tempo de desenvolvimento.
* Menor custo.
* Melhor qualidade (componentes já testados).
* Facilidade de manutenção.
