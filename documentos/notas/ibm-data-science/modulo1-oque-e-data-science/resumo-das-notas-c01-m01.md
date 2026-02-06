# Módulo 1 — Fundamentos de Ciência de Dados (Notas)

> Objetivo do módulo: entender o que é Ciência de Dados, por que ela importa agora, como o processo funciona na prática e quais “pilares” sustentam um bom profissional.

---

## 1) Ideia central (definição que funciona no mundo real)

**Ciência de Dados é um processo contínuo, não um evento.**  
O propósito é **usar dados para entender fenômenos**, **validar hipóteses** e **responder perguntas** — combinando **curiosidade + investigação + ferramentas analíticas**.

O “produto final” raramente é um modelo; é **clareza para decidir**.

---

## 2) O que a prática exige (os pilares)

### 2.1 Curiosidade + hipótese
- O trabalho começa com **uma pergunta boa** (ou uma dor real da operação).
- Hipóteses nascem do mundo real (observação fora do notebook ajuda muito).

### 2.2 Encontrar padrão e gerar insight
- Identificar **padrões, tendências e anomalias**.
- Transformar “dado bruto” em **explicação + previsão + recomendação**.

### 2.3 Storytelling com dados (pilar obrigatório)
- Você “traduz” resultado para stakeholders: **narrativa compreensível + implicação + ação**.
- Visualização ajuda, mas o principal é: **o que mudou / por que mudou / o que fazer agora**.

---

## 3) Por que “nunca foi tão relevante quanto hoje”

O módulo destaca que o momento atual é favorável por:
- **Volume massivo de dados**
- **Algoritmos avançados e acessíveis**
- **Softwares gratuitos e open source**
- **Armazenamento barato**
- **Ferramentas de análise difundidas**

Tradução: o mundo está “dando dados” e cobrando gente que **pense** em cima deles.

---

## 4) Processo típico de Ciência de Dados (pipeline mental)

1. **Definir a pergunta** (o que a organização quer responder?)
2. **Coletar / integrar dados** (estruturados e não estruturados)
3. **Limpar e preparar** (transformar caos em tabela/modelo)
4. **Explorar** (EDA): padrões, outliers, hipóteses
5. **Modelar** (estatística/ML) e **avaliar**
6. **Comunicar** (storytelling + visual + trade-offs)
7. **Recomendar ação** e **monitorar** (efeito no mundo real)

> Se não vira decisão/ação, virou só “projeto bonito”.

---

## 5) “Ouro” dos cases citados (takeaways práticos)

### Case A — Motor de recomendação em empresa grande
- Ponto alto: **solução simples, explicável**, e tão eficiente quanto opções complexas.
- **Lição:** simplicidade escala e vende internamente.

### Case B — Prever blooms de algas (risco de toxicidade)
- Abordagem tradicional não resolveu; usaram **redes neurais** para prever recorrência.
- **Lição:** quando o método clássico não pega, ML pode destravar operação.

### Case C — Toronto Transit Commission (TTC) e 500k reclamações
- Dados estruturados + não estruturados; não achavam padrão.
- Hipótese veio da vida real (clima ruim).
- Cruzaram reclamações com **dados externos de clima** e encontraram correlação forte.
- Board: “boa notícia: sei o motivo; má notícia: vocês não controlam o clima”.
- **Lições:**
  - Observação fora do notebook destrava hipótese
  - **Dados internos + dados externos** = diferencial
  - Storytelling executivo é meio caminho andado

---

## 6) Tipos de dados e formatos (o que usar e quando)

### Estruturados vs não estruturados
- **Estruturados:** tabela (linhas/colunas) — fácil de consultar/modelar.
- **Não estruturados:** texto, áudio, vídeo, web — você normalmente trabalha para “virar estrutura”.

### Formatos abordados
- **CSV/TSV (delimitados):** troca rápida, simples; TSV evita conflito com vírgulas.
- **XLSX:** ótimo para consumo humano, análises rápidas e compartilhamento com negócio.
- **XML:** integração enterprise/legados; auto-descritivo.
- **PDF:** “congela” documento (jurídico/financeiro/auditoria).
- **JSON:** padrão de APIs; leve, legível e multiplataforma.

