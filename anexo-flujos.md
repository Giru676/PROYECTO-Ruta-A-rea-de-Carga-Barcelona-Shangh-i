# ANEXO I - Mapa de Flujos Comerciales

## Situación Actual vs. Propuesta

```mermaid
flowchart TD
    BCN[🏭 Barcelona<br/>Origen de la Carga]
    
    subgraph RUTA_ACTUAL [Ruta Actual - INEFICIENTE]
        BCN -->|Camión 24-48 horas| FRA[🛩️ Frankfurt]
        FRA -->|Vuelo a Asia| PVG[🏙️ Shanghái]
    end
    
    subgraph RUTA_NUEVA [Propuesta - EFICIENTE]
        BCN2[🏭 Barcelona] -->|Vuelo Directo 14h| PVG2[🏙️ Shanghái]
    end

    style RUTA_ACTUAL fill:#ffcccc,stroke:#red
    style RUTA_NUEVA fill:#ccffcc,stroke:#green
