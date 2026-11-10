# Guía de interfaz del prototipo PoliShop

Instrucciones para que Claude modifique el prototipo en Figma con una interfaz **limpia y coherente**. Aplica todo lo que sigue.

- **Archivo Figma:** https://www.figma.com/design/PRqGFrIrwHwSZbTaI32kqu
- **Carpeta de recursos:** `Proyecto/Prototipo/`

Documentos relacionados:
- [paleta-colores.md](paleta-colores.md): detalle de la paleta.
- [CLAUDE.md](CLAUDE.md): reglas de iconos.

---

## 1. Principios generales

- **Poco color, mucho espacio en blanco.** La interfaz debe verse ordenada, no recargada.
- **Un solo botón principal (ámbar) por pantalla.** El resto son secundarios (contorno azul) o enlaces.
- **Nada de degradados, texturas ni sombras fuertes.** Como máximo, una sombra suave en tarjetas: `0 2px 8px rgba(11,60,140,0.08)`.
- **Consistencia:** el mismo componente se ve igual en todas las pantallas. Usa componentes e instancias, no copias sueltas.
- Antes de crear algo nuevo, revisa si ya existe un componente en el archivo.

## 2. Paleta de colores

Crea o actualiza en Figma una colección de variables llamada **`PoliShop`** y aplica **siempre** variables, nunca hex sueltos:

| Variable | HEX | Uso |
|---|---|---|
| `color/primary` | `#0B3C8C` | Top bar, títulos, precios, enlaces, chips activos, ítem activo del tab bar, botón secundario (borde y texto) |
| `color/accent` | `#FFB23F` | Botón principal (Comprar, Reservar, Publicar, Postular), badge Premium, estrellas de reseña, destacados |
| `color/ink` | `#0E1A2B` | Texto principal y texto sobre botones ámbar |
| `color/background` | `#FFFFFF` | Fondo de todas las pantallas (blanco, cambiado el 2026-11-08; antes `#F4F7FC`) |
| `color/surface` | `#FFFFFF` | Tarjetas, modales, inputs, bottom sheets, tab bar |
| `color/border` | `#DCE3EE` | Divisores, bordes de inputs y tarjetas |
| `color/muted` | `#55657D` | Texto secundario, placeholders, iconos inactivos |
| `color/error` | `#D92D20` | Solo errores de formulario y "Agotado" |

Reglas:
1. **Proporción por pantalla:** cerca del 70% fondo y blanco, 20% azul y 10% ámbar.
2. **Texto sobre ámbar:** siempre `color/ink`, nunca blanco.
3. **Texto sobre azul:** siempre blanco.
4. **Estados sin colores nuevos:**
   - Disponible, Verificado ESPOL y Entregado: `color/primary` con un icono `checkmark-circle`.
   - Pocas unidades: texto en `color/ink` sobre una etiqueta ámbar.
   - Agotado y errores: `color/error`.
5. **Ferias y mercaditos (rol organizador):** tarjetas con fondo `color/primary` al 8–12% de opacidad y títulos en `color/primary`.
6. **No agregues verdes, morados ni otros tonos.** Si un color existente no está en la tabla, reemplázalo por la variable más cercana.

## 3. Tipografía

- **Títulos:** Bricolage Grotesque, SemiBold y Bold.
- **Texto e interfaz:** Figtree, Regular, Medium y SemiBold.

Si alguna no está disponible en Figma, usa Figtree para todo.

| Estilo | Tamaño / interlineado | Peso |
|---|---|---|
| Título de pantalla | 24 / 30 | Bricolage Bold |
| Título de sección | 18 / 24 | Bricolage SemiBold |
| Título de tarjeta | 15 / 20 | Figtree SemiBold |
| Cuerpo | 14 / 20 | Figtree Regular |
| Precio | 16 / 20 | Figtree Bold, `color/primary` |
| Etiqueta o metadato | 12 / 16 | Figtree Medium, `color/muted` |
| Botón | 15 / 20 | Figtree SemiBold |

Crea estos estilos de texto en Figma y aplícalos en todas las pantallas.

## 4. Espaciado y formas

- **Retícula de 8 px.** Espacios permitidos: 4, 8, 12, 16, 24, 32.
- **Márgenes laterales de pantalla:** 16 px.
- **Radios:** tarjetas e inputs 12 px; botones 12 px; chips y badges 999 px (pill); modales y bottom sheets 20 px arriba.
- **Botones:** 48 px de alto, ancho completo en acciones principales.
- **Inputs:** 48 px de alto, borde 1 px `color/border`, foco con borde 2 px `color/primary`.
- **Tarjetas de producto:** fondo `color/surface`, borde 1 px `color/border`, imagen arriba con radio 12 px y padding interno de 12 px.

## 5. Iconos

Sigue las reglas de [CLAUDE.md](CLAUDE.md):
- **Los iconos no llevan fondo.** Nada de círculos, cuadros, pills ni rellenos detrás del icono.
- Librería **Ionicons**, variante outline por defecto y rellena solo para estados o énfasis.
- Color desde las variables:
  - `color/muted` cuando está inactivo.
  - `color/primary` cuando está activo.
  - `color/ink` dentro de botones ámbar.
- Si encuentras iconos con contenedor o fondo, **quítaselo** y deja solo el icono.

## 6. Logo

Los archivos están en `Proyecto/Prototipo/logo/`. **Usa siempre las versiones `-transparente.png`** y súbelas a Figma con `upload_assets`.

