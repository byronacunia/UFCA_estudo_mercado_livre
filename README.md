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

Esse repositório faz parte do projeto de estudo de migração do mercado cativo ao livre com base na UFCA. Além do repositório, o relatório completo pode ser encontrado no formato PDF no link https://www.google.com.br/drive/apps.html. Os dados utilizados para o relatório inicial e final estão compilados no código principal final UFCA.ipynb. 

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

Nos últimos anos no Brasil tem crescido o número de consumidores que migram para o mercado livre de energia. Nessa perspectiva, as universidades brasileiras também podem ter grande potencial para migração e gerar economia nos cofres públicos. Neste ensejo, o presente trabalho escolheu a Universidade Federal do Cariri (UFCA) para realização da análise de migração para o mercado livre. Nesse documento, serão apresentadas as análises realizadas para migração do mercado cativo para o livre. A análise foi feita utilizando os dados examinados anteriormente da UFCA, definido a demanta ótima, aspectos jurídicos, observação do SWOT (strengths, weaknesses, opportunities, threats - no português, forças, fraquezas, oportunidades e ameaças), e análise econômica do processo de migração. Assim, foi obtido como resultado um ganho de X% ao migrar para o mercado livre, sendo possível o processo de migração para UFCA. No geral, observou-se como funciona o processo de migração ao mercado livre e como utilizar ferramentas para realizar as análises.


# Abstract in English

In recent years in Brazil, the number of consumers who migrate to the free energy market has grown. In this perspective, Brazilian universities may also have great potential for migration and generate savings in public coffers. In this opportunity, the present work chose the Federal University of Cariri (UFCA) to analyze migration to the free market. In this document, the analyzes performed for migration from the captive to the free market will be presented. The analysis was made using the previously examined data from UFCA, defining the optimal demand, legal aspects, observation of SWOT (strengths, weaknesses, opportunities, threats), and economic analysis of the process of migration. Thus, a gain of X% was obtained as a result of migrating to the free market, making the migration process to UFCA possible. In general, it was observed how the migration process to the free market works and how to use tools to carry out the analyzes.


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

Nos últimos anos o setor elétrico brasileiro vem se reformulando, principalmente com o crescimento no número de fontes renováveis de energia. Em paralelo, o monopólio das distribuidoras e transmissoras possibilitou altos custos que refletiram na economia como um todo [1]. Tudo isso, criou um cenário favorável para o crescimento recente do mercado livre de energia.

O mercado livre de energia propiciou a comercialização de energia elétrica com a negociação de produtores e consumidores de energia. Incluindo benefícios na venda de energia de origem renovável. Assim, o ambiente de contratação livre (ACL) tornou-se um opção ao mercado cativo.

Os benefícios de conseguir negociar o próprio contrato de energia são inúmeros. O primeiro é criar um ambiente competitivo reduzindo custos, gerando novos produtos e serviços, descentralizando as decisões e limitando poder de intervenção estatal [2].

Entretanto, analisar contratos e fundamentos técnicos para migração são necessários, já que um contrato errado pode trazer prejuízos por longos anos. Assim, nesse trabalho o objetivo foi analisar a viabilidade da migração para o mercado livre da Universidade Federal do Cariri (UFCA). Além disso, a proposta da disciplina IT304S - Contratação de Energia para Grandes Consumidores, permitiu conhecer ferramentas e se aprofundar no conteúdo sobre mercado livre. Os resultados foram favoráveis a migração das quatro unidades consumidoras da UFCA em comunhão de carga. O relatório completo do projeto é visto em: https://www.google.com.br/drive/apps.html.

Para tanto, no PDF relatório completo do trabalho apresentou-se na seção III a descrição da universidade escolhida; na seção IV foi apresentado um conteúdo teórico sobre mercado livre e processo de migração, com vantagens e desvantagens; seção V otimização da demanda; na seção VI foi realizado a análise SWOT (strengths, weaknesses, opportunities, threats - no português, forças, fraquezas, oportunidades e ameaças); seção VII comentou-se os aspectos jurídicos; seção VIII analisou a migração para o mercado livre com vies econômico; e finalizando com as considerações finais. No presente GitHub, é apresentado a seguir as perguntas de pesquisa, objetivos do projeto, recursos e metódos utilizados, evolução do projeto, resultados e discussão e as conclusões.


## Perguntas de Pesquisa

Vale a pena migrar para o Mercado Livre? Como consumidor livre ou especial? Qual é a economia estimada? Qual é o preço da energia a partir de quando compensa a migração? Qual a recomendação para uma contratação?


## Objetivos do projeto

O principal objetivo do trabalho foi avaliar a possível migração do mercado cativo ao mercado livre da Universidade Federal do Cariri (UFCA).

Os objetivos específicos são:
  - Definir premissas para o processo de contrato da UFCA;
  - Estudar o conceito e etapas do mercado livre de energia;
  - Estudar a demanda ótima para UFCA;
  - Verificar o SWOT para mercado livre de uma autarquia estatal;
  - Apresentar aspectos jurídicos do processo de migração para o mercado livre de uma universidade;
  - Avaliar a viabilidade e econômica com a migração ao mercado livre de energia.>


