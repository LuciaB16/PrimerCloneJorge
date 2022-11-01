Calcula el area de figuras usando el [Switch](Main.java)

```mermaid
graph TD;
 A[Start] -->B[/Mostrar Menu/]
B-->C[\Introducir Opcion\]
C --> D{SWITCH}
D --- |=1|E[\Introducir lado\]
E-->e1(Calcular area l^2)
e1-->e2[\Mostrar area\]
D --- |=2|F[\Introducir base y altura\]
F --> f1(Calcular area b*h/2)
f1-->f2[\Mostrar area\]
D --- |=3|G[\Introducir radio\]
G --> g1[\Calcular area PI*r^2\]
g1 -->g2[\Mostrar area Cincunferencia\]
D --> |default| H[\Incorrecto\]
e2-->I[FIN]
f2 --> I[FIN]
g2-->I[FIN]
H-->I[FIN]