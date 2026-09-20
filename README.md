# Frutero v2.3 — Precio sugerido + calculadora

Esta versión conserva las correcciones anteriores y recupera la función principal de precio sugerido.

## Compra
Al registrar una compra se ingresan:
- Producto.
- Kilos comprados.
- Costo total del bulto/caja.
- Porcentaje de ganancia deseado.

La app calcula en tiempo real:
- Costo por kilo = costo total / kilos.
- Precio sugerido = costo por kilo × (1 + porcentaje / 100).

Ejemplo:
- Papa: 30 kg por $130.
- Costo por kilo: $130 / 30 = $4.33.
- Con 30% de ganancia: $4.33 × 1.30 = $5.63 por kg.

El porcentaje puede cambiarse a 20%, 30%, 40% o cualquier otro valor y el precio sugerido se actualiza al instante.

## Calculadora
Incluye una calculadora dentro del menú lateral de la app.

También conserva:
- Compra, Venta, Gasto y Merma.
- Iconos automáticos por producto.
- Inventario y precio sugerido.
- Reportes.
- Modo oscuro.
- Respaldo y restauración.
- Datos existentes en localStorage.
