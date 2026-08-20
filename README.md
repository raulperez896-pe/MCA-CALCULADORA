# MCA CALCULADORA — V4

## Subir a GitHub Pages
Sube a la raíz del repositorio estos archivos:
- index.html
- base_convenios_editable.csv
- logo-mca.png
- logo-bbva.jpg

La lista de convenios se carga INMEDIATAMENTE desde una base interna de respaldo y luego intenta actualizarse con el CSV. Esto evita que una falla de carga del CSV deje la calculadora sin convenios.

## Seguro
Se incorporan exactamente las 5 opciones del desplegable de `Cronograma!O16`:
1. Sin devolución
2. Con devolución
3. PNP-Sin devolución
4. PNP-Con devolución
5. Sin seguro

Para las cuatro primeras se usa la columna `Tasa Con Seguro`; para `Sin seguro` se usa `Tasa Sin Seguro`.

Las tasas de desgravamen tomadas de la fórmula de la hoja Cronograma son:
- Sin devolución: 0.05511%
- Con devolución: 0.05823%
- PNP-Sin devolución: 0.06503%
- PNP-Con devolución: 0.06871%
- Sin seguro: 0%

## Base
`base_convenios_editable.csv` contiene los registros de `Adicional Core`. Puede editarse en Excel y volver a subir al repositorio conservando los encabezados.
