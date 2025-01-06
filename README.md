# 1)Lendo-APIs_Python
Utilizando a linguagem python, Carregando dados públicos do governo através de um API (Application Programming Interface). Baixando os dados de pedidos de verificação de limites (PVL) realizados por estados, e selecionar apenas aqueles referentes ao estado de São Paulo.
1. Repita os mesmos passos feitos em aula, mas selecione os PVLs realizados por municípios no estado do Rio de Janeiro.
2. Quais são os três status das solicitações mais frequentes na base? Quais são suas frequências?
3. Construa uma nova variável que contenha o ano do status. Observe que data_status vem como tipo object no DataFrame. Dica: você pode usar o método .str para transformar o tipo da variável em string, em seguida um método como slice() ou split().
4. Indique a frequência de cada ano do campo construído no item (3).

# 2) Melhorando a interação com o API
Observe dois URLs de consultas diferentes. Compare-os e observe as diferenças.

1. Faça uma função em Python que recebe como argumento o UF da consulta e o tipo de interessado ('Estado'ou Município), e que devolve os dados da consulta no formato DataFrame.
2. Quantas solicitações para o Estado podem ser consultadas para Minas Gerais com status em 'Arquivado por decurso de prazo' estão registradas?
3. Qual é o município da Bahia com mais solicitações deferidas?
4. Salve um arquivo .csv com os dados de solicitações da Bahia, com interessado = 'Estado'
