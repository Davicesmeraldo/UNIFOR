
# UNIFOR
**Nome**: Davi de Cerqueira
**Disciplina**: Raciocínio lógico algoritmo

## Exercício 1
## Fluxograma

```mermaid
flowchart TD
A([INÍCIO]) --> B[/N1, N2/]
B --> C[M=N1+N2/2]
C --> D{M>=7}
D --NÃO--> E{{O aluno está reprovado}}
D --SIM--> F{{O aluno está aprovado}}
F --> G([FIM])
E --> G
```
### pseudocódigo
```
ALGORITMO
DECLARE N1, N2, M NUMÉRICO
ESCREVA "Digite dois números:"
LEIA N1,N2
M ← (N1+N2)/2
SE M>=7
    ESCREVA "Aluno aprovado"
SENÃO
    ESCREVA "Aluno reprovado"
ALGORITMO_FIM
```
## Exercício 2
## Fluxograma

```mermaid
flowchart TD

A([INÍCIO]) --> B[/S/]
B --> C{S<=500}
C --NÃO--> D[NS=S*1,1]
C --SIM--> E[NS=S*1,2]
E --> F{{O novo salário é:NS}}
D --> F 
F --> G([FIM])
```
### pseudocódigo
```
ALGORITMO 
DECLARE S, NS NUMÉRICO
ESCREVA "Digite salário atual:"
LEIA S
SE S<=500
   ENTAO NS ← S*1,2
SENÃO
   NS ← S*1,1
ESCREVA "Novo salário:", NS
ALGORITMO_FIM
```
## Exercício 3
## fluxograma

```mermaid
flowchart TD
A([INÍCIO]) --> B{{Digite um número:}} 
B --> C[/N/]
C --> D{número>0}
D --NAO--> E[número não é positivo]
D --SIM--> F[resto é igual a número %2] 
E --> Z([FIM])
F --> G{Resto == 0}
G --NAO--> H{{O NUMERO É ÍMPAR}}
G --SIM--> I{{O NUMERO É PAR}}
H --> Z
I--> Z
```
### Pseudocódigo
```
1  ALGORITMO verifica_par_impar
2  DECLARE numero, resto NUMERICO
3  ESCREVA "Digite o número:"
4  LEIA numero
5  SE numero > 0 ENTAO
6    resto = numero % 2
7    SE resto == 0 ENTAO
8      ESCREVA "O número é par"
9    SENAO
10     ESCREVA "O número é impar"
11  SENAO
12   ESCREVA "O número não é positivo"
13  FIM_ALGORITMO
```
## Exercício 4
## Fluxograma

```mermaid
flowchart TD

A([INÍCIO]) --> B[/Idade x/]
B --> C{x>=18}
C --NÃO--> D[y=18-x]
C --SIM--> E{{Pode tirar a CNH}}
D --> F{{Pode tirar a CNH daqui a 'y' anos}}
F --> G([FIM])
E --> G
```
### pseudocódigo
```
ALGORITMO
DECLARE X NUMÉRICO
ESCREVA "Digite a idade:"
LEIA X
SE X>=18
   ESCREVA "Pode tirar a CNH"
SENAO
   Y ← 18 - X
   ESCREVA "Poderá tirar a CNH daqui", y ano(s)
ALGORITMO_FIM
```
```