**Regra prática:**  
- API? **JSON**.  
- Troca rápida? **CSV/TSV**.  
- Negócio quer mexer? **XLSX**.  
- Documento “imutável”? **PDF**.  
- Integração legado? **XML**.

---

## 7) Regressão (explicação que cola na cabeça)

Analogia do táxi:

- **Tarifa base (intercepto):** valor inicial ao entrar no táxi.
- **Coef. distância:** quanto aumenta por km.
- **Coef. tempo:** quanto aumenta por minuto (trânsito).

Modelo mental:
**Preço ≈ base + (coef_dist × distância) + (coef_tempo × tempo)**

O que a regressão faz:
- Estima **base** e **pesos** a partir de exemplos (dados históricos).
- Serve para **explicar** e **prever**.

---

## 8) k-Nearest Neighbors (KNN) — TODO de estudo
- Algoritmo simples que muitas vezes performa bem.
- **Tarefa:** estudar ideia, distância, escolha de K, normalização, e como avaliar.

Checklist do KNN:
- [ ] O que é “vizinho” (métrica de distância)
- [ ] Escalonamento/normalização (evitar variável dominar)
- [ ] Como escolher K (validação)
- [ ] Overfitting vs underfitting
- [ ] Classificação vs regressão com KNN

---

## 9) Mini-glossário (pra revisar rápido)
- **Hipótese:** palpite estruturado que você testa com dados.
- **Insight acionável:** conclusão que muda uma decisão.
- **Stakeholders:** quem decide/é impactado.
- **Storytelling:** narrativa + evidência + implicação + ação.

---

## 10) Textos integrais (colar manualmente no repositório)
> Por motivos de copyright, eu não replico aqui “textos grandes” completos.
> Sugestão: crie `appendix_textos_integrais.md` e cole os 2 textos abaixo.

### Texto integral 1 


No mundo orientado por dados, cientistas de dados se tornaram profissionais extremamente disputados. A busca por talentos em ciência de dados está intensa, e especialistas estimam que milhões de vagas podem ficar abertas por falta de profissionais qualificados. As empresas procuram não apenas estatísticos ou cientistas da computação, mas profissionais completos, com conhecimento técnico, domínio de programação, entendimento de negócios e excelentes habilidades de comunicação.
A quantidade de dados digitais cresceu rapidamente. Em 1995, o universo digital tinha cerca de 130 bilhões de gigabytes; em 2020, chegou a 40 trilhões de gigabytes. Assim, empresas competem por milhares ou milhões de profissionais capazes de navegar por esse mundo digital. Por isso, a revista Harvard Business Review chamou ciência de dados de “o trabalho mais sexy do século XXI”.
Um relatório do McKinsey Global Institute alerta sobre a grande escassez de talentos. Só nos Estados Unidos, até 2018 haveria um déficit de 140 a 190 mil profissionais com habilidades analíticas profundas, além de 1,5 milhão de gestores capazes de usar dados para tomar decisões.
Com a revolução digital, a oportunidade de entender e prever comportamentos humanos é maior do que nunca. Pesquisas de neurologia e psicologia mostram como hábitos são formados, e varejistas como a Target lucram com isso — mas apenas com cientistas de dados em suas equipes. “É como uma corrida armamentista para contratar estatísticos”, disse Andreas Weigend, ex-cientista-chefe da Amazon.
Ainda é necessário convencer executivos de alto escalão. Muitos chegaram ao topo sem lidar com dados. Segundo o professor Peter Fader, mudanças reais ocorrerão quando esses líderes dominarem analytics.
A SAP relatou que 92% das empresas pesquisadas tiveram forte aumento nos seus volumes de dados, e 75% afirmaram precisar de novas habilidades em ciência de dados. A Accenture calcula que a demanda poderia superar a oferta em 250 mil profissionais em 2015. A KPMG encontrou que 85% dos executivos não sabiam analisar dados.
Bernard Marr, da Forbes, também alerta para o déficit de talentos: não há pessoas suficientes capazes de transformar dados brutos em insights acionáveis. Em uma pesquisa da Gartner, mais da metade dos líderes de negócios afirmou não ter expertise interna. O Walmart recorreu ao crowdsourcing e lançou uma competição na Kaggle para melhorar suas previsões de vendas.
Devido à escassez, empresas pagam salários muito altos. Michael Chui, da McKinsey, afirma que “há uma guerra por esse tipo de talento”. O caso de Paul Minton ilustra isso: depois de trabalhar servindo mesas e fazer um curso de programação de três meses, passou a ganhar mais de US$ 100 mil como cientista de dados. A média salarial relatada pelo New York Times é de US$ 100 mil para engenheiros de software e US$ 112 mil para cientistas de dados.


