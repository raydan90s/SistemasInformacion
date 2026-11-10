# Prompts para el logo de PoliShop (ChatGPT)

Colores: ver [paleta-colores.md](paleta-colores.md). Azul Politécnico `#0B3C8C` y Ámbar Feria `#FFB23F`.

## Paso 1: varias ideas en una lámina

```
Actúa como diseñador de marca. Genera UNA imagen cuadrada (1:1) tipo hoja de exploración de logos, fondo blanco, con 6 propuestas DISTINTAS de logotipo para "PoliShop", ordenadas en una cuadrícula de 3 columnas x 2 filas. Cada propuesta lleva debajo un número grande (1 a 6) para poder elegirla.

Contexto de la marca: PoliShop es un marketplace digital (app móvil y web) de la comunidad universitaria ESPOL en Guayaquil, Ecuador. Estudiantes, docentes y personal compran y venden productos y servicios dentro del campus (comida, útiles, ropa, tutorías, impresiones), retiran en puntos del campus y participan en ferias de emprendimiento estudiantil. La marca debe transmitir confianza (usuarios verificados, reseñas, pagos seguros) y energía joven de emprendimiento.

Colores OBLIGATORIOS, sin agregar ningún otro:
- Azul Politécnico #0B3C8C (color principal, la mayor parte del logo)
- Ámbar Feria #FFB23F (solo en un detalle de acento)
- Blanco de fondo

Las 6 propuestas deben explorar conceptos diferentes:
1. Letra "P" que forma una bolsa de compras (el asa en ámbar).
2. Etiqueta de precio con un pequeño birrete o la forma de la P en su interior.
3. Pin de ubicación con forma de bolsa (referencia a los puntos de retiro en el campus).
4. Toldo o carpa de feria estilizada sobre la palabra PoliShop (toldo con franjas azul y ámbar).
5. Dos flechas o manos formando un intercambio dentro de un círculo (compra y venta entre la comunidad).
6. Solo tipografía (wordmark): "Poli" en azul y "Shop" en ámbar, con un detalle creativo en una letra.

Cada propuesta incluye el ícono y el texto "PoliShop" escrito correctamente. Estilo: vector plano, geométrico, moderno, simple, legible como ícono de app pequeño. Sin degradados, sin 3D, sin sombras, sin texturas. Tipografía sans-serif redondeada y amigable. No uses el escudo ni el logo oficial de ESPOL.
```

## Paso 2: desarrollar la idea elegida

Reemplaza `N` por el número elegido.

```
Me gusta la propuesta N. Desarróllala como logo final, en una sola imagen horizontal 16:9 sobre fondo blanco, mostrando:
1) Logotipo horizontal (ícono + texto "PoliShop").
2) Ícono de app cuadrado con esquinas redondeadas sobre fondo #0B3C8C.
3) Versión monocromática en #0B3C8C.
4) Versión en negativo (blanco sobre #0B3C8C).
5) El ícono en tamaño pequeño (favicon) para comprobar que se entiende.

Mantén exactamente los colores #0B3C8C y #FFB23F, sin agregar otros. Vector plano, sin degradados ni sombras. Escribe "PoliShop" correctamente.
```

## Paso 3: correcciones habituales

- Colores alterados: `Ajusta los colores exactamente a #0B3C8C (azul) y #FFB23F (ámbar), sin otros tonos.`
- Texto mal escrito: `El texto debe decir exactamente "PoliShop", con P y S mayúsculas.`
- Demasiado detalle: `Simplifica el ícono: menos elementos, trazos más gruesos, que se entienda a 48 px.`
- Fondo para Figma: `Genera solo el ícono, centrado, sobre fondo blanco liso, sin texto.` Luego quita el fondo en Figma o con remove.bg.

## Ideas por revisar

Anotar aquí qué propuestas gustaron al grupo:

- **Ronda 1 (2026-11-08):** el favorito es el **#1**, la P con forma de bolsa y el asa ámbar. Hay que simplificarlo: quitar el carrito interior y los destellos. El #6 (Poli azul y Shop ámbar) sirve como estilo del texto. Descartados:
  - #2: demasiados elementos.
  - #3: genérico, parece de app de delivery.
  - #4: el ícono no funciona sin el texto.
  - #5: parece un ícono de "actualizar" o "reciclar".

### Prompt de desarrollo (idea 1 + texto de la 6)

