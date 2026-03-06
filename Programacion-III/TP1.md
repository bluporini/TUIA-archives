## Escape del laberinto

### Ítem 1

ESTADOS = {(0,3), (1,0), (1,1), (1,2), (1,3), (2,1), (2,2), (3,0), (3,1), (3,2), (3,3)} \
ESTADO-INICIAL = (0,3)

ACCIONES = {(1,0), (-1,0), (0,1), (0,-1)} 

ACCIONES(0,3) = {(1,0)} \
ACCIONES(1,0) = {(0,1)} \
ACCIONES(1,1) = {(0,1), (0,-1), (1,0)} \
ACCIONES(1,2) = {(0,1), (0,-1), (1,0)} \
ACCIONES(1,3) = {(-1,0),(0,-1)} \
ACCIONES(2,1) = {(-1,0), (1,0), (0,1)} \
ACCIONES(2,2) = {(-1,0), (1,0), (0,-1)} \
ACCIONES(3,0) = {(0,1)} \
ACCIONES(3,1) = {(0,1), (0,-1), (-1,0)} \
ACCIONES(3,2) = {(0,1), (0,-1), (-1,0)} \
ACCIONES(3,3) = {(0,-1)}

RESULTADO((x,y), (a,b)) = (x+a, y+b)

TEST-OBJETIVO(x,y) = TRUE si (x,y) = (3,3), FALSE en otro caso

COSTO-INDIVIDUAL((x,y), (a,b)) = 1 \
COSTO-CAMINO = suma_{E,A} COSTO_INDIVIDUAL(E,A)

### Ítem 2


