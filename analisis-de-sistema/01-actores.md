# Actores del Sistema

| Actor | ¿Qué necesita realizar? |
| --- | --- |
| **Cliente** | Buscar productos, consultar información, agregar productos al carrito, realizar pedidos, efectuar el pago y consultar sus pedidos. |
| **Seller** | Ofrecer productos, Registrar productos, actualizar productos, consultar sus productos y gestionar la información relacionada con sus ventas. |
| **Administrador** | Administrar la plataforma. |
| **Pasarela de pago** | Procesar pagos. |
| **Servicio de envío** | Gestionar información de entrega. |
| **Servicio de Facturación** | Generar comprobantes de pago. |
| **ERP** | Proporcionar información de productos y stock. |

## Detalle de Actores Principales

### 1. Cliente
- **Rol:** Usuario final comprador.
- **Acciones clave:** Búsqueda en catálogo, gestión de carrito de compras, seguimiento de estados de pedido.

### 2. Seller (Vendedor)
- **Rol:** Comerciante o tienda asociada.
- **Acciones clave:** Publicación de catálogo, actualización de stock, gestión de inventario y reporte de ventas.

## Integraciones y Sistemas Externos

- **Pasarela de Pago:** Integración vía API REST para validación de tarjetas y transacciones en línea.
- **Servicio de Envío:** Integración con proveedores logísticos para cotización y seguimiento de rastreo.
- **ERP:** Conexión con sistemas de gestión empresarial para sincronización de inventario global.
