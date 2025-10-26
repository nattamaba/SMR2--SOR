```mermaid
flowchart TD
    A[Abrir PowerShell o Terminal como administrador] --> B[Ejecutar: wsl --install]
    B --> C[Esperar a que termine la instalación]
    C --> D{¿Pide reiniciar?}
    D -->|Sí| E[Reiniciar el equipo]
    D -->|No| F[Saltar al paso siguiente]
    E --> G[Abrir Microsoft Store]
    F --> G
    G --> H[Buscar e instalar una distribución Linux (Ubuntu, Debian, etc.)]
    H --> I[Abrir la distro instalada y terminar el setup]
```
