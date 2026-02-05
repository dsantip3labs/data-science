# Data Science — IBM Track + Projects

Repositório para centralizar meus estudos de Ciência de Dados (principalmente via Coursera/IBM) + prática diária + projetos de portfólio.

---

## Objetivos

- Consolidar fundamentos (método, ferramentas, Python, SQL, análise, visualização).
- Construir projetos aplicados (mini-projetos + capstone-like) com documentação.
- Manter uma trilha rastreável: progresso, entregas, revisão e aprendizado real.

---

## Estrutura do repositório

```bash
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
```

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
```

## Livros

Guia Do Python Para Data Science - Tradução da Segunda Edição: Ferramentas Essenciais Para Trabalhar com Dados: https://www.amazon.com.br/Guia-Python-Para-Data-Science/dp/8550821713/ref=sr_1_2_sspa?__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1H1T8QEL47001&dib=eyJ2IjoiMSJ9.n2IBd1nTI6BYwchEpxjoGLpkJDeCJFZ1pxdYqVgmJ2M_Xy5wbjj219VZSfLV7Sum3IACe-ihcOOkhY6oKLBRSwnQo1t9ewwwHT9ZZ-QeXWzMbECgvxV1HTvKgtuzPZArg_jTElKr_9RujNdQVG1Z21IYfi-QHr_KPqA9stWsU6LFNMT9w0SHQ6qXGC2qiihRG5aEtFQiFvy5Ehb3bMwsGr6w-iTF4Xi6SjZRy7P6LanbIg2P5X_C39Oj9H0f-gpe4RBYNLqGPluuxNnqwPKcPqpVDiLNavMkHj_Lq-2ajp4.fJEF43TmQimlRWCD2jt1MarvIkopI8Y4vAczj-LKL38&dib_tag=se&keywords=ciencia+de+dados&qid=1770231578&sprefix=ciencia+de+dad%2Caps%2C290&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1

Data Science do Zero - 2º Edição: Noções Fundamentais com Python : https://www.amazon.com.br/Data-Science-Do-Zero-Fundamentais/dp/8550811769/ref=sr_1_5?__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1H1T8QEL47001&dib=eyJ2IjoiMSJ9.n2IBd1nTI6BYwchEpxjoGLpkJDeCJFZ1pxdYqVgmJ2M_Xy5wbjj219VZSfLV7Sum3IACe-ihcOOkhY6oKLBRSwnQo1t9ewwwHT9ZZ-QeXWzMbECgvxV1HTvKgtuzPZArg_jTElKr_9RujNdQVG1Z21IYfi-QHr_KPqA9stWsU6LFNMT9w0SHQ6qXGC2qiihRG5aEtFQiFvy5Ehb3bMwsGr6w-iTF4Xi6SjZRy7P6LanbIg2P5X_C39Oj9H0f-gpe4RBYNLqGPluuxNnqwPKcPqpVDiLNavMkHj_Lq-2ajp4.fJEF43TmQimlRWCD2jt1MarvIkopI8Y4vAczj-LKL38&dib_tag=se&keywords=ciencia+de+dados&qid=1770231578&sprefix=ciencia+de+dad%2Caps%2C290&sr=8-5

Estatística e Ciência de Dados: https://www.amazon.com.br/Estat%C3%ADstica-Ci%C3%AAncia-Dados-Alberto-Morettin/dp/852163899X/ref=sr_1_4?__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1H1T8QEL47001&dib=eyJ2IjoiMSJ9.n2IBd1nTI6BYwchEpxjoGLpkJDeCJFZ1pxdYqVgmJ2M_Xy5wbjj219VZSfLV7Sum3IACe-ihcOOkhY6oKLBRSwnQo1t9ewwwHT9ZZ-QeXWzMbECgvxV1HTvKgtuzPZArg_jTElKr_9RujNdQVG1Z21IYfi-QHr_KPqA9stWsU6LFNMT9w0SHQ6qXGC2qiihRG5aEtFQiFvy5Ehb3bMwsGr6w-iTF4Xi6SjZRy7P6LanbIg2P5X_C39Oj9H0f-gpe4RBYNLqGPluuxNnqwPKcPqpVDiLNavMkHj_Lq-2ajp4.fJEF43TmQimlRWCD2jt1MarvIkopI8Y4vAczj-LKL38&dib_tag=se&keywords=ciencia+de+dados&qid=1770231578&sprefix=ciencia+de+dad%2Caps%2C290&sr=8-4&ufe=app_do%3Aamzn1.fos.fcd6d665-32ba-4479-9f21-b774e276a678

Data science para negócios: https://www.amazon.com.br/Data-Science-para-neg%C3%B3cios-Fawcett/dp/8576089726/ref=sr_1_1_sspa?__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1H1T8QEL47001&dib=eyJ2IjoiMSJ9.n2IBd1nTI6BYwchEpxjoGLpkJDeCJFZ1pxdYqVgmJ2M_Xy5wbjj219VZSfLV7Sum3IACe-ihcOOkhY6oKLBRSwnQo1t9ewwwHT9ZZ-QeXWzMbECgvxV1HTvKgtuzPZArg_jTElKr_9RujNdQVG1Z21IYfi-QHr_KPqA9stWsU6LFNMT9w0SHQ6qXGC2qiihRG5aEtFQiFvy5Ehb3bMwsGr6w-iTF4Xi6SjZRy7P6LanbIg2P5X_C39Oj9H0f-gpe4RBYNLqGPluuxNnqwPKcPqpVDiLNavMkHj_Lq-2ajp4.fJEF43TmQimlRWCD2jt1MarvIkopI8Y4vAczj-LKL38&dib_tag=se&keywords=ciencia+de+dados&qid=1770231578&sprefix=ciencia+de+dad%2Caps%2C290&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1

Estatística Prática Para Cientistas de Dados: +50 Conceitos Essenciais Usando R e Python: https://www.amazon.com.br/Estat%C3%ADstica-Pr%C3%A1tica-Para-Cientistas-Dados/dp/8550826510/ref=sr_1_6?__mk_pt_BR=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1H1T8QEL47001&dib=eyJ2IjoiMSJ9.n2IBd1nTI6BYwchEpxjoGLpkJDeCJFZ1pxdYqVgmJ2M_Xy5wbjj219VZSfLV7Sum3IACe-ihcOOkhY6oKLBRSwnQo1t9ewwwHT9ZZ-QeXWzMbECgvxV1HTvKgtuzPZArg_jTElKr_9RujNdQVG1Z21IYfi-QHr_KPqA9stWsU6LFNMT9w0SHQ6qXGC2qiihRG5aEtFQiFvy5Ehb3bMwsGr6w-iTF4Xi6SjZRy7P6LanbIg2P5X_C39Oj9H0f-gpe4RBYNLqGPluuxNnqwPKcPqpVDiLNavMkHj_Lq-2ajp4.fJEF43TmQimlRWCD2jt1MarvIkopI8Y4vAczj-LKL38&dib_tag=se&keywords=ciencia+de+dados&qid=1770231578&sprefix=ciencia+de+dad%2Caps%2C290&sr=8-6