# Master Center — Calculadora de Convenios V2

## Estructura
- `index.html`: calculadora web.
- `base_convenios_editable.csv`: base editable. Puedes modificar tasas, RCI, edades, condiciones, etc.
- `README.md`: instrucciones.

## Cómo actualizar la base
1. Abre `base_convenios_editable.csv` en Excel.
2. Mantén exactamente los nombres de las columnas.
3. Modifica/agrega/elimina filas.
4. Guarda nuevamente como CSV UTF-8.
5. Sube el CSV al mismo repositorio de GitHub Pages.
6. Recarga la web.

La versión V2 intenta cargar `base_convenios_editable.csv` automáticamente. Si el navegador bloquea la lectura local al abrir `index.html` directamente, publícala en GitHub Pages; allí funcionará correctamente.

## Nota
La lógica es referencial y debe validarse contra las reglas vigentes de BBVA antes de producción.
