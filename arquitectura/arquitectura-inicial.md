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
