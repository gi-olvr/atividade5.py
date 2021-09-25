# atividade5.py

    aluno = input('Nome do aluno: ')
    nota = float(input('Nota final: '))
    
    if 0 <= nota < 5:
        conceito = 'E'
    elif 5 <= nota < 6:
        conceito = 'D'
    elif 6 <= nota < 7:
        conceito = 'C'
    elif 7 <= nota < 9:
        conceito = 'B'
    elif nota >= 9:
        conceito = 'A'
    
    print(f"O aluno {aluno} tirou a nota {nota} e se enquadra no conceito {conceito}")
    opcao = int(input('Inserir dados? 0 - Não     1 - Sim '))
