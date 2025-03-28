# # Crie uma lista de compras de um supermercado com 10 elementos.
# Na posição 6 crie uma lista com 5 elementos.

# Altere 2 elementos da lista.
# Exclua 3 elementos da lista.
# Adicione 4 elementos na lista.

# Acesse o terceiro e quinto elemento da lista.

# Mostre o número de elementos da lista.

# Mostre todos os elementos da lista.



 #criando 2 listas de supermercado 
supermercado = ["melancia","abacate","melao","uva","papel higienico","acucar","livro","ca
 supermercado2 = ["batata","caneta","banana","doce","arroz"]
 supermercado.insert(6,supermercado2)
 print(supermercado)
 ['melancia', 'abacate', 'melao', 'uva', 'papel higienico', 'acucar', ['batata', 'cane
 
 Clique duas vezes (ou pressione "Enter") para editar
 # Alterando 2 elementos da lista
 supermercado[0] = "laranja"  # Alterando o primeiro elemento
 supermercado[2] = "kiwi"     
# Alterando o terceiro elemento
 # Excluindo 3 elementos da lista
 supermercado.pop(5)  # Remove o quarto elemento (uva)
 supermercado.pop(2)  # Remove o oitavo elemento (carrinho)
 supermercado.pop(3)  # Remove o décimo elemento (maca)
 '
 acucar
 '
 # Adicionando 4 elementos na lista
 supermercado.append("abacaxi")
 supermercado.append("pao")
 supermercado.append("leite")
 supermercado.append("queijo")
 print(supermercado)
 
 a', 'abacaxi', 'pao', 'leite', 'queijo', 'abacaxi', 'pao', 'leite', 'queijo', 'abacaxi
 
 https://colab.research.google.com/#scrollTo=HB2NCD9jItDE&printMode=true
 
 2/3
28/03/2025, 20:42
 Olá, este é o Colaboratory - Colab
 # Acessando o terceiro e o quinto elemento
 terceiro_elemento = itens[2]  # Índice 2 é o terceiro elemento
 quinto_elemento = itens[4]  # Índice 4 é o quinto elemento
  File 
"<ipython-input-49-251be378965c>", line 1
    print(len(supermercado)
                           ^
 SyntaxError: incomplete input
 Próximas etapas:
 Corrigir erro
 # Mostrando o número de elementos da lista
 numero_elementos = len(itens)
 # Mostrando todos os elementos da lista
 todos_elementos = itens
 # Exibindo os resultados
 print(f'Terceiro elemento: {terceiro_elemento}')
 print(f'Quinto elemento: {quinto_elemento}')
 print(f'Número de elementos: {numero_elementos}')
 print('Todos os elementos:', todos_elementos)
