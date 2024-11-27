#exemplo criação matriz 2x2
matriz=[
    [24,52],
    [11,30]
]
#elementos de uma matriz
for linha in matriz:
    print(linha)

#pra estudar
def soma_tupla(tupla):
    return sum(tupla)

if __name__ == "__main__":
    entrada = input()
    elementos = tuple(map(int, entrada.split(' ')))

    resultado = soma_tupla(elementos)
    print(f"A soma dos elementos da tupla é: {resultado}")

    #Outra atividade
    print(" Cadastro de Currículos ".center(85, "-"))

#informações básicas do usuário
nome = input("Nome completo: ")
cpf = input("CPF (apenas números): ")
estado_civil = input("Estado civil: ")
endereco = input("Endereço (Rua, número, bairro): ")
telefone = input("Telefone (com DDD): ")
email = input("E-mail: ")

#informações adicionais
print("\nAgora vamos adicionar seu Mini Currículo!\n")
experiencias = []
empresas = []
tempos_experiencia = []
qualificacoes = []

#um mini currículo com até 3 experiências
for i in range(3):
    print(f"-- Preenchendo Experiência {i+1} --".center(85))
    exp = input(f"Qual foi a sua {i+1}ª experiência? (Deixe vazio se não tiver mais experiências): ")

    if exp.strip() == "":
        break #não houver experiência

    empresa = input(f"Em qual empresa você trabalhou nessa experiência? (Ex: Tech Solutions): ")
    tempo = input(f"Por quanto tempo você trabalhou em {exp}? (Ex: 2 anos): ")
    qual = input(f"Qual foi a principal função na empresa? (Ex: Estagiario Administrativo): ")

    #armazenando as informações
    experiencias.append(exp)
    empresas.append(empresa)
    tempos_experiencia.append(tempo)
    qualificacoes.append(qual)

#exibindo o currículo formatado
print("\n Currículo Gerado \n".center(85, "-"))

#exibindo as informações básicas
print(f"Nome: {nome}".ljust(50), f"CPF: {cpf}".rjust(35))
print(f"Estado civil: {estado_civil}".ljust(50), f"Telefone: {telefone}".rjust(35))
print(f"Endereço: {endereco}".ljust(85))
print(f"E-mail: {email}".ljust(85))

#exibindo o mini currículo formatado
print("\n Mini Currículo ".center(85, "-"))
if experiencias:
    print(f"{'Experiência':<30} {'Empresa':<30} {'Tempo':<15} {'Qualificação':<15}")
    print("-" * 85)
    for i in range(len(experiencias)):
        print(f"{experiencias[i]:<30} {empresas[i]:<30} {tempos_experiencia[i]:<15} {qualificacoes[i]:<15}")
else:
    print("Sem experiência registrada.".center(85))

  #Outro Codigo
#inicializa uma lista vazia chamada 'nomes'
nomes = []
#loop que itera 5 vezes
for i in range(5):
    #solicita ao usuário que digite um nome e armazena na variável 'nome'
    nome = input(f'Digite o nome: {i+1}')
    #adiciona o nome digitado à lista 'nomes'
    nomes.append(nome)

#imprime uma mensagem informando que os nomes digitados serão exibidos
print('\nOs nomes digitados foram:')

#loop que percorre cada nome na lista 'nomes'
for nome in nomes:
    #imprime cada nome
    print(nome)
#código para calcular informações de alunos em uma pesquisa

def main():
    total_alunos = 0
    ccp_menos_23 = 0
    ads_gostando = 0

    while True:
        #coleta o curso que o aluno faz
        curso = input("Informe o curso (C para Ciências da Computação, A para Análise e Desenvolvimento de Sistemas) ou 'S' para sair: ").strip().upper()
        if curso == 'S':
            break
        if curso not in ('C', 'A'):
            print("Curso inválido! Tente novamente.")
            continue

        #coleta a idade do aluno
        idade = int(input("Informe a idade (em anos): "))
        # Coleta a resposta sobre gostar do curso
        gosta = input("Gosta do curso? (S para sim, N para não): ").strip().upper()

        #atualiza os contadores
        total_alunos += 1

        if curso == 'C' and idade < 23:
            ccp_menos_23 += 1
        elif curso == 'A' and gosta == 'S':
            ads_gostando += 1

    #resultados
    print(f"\nNúmero de alunos de CCP com menos de 23 anos: {ccp_menos_23}")
    print(f"Número de alunos de ADS que estão gostando do curso: {ads_gostando}")
    print(f"Total de alunos entrevistados: {total_alunos}")

#chama a função principal
main()
