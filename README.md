
idade = 5
print(idade)


idade = 10
print(idade)

idade = 15
idade

nome = 'Gabriel'
nome

i = 5
type(i)

f =9.8
type(f)

s ='mirra'
type(s)

b = True
type(b)

nome_aluno ='Fabricio Daniel'
idade_aluno = 15
media_aluno = 8.45
situacao_aprovado = True
print(f'''nome do aluno:', nome_aluno, 'idade do aluno:', idade_aluno, 'media do aluno:', media_aluno, 'aprovação:', situacao_aprovado''')




q_seguranca = 5
s_seguranca = 3000

q_docente = 16
s_docente = 6000

q_diretoria = 1
s_diretoria = 12500


total_empregados = q_seguranca + q_docente + q_diretoria
total_empregados

diferenca_salario = s_diretoria - s_seguranca
diferenca_salario

media = (q_seguranca*s_seguranca + q_docente*s_docente + q_diretoria*s_diretoria) / (total_empregados)
media

s1 = 'Alura '
s2 = "Alura"
print(type(s1),type(s2))

texto = 'Geovana Alessandra dias Sanyos '

texto.upper()

texto.lower()

texto.replace('y','t')

texto = texto.strip().replace('y','t').upper()
texto

nome = input('Escreva seu nome: ')

nome

ano_entrada = input('Escreva o ano de ingresso do(a) estudante:')


ano_entrada = int(input('Escreva o ano de ingresso do(a) estudante:'))


type(ano_entrada)

nota_entrada = float(input('Digite a nota do teste de ingresso: '))
print(f'Ano de entrada {ano_entrada} - nota de teste de ingresso {nota_entrada}')





if 2 >7:
  print('condição verdadeira')
  print()
print('fora do bloco')

media = float(input('Digite a media: '))
if media >=6.0:
  print('Aprovado')
else:
  print('Reprovado')


media = float(input('Digite a media: '))
if media >= 6.0:
   print('Aprovado')
if 6.0 > media >= 4.0:
    print('Recuperação')
if media < 4.0:
    print('Reprovado')

media = float(input('Digite a media: '))

if media >= 6.0:
   print('Aprovado')
if 6.0 > media >= 4.0:
    print('Recuperação')
else:
    print('Reprovado')

media = float(input('Digite a media: '))
if media >= 6.0:
   print('Aprovado')
elif 6.0 > media >= 4.0:
    print('Recuperação')
else:
    print('Reprovado')

t1 = t2 = True
f1 =f2 = False


if t1 and f2:
  print('expressâo verdadeira')
else:
  print('expressão falsa')

if  t1 or f2:
  print('expressâo verdadeira')
else:
  print('expressão falsa')

if not False:
  print('expressâo verdadeira')
else:
  print('expressão falsa')

lista = 'José da Silva, Maria Oliveira, Pedro Martins, Ana Souza, Carlos Rodrigues, Juliana Santos, Bruno Gomes, Beatriz Costa, Felipe Almeida, Mariana Fernandes, João Pinto, Luísa Nascimento, Gabriel Souza, Manuela Santos, Thiago Oliveira, Sofia Ferreira, Rafael Albuquerque, Isabella Gomes, Bruno Costa, Maria Martins, Rafaela Souza, Matheus Fernandes, Luísa Almeida, Beatriz Pinto, Mariana Rodrigues, Gabriel Nascimento, João Ferreira, Maria Albuquerque, Felipe Oliveira'
lista

nome_1 = 'Mariana Rodrigues'
nome_2 = 'Marcelo Nogueira'

if nome_1 in lista:
  print(f'{nome_1} esta na lista')
else:
  print(f'{nome_1} nao está na lista')

if nome_2 in lista:
  print(f'{nome_2} esta na lista')
else:
  print(f'{nome_2} nao está na lista')

nota_1 =float(input('Digite a  1° nota: '))
nota_2 =float(input('Digite a 2° nota: '))
print(f'Media: {(nota_1+nota_2)/2}')

contador = 1
while contador <= 10:
  print(contador)
  contador += 1

contador = 1
while contador <=3:
 nota_1 =float(input('Digite a  1° nota: '))
 nota_2 =float(input('Digite a 2° nota: '))
 print(f'Media: {(nota_1+nota_2)/2}')
 contador+=1

for contador in range(1,11):
  print(contador)

for contador in range(1,4):
  nota_1 =float(input('Digite a  1° nota: '))
  nota_2 =float(input('Digite a 2° nota: '))
print(f'Media: {(nota_1+nota_2)/2}')

lista = ['Fabricio Daniel', 9.5,9.0,8.0,True]
lista

lista[0]

lista[1]

lista[-1]

for elemento in lista:
  print(elemento)

lista[3] =10.0
lista

media =(lista[1] +lista[2] +lista[3])/3
media

len( lista)

lista[1:4]

lista[1:3]

lista[:3]

lista[3:]

lista[:]

lista.append(media)
lista

lista.extend([10.0,8.0,9.0])
lista

lista.append([10.0,9.5,9.0,8.0])
lista

lista.remove([10.0, 9.5, 9.0, 8.0])
lista

dicionario = {'chave_1' :1, 'chave_2' :2}
dicionario

cadastro = {'matricula': 2000168933,
              'dia_cadastro':25,
              'mes_cadastro':10,
              'turma':'2E'}
cadastro             

cadastro['matricula']

cadastro['turma']

cadastro['turma'] ='2G'
cadastro

cadastro['modalidade'] ='EAD'
cadastro

cadastro.pop( 'turma')


cadastro

cadastro.items()

cadastro.keys()

cadastro.values()

for chaves in cadastro.keys():
  print(cadastro[chaves])

for valores in cadastro.values():
 print(valores)

for chaves, valores in cadastro.items():
  print(chaves, valores)

