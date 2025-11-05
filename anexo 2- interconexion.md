```markdown
# ANEXO II - Interconexión Logística Barcelona

## El Hub Integrado

```mermaid
flowchart TB
    A[✈️ AEROPUERTO BCN<br/>Terminal de Carga]
    B[🏭 ZAL PORT<br/>Zona Logística]
    C[🚢 PUERTO BARCELONA<br/>3er mayor del Mediterráneo]
    
    A <-->|Conexión Directa| B
    B <-->|Carretera + Tren| C
    
    style A fill:#ccffff
    style B fill:#ccffcc  
    style C fill:#ffffcc
