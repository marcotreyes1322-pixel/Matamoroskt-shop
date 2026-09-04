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
| `MATA5-RNY8` | `MATA10-RFYZ` | `MATA15-VJ6V` |
| `MATA5-JN7Q` | `MATA10-XXYN` | `MATA15-JPC2` |
| `MATA5-YSAQ` | `MATA10-BHNA` | `MATA15-JBVJ` |
| `MATA5-M8HC` | `MATA10-LQT5` | `MATA15-5TG1` |
| `MATA5-P45G` | `MATA10-VC78` | `MATA15-BPZ5` |
| `MATA5-NQ40` | `MATA10-W7VG` | `MATA15-GAD3` |
| `MATA5-4T3I` | `MATA10-8Z44` | `MATA15-J6ZB` |
| `MATA5-FC4E` | `MATA10-NJWL` | `MATA15-462X` |
| `MATA5-ET9H` | `MATA10-C5ML` | `MATA15-5MCW` |
| `MATA5-MSDH` | `MATA10-C9P4` | `MATA15-YRD8` |
| `MATA5-FHNF` | `MATA10-HY5E` | `MATA15-PYJ6` |
| `MATA5-ZUZU` | `MATA10-S3HU` | `MATA15-F3NM` |

> **Ojo con esto:** el sitio es un archivo que cualquiera puede abrir, así que la
> regla de los códigos se puede deducir leyendo el código fuente. Sirve para que
> nadie caiga en uno tecleando de casualidad, pero no es una caja fuerte. La
> validación de verdad la haces tú: el pedido te llega por WhatsApp con el
> código escrito, y tú sabes a quién se lo diste.

## Antes de enseñárselo a un cliente

Hay tres cosas que todavía traen datos de relleno:

- [ ] **El WhatsApp** (`WHATSAPP` en `index.html`) está en `521625XXXXXXX`. Los
      tres botones de pedido no llevan a ningún lado hasta que se ponga el
      número real.
- [ ] **Los tres eventos** de la agenda son de ejemplo, no son reales.
- [ ] **Precios y disponibilidad** del catálogo, sin confirmar.

Todo eso se edita en el bloque marcado `EDITA AQUÍ`, arriba del archivo.