# Recursos e Métodos

## Bases de Dados
`A base de dados utilizada foram as contas de energia das quatro UC's repassadas na disciplina de IT304S - Contratação de Energia para Grandes Consumidores, digitalizadas no Excel disponibilizado no Google Drive do curso e tratamento em UFCA.ipynb.

## Ferramentas

Microsoft Excel | https://office.live.com/start/Excel.aspx?ui=pt-BR | `<Editor de planilhas de dados Excel, utilizado para digitalização inicial dos dados de conta de energia das UC's.>`

Colab | https://colab.research.google.com/ | `<Elaboração do código em Python para tratamento dos dados, análises, e avaliação econômica.>`

# Metodologia

O primeiro passo para estudo de migração ao mercado livre foi realizado no primeiro relatório da disciplina IT304S - Contratação de Energia para Grandes Consumidores (disponibilizado no Google Drive do curso, pasta UFCA), em que foi analisado as contas da UFCA, observando aspectos como uso da demanda e valores de reativos. Bem como, observou-se o comportamento dos dados. Pode-se dizer a metodologia utilizou-se de pesquisas qualitativas e quantitativas.

Nesse GitHub, é apontado o código em Python para analisar a viabilidade de migração do mercado cativo ao mercado livre da UFCA. A primeira parte do trabalho nessa etapa foi estudar o mercado livre, verificando as possibilidades de migração para uma universidade pública como a UFCA, baseado no perfil traçado anteriormente no primeiro relatório. Os resultados e teória foi disponibilizado no relatório final completo em: 

Posteriormente, foi realizado um processo para otimização de demanda, variando o valor de demanda contratada até chegar ao valor ótimo. Em seguida, aspectos de SWOT e jurídicos foram comentados no relatório completo, já que muito se tem discutido sobre a legalidade e fundamentação da migração do mercado cativo ao livre de universidades públicas. Mesmo já existindo exemplos de sucesso como a UNICAMP.

Por fim, uma análise foi realizada para o processo de migração ao mercado livre. Os dados da UFCA faltantes foram preenchidos com previsão de dados utilizando a plataforma Google Colab [3] em Python, e os valores da conta de energia no cenário de demanda atual e demanda ótima foram obtidos para o mercado cativo e livre, verificando se o processo de migração compensa.

## Detalhamento do Projeto

Os detalhes completo do projeto podem ser visualizados no relatório final em . Devido o formato da estrutura do README foi optado por disponibilizar um PDF para facilitar a leitura e apresentar um resumo nessa página, além do código completo. 

### Etapas para migração para o mercado livre

Diante destes conceitos e análises de riscos, faz-se necessário delinear quais são os passos que a Universidade Federal do Cariri deverá seguir para adentrar ao Mercado Livre. 

- Atendimento ao Pré-Requisito de Demanda Contratada: Como previamente mencionado, a Universidade possui uma demanda contratada de todas as suas unidades consumidoras equivalente a X MW, o que a determina ser um Cliente Especial. Por esta razão, ela terá certas limitações, como atendimento mínimo em média tensão e compra voltada apenas a fontes incentivadas, como a eólica, solar, pch ou biomassa. Como todas as unidades são atendidas na média tensão, não há entraves iniciais para o processo.

- Renúncia de Contrato com a Distribuidora Local: Antes de migrar para o mercado livre, as unidades consumidoras em questão devem realizar a rescisão do contrato com a distribuidora responsável pelos respectivos fornecimentos de energia. Usualmente após a rescisão do contrato com a distribuidora, é necessário aguardar a vigência de 12 meses para que a desvinculação com o mercado cativo seja efetuado em definitivo. 

- Adequação do Sistema de Medição e Faturamento: Para se tornar um adepto à CCEE, é necessário solicitar a alteração do método de medição de energia, visando a coleta de dados que serão alimentados no Sistema de Coleta de Dados de Energia (SCDE).

- Modelagem de Ativos: Para que o agente possa efetuas as operações na CCEE, é necessário que, através de uma representação contábil, seja apresentada a modelagem dos ativos ao sistema de contabilização e liquidação. Vale salientar, que para o caso da UFCA, será necessário englobar os ativos de todos os campus. 

- Abertura de Conta Corrente Específica: Visando a liquidação financeira, o  agente deverá abrir uma conta corrente no mesmo CNPJ matriz das unidades consumidoras, como é o caso da UFCA na qual fará uma comunhão de cargas. Esta conta deverá ser aberta na instituição financeira Banco Bradesco S/A, situada na Avenida Paulista, da cidade de São Paulo/SP.

- Adesão Aprovada pelo Conselho de Administração: Findados os procedimentos supracitados pelo Conselho de Administração, o agente está apto a adentrar ao mercado livre.


