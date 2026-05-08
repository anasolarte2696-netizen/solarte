flowchart TD
A[Inicio de preparación de pan] --> B[Llegan pedidos]
B --> C[Preparar bandejas de pan]
C --> D{¿Horno disponible?}
D -->|Sí| E[Hornear pan]
E --> F[Pan listo]
F --> G[Entregar pedidos]
G --> H[Fin]
D -->|No| I[Colocar bandejas en fila de espera]
I --> J{¿Hay espacio en la fila?}
J -->|Sí| K[Esperar turno]
K --> D
J -->|No| L[Detener preparación temporalmente]
L --> M[Esperar espacio disponible]
M --> I
