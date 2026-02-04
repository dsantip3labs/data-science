# Data Science — IBM Track + Projects

Repositório para centralizar meus estudos de Ciência de Dados (principalmente via Coursera/IBM) + prática diária + projetos de portfólio.

---

## Objetivos

- Consolidar fundamentos (método, ferramentas, Python, SQL, análise, visualização).
- Construir projetos aplicados (mini-projetos + capstone-like) com documentação.
- Manter uma trilha rastreável: progresso, entregas, revisão e aprendizado real.

---

## Estrutura do repositório

data-science/
├─ README.md
├─ ROADMAP.md
├─ requirements.txt
├─ .gitignore
├─ data/ # NÃO versionar dados pesados
│ ├─ raw/ # ignorado
│ ├─ interim/ # ignorado
│ └─ processed/ # ignorado
├─ notebooks/
│ ├─ course/ # alinhado ao curso (IBM)
│ │ ├─ c01_.../
│ │ ├─ c02_.../
│ │ └─ ...
│ └─ experiments/ # testes soltos
├─ projects/
│ ├─ mini_projects/
│ └─ capstone/
├─ src/ # código reutilizável (limpeza, features, modelos)
│ ├─ data/
│ ├─ features/
│ ├─ models/
│ └─ visualization/
├─ reports/
│ ├─ figures/
│ └─ summaries/ # one-pagers, conclusões
├─ docs/
│ ├─ notes/ # notas em Markdown
│ └─ references/ # links/cheatsheets
└─ scripts/
├─ download_data.py
└─ train_model.py

---

## Convenções (pra não virar caos)

### Notebooks

- Padrão: `YYYY-MM-DD_tema.ipynb`
- Ex.: `2026-02-04_pandas_groupby.ipynb`

### Pastas de curso

- `notebooks/course/cXX_nome/` (um “cXX” por módulo/curso)

### Commits

- `course: ...` (conteúdo do curso)
- `practice: ...` (notebook de prática)
- `project: ...` (projeto)
- `docs: ...` (notas e documentação)

---

## Setup do ambiente (simples)

### 1) Criar e ativar venv

**Windows (PowerShell):**

```bash
python -m venv .venv
.\.venv\Scripts\Activate.ps1
