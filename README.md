# Marcador del concurso

¿Crees que los marcadores del concurso están equivocados? Esta es tu oportunidad de crear la clasificación correcta.

Los concursantes se clasifican primero por la cantidad de problemas resueltos (cuanto más, mejor), luego por cantidades decrecientes de tiempo de penalización. Si dos o más concursantes están empatados tanto en problemas resueltos como en tiempo de penalización, se muestran en orden creciente de número de equipos.

Se considera que un concursante ha resuelto un problema si alguna de las presentaciones para ese problema se consideró correcta. El tiempo de penalización se calcula como la cantidad de minutos que tardó en recibirse la primera presentación correcta de un problema más 20 minutos por cada presentación incorrecta recibida antes de la solución correcta. Los problemas sin resolver no incurren en penalizaciones de tiempo.

## Entrada
La entrada comienza con un solo número entero positivo en una línea sola que indica la cantidad de casos siguientes, cada uno de ellos como se describe a continuación. Esta línea está seguida por una línea en blanco, y también hay una línea en blanco entre dos entradas consecutivas.

La entrada consiste en una instantánea de la cola de evaluación, que contiene las entradas de algunos o todos los concursantes del 1 al 100 que resuelven los problemas del 1 al 9. Cada línea de entrada constará de tres números y una letra en el formato

```
contestant problem time L
```

donde L puede ser 'C', 'I', 'R', 'U' o 'E'. Estos representan envío correcto, incorrecto, pedido de aclaración, no evaluado y envío erróneo. Los últimos tres casos no afectan la puntuación.

Las líneas de entrada están en el orden en que se recibieron los envíos.

## Salida
Para cada caso de prueba, la salida debe seguir la descripción a continuación. Las salidas de dos casos consecutivos estarán separadas por una línea en blanco.

La salida constará de un tablero de puntuación ordenado como se describió anteriormente. Cada línea de salida contendrá un número de concursante, la cantidad de problemas resueltos por el concursante y la penalización de tiempo acumulada por el concursante. Dado que no todos los concursantes del 1 al 100 participan realmente, se muestran solo los concursantes que han realizado un envío.

## Entrada de muestra
```
1

1 2 10 I
3 1 11 C
1 2 19 R
1 2 21 C
1 1 25 C
```

## Salida de muestra
```
1 2 66
3 1 11

```
[Fuente](https://onlinejudge.org/external/102/10258.pdf)
