# MCA CALCULADORA V46

Corrección del plazo máximo:
- Usa los IDs reales de la calculadora: conv, cargo y cond.
- Usa el perfil exacto devuelto por current().
- Toma Edad máxima del convenio/perfil seleccionado.
- Fecha límite = un mes antes de cumplir la edad máxima.
- Plazo máximo = meses completos desde fecha de desembolso hasta esa fecha límite.
- Se muestra en Resultado de la simulación.
- Si el cliente ya supera esa fecha límite, muestra NO OTORGABLE.
- La edad utilizada para las validaciones se calcula desde fecha de nacimiento y fecha de desembolso.
