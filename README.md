# MCA CALCULADORA V30

Correcciones principales:

1. Se corrigió la búsqueda del perfil Convenio + Cargo + Condición.
   - Normaliza espacios, saltos de línea, BOM y espacios no separables.
   - Evita que un perfil quede sin parámetros por diferencias invisibles del CSV.

2. Se corrigió la lectura de tasas.
   - Reconoce rangos como G1 - G3, G4 - G5 y G6 - OTROS.
   - También tolera rangos escritos con "a".
   - Aplica la tasa según Buró + tipo de seguro.

3. Parámetros del convenio se actualizan inmediatamente al seleccionar el perfil.

4. Sección 3 Datos financieros ahora ocupa 2/3 del ancho y Parámetros 1/3, manteniendo el ancho total alineado con la sección 2.

5. Se mantiene la sección 4 a todo el ancho inferior.
