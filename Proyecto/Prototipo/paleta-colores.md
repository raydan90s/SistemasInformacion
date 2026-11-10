# Paleta de colores — PoliShop

Paleta oficial del prototipo. Es la **opción A: Azul y ámbar**, elegida el 2026-11-08.

## Colores de marca (solo 4)

| Rol | Nombre | HEX | RGB | Uso |
|---|---|---|---|---|
| Principal | Azul Politécnico | `#0B3C8C` | 11, 60, 140 | Barra superior, títulos, precios, enlaces, chips activos, botón secundario (contorno) |
| Acento | Ámbar Feria | `#FFB23F` | 255, 178, 63 | Botón Comprar/Reservar, badge Premium, estrellas de reseña, publicaciones destacadas |
| Texto | Tinta | `#0E1A2B` | 14, 26, 43 | Texto principal y texto sobre botones ámbar |
| Fondo | Fondo Campus | `#FFFFFF` | 255, 255, 255 | Fondo de todas las pantallas (blanco desde el 2026-11-08; antes `#F4F7FC`) |

## Complementos (no son colores de marca)

| Nombre | HEX | Uso |
|---|---|---|
| Blanco | `#FFFFFF` | Tarjetas de producto, modales, inputs |
| Borde | `#DCE3EE` | Divisores y contornos de inputs |
| Texto secundario | `#55657D` | Descripciones, placeholders, fechas |
| Rojo error | `#D92D20` | Solo errores de formulario y productos agotados |

## Reglas

1. **Proporción por pantalla:** aproximadamente 70% fondo y blanco, 20% azul y 10% ámbar. Si todo es ámbar, nada destaca.
2. **Texto sobre ámbar siempre en Tinta (`#0E1A2B`)**, nunca blanco, porque no se lee.
3. **Texto sobre azul siempre blanco.**
4. **Estados sin colores extra:**
   - Disponible y Verificado ESPOL: azul con ícono ✓.
   - Pedido entregado: azul con ícono ✓.
   - Pocas unidades: ámbar con texto Tinta.
   - Agotado y errores: rojo error.
5. **Ferias y mercaditos (rol organizador):** fondo azul al 10–15% de opacidad con títulos en azul.
6. **Acento por rol, para el video:**
   - Comprador: azul.
   - Emprendedor: ámbar en el panel de ventas y en el plan Premium.
   - Organizador: el azul claro del punto 5.

## Tipografía sugerida

- **Títulos:** Bricolage Grotesque (600–800).
- **Texto:** Figtree (400–600).

Ambas son gratuitas en Google Fonts y están disponibles en Figma.

## Variables para Figma

En Figma, crea una colección de variables llamada `PoliShop` con estos colores:

```
color/primary      #0B3C8C
color/accent       #FFB23F
color/ink          #0E1A2B
color/background   #FFFFFF
color/surface      #FFFFFF
color/border       #DCE3EE
color/muted        #55657D
color/error        #D92D20
```

## Referencia visual

Página con las muestras de color y un mockup: https://claude.ai/artifact/2fh38fsmDvdGDtYfTHE49D
