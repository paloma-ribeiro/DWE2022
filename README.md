# DWE2022
Desafio realizado para o Bootcamp Data Women Engineers 2022

### Descrição

1. Criar um banco de dados chamado desafio (localmente), com as tabelas, conforme diagrama de dados da [figura-1](../Exercicio_01/figura-01.jpg). Os scripts devem ser criados no Notebook.

2. Restaurar o arquivo treino.bak, para resolver as questões:
- Listar todos os clientes com seus nomes e com suas respectivas cidades e estados.
- Listar o código do produto, descrição do produto e a descrição das categorias dos produtos que tenham o valor unitário na faixa de R$ 10,00 a R$ 1500,00.
- Liste o código do produto, descrição do produto e descrição da categoria dos produtos, e também apresente uma coluna condicional com o nome de "faixa de preço". Com os seguintes critérios:
  #### preço< 500 : valor condicional será igual "preço abaixo de 500"
  #### preço >= 500 e <=1000 valor condicional será igual "preço entre 500 e 1000"
  #### preço > 1000 : valor condicional será igual "preço acima de 1000".
3. Desenvolva um pipeline de integração de dados usando o SSIS e realize a modelagem multidimensional, desnormalizando os dados, gerando um DW, a tabela fato e suas dimensões de acordo com seu entendimento e realize a carga de dados disponibilizados.
#### Origem de dados: BaseDadosDesafio.csv
