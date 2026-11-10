# 🐍 Python Study Lab & LeetCoding (Trilha Completa — 10 Fases)

Plataforma interativa de estudo de **Python** e **Algoritmos (LeetCode)**, construída para aprendizado prático no navegador com execução de código em tempo real, simuladores visuais passo a passo, tabelas de rastreamento de variáveis (*trace tables*) e sistema gamificado de **Perfil, XP, Níveis e Conquistas** persistido via `localStorage`.

---

## 📚 Módulos e Laboratórios Disponíveis (Fases 1 a 10)

| Fase | Arquivo | Conceitos de Python & Algoritmos | Desafio LeetCode Final |
| :--- | :--- | :--- | :--- |
| **Fase 1** | [`index.html`](./index.html) | Variáveis, Listas, Loops (`enumerate`) e Dicionários (*Hash Maps* `O(1)`) | **LeetCode #1 — Two Sum** |
| **Fase 2** | [`lab2_strings_twopointers.html`](./lab2_strings_twopointers.html) | Manipulação de Strings, `isalnum()`, *Slicing* (`[::-1]`) e Técnica **Two Pointers** | **LeetCode #125 — Valid Palindrome** |
| **Fase 3** | [`lab3_stacks_valid_parentheses.html`](./lab3_stacks_valid_parentheses.html) | Estrutura de Dados **Pilha (Stack — LIFO)**, `.append()`, `.pop()`, topo `stack[-1]` e Pareamento com Dicionários | **LeetCode #20 — Valid Parentheses** |
| **Fase 4** | [`lab4_sliding_window_stocks.html`](./lab4_sliding_window_stocks.html) | Estado Dinâmico, Rastreamento de Mínimo Histórico e **Sliding Window (Janela Deslizante)** em `O(n)` | **LeetCode #121 — Best Time to Buy and Sell Stock** |
| **Fase 5** | [`lab5_binary_search.html`](./lab5_binary_search.html) | Divisão e Conquista, Divisão Inteira (`//`), Ponteiros `esq`/`dir` e **Busca Binária** em `O(log n)` | **LeetCode #704 — Binary Search** |
| **Fase 6** | [`lab6_sets_duplicates.html`](./lab6_sets_duplicates.html) | Conjuntos (`set()`), `.add()`, Unicidade e Detecção de Colisões em `O(1)` | **LeetCode #217 — Contains Duplicate** |
| **Fase 7** | [`lab7_kadane_max_subarray.html`](./lab7_kadane_max_subarray.html) | Somas Acumuladas, Subarrays Contíguos e **Algoritmo de Kadane** (`max(n, soma + n)`) em `O(n)` | **LeetCode #53 — Maximum Subarray** |
| **Fase 8** | [`lab8_two_pointers_water.html`](./lab8_two_pointers_water.html) | Geometria de Índices, Gargalo Mínimo (`min()`) e **Dois Ponteiros Convergentes** em `O(n)` | **LeetCode #11 — Container With Most Water** |
| **Fase 9** | [`lab9_dp_climbing_stairs.html`](./lab9_dp_climbing_stairs.html) | **Programação Dinâmica (DP 1D)**, Subproblemas Sobrepostos e Recorrência (`dp[i] = dp[i-1] + dp[i-2]`) | **LeetCode #70 — Climbing Stairs** |
| **Fase 10** | [`lab10_intervals_merge.html`](./lab10_intervals_merge.html) | Listas 2D, Ordenação (`.sort()`), Detecção de Sobreposição e **Fusão de Intervalos** em `O(n log n)` | **LeetCode #56 — Merge Intervals** |

---

## ✨ Recursos da Plataforma

- **🖥️ Editor Inteligente de Código Python no Navegador:**
  - Suporte a indentação com `Tab` (4 espaços), `Shift + Tab` (recuo) e auto-indentação inteligente ao pressionar `Enter` após `:`.
  - Auto-expansão dinâmica da área de código e acompanhamento automático do cursor (*scroll-to-cursor*).
  - Transpilador Python-para-JS embutido com suporte a funções, classes (`class Solution`), listas, dicionários, conjuntos (`set()`), *list comprehensions*, *slicing* (`nums[1:]`, `[::-1]`), divisão inteira (`//`), ordenação (`.sort()`), `enumerate`, `range`, indexação negativa (`stack[-1]`), `if/elif/else` e métodos nativos.
- **📖 Didática Passo a Passo:**
  - 30 Mini-desafios + 10 Problemas Oficiais do LeetCode com campos limpos para prática ativa, botões de **💡 Dica**, **📖 Passo a Passo Explicado** e **👁️ Ver Solução**.
  - Tabelas de simulação linha a linha (*Trace Tables*) e anatomia comentada do código.
  - 10 Simuladores visuais interativos (um para cada fase).
- **🏆 Gamificação & Persistência de Dados (`localStorage`):**
  - **Auto-Save:** O código digitado em cada exercício e o status de conclusão ficam salvos automaticamente no navegador em todas as 10 fases.
  - **Sistema de XP e Patentes:** Ganhe XP ao resolver mini-desafios (`+50 XP`), simuladores (`+50 XP`) e desafios do LeetCode (`+150 XP`) — até **3.500 XP** no total e **12 Medalhas de Conquista**.

---

## 🚀 Como Executar

Basta abrir o arquivo [`index.html`](./index.html) em qualquer navegador moderno — não é necessário instalar dependências ou servidores externos.
