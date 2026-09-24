# Matamoros Skateshop

Skateshop móvil en Cuauhtémoc, Chihuahua. Armas tu patineta pieza por pieza y la
pides por WhatsApp.

## 🛹 Ver el sitio

**https://marcotreyes1322-pixel.github.io/Matamoroskt-shop/**

Este es el enlace para compartir: se abre en cualquier teléfono o computadora,
sin cuenta ni permisos. *(Falta prenderlo una vez — ver abajo.)*

## Cómo prender el enlace (una sola vez, 30 segundos)

1. Entra a **[Settings → Pages](https://github.com/marcotreyes1322-pixel/Matamoroskt-shop/settings/pages)** del repo.
2. En **Source**, elige **Deploy from a branch**.
3. En **Branch**, elige `claude/design-complexity-ivm6lz` y la carpeta `/ (root)`. Dale **Save**.
4. Espera un par de minutos y abre el enlace de arriba.

Es gratis porque el repo es público. Una vez prendido, cada vez que se suba un
cambio el sitio se actualiza solo.

**Y de pasada se arregla la vista previa.** Cuando pegas el enlace en WhatsApp,
el chat muestra una tarjeta con foto. Esa foto es
[`portada.jpg`](portada.jpg) — el Mapache en pleno truco, con el nombre encima,
sacada de la portada real del sitio. Las etiquetas ya están puestas apuntando
ahí, pero WhatsApp sólo puede ir a buscarla si el sitio está publicado: sin
Pages prendido, el enlace se ve como un cuadro gris sin nada.

## Qué es

Todo el sitio es **un solo archivo**, [`index.html`](index.html). No hay build,
no hay dependencias, no hay servidor: se abre y funciona.

- **El taller** — el arco 3D donde eliges lija, tabla, trucks y ruedas, con el
  precio armándose en vivo. Las piezas se renderizan en 3D en tu propio
  navegador, con WebGL, así que no pesan nada en el archivo.
- **El catálogo** — 16 piezas con búsqueda, filtros, favoritos y carrito.
- **La portada** — un montaje de siete escenas que se van fundiendo.
- **Todo desemboca en WhatsApp**, con el pedido ya escrito.

Sin WebGL (equipos viejos) el sitio no se rompe: las piezas caen a dibujos
técnicos y lo demás sigue funcionando igual.

## Los códigos de descuento

Cuando alguien te manda un clip por WhatsApp y te gusta, le pasas uno de estos.
La persona lo escribe en el carrito o en el panel del taller, ve su total ya
rebajado, y el código se va escrito dentro del pedido que te llega — así sabes
cuál usaste y a quién.

**Ve tachando los que ya diste.** Si se acaban, se pueden hacer más.

| 5% | 10% | 15% |
|---|---|---|
| `MATA5-FELJS` | `MATA10-JFCGT` | `MATA15-A238J` |
| `MATA5-H8APO` | `MATA10-MJ8S1` | `MATA15-TFDTF` |
| `MATA5-UARKX` | `MATA10-H5ZLF` | `MATA15-69N9O` |
| `MATA5-826P3` | `MATA10-9DGTE` | `MATA15-THPVH` |
| `MATA5-NLUNM` | `MATA10-QWU2T` | `MATA15-QTGXH` |
| `MATA5-Z5NZY` | `MATA10-XXPAE` | `MATA15-LZNDD` |
| `MATA5-A96JD` | `MATA10-5MT2Q` | `MATA15-8J954` |
| `MATA5-RZRYD` | `MATA10-PVRB6` | `MATA15-KN4BM` |
| `MATA5-89NVS` | `MATA10-8QSE8` | `MATA15-8ZVJP` |
| `MATA5-RDMFA` | `MATA10-ZRPMM` | `MATA15-6EKJX` |
| `MATA5-D7VQM` | `MATA10-JA3C2` | `MATA15-Z87X6` |
| `MATA5-8AC2D` | `MATA10-9LX0R` | `MATA15-TJKX2` |

> **Ojo con esto:** el sitio es un archivo que cualquiera puede abrir, así que la
> regla de los códigos se puede deducir leyendo el código fuente. Adivinando a
> ciegas pasa uno de cada 1,300 intentos, así que nadie cae en uno de
> casualidad — pero no es una caja fuerte. La validación de verdad la haces tú:
> el pedido te llega por WhatsApp con el código escrito, y tú sabes a quién se
> lo diste.

## Antes de enseñárselo a un cliente

Hay tres cosas que todavía traen datos de relleno:

- [ ] **El WhatsApp** (`WHATSAPP` en `index.html`) está en `521625XXXXXXX`. Los
      tres botones de pedido no llevan a ningún lado hasta que se ponga el
      número real.
- [x] ~~**Los tres eventos** de la agenda son de ejemplo~~ — ya se quitaron. La
      sección de agenda está escondida (y su liga del menú también) mientras no
      haya fechas reales. Para que vuelva, descomenta el renglón de ejemplo en
      `EVENTOS` y cámbiale los datos: reaparece sola, con su cuenta regresiva y
      su botón de "cómo llegar".
- [ ] **Precios y disponibilidad** del catálogo, sin confirmar.

Todo eso se edita en el bloque marcado `EDITA AQUÍ`, arriba del archivo.
