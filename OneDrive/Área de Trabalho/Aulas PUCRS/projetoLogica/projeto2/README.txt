Projeto Fase 2
Python 3.10.11

O Projeto foi dividido nos seguintes passos
# 1- Leitura do arquivo
Alem da leitura foi realizado uma checagem dos dados e conversao de dados

# 2- Vizualização dos dados
Na vizualização foi feita uma função para vizualizar o data frame de acordo com algumas exigencias
OBS: Não realizei a leitura em dicionario ou lista porque foi muito dificil tentar aplicar validação e filtro dentro das mesma

# 3- Calculando mês menos chuvoso
Nessa parte do codigo criei 2 funções a primeira que realiza a coleta da menor precipitação. A função recebe o df (dataframe) como argumento.
A segunda função realiza a mesma coleta porem com um filtro que a precipitação deve ser maior que 1.
Como eu nao sabia qual utilizar e não tive tempo de tirar duvida com os tutores eu deixei as duas.
OBS: Novamente foi feita tudo em pandas dataframe pois estava inviavel fazer em lista/tupla/dict

# 4- Calculando a média de temperatura mínima  de um determinado mês.
Em uma unica função a mesma filtra e exibe a media do mes escolhido entre 2006 a 2016. 
A entrada do usuário foi feita fora da função para a mesma ser reaproveitada na função seguinte.
Depois de receber a entrada do usuário é feita uma rapida validação com fim de orietar o usuário apenas para nao deixar sem validação de entrada.
OBS: a função recebe o dataframe e a variavel do mes escolhido como parametro.

# 5- Vizualizando o gráfico em barras
Em uma unica função ,que recebe o dataframe e a variavel anterior escolhida, é realizado a "plotagem" do grafico em barras agrupado e filtrado: "mes escolhido por ano"




Nesse projeto foi usado 4 bibliotecas e uma subbiblioteca sendo elas:
 -pandas: para leitura, vizualização, e tratamento dos dados;
 -matplotlib: para importar a subbiblioteca matplotlib.pyplot que por sua vez serviu apenas para plotar o grafico;
 -calendar: usado para filtrar o data frame na aplicação das funções.
 -datetime: usado para converter os dados "data" do dataframe e exibir determinada data filtrada


Considerações finais:

Por conta da falta de tempo nao pude terminar todas as aulas e fazer o trabalho ao mesmo tempo.
Foi gasto muito tempo tentando realizar todas as atividades em um dicionario ou lista/tupla e mesmo assim eu não conseguia avançar no trabalho, acabou que o pandas fez quase todo o projeto.
Algumas validações poderiam ser mais funcionais sem precisar executar a linha de codigo novamente, mas estava ficando muito feio e faltava tempo, resolvi apenas validar as entradas de forma orientativa.
As funções do projeto foram feitas para realizar no arquivo proposto, outro arquivo usado nesse mesmo projeto vai apresentar erros.