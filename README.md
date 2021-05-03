# RNA_Soft_Sensor
Propostas de modelos de Soft Sensors aplicados na medição de vazão em uma industria sucroalcooleira.

## Conclusão
Nesse trabalho foram propostos 3 modelos de soft sensros baseados em redes neurais artificiais profundas para medição de vazão em uma industria sucroalcooleira, os dados foram tratados, normalizados e divididos.

O primeiro modelo apresentou desempenho satisfatório, porem com alto ruído e uma incerteza considerável.O segundo modelo apresentou o melhor desempenho mas utiliza uma amostras amostras anteriores dos sinais incluindo a medição da vazão anterior, o que faz necessário a existência de um sensor e os problemas apresentados na seção 1 não são resolvidos.

Outra característica do modelo 2 observada foi a quase cópia direta da entrada Q2 atrasada diretamente para a saída, o que pode não justificar o custo computacional do modelo.
Por fim o modelo 3 apresentou um desempenho superior ao modelo 1 e inferior ao modelo 2, porem não utiliza leituras anteriores da variável predita, o que possibilita a retirada do sensor físico.

Sugere-se aqui a aplicação de mais dados para o treino antes de implementar um modelo definitivo na industria, visto que um dia de dados não representa em totalidade os possíveis cenários de operação da planta e uma maior quantidade de dados de treino ajuda na generalização do modelo.

## Mais informações
- [Relatório](relatório.pdf)
- [Código do modelo 1](modelo_1.ipynb)
- [Código do modelo 2](modelo_2.ipynb)
- [Código do modelo 3](modelo_3.ipynb)
