# Estudo de migração para o mercado livre de energia com base na UFCA
## IT304S - Contratação de Energia para Grandes Consumidores
### Estudante: Byron Alejandro Acuña Acurio, R.A: 209428
### Estudante: Diana Estefanía Chérrez Barragán, R.A: 227041
### Estudante: Elson Yoiti Sakô, R.A: 148482
### Estudante: João Lucas de Souza Silva, R.A: 211497
### Estudante: Micaella Aynoã Loiola Ferreira, R.A: 265574
### Estudante: Bruno Furtado Albuquerque, R.A: 214574
### Professor: Dr. Luiz Carlos Pereira da Silva
### Professor: MSc. Lia Farias

Esse repositório faz parte do projeto de estudo de migração do mercado cativo ao livre com base na UFCA. Além do repositório, o relatório completo pode ser encontrado no formato PDF no link https://www.google.com.br/drive/apps.html.

A estrutura geral deste repositório é apresentada a seguir. 

~~~
├── README.md          <- apresentação do projeto
│
├── data
│   ├── external       <- dados de terceiros
│   ├── interim        <- dados intermediários, e.g., resultado de transformação
│   ├── processed      <- dados finais usados para a modelagem
│   └── raw            <- dados originais sem modificações
│
├── notebooks          <- Jupyter notebooks ou equivalentes
│
├── src                <- fonte em linguagem de programação ou sistema (e.g., Orange)
│   └── README.md      <- instruções básicas de instalação/execução
│
└── assets             <- mídias usadas no projeto
~~~

## `data`