✅ 📌 Resumo do Texto

A ciência de dados tornou-se uma das profissões mais valorizadas do século XXI devido ao enorme crescimento na geração de dados. 
Há uma escassez global de profissionais com habilidades analíticas, programação, domínio de negócios e boa comunicação. 
Relatórios de consultorias como McKinsey, Accenture, SAP e KPMG apontam grande déficit de talentos. 
Muitas empresas ainda não entendem totalmente o potencial da análise de dados, principalmente na alta liderança (C‑suite). 
Cientistas de dados permitem que empresas entendam hábitos de consumo e tomem decisões mais precisas — o que tem grande valor comercial. 
A falta de profissionais leva empresas a buscarem alternativas, como competições na Kaggle. 
Os salários são muito altos: casos como o de Paul Minton mostram como uma formação rápida pode levar a empregos acima de US$ 100 mil/ano. 
Em média, cientistas de dados ganham mais do que engenheiros de software.



### Texto integral 2 


Agora que você já sabe o que há no livro, é hora de estabelecer algumas definições. Apesar de serem usadas o tempo todo, ainda não existe consenso sobre o que significam “Big Data” e “Ciência de Dados”. A pergunta “Quem é um cientista de dados?” continua muito viva — e é disputada por pessoas que, em alguns casos, só querem proteger sua disciplina ou seu “território” acadêmico. Nesta seção, tento tratar dessas controvérsias e explicar por que definições muito estreitas de Big Data ou de Ciência de Dados acabam excluindo centenas de milhares de pessoas que recentemente migraram para essa área emergente.
“Todo mundo ama um cientista de dados”, escreveu Simon Rogers (2012) no jornal The Guardian. Ele também relacionou esse amor recente por “mexer com números” a uma frase do Hal Varian, do Google, que declarou que o “trabalho sexy” dos próximos dez anos seria o de estatísticos.
Embora Hal Varian tenha chamado estatísticos de “sexy”, muita gente acredita que ele quis dizer, na prática, cientistas de dados. Isso levanta algumas perguntas importantes:

