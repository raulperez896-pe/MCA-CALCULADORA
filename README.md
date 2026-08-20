# MCA CALCULADORA V15

## Saco de liquidez — lógica corregida

El ingreso variable NO se toma completo. Primero se aplica el porcentaje `% Ingreso variable` del perfil seleccionado en `Adicional Core`.

1. Promedio Ingreso Fijo.
2. Promedio Ingreso Variable.
3. Ingreso Variable Convertido = Ingreso Variable × `% Ingreso variable`.
4. Base RCI = Ingreso Fijo + Ingreso Variable Convertido − Descuento de Ley.
5. Base RCI × RCI del convenio.
6. Se resta el Facultativo promedio.
7. Se resta la Provisión automática del convenio.

Resultado:
`Saco de liquidez = (Fijo + Variable×%Conversión − Ley) × RCI − Facultativos − Provisión`

## Buró
Los rangos se interpretan de forma consecutiva:
- G1-G3 = G1/G2/G3
- G4-G6 = G4/G5/G6
- NB-G6 = NB/G1/G2/G3/G4/G5/G6

La misma lógica se usa para encontrar la tasa.

## Interfaz
No se muestra:
- Factor cuota
- Capacidad RCI
- Fórmula del cálculo

La provisión es automática.
