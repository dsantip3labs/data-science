# 📅 Objetivo: 7h/dia, 5x na semana

## Distribuição Diária

- **5h** IBM (aula + lab)
- **2h** prática/projeto (GitHub, Notebooks, etc)

---

## 📚 Regra de Ouro: Como Estudar no Coursera Sem Virar Espectador

### 1) Regra 70/30

**70% fazendo** (labs, notebooks, exercícios, código)  
**30% consumindo** (vídeos/leitura)  

⚠️ **Se você passar disso, vira Netflix com certificado.**

### 2) Sempre "Duas Passadas"

**Passada 1 (rápida):** assistir/ler sem pausar muito, só marcando dúvidas.

**Passada 2 (ativa):** refazer com as mãos:

- Código do zero
- Explicar em 5 linhas

### 3) "Feynman do Pobre" (funciona absurdamente)

No final de cada aula/módulo, escreva:

1. **O que é**
2. **Pra que serve**
3. **Como eu aplico**
4. **Erro comum**
5. **Mini-exemplo** (3–10 linhas de código)

// ...existing code...

### ✅ Opção A (recomendado): Markdown dentro do repo

Crie `docs/notes/` e faça notas por curso:

```
docs/notes/c04_python.md
docs/notes/c06_sql.md
docs/notes/c07_dataviz.md
...
```

**Vantagens:**

- ✔️ Versionado
- ✔️ Organizado
- ✔️ Você acha tudo
- ✔️ Vira portfólio

### ⚠️ Opção B: Notion/Obsidian (se você curte UI)

Só vale se você:

- Mantiver um padrão fixo
- Linkar suas notas pros notebooks no GitHub

// ...existing code...

## 🧠 Como Fixar (o que realmente dá resultado)

### 1) Um Notebook por Dia

No seu repo: `notebooks/course/cXX/2026-02-04_tema.ipynb`

**Conteúdo mínimo:**

- import + carregamento
- 1 transformação
- 1 visual simples
- 3 bullets de conclusão

### 2) Cartões de Revisão

Crie no final do dia **5–10 "perguntas curtas"**, tipo:

- "Qual a diferença entre loc e iloc?"
- "Quando usar groupby + agg?"
- "O que é data leakage?"
- "Como fazer feature scaling?"
- "Qual a diferença entre train/test split?"

// ...existing code...

### 3) Revisão Espaçada (15 min)

| Quando | Ação |
|--------|------|
| **D+1** | Releia seu resumo + rode o notebook |
| **D+7** | Reescreva o resumo em 10 linhas |
| **D+30** | Refaça o exercício sem olhar |

// ...existing code...

## 📋 Template Pronto pra Usar (copia e cola)

Crie um arquivo por módulo: `docs/notes/TEMPLATE.md`

```markdown
# [Nome do Módulo]

## Resumo em 10 linhas
[seu resumo aqui]

## 3 Ideias-Chave

1. [Ideia 1]
2. [Ideia 2]
3. [Ideia 3]

## 2 Erros Comuns

1. [Erro 1]
2. [Erro 2]

## 1 Analogia / Explicação Simples
[Sua analogia aqui]

## Código Mínimo (Exemplo)
\`\`\`python
# seu código aqui
\`\`\`

## Checklist do que eu sei fazer agora

- [ ] Conceito 1
- [ ] Conceito 2
- [ ] Conceito 3

## Perguntas pra Revisão (5)

1. [Pergunta 1]
2. [Pergunta 2]
3. [Pergunta 3]
4. [Pergunta 4]
5. [Pergunta 5]
```

---

## 🎯 Como Usar os Quizzes do Coursera do Jeito Certo

1. **Faça uma tentativa "no seco"** (sem olhar nada)
2. **Depois revise o conteúdo**
3. **Refaça o quiz** explicando por que as alternativas erradas são erradas