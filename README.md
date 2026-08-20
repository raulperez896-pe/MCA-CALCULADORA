# MCA CALCULADORA V22

Corrección del acceso de promotores.

### Acceso de Raul Perez
- Código: `RP001`
- Usuario: `RAULPEREZ`
- Contraseña: `1234567`
- Estado: ACTIVO

El login acepta indistintamente **Código o usuario**.

Se corrigió el problema por el cual la base de accesos se estaba intentando leer con el parser de la base de convenios. Ahora `base_accesos_editable.csv` tiene su propio parser.

No existe usuario demo de respaldo si la base de accesos no carga.
