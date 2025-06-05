saldo = 1000
opcao = int(input("informe: 1-sacar,2-deposito,3-consultar,4-sair:"))

opcao1 ="verificando saque..."
opcao2 ="depositando..."
opcao3 ="consultando saldo..."
opcao4 ="saindo"
opcao5 ="opcao invalida"
reposta_saque = "saldo insuficiente"


if opcao == 1:
   opcao_saque =int(input("informe o valor para saque:"))
   saldo_atual = saldo - opcao_saque
elif opcao == 2:
   opcao_deposito =int(input("informe o valor para deposito:"))
   saldo_atual = saldo + opcao_deposito
elif opcao == 3:
    saldo_atual = saldo
match opcao:
  case 1:
   escolha = opcao1
  case 2:
   escolha = opcao2
  case 3:
   escolha = opcao3
  case 4:
   escolha =  opcao4
  case _:
   escolha = opcao5
print("valor_anterior:",saldo)
print(escolha)
print("valor atual:",saldo_atual)
