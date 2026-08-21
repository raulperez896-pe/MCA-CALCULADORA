# MCA CALCULADORA V40

## Cambio principal
Se agregó **Fecha de desembolso** como campo editable en la calculadora.

El cronograma ya no toma la fecha actual para determinar los días de gracia. Utiliza la fecha real ingresada por el usuario y calcula:

- ciclo según fecha de desembolso y fecha de corte;
- primer vencimiento según fecha de pago;
- periodo de gracia del convenio;
- fecha de inicio de devengo (un mes antes del primer vencimiento);
- número exacto de días entre desembolso y devengo;
- interés generado por esos días;
- capitalización de ese interés al saldo inicial;
- cronograma posterior con amortización, interés, seguro y total a pagar.

También se muestran en el resumen **Fecha desembolso** y **Días de gracia calculados**.