```
Me gusta la propuesta 1 (la letra P con forma de bolsa de compras y el asa en ámbar). Desarróllala como logo final con estos cambios:
- Quita el carrito de compras del interior de la P: el hueco de la P queda como un círculo o forma blanca limpia.
- Quita las líneas de destello de la esquina.
- La P-bolsa debe ser más geométrica: esquinas redondeadas uniformes y trazos gruesos.
- Texto "PoliShop" con "Poli" en #0B3C8C y "Shop" en #0B3C8C (todo en azul). El ámbar se usa solo en el asa.

Entrega en una sola imagen horizontal 16:9, fondo blanco, mostrando:
1) Logotipo horizontal (ícono a la izquierda + texto "PoliShop").
2) Ícono de app cuadrado con esquinas redondeadas: fondo #0B3C8C, P-bolsa en blanco y asa en #FFB23F.
3) Versión monocromática toda en #0B3C8C.
4) Versión en negativo (blanco sobre #0B3C8C).
5) El ícono en tamaño pequeño (32 px y 48 px) para comprobar que se entiende.

Solo los colores #0B3C8C, #FFB23F y blanco. Vector plano, sin degradados, sin sombras, sin 3D. Escribe "PoliShop" exactamente así.
```

### Ronda 2: identidad politécnica sobre la idea 1

```
Partimos de la propuesta 1 (la letra P con forma de bolsa de compras y asa en ámbar), pero le falta identidad POLITÉCNICA: debe sentirse de una universidad de ingeniería y tecnología, no de una tienda cualquiera.

Genera UNA imagen cuadrada (1:1), fondo blanco, con 6 variaciones de esa misma P-bolsa en una cuadrícula de 3 x 2, cada una con un número grande debajo (1 a 6) y el texto "PoliShop" en #0B3C8C. Cada variación integra UN solo elemento de ingeniería, sin recargar:

1. El hueco interior de la P es una tuerca hexagonal (el agujero de la P tiene forma de hexágono).
2. El asa de la bolsa es un compás de dibujo técnico abierto, en ámbar.
3. El hueco de la P es un engranaje pequeño, en ámbar.
4. La P está construida sobre una cuadrícula técnica tipo plano (blueprint): líneas finas de construcción y cotas visibles detrás del ícono, en azul claro muy sutil.
5. El asa es la borla (tassel) de un birrete de graduación, que cuelga en ámbar.
6. El trazo de la P termina en nodos de circuito (pequeñas líneas con puntos, estilo pista de circuito impreso) en ámbar.

Reglas:
- Solo los colores #0B3C8C (azul), #FFB23F (ámbar) y blanco.
- El ámbar aparece en un solo detalle por variación.
- Sin carritos de compra y sin líneas de destello.
- Cada ícono debe seguir entendiéndose como bolsa de compras y como letra P a 48 px.
- Vector plano y geométrico, trazos gruesos, sin degradados, sin sombras, sin 3D.
- No uses el escudo, el logo oficial ni el nombre "ESPOL".
```

### Ronda 3: tortuga de ESPOL y logo de ESPOL (prototipo académico)

Adjunta a ChatGPT una imagen del logo de ESPOL y otra de la tortuga como referencia. Si no, la inventará.

```
Este logo es para un prototipo académico de una materia universitaria, no es una marca comercial, así que sí puedes inspirarte en la identidad de ESPOL. Te adjunto como referencia el logo de ESPOL y la tortuga que la representa.

Genera UNA imagen cuadrada (1:1), fondo blanco, con 6 propuestas de logo para "PoliShop" (marketplace de la comunidad ESPOL) en una cuadrícula de 3 x 2, cada una con un número grande debajo (1 a 6) y el texto "PoliShop" en #0B3C8C:

1. Tortuga vista desde arriba cuyo caparazón es una bolsa de compras, con el asa en ámbar sobre el caparazón.
2. La letra P con forma de bolsa (como la versión anterior), con el hueco de la P relleno con el patrón hexagonal de un caparazón de tortuga.
3. Una tortuga simpática y simple, de perfil, que carga una bolsa de compras ámbar en su caparazón (estilo mascota, ideal para ícono de app).
4. Un caparazón de tortuga formado por hexágonos, donde un hexágono central contiene la P en ámbar.
5. La P-bolsa de la versión anterior combinada con un elemento gráfico tomado del logo de ESPOL que te adjunto (su forma o símbolo principal), adaptado a la bolsa.
6. Wordmark "PoliShop" donde la "o" de "Poli" es una pequeña tortuga vista desde arriba con caparazón hexagonal, y el asa de una bolsa en ámbar sobre la "S" o la "h".

Reglas:
- Solo los colores #0B3C8C (azul), #FFB23F (ámbar) y blanco.
- El ámbar aparece en un solo detalle por propuesta.
- Sin carritos de compra y sin líneas de destello.
- Las tortugas deben ser simples y geométricas, no realistas: pocas formas, trazos gruesos, que se entiendan a 48 px.
- Vector plano, sin degradados, sin sombras, sin 3D.
- Escribe "PoliShop" exactamente así.
```

