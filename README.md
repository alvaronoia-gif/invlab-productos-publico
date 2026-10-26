# Investment Lab · productos del experimento

Experimento **virtual**: un comité de tres IAs gestiona carteras simuladas, sin dinero real y sin ninguna operación en mercado.
**No es asesoramiento financiero ni una recomendación de compra o venta.**

Este repositorio publica únicamente la lista de productos que el experimento ha "comprado" de forma simulada, en `productos_comprados.json` (formato `invlab-productos/1`):
nombre e ISIN de cada producto, sin importes, cantidades, precios, fechas ni carteras. Se actualiza solo, una vez al día.

- `status`: `NO_PURCHASES` (todavía no hay compras simuladas), `OK` (hay productos) o `UNAVAILABLE` (no se pudo leer; en ese caso no se publica y se conserva el fichero anterior).
