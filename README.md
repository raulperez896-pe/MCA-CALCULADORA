# MCA CALCULADORA V55

Corrección principal:
- El cronograma ahora genera TODAS las cuotas. En V54 el motor se detenía después de la primera cuota por una variable `const totalCuota` que se intentaba incrementar.
- La cuota constante vuelve a llegar a la pantalla principal porque `renderCronograma()` completa correctamente.
- La distribución de los datos del cronograma se ajustó para seguir la hoja Cronograma base: convenio/cargo/cargo especial, tasas a la derecha, cuotas y gracia, datos del cliente, seguro, TEA/TCEA, fechas y cuota máxima.
- Se mantiene el botón de impresión.
