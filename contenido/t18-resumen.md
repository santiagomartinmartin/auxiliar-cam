# Tema 18 · Resumen y trampas

## Lo imprescindible

- **Libro** = archivo (.xlsx) con **hojas**; **celda** = intersección de **fila y columna**.
- **Máximo:** **1.048.576 filas × 16.384 columnas** (A–XFD). **Hojas por libro:** limitadas por la **memoria**.
- **Nombre de hoja:** máx. **31 caracteres**, sin `\ / ? * [ ] :`, no vacío, no «Historial».
- La **barra de fórmulas** muestra el contenido de la **celda activa**.
- Las fórmulas empiezan por **=**. Argumentos separados por **;**.
- **Referencias:** relativa `A1`, absoluta `$A$1`, mixtas `A$1` y `$A1`; **F4** alterna.
- **DERECHA** devuelve caracteres **por la derecha**; **CONTAR** cuenta **números**; **CONTARA**, celdas **no vacías**.
- **#¡DESBORDAMIENTO!:** una matriz dinámica (SECUENCIA, FILTRAR…) no puede ocupar celdas que **no están vacías**.
- **Formato condicional** cambia el **aspecto**; **validación de datos** **restringe la entrada**.
- **Tabla dinámica:** **resume y analiza** datos; áreas **Filtros, Columnas, Filas y Valores**; números → **Suma**, texto → **Cuenta**; hay que **Actualizar** si cambia el origen.
- **Minigráfico:** gráfico pequeño **dentro de una celda**.
- **Triángulo rojo** (esquina superior derecha) = **nota/comentario**; **triángulo verde** (superior izquierda) = posible **error**.
- **F1C1:** referencias por número de fila y columna. **Sistema de fechas 1904:** compatibilidad con Mac.
- **Organizar ventanas → Horizontal:** ventanas **una encima de otra**.

## Errores

`#####` columna estrecha · `#¡DIV/0!` división por cero · `#N/D` no disponible · `#¿NOMBRE?` nombre no reconocido · `#¡REF!` referencia no válida · `#¡VALOR!` tipo incorrecto.

## Trampas habituales

- `=A$1*A2` copiada hacia abajo → `=A$1*A3` (la fila 1 no cambia).
- Al **cambiar el nombre** de una hoja, Excel **actualiza** las fórmulas que la referencian.
- **Alt + F1** = gráfico **incrustado**; **F11** = gráfico en **hoja nueva**.
- El **.csv** guarda **una sola hoja** y **sin fórmulas ni formato**.
