
## Descripción de Capas

| Capa | Pregunta que responde | Responsabilidades y Componentes |
| --- | --- | --- |
| **Presentación** | ¿Cómo interactúa el usuario? | Interfaz de usuario web y endpoints de entrada de la API. Maneja la interacción con el cliente final, vendedor y administrador. |
| **Lógica de negocio** | ¿Qué hace el sistema? | Procesa las reglas del negocio. Contiene los módulos core: Catálogo, Carrito, Pedidos, Sellers y Usuarios. |
| **Datos** | ¿Dónde se almacena la información? | Persistencia de datos, acceso a la base de datos relacional y gestión de repositorios de información. |

## Módulos del Sistema (Lógica de Negocio)

- **Catálogo:** Gestión de productos, categorías y stock.
- **Carrito:** Administración temporal de ítems para compra.
- **Pedidos:** Procesamiento de órdenes y estados del pedido.
- **Sellers:** Gestión de vendedores y sus catálogos.
- **Usuarios:** Autenticación, perfiles y roles del sistema.
