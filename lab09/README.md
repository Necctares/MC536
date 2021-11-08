# Lab09 - Grafo de Conhecimento

# Aluno
* `193400`: `<Alan Freitas Ribeiro>`

## Exemplo de Grafo de Conhecimento - para publicar ou enriquecer
>
> Grafo de Classes:
> 
> ![Modelo Lógico de Grafos](images/lab09classes_v2.jpg)

| Recurso | Propriedade | Valor |
| --- | --- | --- |
| Time | Joga | Partida |
| Time | Possui | Elenco |
| Elenco | Joga | Partida |
| Partida | Tem | Gol |
| Partida | Tem | Impedimento |
| Partida | Tem | Arbitro |
| Gol | Marcado Por | Elenco |
| Impedimento | Cometido Por | Elenco |
| Arbitro | Aplicou | Cartão Amarelo |
| Arbitro | Aplicou | Cartão Vermelho |
| Cartão Amarelo | Mostrado ao | Elenco |
| Cartão Vermelho | Mostrado ao | Elenco |

> Grafo de Exemplos:
> 
> ![Modelo Lógico de Grafos](images/lab09exemplo_v2.jpg)

| Recurso | Propriedade | Valor |
| --- | --- | --- |
| Atletico-MG | Joga | Atletico-MG x America-MG |
| America-MG | Joga | Atletico-MG x America-MG |
| Atletico-MG | Possui | Guilherme Arana |
| America-MG | Possui | Bruno Názario |
| Atletico-MG x America-MG | Tem | Wilton Pereira |
| Atletico-MG x America-MG | Tem | 62' |
| 62' | Marcado Por | Guilherme Arana |
| Wilton Pereira | Aplicou | 87' |
| Wilton Pereira | Aplicou | 89' |
| 87' | Mostrado ao | Bruno Názario |
| 89' | Mostrado ao | Guilherme Arana |
| Guilherme Arana | Joga | Atletico-MG x America-MG |
| Bruno Názario | Joga | Atletico-MG x America-MG |

## Perguntas de Pesquisa ou Queries

> Liste aqui as três perguntas de pesquisa ou queries
> * Qual foi o jogador que mais marcou gols?
> * Quantos gols teve a partida 'x'?
> * O time mandante venceu?
