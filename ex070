cont = soma = 0
preco_barato = 0
preco_maior_1000 = 0
produto_barato = ' '
while True:
    produto = str(input('Produto: '))
    preco = float(input('Preço: R$'))
    resposta = ' '
    while resposta not in 'SN':
        resposta = str(input('Deseja continuar? [S/N]')).upper().strip()[0]
    if resposta == 'N':
        break
    if cont == 0:
        produto_barato = produto
        preco_barato = preco
    else:
        if preco < preco_barato:
            produto_barato = produto
            preco_barato = preco
    if preco > 1000:
        preco_maior_1000 += 1
    soma += preco
    cont += 1
print(f'O total da compra foi {soma}.')
print(f'Houve {preco_maior_1000} produto(s) com preço maior que R$1000,00.')
print(f'O produto mais barato foi {produto_barato} que custou R${preco_barato}.')
