# MCA CALCULADORA V13

## Verificación
La versión pública anterior estaba sirviendo una versión vieja: el encabezado público decía `Base local: cargada`, no el contador de convenios de la V12. Además, la V12 todavía tenía una referencia a un elemento `rciDetail` que no existe y podía detener la simulación al ejecutar `calc()`.

V13:
- carga 238 convenios / 548 perfiles desde un respaldo interno antes de leer el CSV;
- inicializa después de `DOMContentLoaded`;
- el CSV es opcional y solo actualiza la base una vez cargada;
- elimina la referencia inexistente `rciDetail`;
- provisión automática desde el perfil;
- logos originales MCA y BBVA;
- fondo azul BBVA.

Subir exactamente:
- index.html
- base_convenios_editable.csv
- logo-mca.png
- logo-bbva.png
- README.md
