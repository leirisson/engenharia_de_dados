# engenharia_de_dados
estudo de dados para os meios politicos

Vamos montar um mini-laboratório de Análise Exploratória com Pandas, focado em cenários políticos.
A ideia: cada exercício terá um contexto político diferente, um CSV sintético com 1000 registros, e perguntas de análise para você responder.

📊 Exercício 1 – Intenção de Voto em Cidades

Contexto: Um instituto de pesquisa coletou dados de intenção de voto para prefeito em diferentes cidades.

📁 Arquivo CSV (simulado: intencao_voto.txt)
Colunas:

id → identificador do entrevistado

cidade → nome da cidade

idade → idade do eleitor

genero → M/F

candidato → nome do candidato escolhido

renda → faixa salarial (Baixa, Média, Alta)
🔎 Perguntas para explorar:

Qual candidato lidera em número total de votos?
Qual é a média de idade dos eleitores de cada candidato?
A renda influencia o voto? (compare distribuição de votos por faixa de renda).
Qual cidade tem maior concentração de votos no Candidato A?
========================================================================================
📊 Exercício 2 – Participação em Audiências Públicas
Contexto: A câmara municipal quer analisar a participação da população nas audiências públicas.
📁 Arquivo CSV (simulado: audiencias_publicas.txt)
Colunas:
id_evento
cidade
tema (Saúde, Educação, Segurança, Transporte, Habitação)
participantes → número de pessoas presentes
ano (2021–2025)
🔎 Perguntas para explorar:
Qual tema teve maior número médio de participantes?
Existe tendência de crescimento ou queda no comparecimento ao longo dos anos?
Quais cidades apresentam maior engajamento médio?
Qual tema foi mais debatido em 2025?
=======================================================================================
📊 Exercício 3 – Orçamento de Campanha
Contexto: Os partidos declararam seus gastos de campanha à justiça eleitoral.
📁 Arquivo CSV (simulado: orcamento_campanha.txt)
Colunas:
id
partido
candidato
valor_gasto
tipo_gasto (Propaganda, Eventos, Redes Sociais, Pesquisa, Logística)
estado
🔎 Perguntas para explorar:
Qual partido teve maior gasto total?
Qual categoria de gasto mais recebeu investimento?
Existe relação entre gasto médio e estado?
Qual candidato gastou mais em redes sociais?
=================================================================================================
📊 Exercício 4 – Aprovação de Governo
Contexto: Uma pesquisa avaliou a aprovação de governadores em diferentes estados.
📁 Arquivo CSV (simulado: aprovacao_governo.txt)
Colunas:
id
estado
idade
genero
avaliacao (Ótimo, Bom, Regular, Ruim, Péssimo)
escolaridade (Fundamental, Médio, Superior, Pós-graduação)
🔎 Perguntas para explorar:
Qual a avaliação mais frequente no geral?
Existe diferença de aprovação entre homens e mulheres?
Como a escolaridade influencia a percepção do governo?
Quais estados concentram maior índice de avaliação “Ótimo”?
=================================================================================================
Exercício 5 – Presença no Congresso
Contexto: Um levantamento sobre presença dos deputados federais em sessões no Congresso Nacional.
📁 Arquivo CSV (simulado: presenca_congresso.txt)
Colunas:
id_deputado
nome
partido
estado
presencas → número de sessões que compareceu
faltas → número de sessões que faltou
ano (2022–2025)
🔎 Perguntas para explorar:
Quais deputados tiveram mais de 90% de presença?
Qual partido apresenta maior média de faltas?
Existe tendência de queda ou aumento na presença ao longo dos anos?
Quais estados têm maior taxa média de presença?
================================================================================================
