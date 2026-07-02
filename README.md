# Generador de Dinámicas y Financiaciones

Herramienta web para armar las filas de la hoja **Items** del template de promos (Dinámicas de descuento y Financiaciones en cuotas). Es un único archivo HTML autocontenido: funciona sin internet y sin instalar nada, con lector/escritor de Excel (SheetJS) embebido.

**➡️ Usala online:** https://ramironicastro.github.io/GENERADOR-DE-DINAMICAS-Y-FINANZAS/

## Qué hace

- Cargás tu **maestro de artículos** (pegando desde Excel o subiendo un archivo `.xlsx`/`.csv`) y queda cacheado en el navegador.
- Definís los **datos de la campaña** (fechas, formatos de tienda, testimonial, forecast, región/tiendas, etc.).
- Armás **acciones** buscando productos por SKU, descripción, clase o subclase, con tipos de acción validados (`2x1`, `70% 2da U`, `12 CSI`, etc.).
- La app genera las filas listas para **copiar y pegar en la celda A2** de la hoja Items, o para **descargar como Excel**.
- Avisa si un SKU quedó en más de una acción (descuentos potencialmente acumulables) y permite guardar/retomar corridas.

## Novedades v10.4

- **Filtros de clase y subclase por chips** en el buscador de productos: un clic **incluye ✓**, dos clics **excluyen ✕**, tres la sacan del filtro. Se pueden combinar (ej. tildar dos clases y excluir una subclase) y cada grupo tiene su buscador de texto y botón "limpiar".

## Archivos

- [`index.html`](index.html) — la aplicación completa.
- [`Guia_de_uso_DDP_v10.html`](Guia_de_uso_DDP_v10.html) — guía de uso paso a paso (enlazada desde la app).

## Uso local

Descargá `index.html` y abrilo con doble clic en cualquier navegador moderno. No necesita servidor ni conexión.

---

Desarrollado por **Ramiro Nicastro**.
