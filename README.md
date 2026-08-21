# MCA CALCULADORA V31

Correcciones definitivas:

- La base de 238 convenios / 548 perfiles queda embebida dentro de `index.html`, por lo que la calculadora no depende de que GitHub cargue el CSV para mostrar tasas y parámetros.
- Se mantiene `base_convenios_editable.csv` para futuras actualizaciones.
- Se corrigió el error de cálculo de endeudamiento que impedía continuar la función `calc()`.
- La tasa se calcula por Buró + Tasa Con Seguro / Tasa Sin Seguro y reconoce rangos consecutivos.
- Los parámetros del convenio se cargan con Convenio + Cargo + Condición.
- Si solo se llena Boleta 1, los promedios se calculan con divisor 1, no con 3.
- Si se llenan dos boletas, el promedio usa 2; con tres, usa 3.
- El autollenado de B2/B3 al ingresar ingreso variable se mantiene.
- El ancho de Datos financieros y Parámetros se mantiene en la nueva distribución.
