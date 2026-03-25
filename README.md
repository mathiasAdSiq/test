nome_cliente = input("Digite o nome do cliente:")
valor_compra = float(input("Digite o valor da compra:"))
forma_pagamento = input("Digite 1 para dinheiro, e 2 para cartão:")
dinheiro = 1
cartão = 2
if valor_compra >200:
    if forma_pagamento == 1:
        print(nome_cliente,valor_compra, valor_compra*0.85,"Reais")          
    else: 
         print(nome_cliente,valor_compra, valor_compra*0.95,"Reais")

else:
    if forma_pagamento == 1:
        print(nome_cliente,valor_compra, valor_compra*0.90,"Reais")
    else :
         print(nome_cliente,valor_compra, valor_compra,"Reais") 
