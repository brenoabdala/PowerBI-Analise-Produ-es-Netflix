# Analise da base de dados de produções disponibilizadas na Netflix

![image](https://github.com/user-attachments/assets/b459d293-3ee0-4e3f-ba8b-0d61fc66ef2c)

 
### Objetivo do Dashboard 

O dashboard tem como objetivo analisar a base de dados de filmes e séries lançados na plataforma da Netflix entre os anos de 2008 e 2021.

### Fonte dos Dados:

Os dados utilizados para a análise foram extraídos da base disponível no Kaggle, que contém informações detalhadas sobre os títulos da Netflix. Você pode acessar a fonte completa aqui.

### Descrição das Colunas
<strong> show_id </strong>
<p>Identificador único de cada título na plataforma. Essa coluna contém um código exclusivo para cada filme ou série, que pode ser utilizado para referenciar o conteúdo de forma precisa dentro da base de dados.</p>

<strong> type </strong>
<p> Indica o tipo de conteúdo disponível na plataforma: pode ser um filme ou uma série. Esse campo ajuda a diferenciar entre conteúdos de longa duração, como filmes, e conteúdos com múltiplos episódios ou temporadas, como séries. </p>

<strong> title </strong>
<p>Nome do título. A coluna contém o título completo do filme ou série conforme listado na plataforma da Netflix. Essa informação é essencial para identificar o conteúdo em questão.
</p>
<strong> director </strong>
<p>Nome do(s) diretor(es) do filme ou série. Essa coluna apresenta os profissionais responsáveis pela direção da obra, oferecendo uma perspectiva sobre os criadores do conteúdo.
</p>
<strong> cast </strong>
<p>Nome dos principais atores ou atrizes que fazem parte do elenco do filme ou série. Esta coluna é importante para entender quais são os artistas mais proeminentes que participaram da produção. </p>

<strong> country </strong>
<p>País de origem do conteúdo. Indica o local onde o filme ou série foi produzido, ajudando a analisar a diversidade geográfica dos títulos presentes na plataforma.</p>

<strong> date_added </strong>
<p>Data em que o título foi adicionado à plataforma Netflix. Essa coluna é útil para analisar como a biblioteca da plataforma se expandiu ao longo do tempo e identificar padrões de lançamento.</p>

<strong> release_year </strong>
<p>Ano em que o filme ou série foi lançado originalmente. Esse campo é essencial para entender o período de produção e lançamento dos conteúdos, permitindo fazer análises sobre tendências temporais e evolução do catálogo ao longo dos anos.</p>

<strong> rating </strong>
<p>Classificação indicativa do conteúdo, que pode variar de acordo com a faixa etária recomendada para o público. Esse campo ajuda a segmentar o conteúdo de acordo com a adequação para diferentes idades.</p>

<strong> duration </strong>
<p>Para filmes, a duração é dada em minutos. Para séries, esse campo geralmente indica o número de temporadas. Essa informação é relevante para entender o tempo médio de consumo dos títulos, seja em filmes ou séries.</p>

<strong> listed_in </strong>
<p>Gêneros ou categorias em que o título é listado na plataforma. Pode incluir opções como Ação, Comédia, Drama, entre outros. Essa coluna ajuda a entender as preferências de conteúdo e a segmentação por gêneros na plataforma.</p>

<strong>description</strong>
<p>Resumo ou sinopse do conteúdo. Essa coluna oferece uma breve descrição do filme ou série, o que pode ser útil para quem deseja entender rapidamente o enredo ou o tema principal da obra.</p>
