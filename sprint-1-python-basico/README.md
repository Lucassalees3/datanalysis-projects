# Sprint 1 — Python Básico

**Bootcamp:** TripleTen Data Analyst  
**Autor:** Lucas Henrique Sales Santos  
**Status:** ✅ Completo  
**Período:** Outubro/2026

---

## 🎯 Objetivo da Sprint

Dominar os fundamentos da linguagem Python: variáveis, tipos de dados, estruturas de controle (if/else, for, while), tratamento de exceções e manipulação de listas.

---

## 📊 Mini Projeto 1: Qualidade de Dados

**Contexto:** A Store 1 (e-commerce) está coletando dados de clientes e precisa avaliar a qualidade da amostra antes de análises futuras.

### Problemas Identificados e Corrigidos

| Problema | Variável | Solução Aplicada |
|----------|----------|------------------|
| Espaços e underscore no nome | `user_name` | `strip()` + `replace('_', ' ')` |
| Tipo float para idade | `user_age` | `int(user_age)` |
| Categorias em maiúsculas | `fav_categories` | Loop com `.lower()` |
| Conversão inválida de idade | `user_age` | Bloco `try/except ValueError` |

### Conceitos Aplicados

- **Manipulação de strings:** `strip()`, `replace()`, `split()`, `join()`
- **Conversão de tipos:** `int()`, tratamento de `ValueError`
- **Listas:** criação, iteração com `for`, append, indexação
- **Loops:** `for` e `while` com condição de parada
- **Funções built-in:** `sum()`, `max()`, `min()`, `randint()`
- **f-strings:** formatação de saída

### Resultado Final

- ✅ Receita total calculada: **$2.109**
- ✅ Filtro de clientes jovens (< 30 anos) com gastos > $1.000
- ✅ Relatório formatado de informações do usuário

---

##  Lições Aprendidas

1. **Dados reais são bagunçados:** Espaços, tipos errados e inconsistências são a regra, não a exceção.
2. **Defensive programming:** O bloco `try/except` evita que o programa quebre com entradas inválidas.
3. **Nomes descritivos importam:** Variáveis como `user` são mais legíveis que `values` em loops.
4. **f-strings são poderosas:** Permitem construir strings complexas de forma limpa.

---

## 📁 Estrutura
