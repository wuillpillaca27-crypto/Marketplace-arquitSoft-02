# Arquitectura inicial del sistema

## Diagrama de arquitectura

```mermaid
flowchart TD

%% ===========================
%% ACTORES
%% ===========================
subgraph ACTORES["ACTORES"]
    Cliente["Cliente"]
    Seller["Seller"]
    Admin["Administrador"]
end

%% ===========================
%% PRESENTACIÓN
%% ===========================
subgraph PRESENTACION["PRESENTACIÓN"]
    Web["Aplicación Web -> API REST"]
end

%% ===========================
%% LÓGICA DE NEGOCIO
%% ===========================
subgraph NEGOCIO["LÓGICA DE NEGOCIO"]
    Usuarios["Usuarios"]
    Sellers["Sellers"]
    Catalogo["Catálogo"]
    Carrito["Carrito"]
    Pedidos["Pedidos"]
end

%% ===========================
%% DATOS
%% ===========================
subgraph DATOS["DATOS"]
    BD["Base de datos"]
end

%% ===========================
%% SISTEMAS EXTERNOS
%% ===========================
subgraph EXTERNOS["SISTEMAS EXTERNOS"]
    Pago["Pasarela de pago"]
    ERP["ERP"]
    Envio["Servicio de envío"]
end

%% ===========================
%% FLUJO PRINCIPAL
%% ===========================
ACTORES --> PRESENTACION
PRESENTACION --> NEGOCIO
NEGOCIO --> DATOS

%% Integraciones
DATOS -->|"integraciones"| EXTERNOS

Además, el módulo de **Pedidos** se integra con sistemas externos como la **pasarela de pago** y el **servicio de envío**.
