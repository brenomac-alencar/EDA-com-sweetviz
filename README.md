# EDA-com-sweetviz

A análise exploratória dos dados ou Exploratory Data Analysis(EDA)
é o processo de analisar e resumir as principais características de um conjunto de dados, muitas vezes com o objetivo de compreender os padrões, relacionamentos e tendências existentes.

A EDA é a primeira etapa fundamental para o desenvolvimento de insights ou modelos, podendo ser um processo demorado e trabalhoso quando se estiver tratando grande bases de dados.

Felizmente hoje existem ferramentas que facilitam esse processo e conseguem entregar resultados surpreendentes, umas delas é o **sweetviz**.

O framework **sweetviz** é uma biblioteca aberta em python, a qual  permite analisar as principais caracteristicas e relações existentes em um conjunto de dados com poucas linhas de código.

O output do **sweetviz** é em HTML e gera resultados como:

**Resumo de métricas por variáveis** = o framewoork infere por variáveis medidas como soma, média, mediana, variância, desvio padrão, mínimos, máximos, amplitude, quartis, assimetria, curtose, quantidade de valores destintos e percentual de missing.

**Comparação de bases** = o pacote permite compara as medidas de distribuição das variáveis entre bases distintas, como por exemplo, comparar bases de treino e teste de um modelo ou dados de ocorrências de anos diferentes.

**Análises de target** = A ferramenta permite você determinar uma coluna target, como por exemplo um modelo de clasificação, assim entregando insights de como a variável dependente (Target) se comportar por variáveis independentes (Features).


Aqui vai um depoimento pessoal, eu utilizo o sweetviz no meu dia a dia por que ele aguenta o "tranco" do trabalho, já apliquei ele em bases de 5 até 10 milhōes de registros aproximadamente e ele conseguiu processar sem problemas, ao contrário de outros pacotes como Pandas Profiling ou Dataprep, que comigo tiveram problemas em lidar com grandes volumes de dados e precisaram de uma amostragem dos dados para realizar as análises.
