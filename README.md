# Análise dos dados nacionais do INCA (Instituto Nacional de Câncer)

## Contextualização

<div align="justify"><p> O câncer não é uma doença recente, ele assola a sociedade mundial há séculos causando milhares de mortes todos anos. Embora seja conhecido há muito tempo, foi apenas com o avanço dos estudos e da tecnologia que se pôde entender melhor quais os melhores métodos de prevenção e tratamento.</p>

<p>Os primeiros marcos, sem dúvida alguma, foram as descobertas dos raios-X em 1895 pelo alemão Wilhelm Conrad Röentgen e dos elementos radiotivos em 1902 pelo casal Curie. A partir desse momento começaram-se as utilizações clínicas dessas descobertas e a evolução no tratamento de câncer. Hoje, temos a consolidação da radio e quimioterapias sendo amplamentes utilizadas, fármacos mais eficientes, além de diversos estudos em prevenção de novos casos.</p>

<p>No Brasil, em 1941 foi criado formalmente o Serviço Nacional de Câncer (SNC), primeiro exclusivo para atender às preocupações com a doença. Depois dele, foram realizados diversos congressos para debater os tratamentos, revistas para discussão, órgãos responsáveis, bancos de dados da população para elaboração de planos de ações, equipamentos, criação do SUS em 1990, legislações e muitos outros acontecimentos que propiciaram um maior acesso da população aos tratamentos. <b>Todavia, o câncer ainda é uma doença delicada e assunto preocupante no país porque continua matando milhares de pessoas anualmente no Brasil e no mundo. Portanto, é inquestionável a necessidade de avaliação contínua do máximo de parâmetros possíveis sobre a doença</b>.</p></div>

**Fontes:**

<http://www.historiadocancer.coc.fiocruz.br/linhadotempo/>

<https://www.scielo.br/j/qn/a/xtjYm7RZvYjTyGf5zJJjgCQ/?lang=pt>

<https://www.gov.br/casacivil/pt-br/assuntos/noticias/2020/setembro/sus-completa-30-anos-da-criacao>


## Descrição do projeto

<div align="justify"><p>O projeto visa analisar o banco de dados sobre diagnósticos de câncer no Brasil disponibilizados pelo INCA (https://www.inca.gov.br/) utilizando as seguintes tecnologias:</p></div>

>* Pandas
>* Numpy
>* Jupyter
>* Matplotlib
>* Seaborn

<div align="justify"><p>O projeto foi dividido em duas etapas:</p></div>

### ETAPA 01
<div align="justify"><p>Essa foi a primeira etapa do projeto. Nela, foi utilizado um dataset disponibilizado via pedido por e-mail - disponível no site - para o INCA que mostra os dados de 2012 a 2019. </p></div>

### Objetivo da ETAPA 01

#### Objetivo

<div align="justify"><p>O objetivo dessa etapa é respoder as seguintes perguntas pela ANÁLISE EXPLORATÓRIA:</p></div>

> 01. Qual é a distribuição quantitativa de casos de câncer de 2012 a 2019 no Brasil?
> 02. Qual é a idade mais afetada pelo câncer na população total?
> 03. Qual é a faixa etária mais afetada pelo câncer?
> 04. Qual é o sexo mais afetado considerando faixas etárias?
> 05. Qual é a distribuição quantitativa de casos por estado?
> 06. Houveram deslocamentos interestaduais para a realização do tratamento?

### ETAPA 02 (Em andamento...)
<div align="justify"><p>Na etapa 01 desse projeto, foram encontradas diversas dificuldades em virtude da ausência de alguns dados que são de suma importância para uma análise coesa e mais próxima da realidade. Por isso, nessa etapa, está sendo utilizado um dataset mais robusto retirado diretamente do site do INCA (<https://irhc.inca.gov.br/RHCNet/visualizaTabNetExterno.action>).</p></div>

#### Objetivo

<div align="justify"><p>O objetivo dessa etapa é respoder as seguintes perguntas pela ANÁLISE EXPLORATÓRIA:</p></div>

> 01. Qual é a distribuição quantitativa de casos de câncer de 2000 a 2019 no Brasil?
> 02. Qual é a idade mais afetada pelo câncer na população total?
> 03. Qual é a o tipo de câncer mais comum na população total?


