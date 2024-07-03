# Divisió entera, diagrama de flux

- Diagrama de flux
- Luis Rey Cabrerizo
- 2 de juny de 2024
- Versió 1
- Càlcul del quocient i residu de la divisió entera de dos nombres

```mermaid
flowchart TB 

inici([Inici]) --> entrada1[/Entrada D/]

entrada1 --> entrada2[/Entrada d/]

entrada2 --> calcul1(Càlcul quocient)
calcul1 --> calcul2(Càlcul divisor)
calcul2 --> imprimir[/Imprimir divisió
Imprimir quocient
Imprimir residu/]

imprimir --> fi([Fi])

```

Diagrama amb mermaid. El problema és veure'l fora de VSCode.
