# To-Do List Interativa

## 🎯 Objetivo

Criar uma aplicação de lista de tarefas (**To-Do List**) com interface visual, onde o usuário possa adicionar, editar, marcar como concluída e remover tarefas.  
O foco será revisar **manipulação de estruturas de dados**, **algoritmos simples de busca e ordenação** e **interatividade na interface**.

## 🏆 Desafio

- Criar a interface gráfica para exibir e interagir com a lista.
- Implementar as operações principais (CRUD):
  - Criar tarefa
  - Listar tarefas
  - Atualizar tarefa
  - Remover tarefa
- Permitir **busca por palavra-chave** usando um algoritmo de busca simples.
- Permitir **ordenação** das tarefas (por data de criação ou ordem alfabética).
- Armazenar as tarefas em **memória** usando uma estrutura de dados (lista encadeada).
- Salvar e carregar as tarefas usando **Local Storage**.

## 📚 Conhecimento em prática

- Estruturas de dados básicas: arrays, listas.
- Algoritmos de busca linear.
- Algoritmo de ordenação simples (Insertion Sort ou Bubble Sort).
- Manipulação do DOM.
- Persistência de dados simples.
- Boas práticas de organização de código.

## 🧠 Conceitos e Habilidades Testadas

- **Estruturas de dados**:
  - Arrays para armazenamento dinâmico de tarefas.
  - Listas encadeadas (opcional para explorar outra abordagem).
- **Algoritmos**:
  - Busca linear para localizar tarefas por nome.
  - Ordenação por Insertion Sort ou Bubble Sort para organizar tarefas.
- **Análise de complexidade**:
  - Revisão de Big O para inserção, remoção, busca e ordenação.
- **Manipulação de dados**:
  - Adição, edição e exclusão em tempo real.
  - Persistência usando Local Storage ou arquivo local.
- **Programação com interface gráfica**:
  - Manipulação do DOM (JavaScript) ou componentes visuais (JavaFX).
  - Eventos de clique, entrada de texto e atualização de tela.
- **Organização de código**:
  - Separação entre lógica (funções) e apresentação (UI).
  - Modularização e reutilização de código.
- **Boas práticas**:
  - Nomenclatura clara de variáveis e funções.
  - Comentários explicativos.
  - Estrutura de pastas organizada.
- **Experiência do usuário (UX)**:
  - Layout limpo e intuitivo.
  - Feedback visual para ações (ex.: marcar tarefa como concluída).

## 🛠 Tecnologias sugeridas

- **JavaScript + HTML + CSS** (mais rápido para UI e fácil de visualizar)
- Local Storage (se JS) para persistência.

## 📌 Issues sugeridas (para medir progresso)

### Etapa 1 — Base do projeto

- [x] Criar repositório e README.md inicial.
- [ ] Estruturar pastas (`/src`, `/assets`, `/styles`).
- [ ] Criar arquivo HTML com estrutura inicial.

### Etapa 2 — Funcionalidades principais

- [ ] Criar array para armazenar tarefas.
- [ ] Implementar função para **adicionar** tarefa.
- [ ] Implementar função para **listar** tarefas.
- [ ] Implementar função para **remover** tarefa.
- [ ] Implementar função para **marcar tarefa como concluída**.

### Etapa 3 — Recursos extras

- [ ] Implementar **busca linear** de tarefa por nome.
- [ ] Implementar **ordenação alfabética** (Insertion Sort).
- [ ] Implementar **salvar no Local Storage**.
- [ ] Implementar **carregar do Local Storage**.

### Etapa 4 — Interface visual

- [ ] Criar layout com campos de entrada e lista visual.
- [ ] Adicionar botões de ação (adicionar, remover, concluir).
- [ ] Estilizar com CSS para melhor experiência.

### Etapa 5 — Refinamento

- [ ] Revisar código e adicionar comentários.
- [ ] Otimizar funções.
- [ ] Criar documentação final no README.md.

## 🔮 Extras (opcional)

- Filtro para mostrar apenas tarefas concluídas ou pendentes.
- Adicionar categorias para as tarefas.
- Modo escuro (dark mode).
- Animações na adição/remoção de tarefas.
