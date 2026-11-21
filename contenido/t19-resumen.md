# Tema 19 · Resumen y trampas

## Lo imprescindible

- **Access:** gestor de **bases de datos relacionales**; archivo **.accdb**. **Una base de datos abierta por instancia**.
- **Objetos:** **tablas** (**almacenan** los datos), **consultas**, **formularios**, **informes**, macros y módulos.
- **Registro** = fila; **campo** = columna. **Clave principal:** identifica **de forma única** cada registro.
- **Vista Diseño:** definir **campos, tipos y propiedades**.
- **Autonumeración:** número **único** asignado **automáticamente**; típico de la clave principal.
- **Formato, Título, Máscara de entrada, Valor predeterminado…** son **propiedades de campo**.
- **Relación:** asociación lógica entre **campos comunes** de dos tablas. **Uno a varios:** clave principal en la tabla «uno» y **clave externa** en la «varios» (Autonumeración ↔ **Número Entero largo**).
- **Integridad referencial:** no se admiten claves externas **sin registro principal** ni se borran registros principales **con relacionados** (salvo **cascada**).
- **Consultas de acción:** **creación de tabla**, **datos anexados** (copiar registros a **otra tabla existente**), **actualización** (fila **«Actualizar a»**) y **eliminación**.
- **Informes:** **Encabezado de informe** (una vez al **principio**) frente a **Encabezado de página** (en **cada página**). **Vista Presentación:** cambiar el diseño **viendo datos reales**.
- **Asistente para etiquetas:** pestaña **Crear**.
- **Importar** = **copia** de los datos · **Vincular** = los datos **siguen en el origen** y se ven los cambios.
- **Guardar pasos de importación:** **repetir** la importación sin el asistente.
- **Compactar y reparar:** **reduce el tamaño** y **repara** la base de datos.
- **Power BI:** **business intelligence**: conectar, transformar (**Power Query**), modelar (**DAX**) y **visualizar** datos en **informes** y **paneles** interactivos. **Desktop** (crear, .pbix) y **servicio** (publicar y compartir).

## Trampas habituales

- Las **consultas** no guardan datos: los **muestran** a partir de las tablas.
- **Panel** (dashboard, una página en el servicio) ≠ **informe** (varias páginas).
- La **máscara de entrada** controla cómo se **introduce** un dato; el **formato**, cómo se **muestra**.
