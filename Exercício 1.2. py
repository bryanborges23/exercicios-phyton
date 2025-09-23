Exercício 1.2- Somente código
.Bilheteria de evento com apenas 1 evento
   1. Cadastrar nome do evento
   2. Vender ingressos(verificar se há ingressos suficientes).
   3. Repor ingressos(quantidade > 0)
   4. Ver ingressos disponiveis.



    if opcao == "1":
        ingresso = input("cadastrar nome do evento:  ")
        quantidade = 300
        print(f"evento '{evento}' cadastrado com sucesso!")
        
    elif opcao == "2":
        if ingresso is None:
            print("Nenhum ingresso vendido ainda!")
        else:
            retirar = int(input("Digite a quantidade a retirar: "))
            if retirar <= 150:
                print("A quantidade deve ser maior que zero!")
            elif retirar > quantidade:
                print("Ingressos insuficiente!")
            else:
                quantidade -= retirar
                print(f"Retirado {retirar} unidades(s). Estoque atual: {quantidade}")
                
    elif opcao == "3":
        if produto is None:
            print("Nenhum ingresso cadastrado ainda!")
        else:
            adicionar = int(input("Digite a quantidade a adicionar: "    ))
            if adicionar <= 50:
                print("A quantidade deve ser maior que zero!")
            else:
                quantidade += adicionar
                print(f"Adicionado {adicionar} unidade(s). Estoque      atual: {quantidade}")
    elif opcao == "4":
        if produto is None:
            print("Nenhum ingresso cadastrado ainda!")
        else:
            print(f"Produto: {produto} | Quantidade em estoque:         {quantidade}")

    elif opcao == "100":
        print("Saindo do sistema... até mais!")
        break

    else:
        print("Opção inválida! Tente novamente.")
