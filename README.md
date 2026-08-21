# MCA CALCULADORA V37

Se agrega el módulo 5. Cronograma de simulación, basado en la hoja Cronograma de Calculadora_Convenios_Base_2026.xlsx.

- Columnas: N°, Fecha, Saldo inicial, Cuota, Seguro, Cuota total, Interés, Capital y Saldo final.
- La cuota de crédito usa exactamente la misma tasa mensual y fórmula PMT de la hoja base: (1+tasa anual)^(1/12)-1.
- Las fechas consideran Fecha de corte, Fecha de pago y Periodo de gracia del perfil seleccionado.
- El seguro se calcula mensualmente sobre el saldo insoluto y se muestra separado; la cuota total = cuota de crédito + seguro.
- La cuota de crédito del cronograma coincide con la cuota simulada de la tarjeta de resultados.
- Mantiene la base de convenios, accesos, tasas, promedio de boletas y correcciones anteriores.
