
# UNIFOR
**Nome**: Davi de Cerqueira
**Disciplina**: Raciocínio lógico algoritmo

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


