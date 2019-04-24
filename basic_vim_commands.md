# Contenido
- [Movimiento](#movimiento)
- [Entrar Modo Insertar](#entrar-modo-insertar)
- [Movimiento en Modo Insertar](#movimiento-en-modo-insertar)
- [Modo Visual](#modo-visual)
- [Copiar y Pegar](#copiar-y-pegar)
- [Editar](#editar)
- [Salir](#salir)
- [Buscar y Reemplazar](#buscar-y-reemplazar)
- [Otros](#otros)

## Movimiento
- Izquierda, abajo, arriba, derecha
    > h, j, k, l
    > flechas

- Inicio de siguiente palabra (con/sin puntuación)
    > w / W

- Final de siguiente palabra (con/sin puntuación)
    > e / E

- Inicio de anterior palabra (con/sin puntuación)
    > b / B

- Inicio de linea
    > 0 (cero)

- Primer caracter no-en-blanco de linea
    > ^ / _

- Final de linea
    > $

- Inicio de documento
    > gg

- Fin de documento
    > G


## Entrar Modo Insertar
- En el cursor
    > i

- En el inicio de la linea
    > I

- Añadir después del cursor
    > a

- Añadir al final de la linea
    > A

- Añadir linea en blanco ABAJO
    > o

- Añadir linea en blanco ARRIBA
    > O

- Añadir al final de la palabra
    > ea

- Salir modo insertar
    > ESC / Ctrl+c


## Movimiento en Modo Insertar
- Izquierda, abajo, arriba, derecha
    > Alt+h, Alt+j, Alt+k, Alt+l
    > flechas

- Inicio/fin linea
    > Alt+0 (cero) / Alt+A (mayus)

- Añadir linea
    > Alt+o


## Modo Visual
- Iniciar modo visual
    > v

- Iniciar modo visual con lineas
    > V

- Cambiar entre extremos de lineas seleccionadas
    > o

- Salir modo visual
    > ESC / Ctrl+c


## Copiar y Pegar
- Copiar palabra
    > yw

- Copiar linea(s)
    > yy

- Copiar hasta final de linea
    > y$

- Pegar después de cursor
    > p

- Pegar antes de cursor
    > P

- Borrar linea
    > dd

- Borrar palabra actual
    > dw

- Borrar caracter después/antes de cursor
    > x / X


## Editar
- Reemplazar solo un caracter
    > r

- Unir linea actual con la de abajo
    > J

- Cambiar linea entera
    > cc

- Cambiar palabra
    > cw

- Cambiar hasta el final de la linea
    > c$

- Eliminar caracter y añadir texto
    > s

- Deshacer último cambio
    > u

- Repetir último comando
    > .


## Salir
- Guardar
    > :w

- Guardar y salir
    > :wq / ZZ

- Salir si está guardado
    > :q

- Forzar salida aún sin guardar
    > :q!

- Recargar archivo original abierto
    > :e!


## Buscar y Reemplazar
- Buscar palabra hacia delante
    > /

- Buscar palabra hacia atrás
    > ?

- Repetir búsqueda en misma dirección
    > n

- Repetir búsqueda en dirección contraria
    > N

- Reemplazar SIN confirmación en todo el archivo
    > :%s/X/Y/g (X es lo que se busca, Y por lo que se va a sustituir)

- Reemplazar Con confirmación
    > :%s/X/Y/gc (X es lo que se busca, Y por lo que se va a sustituir)


## Otros
- Centrar lineas
    > :ce

- Alinear lineas a la derecha
    > :ri

- Alinear lineas a la izquierda
    > :le

- Editar archivo en un nuevo buffer
    > :e

- Deshacer cambios indicando tiempo
    > :earlier x (donde x es el tiempo -> :earlier 2m deshace 2 minutos)

- Ver / no ver número de linea
    > :set nu / :set nonu
