Despues de Haber Jugado 32 Veces Space Shooter,
puedo Concluir en un patr�n que me permitio alcanzar altas puntuaciones.
Analizando al enemigo me percate que el mismo se mueve en sig sag de izquierda a derecha disparando cada un segundo por fila (3 filas)
en el movimiento inicial cuando empieza el juego el enemigo dispara inmediatamente y se mueve en masa hacia la izquierda,
as� que el primer movimiento por parte de nosotros debe de ser al lado contrario (derecha), en promedio podr�a ser (right >= 26), luego el enemigo se mueve a la derecha
asi que nosotros nos movemos a la izquierda podr�a ser (left de 1 a 7), esto la primera vez cuando el enemigo tiene sus filas completas, disparamos la cantidad de veces
que queramos, el objetivo ser�a destruir las columnas de enemigos que est�n al lado derecho, con esto se iria incrementando el patr�n,
el patr�n que yo vi fue (right(x cantidad) -> left(x cantidad) ->space(x cantidad) en donde x se va incrementado.
En la carpeta coloque una imagen de una puntuaci�n alta.
Es posible que alla otros patrones utilizando arriba y abajo pero por la forma en que se mueve el enemigo creo que esta podr�a ser una optima, si el enemigo usara un
movimiento de derecha a izquierda y abajo arriba, el patr�n debe de ser totalmente diferente.
