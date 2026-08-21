# MCA CALCULADORA V24

## Lógica corregida de boletas

### Caso 1: solo Boleta 1
Si el usuario llena únicamente Boleta 1, la simulación utiliza únicamente los valores de Boleta 1.
No divide los valores entre 3 ni considera Boleta 2/3 vacías como ceros.

### Caso 2: Boleta 2
Cuando se ingresa el Ingreso Variable de Boleta 2, se copian automáticamente desde Boleta 1:
- Ingreso Fijo
- No constante
- Descuento de Ley
- Facultativo

El Ingreso Variable de Boleta 2 queda con el valor ingresado por el usuario.

### Caso 3: Boleta 3
Cuando se ingresa el Ingreso Variable de Boleta 3, se copian automáticamente desde Boleta 1:
- Ingreso Fijo
- No constante
- Descuento de Ley
- Facultativo

El Ingreso Variable de Boleta 3 queda con el valor ingresado por el usuario.

### Promedios
- Solo B1 llena → promedio = B1.
- B1 + B2 → promedio = (B1+B2)/2.
- B1 + B2 + B3 → promedio = (B1+B2+B3)/3.

La réplica se realiza mediante delegación de eventos para que funcione aunque la interfaz actualice/re-renderice los campos.
