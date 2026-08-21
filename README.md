# MCA CALCULADORA V43 — CRONOGRAMA CORREGIDO E INTEGRADO

Corrección basada en las tres imágenes de referencia del usuario.

Caso de prueba:
- Monto: S/ 50,000
- TEA: 10.35%
- Fecha desembolso: 21/08/2026
- Corte: 7
- Vencimiento: 17
- Periodo de gracia: 2 meses
- Seguro sin devolución: 0.05511%

Modelo:
- Interés de gracia = monto * ((1+TEA)^(días/360)-1).
- Capital inicial = monto + interés de gracia.
- El plazo total incluye el periodo de gracia; cuotas = plazo - gracia.
- Interés de cada periodo = saldo * ((1+TEA)^(días/360)-1).
- Seguro = saldo * 0.05511% * días/30.
- Se resuelve una cuota TOTAL FIJA para que cada fila de Total a Pagar sea igual y el saldo final sea cero.
- En el caso de prueba, el resultado esperado es aproximadamente S/ 978.61 de Total a Pagar por cuota.
- La primera cuota de crédito es Total a Pagar menos seguro; por eso puede diferir ligeramente entre meses mientras el Total a Pagar permanece constante.

Además se conserva toda la calculadora integrada: convenios, perfiles, accesos, tasas, provisión, boletas, endeudamiento, deudas, logos y fecha de desembolso.
