# Reglas del prototipo PoliShop (Figma)

Archivo Figma: https://www.figma.com/design/PRqGFrIrwHwSZbTaI32kqu

**Antes de modificar el prototipo, lee [guia-interfaz.md](guia-interfaz.md).** Ahí está todo lo visual:
- La paleta como variables.
- La tipografía y el espaciado.
- Qué variante del logo va en cada pantalla.
- Qué pose de la mascota va en cada estado.

Los recursos están en `logo/` y `mascota/`, y la paleta en [paleta-colores.md](paleta-colores.md).

## Iconos
- Los iconos NO llevan fondo: nada de contenedores, círculos, cuadros redondeados, pills ni rellenos detrás del icono.
- Se usa solo el icono (instancia de `icon/*`), con su color de trazo y tamaño; el área táctil se resuelve con padding transparente, nunca con un fondo visible.
- Aplica a todo: botones de icono, iconos de categorías, filas de lista, tab bar, top bar, tarjetas, banners y overlays.
- Mismo estilo que el repo de aLata (`D:\GitHub\aLataFrontend`): librería **Ionicons** (MIT), SVG oficiales de ionic.io/ionicons.
  - Por defecto la variante **outline** (`notifications-outline`, `time-outline`, `calendar-outline`, `card-outline`, `chatbubble-outline`…).
  - Variante **rellena** solo para estados o énfasis: ítem activo del tab bar, `checkmark-circle`, `star` de calificación, `location`, `shield-checkmark`.
  - Chevrons y acciones simples: `chevron-forward`, `chevron-back`, `chevron-down`, `close`, `checkmark`, `search`.
  - Tamaños: 20–22 px en navegación y botones, 18 px en filas y metadatos, 14–16 px en detalles pequeños.
  - Color siempre desde las variables de color del archivo (nunca hex fijo).
- No usar Lucide ni mezclar librerías; los únicos SVG propios permitidos son logos de marca.
