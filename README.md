# MCA CALCULADORA V18

## Correcciones
- La liquidez ya no divide una sola boleta ingresada entre 3.
- El promedio de cada concepto considera únicamente las boletas que tienen un valor ingresado.
- Si se ingresan 3 boletas, el promedio es el promedio de las 3.
- Si se ingresa una sola boleta, esa boleta es el promedio.
- La lógica del saco de liquidez es:
  `(Ingreso fijo promedio + Ingreso variable promedio × % conversión − Descuento de ley promedio) × RCI − Facultativos promedio − Provisión`.
- La provisión sigue siendo automática y se descuenta después del RCI.
- Parámetros del convenio queda debajo de Resultado de la simulación.
- Eliminado el texto explicativo de provisión.
- Eliminado Detalle del cálculo.
- Adicional solo endeudamiento participa únicamente en endeudamiento global.
