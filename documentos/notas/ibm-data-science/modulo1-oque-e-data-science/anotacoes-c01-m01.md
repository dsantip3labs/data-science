# Resumo e anotações pessoais do meu entedimento desse primeiro modulo

Isso vai ser um mini texto do meu entendimento enquanto repasso as coisas.

---

## Resumo

Sinceramente, nesse primeiro modulo, poucas coisas são uteis de verdade.
Todo o assunto é bem teorico por enquanto e traz um geral sobre o que é ser cientista de dados e quais são as suas atribuições, além de trazer a definição dessa função na visão de outras pessoas. Alguns a definem como um processo contínuo, e não um evento isolado. Seu propósito central é usar dados para compreender fenômenos, validar hipóteses e responder perguntas sobre o mundo. Ela combina curiosidade, investigação e ferramentas analíticas.
O curso traz um texto bem interessante " Ciência de dados - O trabalho mais sexy do século XXI", falando sobre a evolução dos dados, a necessidade do cargo e como as empresas buscam cientistas qualificados. Basicamente, cientistas de dados permitem que empresas entendam hábitos de consumo e tomem decisões mais precisas — o que tem grande valor comercial. 
Ainda ao longo do curso, eles retornam com alguns conselhos que se resumem a curiosidade, saber contar historias com dados e capacidade de argumentação, o curso define esses 3 coisas como essenciais para alguém que deseja ser cientista de dados.
Depois retorna com casos reais de cientista de dados, a utilização de redes neurais para identificar toxicidade na agua, um motor de recomendaçõ (pesquisar mais sobre isso aqui, achei bem legal) a utilização de dados estruturados e não estruturados para resolver um problema do TTC. Posteriormente, o curso retorna brevemente sobre os tipos de extensão utilizadas (json, csv, excel, xml e demais)

Ao final, esse modulo começa a ficar interessante de verdade. Nos introduz sobre os algoritmos e o conceito de regressão, trazendo uma analogia bem simples e facil de entender. Segue:

A ideia central
Regressão é uma forma de descobrir “a regra do preço” a partir de exemplos.
Você observa várias corridas e quer entender como o valor final é montado.
Traduzindo a corrida de táxi para regressão

- Tarifa base (constante / intercepto)

Quando você entra no táxi, já começa devendo um valor fixo (ex.: R$ 2,50).
Isso é a parte do preço que existe mesmo se você não andar nada.

- Custo por distância (coeficiente da distância)

A cada “x metros”, o valor aumenta.
Isso é a relação: quanto o preço sobe quando a distância aumenta.

- Custo por tempo (coeficiente do tempo)

Se você fica parado no trânsito, o tempo passa e o valor também sobe.
Isso é a relação: quanto o preço sobe quando o tempo aumenta.
Ou seja, o preço final pode ser entendido como:
Preço ≈ Tarifa base + (coef_distância × distância) + (coef_tempo × tempo)
O que a regressão “descobre” pra você
Mesmo que você não saiba:

- qual é a tarifa base,
- quanto cobra por km,
- quanto cobra por minuto,
…se você tiver um conjunto de dados com (distância, tempo, preço final) de várias corridas, a regressão consegue estimar:

- a tarifa base (constante),
- o peso da distância,
- o peso do tempo.

Por que isso é poderoso
Porque você sai de “tenho uma tabela de exemplos” para “tenho uma fórmula que:

- explica o que está acontecendo (interpretação),
- prevê quanto vai custar uma nova corrida (previsão).


E finaliza tudo com um texto bem interessante sobre o que faz alguém ser um cientista de dados. Gostei da definição do autor:

- "Eu defino um cientista de dados como alguém que encontra soluções para problemas analisando dados grandes ou pequenos, usando ferramentas adequadas, e depois conta histórias para comunicar suas descobertas aos stakeholders relevantes. Eu defino “ciência de dados” como aquilo que cientistas de dados fazem."

