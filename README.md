# Projeto de Exploração de Conceitos - Analista de Dados do Microsoft Power BI

## Sumário

[1. Introdução à análise de dados da Microsoft](#Introdução-à-análise-de-dados-da-Microsoft)

&nbsp;&nbsp;&nbsp;&nbsp; [1.1. Introdução](#Introdução)

&nbsp;&nbsp;&nbsp;&nbsp; [1.2. Visão geral da análise de dados](#Visão-geral-da-análise-de-dados)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [1.2.1. Análise descritiva](#Análise-descritiva)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [1.2.2. Análise diagnóstica](#Análise-diagnóstica)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [1.2.3. Análise preditiva](#Análise-preditiva)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [1.2.4. Análise prescritiva](#Análise-prescritivas)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [1.2.5. Análise cognitiva](#Análise-cognitiva)

&nbsp;&nbsp;&nbsp;&nbsp; [1.3. Funções em dados](#Funções-em-dados)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [1.3.1. Analista de negócios](#Analista-de-negócios)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [1.3.2. Analista de dados](#Analista-de-dados)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [1.3.3. Engenheiro de dados](#Engenheiro-de-dados)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [1.3.4. Cientista de dados](#Cientista-de-dados)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [1.3.5. Administrador de banco de dados](#Administrador-de-banco-de-dados)

&nbsp;&nbsp;&nbsp;&nbsp; [1.4. Tarefas de um analista de dados](#Tarefas-de-um-analista-de-dados)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [1.4.1. Preparar](#Preparar)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [1.4.2. Modelar](#Modelar)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [1.4.3. Visualizar](#Visualizar)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [1.4.4. Analisar](#Analisar)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [1.4.5. Gerenciar](#Gerenciar)

&nbsp;&nbsp;&nbsp;&nbsp; [1.5. Resumo](#Resumo)

[2. Preparar dados para análise com o Power BI](#Preparar-dados-para-análise-com-o-Power-BI)

[3. Modelar dados com o Power BI](#Modelar-dados-com-o-Power-BI)

[4. Criar elementos visuais e relatórios do Power BI](#Criar-elementos-visuais-e-relatórios-do-Power-BI)

[5. Gerenciar espaços de trabalho e modelos semânticos no Power BI](#Gerenciar-espaços-de-trabalho-e-modelos-semânticos-no-Power-BI)

[6. Fonte](#Fonte)

# Introdução à análise de dados da Microsoft

## Introdução

O papel do analista de dados é fundamental no cenário atual, onde as organizações geram e armazenam grandes volumes de dados diariamente. Esses dados vêm de diversas fontes, como transações, serviços, redes sociais e comportamentos de consumo. O grande desafio das empresas é transformar esses dados em ações estratégicas que impulsionem os negócios.

Usar dados de forma eficaz pode ajudar no controle de inventário, identificação de padrões de consumo, recomendações personalizadas, detecção de fraudes e otimizações de preço, entre outras aplicações. No entanto, apenas coletar dados não é suficiente: é preciso interpretá-los e criar narrativas claras e significativas que apoiem a tomada de decisões.

Essa narrativa baseada em dados deve ser acessível, direcionada ao público certo e integrada ao dia a dia da organização, promovendo uma cultura orientada por dados. Para isso, o analista precisa trabalhar em parceria com engenheiros e cientistas de dados, garantindo que as análises gerem valor real.

Ao longo do processo, a análise de dados se torna uma ferramenta poderosa para descobrir insights, influenciar decisões e transformar dados em vantagem competitiva.

## Visão geral da análise de dados

Antes de servirem para contar uma história, os dados precisam passar por um processo de preparação — identificação, limpeza, transformação e modelagem — conhecido como análise de dados. Esse processo gera insights úteis que são apresentados por meio de relatórios e narrativas para apoiar a tomada de decisão.

Com o avanço do mundo orientado por dados, contar histórias com dados tornou-se essencial para empresas de todos os tamanhos, justificando a crescente demanda por analistas de dados. No entanto, muitas organizações ainda enfrentam o desafio de não utilizar todo o potencial dos dados.

A análise de dados é crucial para entender o impacto nos negócios, como identificar tendências, avaliar opiniões de clientes e conduzir pesquisas. Seus principais tipos são:

- Descritiva: o que aconteceu

- Diagnóstica: por que aconteceu

- Preditiva: o que pode acontecer

- Prescritiva: o que deve ser feito

- Cognitiva: uso de inteligência artificial para análises autônomas

### Análise descritiva

Responde à pergunta "o que aconteceu?" com base em dados históricos. 

Ela resume grandes volumes de dados para fornecer visão clara aos stakeholders, sendo essencial na criação e acompanhamento de KPIs (indicadores-chave de desempenho), como o ROI. É amplamente usada em relatórios de desempenho financeiro e de vendas, ajudando a avaliar o progresso de metas e objetivos.

### Análise diagnóstica

Busca responder à pergunta "por que algo aconteceu?". 

Ela aprofunda os resultados da análise descritiva para identificar as causas por trás de eventos ou mudanças nos indicadores de desempenho. O processo envolve três etapas:

- Identificar anomalias nos dados;

- Coletar dados relacionados a essas anomalias;

- Aplicar técnicas estatísticas para encontrar relações e tendências que expliquem o ocorrido.

### Análise preditiva

Responde à pergunta "o que poderá acontecer?". 

Ela utiliza dados históricos para identificar tendências e prever eventos futuros. Para isso, aplica técnicas de machine learning e estatística, como redes neurais, árvores de decisão e regressão, oferecendo insights valiosos para a antecipação de cenários.

### Análise prescritiva

Responde à pergunta "o que deverá ser feito?" para alcançar objetivos. 

Ela orienta a tomada de decisões baseada em dados, mesmo em cenários incertos. Utiliza machine learning para identificar padrões em grandes volumes de dados e, com base em decisões passadas, estima a probabilidade de diferentes resultados, ajudando as organizações a escolher as melhores ações.

### Análise cognitiva

Busca inferir conhecimento a partir de padrões e dados existentes, criando um ciclo de autoaprendizado ao alimentar novas descobertas em sua base de conhecimento. Diferente de regras fixas, suas hipóteses são não estruturadas e vêm de diversas fontes, com diferentes níveis de confiança. Utiliza machine learning e processamento de linguagem natural para interpretar dados complexos e não estruturados, como análises de produtos e logs de call center, ajudando a prever possíveis cenários futuros e a lidar com mudanças.

## Funções em dados

Criar uma narrativa com dados não começa com o analista — os dados vêm de outras fontes e, muitas vezes, prepará-los está fora do seu escopo. Projetos atuais são complexos e colaborativos, exigindo o trabalho conjunto de profissionais com habilidades complementares.

Antigas funções, como analistas de negócios e desenvolvedores de BI, evoluíram devido ao aumento e à diversidade dos dados, dando origem a papéis mais especializados nas áreas de engenharia e análise de dados, com foco em modernizar e simplificar o tratamento das informações.

As seguintes seções realçam as diferentes funções em dados e a responsabilidade específica no espectro total, de descoberta e compreensão de dados:

- Analista de negócios

- Analista de dados

- Engenheiro de dados

- Cientista de dados

- Administrador de banco de dados

### Analista de negócios

Apesar das semelhanças, a principal diferença entre analista de dados e analista de negócios está no uso dos dados. O analista de negócios atua mais próximo da empresa, focando na interpretação dos dados para apoiar decisões. Em alguns casos, ambas as funções podem ser desempenhadas por uma única pessoa.

### Analista de dados

O analista de dados ajuda as empresas a extrair valor dos dados por meio de ferramentas como o Power BI, sendo responsável por criação de perfis, limpeza, transformação e modelagem semântica de dados. Ele cria relatórios analíticos avançados e colabora com stakeholders para entender requisitos e gerar insights relevantes.

Também gerencia ativos do Power BI (relatórios, dashboards, workspaces e modelos), garantindo a segurança dos dados conforme as necessidades dos stakeholders. Trabalha em parceria com engenheiros de dados e administradores de banco de dados para localizar fontes adequadas, garantir acesso e melhorar processos de coleta e análise de dados.

### Engenheiro de dados

O engenheiro de dados é responsável por provisionar, configurar e gerenciar plataformas de dados locais e na nuvem, lidando com dados estruturados e não estruturados provenientes de diversas fontes. Ele garante que os serviços de dados estejam seguros e integrados, utilizando ferramentas para ingestão, transformação e saída de dados.

Colabora com stakeholders para entender os requisitos e desenvolver soluções. Seu papel vai além do do administrador de banco de dados, com foco em estruturar dados para apoiar projetos de BI e ciência de dados.

Trabalha em conjunto com analistas de dados, garantindo o acesso às fontes e otimizando modelos semânticos oriundos de data lakes ou data warehouses modernos. Profissionais de BI e DBAs podem migrar para essa função aprendendo as tecnologias voltadas ao processamento de grandes volumes de dados.

### Cientista de dados

Os cientistas de dados realizam análises avançadas, que vão desde a exploratória (EDA) até a preditiva, utilizando machine learning para identificar padrões e anomalias. Alguns atuam também com aprendizado profundo, criando algoritmos personalizados para resolver problemas complexos.

Grande parte do trabalho envolve estruturação de dados e engenharia de atributos, tarefas que podem ser otimizadas com apoio de engenheiros de dados. Embora pareçam distintos, cientistas e analistas de dados trabalham de forma complementar: o cientista formula hipóteses e experimentos, enquanto o analista ajuda na visualização e geração de relatórios.

### Administrador de banco de dados

O administrador de banco de dados (DBA) gerencia os aspectos operacionais de soluções de dados em ambientes híbridos e em nuvem, como Azure e SQL Server. É responsável pela disponibilidade, desempenho, segurança, além de backups e planos de recuperação.

Diferente do engenheiro de dados, que atua na estruturação e preparação dos dados, o DBA foca na integridade dos bancos de dados, no hardware envolvido e no controle de acesso, garantindo que os dados estejam protegidos e otimizados para o uso empresarial.

## Tarefas de um analista de dados

O analista de dados desempenha um papel essencial nas organizações, ajudando a descobrir e compreender informações que mantêm a empresa eficiente e equilibrada. Para isso, é fundamental que conheça bem suas responsabilidades e tarefas diárias.

Além de gerar insights valiosos a partir dos dados disponíveis, o analista colabora com outros profissionais da organização para revelar informações relevantes durante todo o processo de análise de dados, que envolve cinco áreas principais:

### Preparar

Como analista de dados, grande parte do seu tempo será dedicada à preparação e modelagem dos dados, pois dados incorretos podem gerar relatórios inválidos, perda de confiança e impactos negativos nos negócios.

A preparação de dados transforma dados brutos em informações confiáveis e compreensíveis, envolvendo tarefas como: analisar o perfil (características, qualidade e estrutura), limpeza, correção de erros, identificação de dados ausentes, conversão de formatos, melhoria da legibilidade.

Também exige decisões sobre conexões de dados, desempenho, e garantias de privacidade e segurança, como anonimização ou remoção de dados sensíveis. Embora possa ser um processo demorado, é essencial para garantir qualidade e insights confiáveis.

### Modelar

Após a preparação, os dados estão prontos para a modelagem, que consiste em definir relações entre tabelas. Um modelo semântico bem construído é essencial para gerar relatórios precisos, rápidos e fáceis de manter.

Modelos mal planejados afetam negativamente o desempenho e a precisão dos relatórios, principalmente em grandes volumes de dados. No Power BI, problemas de lentidão ou atualização costumam indicar falhas na preparação ou modelagem.

A preparação e modelagem são processos iterativos e interdependentes. Compreender e preparar bem os dados facilita muito a criação de um modelo eficaz.

### Visualizar

A visualização de dados dá vida aos dados e tem como objetivo principal resolver problemas empresariais. Relatórios bem projetados contam uma narrativa clara e envolvente, permitindo que tomadores de decisão compreendam rapidamente os insights e tomem decisões precisas.

Para isso, o analista de dados deve entender o problema da empresa e evitar excesso de informações, criando uma narrativa concisa que destaque os pontos-chave. As ferramentas de IA do Power BI ajudam a criar relatórios avançados sem a necessidade de código, facilitando a descoberta de insights.

A acessibilidade também é essencial: os relatórios devem ser pensados para atender a todos os usuários desde o início. Cores, fontes, visualizações e layout devem trabalhar juntos para construir uma narrativa visual eficaz.

### Analisar

A etapa analisar consiste em entender e interpretar os dados exibidos nos relatórios. Como analista de dados, é essencial dominar os recursos analíticos do Power BI para identificar padrões, tendências e previsões, comunicando esses insights de forma clara.

A análise avançada permite decisões mais eficazes, geração de insights acionáveis e uma visão aprofundada do comportamento e dos dados da empresa. Antes restrita a especialistas, hoje a análise está mais acessível graças ao Power BI, que facilita o trabalho com elementos visuais, métricas e dashboards.

As integrações de IA com o Power BI — como Azure Machine Learning e serviços cognitivos — elevam o nível da análise, tornando os relatórios mais poderosos e enriquecidos.

### Gerenciar

O Power BI possui diversos componentes — como relatórios, dashboards, workspaces e modelos semânticos — que o analista de dados deve gerenciar com responsabilidade, garantindo compartilhamento seguro e distribuição eficaz dos ativos.

Aplicativos facilitam a distribuição para grandes públicos, com navegação personalizada e integração com outros ativos da organização. Um bom gerenciamento promove colaboração, acesso controlado e evita vazamento de dados.

Também ajuda a reduzir silos e duplicações, reutilizando modelos semânticos e garantindo confiabilidade por meio de modelos certificados. Com isso, o Power BI apoia uma gestão eficiente e segura dos dados corporativos.

## Resumo

Neste módulo, você aprendeu que a função de analista de dados é vital para o sucesso de uma organização. Além disso, as tarefas que os analistas de dados executam ajudam a verificar se as decisões empresariais são baseadas em dados confiáveis. Você também conferiu as diferentes funções que trabalham com os dados e como as pessoas nessas funções trabalham em parceria próxima com um analista de dados para fornecer insights valiosos sobre os ativos de dados de uma empresa.

## Preparar dados para análise com o Power BI

## Modelar dados com o Power BI

## Criar elementos visuais e relatórios do Power BI

## Fonte