**Resultado ronda 3:** gustó, pero se busca variar. Notas:
- Las mejores fueron la #1 (tortuga marina con asa), la #3 (mascota de perfil) y la #6 (tortuga como "o").
- La #4 y el hueco de la #2 parecen un balón de fútbol porque tienen demasiados hexágonos.
- La #5 tiene demasiado detalle.

### Ronda 4: tortuga con estilos distintos

```
Me gustó la dirección de la tortuga, pero quiero explorar estilos DIFERENTES a los anteriores. Genera UNA imagen cuadrada (1:1), fondo blanco, con 6 propuestas nuevas de logo para "PoliShop" en una cuadrícula de 3 x 2, cada una con un número grande debajo (1 a 6) y el texto "PoliShop" en #0B3C8C:

1. Espacio negativo: la silueta de una bolsa de compras en azul, y dentro, recortada en blanco, la silueta de una tortuga.
2. Una bolsa de compras de la que asoma la cabeza de una tortuga por arriba, entre las asas, como si la bolsa fuera su caparazón. El asa en ámbar.
3. Monolínea: una tortuga dibujada con UNA sola línea continua de trazo grueso, cuyo caparazón forma la letra P. Un solo detalle en ámbar.
4. Insignia o sticker circular, estilo parche universitario: tortuga de perfil al centro, el texto "PoliShop" siguiendo la curva del círculo y una pequeña bolsa ámbar.
5. Tortuga construida solo con figuras geométricas básicas: un semicírculo para el caparazón, círculos para la cabeza y las patas. Sobre el caparazón, una etiqueta de precio ámbar.
6. Un caparazón visto de frente que es a la vez el techo de un puesto de feria (toldo) y se apoya en las patas de la tortuga como columnas, con franjas azul y ámbar.

Reglas:
- Solo los colores #0B3C8C (azul), #FFB23F (ámbar) y blanco.
- El ámbar aparece en un solo detalle por propuesta.
- Si usas hexágonos en el caparazón, máximo 3 a 5, para que NO parezca un balón de fútbol.
- Sin carritos de compra y sin líneas de destello.
- Simple y geométrico: pocas formas y trazos gruesos, que se entienda a 48 px.
- Vector plano, sin degradados, sin sombras, sin 3D.
- Escribe "PoliShop" exactamente así.
- Que las 6 se vean claramente distintas entre sí y distintas de las propuestas anteriores.
```

## Decisión: tortuga mascota (ronda 3, #3)

Elegida el 2026-11-08: tortuga de perfil con una bolsa ámbar sobre el caparazón.

Qué refinar:
- La bolsa tiene forma de trapecio y parece una pesa. Además flota sobre el caparazón. Debe ser una bolsa clara, sujeta al caparazón.
- Mezcla estilos: el caparazón tiene relleno y las patas y la cabeza solo contorno. Hay que unificar.
- Las placas del caparazón deben ser 3 o 4, para que no parezca un balón.
- Debe caber bien en un cuadrado para el ícono de app.

### Prompt de refinamiento

```
Me quedo con la propuesta 3: la tortuga de perfil que carga una bolsa de compras ámbar sobre el caparazón. Refínala como logo final con estos cambios:

- La bolsa debe verse claramente como una BOLSA DE COMPRAS (rectangular con esquinas suaves y un asa en arco), no como una pesa o trapecio. Que esté apoyada y sujeta sobre el caparazón, no flotando.
- Unifica el estilo: toda la tortuga en formas sólidas rellenas de #0B3C8C (cabeza, patas y caparazón), con las divisiones del caparazón en líneas blancas.
- Caparazón con solo 3 o 4 placas grandes y simples.
- Cara amigable: un ojo y una sonrisa pequeña, mirando hacia adelante (a la derecha).
- Proporciones compactas para que el ícono quepa bien en un cuadrado.
- Bolsa en #FFB23F, opcionalmente con una pequeña "P" blanca en la bolsa.

Entrega en una sola imagen horizontal 16:9, fondo blanco, mostrando:
1) Logotipo horizontal: la tortuga a la izquierda y el texto "PoliShop" a la derecha en #0B3C8C.
2) Logotipo vertical: la tortuga arriba y el texto debajo.
3) Ícono de app cuadrado con esquinas redondeadas: fondo #0B3C8C, tortuga en blanco y bolsa en #FFB23F.
4) Versión monocromática toda en #0B3C8C.
5) El ícono en tamaño pequeño (32 px y 48 px) para comprobar que se entiende.

Solo #0B3C8C, #FFB23F y blanco. Vector plano, geométrico, trazos gruesos, sin degradados, sin sombras, sin 3D. Escribe "PoliShop" exactamente así.
```

