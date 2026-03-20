

## Características Técnicas

### 1. Navegación de Vista Única (SPA) con CSS
Se implementó la sección de Starbucks Rewards utilizando la pseudo-clase :target. Esta técnica permite alternar la visibilidad de grandes bloques de contenido basándose en el ID del fragmento de la URL, eliminando la necesidad de scripts externos o recargas de página.

### 2. Arquitectura Responsiva
El sistema de estilos se diseñó bajo una lógica de adaptabilidad para asegurar la integridad visual en diversos dispositivos:
* Media Queries: Se establecieron puntos de ruptura para reconfigurar el Navbar y los elementos de navegación en pantallas de menor resolución.
* Flexbox y CSS Grid: Se utilizaron modelos de caja flexible para el banner principal y sistemas de rejilla para la sección de beneficios, permitiendo una redistribución fluida de los elementos.


## Estructura del Proyecto

### Vista Principal
* Banner de bienvenida con diseño asimétrico.
* Cuadrícula de productos con categorías de Bebidas, Alimentos y Café en grano.
* Footer con organización de enlaces y barra de redes sociales.

### Vista Rewards
* Interfaz de pantalla dividida (Split-screen).
* Panel informativo con beneficios categorizados por niveles (Green y Gold).
* Sistema de cierre para retorno a la vista principal mediante navegación interna.
