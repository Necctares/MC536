# Aluno
* `193400`: `<Alan Freitas Ribeiro>`

# Análise do Artigo `<CandiDATA: um dataset para análise das eleições no Brasil.>`

| campo | valor |
|------------|----------------------------------------|
| referência | `<VASCONCELOS, Felipe et al. CandiDATA: um dataset para análise das eleições no Brasil. Online: SBC, 2021>` |
| link       | `<https://drive.google.com/file/d/10hh-MLRk9omaGwdormsXwQa7O7XHXFhT/view>` |
| dataset | `<https://github.com/felipeVsc/CandiDATA>` |
| formato | `<Tabelas, em arquivos .csv>` |

## Resumo

> O CandiData é um dataset que foi construído com intuito de facilitar as pesquisas de dados eleitorais brasileiros, este dataset contêm dados eleitorais sobre os candidatos as eleições no período de 1945 até 2020. Estes dados foram obtidos majoritariamente do portal do [TSE](https://www.tse.jus.br/eleicoes/estatisticas/repositorio-de-dados-eleitorais-1), além de algumas outras fontes de dados para complementar as informações adicionais, como por exemplo, o gênero do candidato, que não foram disponibilizadas em alguns anos pelo TSE. Além disso, este dataset buscou uniformizar as informações adquiridas, visto que, os dados originais obtidos pelo TSE continham vários problemas de formatação, principalmente de uniformidade, onde, para cada ano, os dados eram representados/descritos de maneira diferente. Sendo assim, para a construção desse dataset, os autores realizaram três operações principais sobre os dados: Padronização, Transformação e Consolidação, permitindo manipular mais facilmente os mesmos, além de ser criado um novo dicionário padronizado para o dataset atual.

## Perguntas de pesquisa/análises

> Podemos realizar uma série de análises de situação eleitoral sobre este dataset, como os próprios autores apontaram, conseguimos inferir, por exemplo, a participação feminina nas eleições brasileiras ao longo do tempo (1945-2020), o número de profissionais de cada área que se candidata ao pleito eleitoral, a faixa etária com maior número de candidatos, zonas eleitorais com maior número de candidatos ao pleito eleitoral, partidos que possuem maior número de candidatos, coligações partidárias que possuem maior representatividade, distribuição de votos (Homens vs Mulheres) ao longo do tempo, participação de pessoas Trans na politica brasileira, etc.

## Trabalhos relacionados

> Os autores mencionaram diversas outras iniciativas com intenções parecidas ao candiData, podendo ser citados os trabalhos:
> 
> De Camargo *et al*, que a partir dos dados coletados do TSE buscou inferir os perfis dos vereadores nos munícipios do Rio Grande do Sul, no ano de 2012, dando importância para a carreira política de cada candidato, a idade, a sua escolarização e o seu gênero.
>
> De Filho e Pappa (2015), em que foi desenvolvido uma ferramenta para tentar caracterizar os usuários que utilizam o Twitter. Para este trabalho, os autores fizeram uso de dados eleitorais dos usuários obtidos no conjunto de dados disponibilizado pelo TSE, a fim de, construir uma distribuição demográfica realista para comparar com a distribuição gerada a partir dos dados obtidos dos usuários do Twitter.
>
> CEPESP (2020), onde foi desenvolvida a plataforma CepespData, com o mesmo objetivo de facilitar o acesso às bases de dados disponibilizados pelo TSE. Estes dados podêm ser obtidos diretamente do site da [CepespData](https://cepespdata.io/) ou através de uma API, onde os autores também consertaram alguns problemas encontrados no repositório do TSE, porém, em comparação com o CandiData, existe uma restrição maior ao período tratado (1998-2018).
