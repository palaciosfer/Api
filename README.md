# Crear_Usuario
el archivo .env se crea afuera de la carpeta src
los datos que van en el archivo .env ya modifica los que pondrias de tu bd 
# DATABASE_HOST =localhost
# DATABASE_NAME =SocialNetwork
# DATABASE_USER = root
# DATABASE_PASSWORD = RivenR34@
# DATABASE_PORT =3306

flowchart TD
    A[Inicio] --> B[Leer datos del archivo .env]
    B --> C[Conectarse a la base de datos]
    C --> D[Recibir datos del usuario]
    D --> E[Validar datos]
    E --> F{¿Datos válidos?}
    F -- Sí --> G[Insertar usuario en la base de datos]
    F -- No --> H[Mostrar error de validación]
    G --> I[Confirmar creación]
    H --> I
    I --> J[Fin]
