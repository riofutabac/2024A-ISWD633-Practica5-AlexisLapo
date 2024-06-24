## Reflexión sobre la Práctica con Docker Compose

### Conocimientos Previos
Antes de esta práctica, tenía un entendimiento básico de Docker, sin experiencia en la configuración de aplicaciones multi-contenedor con Docker Compose.

### Aprendizajes Clave
- **Configuración de `docker-compose.yaml`:** Aprendí a configurar y entender este archivo, definiendo servicios, redes y volúmenes.
- **Gestión de Redes:** Comprendí la importancia de las redes de tipo bridge para la comunicación entre contenedores.
- **Persistencia de Datos:** Vi cómo configurar volúmenes para mantener los datos seguros entre reinicios de contenedores.
- **Healthchecks:** Implementé pruebas de salud para asegurar el funcionamiento correcto de los servicios antes de iniciar otros dependientes.
- **Dependencias entre Servicios:** Manejé dependencias con `depends_on` para controlar el orden de inicio, crucial para la correcta inicialización de los servicios.

### Problemas Resueltos
Me enfrenté a un problema de conexión entre SonarQube y PostgreSQL por un error en la URL de JDBC. Corregir esto me enseñó a verificar cuidadosamente las configuraciones y la sintaxis correcta.

### Conclusión
La práctica mejoró significativamente mi comprensión y habilidad para usar Docker y Docker Compose en entornos de desarrollo y producción, preparándome mejor para contribuciones futuras en tecnología.