## Decisión final: insignia circular (ronda 4, #4)

Cambio de decisión el 2026-11-08: el grupo prefiere la **insignia tipo parche universitario**, con la tortuga de perfil dentro de un círculo y "PoliShop" en arco.

Qué refinar:
- La bolsa cuelga de la boca o el cuello y no se entiende. Debe ir sobre el caparazón.
- Las rayitas laterales y la línea de suelo meten ruido.
- El aro es delgado comparado con la tortuga.
- A 48 px el texto en arco no se lee. Hace falta una versión sin texto para el ícono.

### Prompt de refinamiento de la insignia

```
Me quedo con la propuesta 4: la insignia circular tipo parche universitario con la tortuga de perfil y el texto "PoliShop" en arco. Refínala como logo final con estos cambios:

- Aro exterior más grueso y uniforme en #0B3C8C, con un segundo aro interior delgado (estilo sello o parche).
- Texto "PoliShop" en arco en la parte superior, en negrita, bien espaciado y centrado. En el arco inferior, el texto "COMUNIDAD ESPOL" más pequeño, en mayúsculas espaciadas. Separa ambos textos con dos puntos o estrellas pequeñas a los lados.
- Tortuga centrada, de perfil y mirando a la derecha, toda en relleno sólido #0B3C8C (cabeza, patas y caparazón), con las divisiones del caparazón en líneas blancas y solo 3 o 4 placas grandes.
- La bolsa de compras #FFB23F va apoyada sobre el caparazón, como si la tortuga la cargara en la espalda, con forma clara de bolsa (rectangular con asa en arco), no colgando de la boca.
- Cara amigable: un ojo y una sonrisa pequeña.
- Elimina las rayitas laterales y la línea de suelo.

Entrega en una sola imagen horizontal 16:9, fondo blanco, mostrando:
1) La insignia completa (con los textos en arco).
2) Versión simplificada para ícono: el círculo con solo la tortuga y la bolsa, sin textos.
3) Ícono de app cuadrado con esquinas redondeadas: fondo #0B3C8C, tortuga en blanco y bolsa en #FFB23F, sin textos.
4) Logotipo horizontal para la barra de la app: la insignia simplificada a la izquierda y "PoliShop" en texto a la derecha.
5) Versión monocromática en #0B3C8C y versión en negativo (blanco sobre #0B3C8C).
6) La versión simplificada en tamaño pequeño (32 px y 48 px).

Solo #0B3C8C, #FFB23F y blanco. Vector plano, geométrico, trazos gruesos, sin degradados, sin sombras, sin 3D, sin texturas. Escribe "PoliShop" exactamente así.
```

**Resultado del refinamiento:** el sistema quedó muy bien. Tiene insignia completa, insignia simplificada, ícono de app, logotipo horizontal, versiones monocromática y en negativo, y prueba en tamaños pequeños.

### Prueba sin sonrisa

```
Mantén EXACTAMENTE el mismo diseño, composición, colores, textos y todas las versiones de esta lámina. El único cambio: quita la sonrisa de la tortuga en todas las versiones. Deja solo el ojo (un punto), con la cara lisa, para una expresión más seria y neutral. No cambies nada más.
```

Para comparar mejor, se puede pedir una variante con las dos lado a lado:

```
Muéstrame lado a lado el ícono de app cuadrado en dos versiones: A) la tortuga con sonrisa (como está ahora) y B) la tortuga sin sonrisa, solo con el ojo. Mismo tamaño, mismo diseño y mismos colores; solo cambia la boca.
```

### Extra: poses de la mascota para el prototipo

Úsalo después de tener el logo final, en el mismo chat:

```
Con esta misma tortuga y exactamente el mismo estilo y colores, genera una lámina con 6 poses para usar en la app, cada una con su etiqueta debajo:
1) Saludando ("¡Bienvenido!").
2) Buscando con una lupa ("Sin resultados").
3) Celebrando con la bolsa en alto ("¡Pedido reservado!").
4) Con la bolsa vacía, triste ("Tu carrito está vacío").
5) Con un letrero de feria ("Próximas ferias").
6) Con una estrella ámbar ("¡Gracias por tu reseña!").
Fondo blanco, solo #0B3C8C, #FFB23F y blanco, vector plano.
```
