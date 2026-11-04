# CSS
Repositorio dedicado al aprendizaje de CSS
"Hallazgos de modelo de caja"
Las diferencias practicas entre padding y margin son:
*Padding: Es el relleno o el contenido entre la caja y el borde
*Margin: El margin es el espacio externo, sirve para separar el borde del archivo con lo que lo rodea

¿Por qué es obligatorio usar box-sizing: border-box?:
*para evitar que la imagen se repita o se deforme al cambiar el tamaño de la ventana

¿Cómo se ven afectados los elementos hermanos cuando le aplicas un margen grande a uno de ellos?:
*Afecta directamente a sus elementos hermanos empujándolos y desplazándolos para reclamar su espacio, ya que el margen actúa como una "barrera invisible" por fuera del borde.

“Hallazgos: Centralización de Identidad Visual y Espaciado”
La lista completa de variables declaradas (colores y espaciados):
*--color
*--fuente-principal
*--espaciado-pequeno
*--espaciado-mediano
*--espaciado-grande
La ventaja de reutilizar medidas de margen y relleno en lugar de inventar valores en cada selector:
*La principal ventaja de reutilizar medidas de margen (margin) y relleno (padding) en lugar de inventar valores en cada selector es la consistencia visual y la mantenibilidad del diseño (escalabilidad).
De qué manera la centralización en :root previene colisiones visuales a medida que la hoja de estilos crece.
*previene colisiones visuales a medida que una hoja de estilos crece principalmente porque establece una "fuente única de verdad" global y elimina la dispersión de valores mágicos (magic numbers) en el código.