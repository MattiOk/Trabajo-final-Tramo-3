El proyecto se fundamenta en la idea de facilitar el intercambio de vivencias entre individuos que exploran diferentes destinos. A través de la aplicación web, los usuarios tienen la posibilidad de compartir sus experiencias de viaje mediante publicaciones, permitiendo que otros viajeros conozcan y compartan vivencias similares. La interacción se enriquece con comentarios de usuarios en las publicaciones de otros.

Para iniciar la aplicación, se deben seguir los siguientes pasos en la terminal:

1. Ejecutar `npm i` en ambas carpetas (backend y frontend) para instalar los paquetes necesarios.
2. Posteriormente, ejecutar `npm run dev` en ambas carpetas, asegurándose de que tanto el backend como el frontend estén activos simultáneamente.
3. Es necesario contar con MongoDB instalado para el correcto funcionamiento.

Detalles clave:

- El acceso para visualizar el contenido está abierto a cualquier persona, incluso sin registro.
- Solo los usuarios registrados pueden acceder a funciones de edición y eliminación.
- La capacidad de editar o eliminar un comentario está restringida al creador del comentario, implementando renderizado condicional para garantizar la seguridad y la privacidad.