O que é ciência de dados?
Como ela difere de estatística?
O que faz alguém ser um cientista de dados?
Na era do Big Data, uma pergunta aparentemente simples como “o que é ciência de dados?” pode gerar muitas respostas. Em alguns casos, a diversidade de opiniões chega perto da hostilidade.
Eu defino um cientista de dados como alguém que encontra soluções para problemas analisando dados grandes ou pequenos, usando ferramentas adequadas, e depois conta histórias para comunicar suas descobertas aos stakeholders relevantes. Eu não uso o tamanho do dado como cláusula restritiva. Um conjunto de dados abaixo de um certo limite arbitrário não torna alguém “menos” cientista de dados. Também não restrinjo minha definição a ferramentas específicas, como machine learning. Se a pessoa tem mente curiosa, fluência analítica e capacidade de comunicar resultados, eu a considero cientista de dados.
Eu defino “ciência de dados” como aquilo que cientistas de dados fazem. Anos atrás, como estudante de engenharia na Universidade de Toronto, eu travava com a pergunta: “o que é engenharia?”. Fiz meu mestrado prevendo preços de casas e meu doutorado prevendo escolhas de construtoras: o que construir, quando construir e onde construir novas moradias. No departamento de engenharia civil, outros estavam projetando prédios, pontes, túneis e estudando estabilidade de encostas. Meu trabalho e o do meu orientador não eram o “arroz com feijão” da engenharia. Por isso, eu ouvia várias vezes se minha pesquisa era realmente engenharia.
Quando compartilhei isso com meu orientador de doutorado, o professor Eric Miller, ele riu. Ele passou a vida pesquisando uso do solo urbano e transporte, e tinha doutorado pelo MIT. “Engenharia é o que engenheiros fazem”, ele respondeu. Nos 17 anos seguintes, eu entendi a sabedoria dessa frase. Você vira engenheiro obtendo um diploma e registrando-se no órgão profissional que regula a engenharia. Agora você é engenheiro. Você pode cavar túneis; escrever código; projetar componentes de um iPhone ou de um jato supersônico — você é engenheiro. E quando você lidera a resposta global a uma crise financeira no cargo de economista-chefe do FMI, como fez o Dr. Raghuram Rajan, você também é engenheiro.
O professor Raghuram Rajan fez sua primeira graduação em engenharia elétrica no Instituto Indiano de Tecnologia. Depois estudou economia na pós-graduação, virou professor em uma universidade prestigiada e acabou no FMI. Hoje ele é o 23º governador do Banco Central da Índia. Alguém poderia dizer que todo o poder intelectual dele vem “somente” da economia e que os fundamentos aprendidos na engenharia não contribuíram para suas habilidades de resolver problemas?
O professor Rajan é engenheiro. Assim como Xi Jinping, presidente da República Popular da China, e Alexis Tsipras, o primeiro-ministro grego que está forçando o mundo a repensar fundamentos da economia global. Eles podem não estar projetando circuitos, equipamentos de destilação ou pontes, mas estão ajudando a construir sociedades e economias melhores — e não existe melhor definição de engenharia e de engenheiros do que pessoas dedicadas a construir economias e sociedades melhores.
Então, de forma breve, eu argumentaria que ciência de dados é o que cientistas de dados fazem.
Outros têm definições bem diferentes. Em setembro de 2015, um co-palestrante num meetup organizado pela BigDataUniversity.com em Toronto limitou ciência de dados a machine learning. Pronto: se você não está usando as “caixas-pretas” que compõem o machine learning, segundo alguns especialistas, você não é cientista de dados. Mesmo que você descubra a cura de uma doença que ameaça milhões, colegas “protetores de território” podem te excluir do “clube” da ciência de dados.
O Dr. Vincent Granville (2014), autor sobre ciência de dados, propõe certos “limites” para alguém ser cientista de dados. Nas páginas 8 e 9 de Developing Analytic Talent, ele descreve o novo professor de ciência de dados como um instrutor não efetivado, numa universidade não tradicional, que publica resultados em blogs, não perde tempo escrevendo pedidos de financiamento, trabalha de casa e ganha mais que professores efetivos tradicionais. Basta dizer que a comunidade acadêmica ativa pode discordar bastante disso.
Granville usa restrições de tamanho de dados e métodos para definir ciência de dados. Ele define cientista de dados como alguém que consegue processar facilmente um conjunto de 50 milhões de linhas em poucas horas e que desconfia de modelos estatísticos. Ele diferencia ciência de dados de estatística — mas ao mesmo tempo lista álgebra, cálculo e formação em probabilidade e estatística como base necessária para entender ciência de dados.
Alguns acham que Big Data é apenas passar de um certo limite de tamanho ou número de observações, ou usar uma ferramenta específica, como Hadoop. Esses limites arbitrários são problemáticos porque, com inovação, computadores comuns e softwares “de prateleira” já conseguem manipular conjuntos enormes. O Stata, software muito usado por cientistas de dados e estatísticos, anunciou que seria possível processar de 2 bilhões a 24,4 bilhões de linhas em soluções de desktop. Se Hadoop é a senha do clube do Big Data, então a capacidade do Stata de processar 24,4 bilhões de linhas (com certas limitações) invadiu essa festa do Big Data.
É importante perceber que quem tenta impor limites arbitrários para excluir outras pessoas tende a cair em inconsistências. O objetivo deveria ser definir ciência de dados de forma mais inclusiva — independente de disciplina, plataforma e tamanho — onde resolver problemas com foco em dados e construir narrativas fortes sejam o centro.
Dada a controvérsia, prefiro consultar outros para ver como descrevem um cientista de dados. Vamos consultar novamente o Chief Data Scientist dos EUA. Lembre que o Dr. Patil disse ao The Guardian em 2012 que um cientista de dados é uma combinação única de habilidades capaz de desbloquear insights nos dados e contar uma ótima história através deles. O admirável dessa definição é que ela inclui pessoas de várias formações acadêmicas e não restringe o conceito a uma ferramenta específica ou a um limite mínimo de tamanho de dados.
Outro ingrediente-chave para um bom cientista de dados é um traço comportamental: curiosidade. Um cientista de dados precisa ter uma mente muito curiosa, disposta a investir tempo e esforço para explorar seus palpites. No jornalismo, editores chamam isso de “faro de notícia”. Nem todo repórter sabe onde a notícia está. Só quem tem faro encontra a história. A curiosidade é tão importante para cientistas de dados quanto para jornalistas.
Rachel Schutt é Chief Data Scientist na News Corp. Ela dá aula de ciência de dados na Universidade Columbia e é autora do excelente livro Doing Data Science. Em entrevista ao New York Times, ela definiu um cientista de dados como alguém que é parte cientista da computação, parte engenheiro de software e parte estatístico (Miller, 2013). Mas isso seria a definição do cientista de dados “médio”. “Os melhores”, ela argumenta, “tendem a ser pessoas muito curiosas — pensadores que fazem boas perguntas e ficam confortáveis lidando com situações não estruturadas e tentando encontrar estrutura nelas.”