| Archivo | Dónde usarlo | Tamaño en pantalla |
|---|---|---|
| `01-insignia-completa-transparente.png` | Splash, pantalla de login con credenciales ESPOL, portada y cierre del video | 160–200 px de ancho, centrado |
| `02-insignia-simplificada-transparente.png` | Encabezado de onboarding, pantalla "Acerca de", avatar de la cuenta oficial PoliShop en chats o soporte | 40–96 px |
| `03-icono-app-transparente.png` | Mockup del ícono en la pantalla de inicio del teléfono, slides del video | 60–120 px |
| `04-logotipo-horizontal-transparente.png` | **Top bar** de la pantalla de inicio (rol comprador) y del panel del emprendedor | 28–32 px de alto |
| `05-monocromatica-transparente.png` | Comprobantes de pedido, recibos y documentos donde el ámbar sobra | 40–64 px |
| `06-negativo-transparente.png` | Cualquier fondo azul `color/primary` (por ejemplo, un splash azul) | 160–200 px |
| `07-icono-32px` / `08-icono-48px` | Favicon y pestaña de la versión web | 32 / 48 px |

Reglas del logo:
- **No lo deformes:** escala siempre proporcional.
- **No le cambies los colores** ni le pongas sombras o bordes.
- Deja **espacio libre** alrededor de al menos el 25% de su tamaño.
- Si el top bar es azul, usa la versión negativa (`06`) o pon el logotipo sobre un top bar blanco. Para una interfaz más limpia se recomienda **top bar blanco** con el logotipo horizontal (`04`).
- Son imágenes rasterizadas de unos 400–600 px. No las amplíes por encima de su tamaño original.

## 7. Mascota (tortuga)

Los archivos están en `Proyecto/Prototipo/mascota/`. **Úsala solo sobre fondo claro** (`color/background` o `color/surface`). Las líneas del caparazón de las versiones transparentes son recortes y sobre un fondo de color se verían raras.
- Sobre `color/surface` (blanco), usa la versión `-fondo-blanco.png`.
- Sobre `color/background`, usa la versión `-transparente.png`.

| Archivo | Pantalla o estado |
|---|---|
| `01-bienvenido` | Onboarding y primer ingreso: "¡Bienvenido a PoliShop!" |
| `02-sin-resultados` | Búsqueda o filtros sin resultados |
| `03-pedido-reservado` | Confirmación de compra o reserva exitosa |
| `04-carrito-vacio` | Carrito vacío, y "Aún no tienes pedidos" |
| `05-proximas-ferias` | Sección de ferias vacía, convocatorias del organizador, confirmación de postulación enviada |
| `06-gracias-resena` | Después de enviar una calificación o reseña |
| `07-retiro-campus` | Pedido listo para retirar, detalle del punto de retiro |
| `08-algo-salio-mal` | Errores de pago, de conexión o de carga |

Reglas de la mascota:
- **Solo en estados vacíos, confirmaciones, onboarding y errores.** Nunca en listas, tarjetas de producto ni barras.
- **Una sola mascota por pantalla**, centrada, de 140–180 px de ancho.
- La estructura de estos estados es siempre la misma, centrada verticalmente:
  1. La mascota.
  2. Un título de 18 px.
  3. Una descripción de 14 px en `color/muted`, de máximo 2 líneas.
  4. Un botón de acción (ámbar si es la acción principal).
- No le agregues fondos, círculos ni sombras detrás.

## 8. Acentos por rol

Mantén la misma identidad; solo cambia el énfasis:

| Rol | Énfasis |
|---|---|
| Comprador | Azul `color/primary`: catálogo, filtros, carrito, reseñas |
| Emprendedor | Ámbar `color/accent` en el badge Premium, el botón "Publicar producto" y los indicadores de ventas del panel |
| Organizador de ferias | Tarjetas con fondo azul al 8–12% para ferias y convocatorias |

## 9. Checklist antes de terminar

- [ ] Todos los colores vienen de variables `PoliShop`, sin hex sueltos.
- [ ] No quedan colores fuera de la paleta (verdes, morados, grises sin tinte).
- [ ] Un solo botón ámbar por pantalla, con texto en `color/ink`.
- [ ] Ningún icono tiene fondo o contenedor.
- [ ] El logotipo horizontal está en el top bar y la insignia completa en el splash y el login.
- [ ] Los estados vacíos, las confirmaciones y los errores usan la pose correcta de la mascota.
- [ ] Los estilos de texto están aplicados y se respetan los márgenes de 16 px y la retícula de 8 px.
- [ ] Los prototipos (conexiones entre pantallas) siguen funcionando después de los cambios.

---

## Prompt para pedirle el cambio a Claude

```
Lee Proyecto/Prototipo/guia-interfaz.md, Proyecto/Prototipo/paleta-colores.md y Proyecto/Prototipo/CLAUDE.md. Luego modifica el prototipo de PoliShop en Figma (https://www.figma.com/design/PRqGFrIrwHwSZbTaI32kqu) para aplicar todo lo que indica la guía:
- La paleta como variables.
- La tipografía.
- Los iconos sin fondo.
- El logo correcto en cada pantalla, subiendo las imágenes de Proyecto/Prototipo/logo.
- La mascota en los estados vacíos, confirmaciones y errores, con las imágenes de Proyecto/Prototipo/mascota.

Revisa pantalla por pantalla, no rompas las conexiones del prototipo y al final recorre el checklist de la sección 9 y dime qué cambiaste y qué quedó pendiente.
```