### Procedimentos e detalhes do mercado livre para UFCA

Os procedimentos para análise de viabilidade do processo de migração de energia elétrica para o mercado livre tem como objetivo final verificar a economia proporcionada por diferentes cenários de migração. Os procedimentos foram esboçados com base na análise de trabalhos da literatura [4,5,6] e implementado partes no GitHub do projeto e/ou Excel para chegar em uma conclusão sobre a migração ao mercado livre de energia da UFCA.

- Procedimento 1: Foi realizado o levantamento das contas de energia disponíveis para as 4 UC's da UFCA e digitalizadas no Colab;
- Procedimento 2: Dados faltantes foram incrementados utilizando uma algoritmo de previsão de dados;
- Procedimento 3: Foi observado o comportamento dos dados, perfil do cliente, tipo de contrato, demanda e ultrapassagem de reativo;
- Procedimento 4: Foi sugerido alterações na demanda com um estudo de otimização;
- Procedimento 5: Levantou-se os custos de energia dos dois últimos anos (2019, e 2020), e aplicou-se algoritmo de previsão para o ano seguinte (2021);
- Procedimento 6: Foi separado (calculado) o custo com TUSD (Tarifa de Uso do Sistema de Distribuição) e TE (Tarifa de Energia) para posterior cálculo da conta no mercado livre;
- Procedimento 7: Foi estudado a análise por SWOT e jurídica para caso de autarquias estatais;
- Procedimento 8: Foi definido o perfil de contrato para o mercado livre de energia compatível com UFCA;
- Procedimento 9: Foi calculada a conta para o mercado livre considerando consumidor especial com 50% e 100% de desconto para fontes incentivadas, e os anos de 2019, 2020, 2021;
- Procedimento 10: Análise dos resultados obtidos para contas no cativo e livre.

É importante destacar que algumas premissas foram consideradas. Considerou-se que na UFCA as curvas futuras de consumo seguem o comportamento/sazonalidade das curvas passadas, aplicando algoritmos de previsão de futura, ou seja, considera-se que não serão implementadas nenhuma carga muito maior do que já existia; a tarifa horosazonal verde é a melhor opção para o cativo, já que é uma universidade nova, e possivelmente foram realizada análises; a migração ao mercado livre irá considerar as 4 UC's em conjunto, já que a maioria tem uma demanda pequena em comparação aos limites necessários para migração, e isso seria bom para o futuro e gestão de energia da universidade como um todo.

Diante dos dados analisados para UFCA foi considerado que o consumidor seria do tipo especial (necessidade de contratar energia incentivada), com modulação de vigência única (flat), pois é o tipo mais comum considerado nas análises de migração para o mercado livre. 


## Evolução do Projeto

A evolução do projeto e procedimentos também são detalhados no relatório completo em .

A maior dificuldade encontrada foi o tempo para aprendizado das ferramentas (programação Python, Colab, e GitHub) e mercado livre de energia. Como o processo de migração é algo de tem um custo alto para consultoria, várias são as estratégias adotadas e a maioria não é comentada na literatura. Entretanto, a análise foi efetuada com sucesso, deixando espaço para trabalhos futuros. As outras possíveis análises são discutidas nos trabalhos futuros.


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

# Referências

[1] J. K. F. de Lima, “Um estudo sobre a instabilidade causada no ambiente de livre
contratação de energia elétrica devido a erros no processo de formação do preço
de liquidação das diferenças,” 2019, universidade Federal do Ceará, Trabalho de
conclusão de curso em Engenharia Elétrica, Fortaleza, Brasil.

[2] Abraceel, “Benefícios, riscos e desafios na transição para um mercado livre,” 2021. [Online]. Available: https://www.aneel.gov.br/documents/656877/17755237/Reginaldo+Medeiros.pdf/529c0dc1-4537-2e7c-8d75-273ebfc37fa3

[3] Google, “Ambiente google colab,” 2021. [Online]. Available: https://colab.research.google.com/

[4] F. M. Lourençato, S. C. Campos, A. M. A. de Castro, J. R. de Castro Barbosa do Amaral, N. F. Rossi, A. P. Araki, F. R. F. S. de Paula, A. P. Filho, L. de Faria Rodrigues, and M. S. F. do Amaral Fregonesi, “Estudo de caso da migração de compra de energia elétrica do mercado cativo para o mercado de energia livre por uma autarquia,” Revista Qualidade HC, pp. 1–13, 2018.

[5] R. E. M. da Costa, “Análise e simulação da migração de uma empresa do mercado cativo para o mercado livre de energia elétrica,” 2019, universidade Federal De Uberlândia, Trabalho de conclusão de curso em Engenharia Elétrica, Uberlândia, Brasil.

[6] K. R. do Nascimento, “Migração para o mercado livre de energia e alteração de tarifa horária: estudo de caso em uma indústria,” 2018, universidade Federal do Rio de Janeiro, Trabalho de conclusão de curso em Engenharia, Rio de Janeiro, Brasil.