Os dados utilizados no projeto foram repassados na disciplina de IT304S - Contratação de Energia para Grandes Consumidores contendo faturas de energia de quatro unidades consumidoras (UC's) da Universidade Federal do Cariri (UFCA). Os dados foram digitalizados no Excel e colocados na pasta da disciplina compartilhada no Google Drive, e posteriomente, foram adicionados no GitHub e processados no ambiente Colab. Foi utilizado um metódo de previsão linear utilizando os dados passados de cada variável para preencher lacunas vazias de modo a permitir a análise, ou acrescentado o valor zero, dependendo do tipo de dado.

## `notebooks`

O código do projeto pode ser obtido no arquivo UFCA.ipynb.

## `src`

O código utilizado na análise é python feito no ambiente Colab.

## `assets`

Relatório Completo: https://www.google.com.br/drive/apps.html

Vídeo de apresentação do Projeto: https:/www.youtube.com

# Projeto `<Estudo de migração para o mercado livre de energia com base na UFCA>`
# Project `<Study of migration to the free energy market based on UFCA>`

# Descrição Resumida do Projeto
~~~
<Nos últimos anos no Brasil tem crescido o número de consumidores que migram para o mercado livre de energia. Nessa perspectiva, as universidades brasileiras também podem ter grande potencial para migração e gerar economia nos cofres públicos. Neste ensejo, o presente trabalho escolheu a Universidade Federal do Cariri (UFCA) para realização da análise de migração para o mercado livre. Nesse documento, serão apresentadas as análises realizadas para migração do mercado cativo para o livre. A análise foi feita utilizando os dados examinados anteriormente da UFCA, definido a demanta ótima, aspectos jurídicos, observação do SWOT (strengths, weaknesses, opportunities, threats - no português, forças, fraquezas, oportunidades e ameaças), e análise econômica do processo de migração. Assim, foi obtido como resultado um ganho de X% ao migrar para o mercado livre, sendo possível o processo de migração para UFCA. No geral, observou-se como funciona o processo de migração ao mercado livre e como utilizar ferramentas para realizar as análises.>
~~~

# Abstract in English
~~~
<In recent years in Brazil, the number of consumers who migrate to the free energy market has grown. In this perspective, Brazilian universities may also have great potential for migration and generate savings in public coffers. In this opportunity, the present work chose the Federal University of Cariri (UFCA) to analyze migration to the free market. In this document, the analyzes performed for migration from the captive to the free market will be presented. The analysis was made using the previously examined data from UFCA, defining the optimal demand, legal aspects, observation of SWOT (strengths, weaknesses, opportunities, threats), and economic analysis of the process of migration. Thus, a gain of X% was obtained as a result of migrating to the free market, making the migration process to UFCA possible. In general, it was observed how the migration process to the free market works and how to use tools to carry out the analyzes.>
~~~

# Equipe
`<Estudante: Byron Alejandro Acuña Acurio - R.A: 209428>`
`<Estudante: Diana Estefanía Chérrez Barragán - R.A: 227041>`
`<Estudante: Elson Yoiti Sakô - R.A: 148482>`
`<Estudante: João Lucas de Souza Silva - R.A: 211497>`
`<Estudante: Micaella Aynoã Loiola Ferreira - R.A: 265574>`
`<Estudante: Bruno Furtado Albuquerque - R.A: 214574>`

# Vídeo do Projeto
`<coloque um link para o vídeo apresentado o projeto.>`

# Introdução e Motivação
~~~
<Nos últimos anos o setor elétrico brasileiro vem se reformulando, principalmente com o crescimento no número de fontes renováveis de energia. Em paralelo, o monopólio das distribuidoras e transmissoras possibilitou altos custos que refletiram na economia como um todo [1]. Tudo isso, criou um cenário favorável para o crescimento recente do mercado livre de energia.

O mercado livre de energia propiciou a comercialização de energia elétrica com a negociação de produtores e consumidores de energia. Incluindo benefícios na venda de energia de origem renovável. Assim, o ambiente de contratação livre (ACL) tornou-se um opção ao mercado cativo.

Os benefícios de conseguir negociar o próprio contrato de energia são inúmeros. O primeiro é criar um ambiente competitivo reduzindo custos, gerando novos produtos e serviços, descentralizando as decisões e limitando poder de intervenção estatal [2].

Entretanto, analisar contratos e fundamentos técnicos para migração são necessários, já que um contrato errado pode trazer prejuízos por longos anos. Assim, nesse trabalho o objetivo foi analisar a viabilidade da migração para o mercado livre da Universidade Federal do Cariri (UFCA). Além disso, a proposta da disciplina IT304S - Contratação de Energia para Grandes Consumidores, permitiu conhecer ferramentas e se aprofundar no conteúdo sobre mercado livre. Os resultados foram favoráveis a migração das quatro unidades consumidoras da UFCA em comunhão de carga. O relatório completo do projeto é visto em: https://www.google.com.br/drive/apps.html.

Para tanto, o trabalho apresentou na seção III a descrição da universidade escolhida; na seção IV foi apresentado um conteúdo teórico sobre mercado livre e processo de migração, com vantagens e desvantagens; seção V otimização da demanda; na seção VI foi realizado a análise SWOT (strengths, weaknesses, opportunities, threats - no português, forças, fraquezas, oportunidades e ameaças); seção VII comentou-se os aspectos jurídicos; seção VIII analisou a migração para o mercado livre com vies econômico; e finalizando com as considerações finais.>
~~~

## Perguntas de Pesquisa
~~~
<Perguntas de pesquisa que o projeto pretende responder ou hipóteses a serem avaliadas, enunciadas de maneira objetiva e verificável.>
~~~

## Objetivos do projeto
~~~
<Como seu projeto propôs abordar o problema apresentado.>
~~~

# Recursos e Métodos

## Bases de Dados
`<Elencar bases de dados utilizadas no projeto preferencialmente no formato da tabela a seguir.>`
Base de Dados | Endereço na Web | Resumo descritivo e uso
----- | ----- | -----
Base 1 | http://base1.org/ | `<Descrição da Base 1 e para que ela foi usada no projeto.>`
Base 2 | http://base2.org/ | `<Descrição da Base 2 e para que ela foi usada no projeto.>`

## Ferramentas

`<Elencar ferramentas utilizadas no projeto preferencialmente no formato da tabela a seguir.>`
Ferramenta | Endereço na Web | Resumo descritivo e uso
----- | ----- | -----
Ferramenta 1 | http://ferramenta1.org/ | `<Descrição da Ferramenta 1 e para que ela foi usada no projeto.>`
Ferramenta 2 | http://ferramenta2.org/ | `<Descrição da Ferramenta 2 e para que ela foi usada no projeto.>`

# Metodologia
~~~
<Abordagem/metodologia adotada, incluindo especificação de quais técnicas foram exploradas, tais como: aprendizagem de máquina, análise de redes, análise estatística, ou integração de uma ou mais técnicas.>
~~~

## Detalhamento do Projeto
~~~
<Apresente aqui detalhes da análise. Nesta seção ou na seção de Resultados podem aparecer destaques de código como indicado a seguir. Note que foi usada uma técnica de highlight de código, que envolve colocar o nome da linguagem na abertura de um trecho com `~~~`, tal como `~~~python`.

Os destaques de código devem ser trechos pequenos de poucas linhas, que estejam diretamente ligados a alguma explicação. Não utilize trechos extensos de código. Se algum código funcionar online (tal como um Jupyter Notebook), aqui pode haver links. No caso do Jupyter, preferencialmente para o Binder abrindo diretamente o notebook em questão.>
~~~

~~~python
df = pd.read_excel("/content/drive/My Drive/Colab Notebooks/dataset.xlsx");
sns.set(color_codes=True);
sns.distplot(df.Hemoglobin);
plt.show();
~~~

## Evolução do Projeto
~~~
<Relate a evolução do projeto: possíveis problemas enfrentados e possíveis mudanças de trajetória. Relatar o processo para se alcançar os resultados é tão importante quanto os resultados.>
~~~

# Resultados e Discussão
~~~
<Apresente os resultados da forma mais rica possível, com gráficos e tabelas. Mesmo que o seu código rode online em um notebook, copie para esta parte a figura estática. A referência a código e links para execução online pode ser feita aqui ou na seção de detalhamento do projeto (o que for mais pertinente).

A discussão dos resultados também pode ser feita aqui na medida em que os resultados são apresentados ou em seção independente. Aspectos importantes a serem discutidos: É possível tirar conclusões dos resultados? Quais? Há indicações de direções para estudo? São necessários trabalhos mais profundos?>
~~~

# Conclusões
~~~
<Apresente aqui as conclusões finais do trabalho e as lições aprendidas.>
~~~

# Trabalhos Futuros
~~~
<Indique trabalhos futuros a partir do ponto alcançado.>
~~~
