# Crear_Usuario
el archivo .env se crea afuera de la carpeta src
los datos que van en el archivo .env ya modifica los que pondrias de tu bd 
# DATABASE_HOST =localhost
# DATABASE_NAME =SocialNetwork
# DATABASE_USER = root
# DATABASE_PASSWORD = RivenR34@
# DATABASE_PORT =3306

```mermaid
flowchart TD
    A[Inicio] --> B{¿Es válido?}
    B -- Sí --> C[Procesar datos]
    B -- No --> D[Mostrar error]
    C --> E[Fin]
```
