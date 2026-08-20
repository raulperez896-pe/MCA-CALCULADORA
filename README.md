# MCA CALCULADORA V20

## Acceso de promotores

Se eliminó del encabezado el contador `238 convenios · 548 perfiles`.

Ahora el encabezado muestra los datos del promotor autenticado:
- Nombre
- Código
- Plaza
- Supervisor

La información proviene de `base_accesos_editable.csv`.

### Base de accesos
Columnas:
`Usuario, Clave, Promotor, Codigo, Supervisor, Plaza, Estado`

Reemplazar el registro DEMO por los usuarios reales.

### Importante
GitHub Pages es un sitio estático. Esta base CSV sirve para control funcional/prototipo, pero NO es un sistema de autenticación seguro para producción: las credenciales pueden ser inspeccionadas por usuarios con conocimientos técnicos. Para producción se recomienda un backend o servicio de autenticación.

El resto de la calculadora y la base de convenios se mantienen.
