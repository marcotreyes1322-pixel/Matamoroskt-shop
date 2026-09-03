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

## Antes de enseñárselo a un cliente

Hay tres cosas que todavía traen datos de relleno:

- [ ] **El WhatsApp** (`WHATSAPP` en `index.html`) está en `521625XXXXXXX`. Los
      tres botones de pedido no llevan a ningún lado hasta que se ponga el
      número real.
- [ ] **Los tres eventos** de la agenda son de ejemplo, no son reales.
- [ ] **Precios y disponibilidad** del catálogo, sin confirmar.

Todo eso se edita en el bloque marcado `EDITA AQUÍ`, arriba del archivo.