Resumo para aplicar no notebook (bem direto)

Definição inclusiva: Cientista de dados é quem resolve problemas com dados (grandes ou pequenos) usando ferramentas apropriadas e comunica insights com storytelling para stakeholders.
Sem gatekeeping: Tamanho do dado e “usar ML ou Hadoop” não definem quem é cientista de dados; limites arbitrários excluem gente boa e viram contradição.
Ciência de dados = prática: “Ciência de dados é o que cientistas de dados fazem” — uma área definida por atividade e entrega, não por rótulo acadêmico.
Skill core do cientista de dados:mente curiosa (faro de descobrir o que importa),
fluência analítica,
capacidade de transformar caos em estrutura (muito dado é não estruturado),
habilidade de contar a história dos dados (impacto e decisão).
Perfil “médio” vs “top”: Médio = mistura de computação + engenharia de software + estatística. Top = isso + curiosidade absurda e boas perguntas.


---

## 11) Resumo em 12 linhas (pra abrir o arquivo e lembrar do módulo)
- DS é processo contínuo: pergunta → dados → modelo → história → ação → feedback.
- Curiosidade e hipóteses são o motor.
- Valor real: padrões + insight + decisão.
- Storytelling não é “extra”: é parte do trabalho.
- Dados podem ser estruturados ou não estruturados (e você costuma “estruturar” o caos).
- Hoje é o melhor momento por volume + open source + armazenamento barato.
- Solução simples e explicável muitas vezes ganha de solução complexa.
- Juntar dados internos com externos pode ser o diferencial.
- Regressão = descobrir “tabela de preços do mundo” (base + pesos).
- KNN é simples e eficaz: estudar e saber explicar.
- Formatos importam: CSV/TSV, XLSX, XML, PDF, JSON.
- Se não vira ação/decisão, é só slide bonito.

## 12) Anotações geral sobre todo modulo