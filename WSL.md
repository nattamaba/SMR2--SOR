```mermaid
flowchart TD
    A[Abrir PowerShell o Terminal<br>como administrador]
      --> B[Ejecutar:<br><code>wsl --install</code>]
    B --> C[Esperar a que termine la instalación]
    C --> D{¿Pide reiniciar?}
    D -- Sí --> E[Reiniciar el equipo]
    D -- No --> F[Saltar al paso siguiente]
    E --> G[Abrir Microsoft Store]
    F --> G
    G --> H[Buscar e instalar<br>una distribución Linux (Ubuntu, Debian, etc.)]
    H --> I[Abrir la distro instalada y terminar la configuración]
    %% Opcional: Puedes añadir estilos personalizados si lo deseas
```
