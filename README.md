# 🐍 Python Study Lab & LeetCoding

Plataforma interativa de estudo de **Python** e **Algoritmos (LeetCode)**, construída para aprendizado prático no navegador com execução de código em tempo real, simuladores visuais passo a passo, tabelas de rastreamento de variáveis (*trace tables*) e sistema gamificado de **Perfil, XP, Níveis e Conquistas** persistido via `localStorage`.

---

## 📚 Módulos e Laboratórios Disponíveis

| Fase | Arquivo | Conceitos de Python & Algoritmos | Desafio LeetCode Final |
| :--- | :--- | :--- | :--- |
| **Fase 1** | [`index.html`](./index.html) | Variáveis, Listas, Loops (`enumerate`) e Dicionários (*Hash Maps* `O(1)`) | **LeetCode #1 — Two Sum** |
| **Fase 2** | [`lab2_strings_twopointers.html`](./lab2_strings_twopointers.html) | Manipulação de Strings, `isalnum()`, *Slicing* (`[::-1]`) e Técnica **Two Pointers** | **LeetCode #125 — Valid Palindrome** |
| **Fase 3** | [`lab3_stacks_valid_parentheses.html`](./lab3_stacks_valid_parentheses.html) | Estrutura de Dados **Pilha (Stack — LIFO)**, `.append()`, `.pop()`, topo `stack[-1]` e Pareamento com Dicionários | **LeetCode #20 — Valid Parentheses** |
| **Fase 4** | [`lab4_sliding_window_stocks.html`](./lab4_sliding_window_stocks.html) | Estado Dinâmico, Rastreamento de Mínimo Histórico e **Sliding Window (Janela Deslizante)** em `O(n)` | **LeetCode #121 — Best Time to Buy and Sell Stock** |

---

## ✨ Recursos da Plataforma

- **🖥️ Editor Inteligente de Código Python no Navegador:**
  - Suporte a indentação com `Tab` (4 espaços), `Shift + Tab` (recuo) e auto-indentação inteligente ao pressionar `Enter` após `:`.
  - Auto-expansão dinâmica da área de código e acompanhamento automático do cursor (*scroll-to-cursor*).
  - Transpilador Python-para-JS embutido com suporte a funções, classes (`class Solution`), listas, dicionários, *list comprehensions*, `enumerate`, `range`, indexação negativa (`stack[-1]`), `if/elif/else` e métodos nativos.
- **📖 Didática Passo a Passo:**
  - Mini-desafios com campos limpos para prática ativa, botões de **💡 Dica**, **📖 Passo a Passo Explicado** e **👁️ Ver Solução**.
  - Tabelas de simulação linha a linha (*Trace Tables*) e anatomia comentada do código.
  - Simuladores visuais interativos em cada fase (Ponteiros, Pilha LIFO animada, Pregão da Bolsa de Valores).
- **🏆 Gamificação & Persistência de Dados (`localStorage`):**
  - **Auto-Save:** O código digitado em cada exercício e o status de conclusão ficam salvos automaticamente no navegador.
  - **Sistema de XP e Patentes:** Ganhe XP ao resolver mini-desafios (`+50 XP`), simuladores (`+30 XP`) e desafios do LeetCode (`+150 XP`), evoluindo do *Nível 1 (Iniciante Python)* ao *Nível 6 (Grão-Mestre Python)*.
  - **Conquistas e Backup:** Desbloqueie medalhas temáticas e exporte/importe seu progresso em JSON.

---

## 🚀 Como Executar

Basta abrir o arquivo [`index.html`](./index.html) em qualquer navegador moderno — não é necessário instalar dependências ou servidores externos.
