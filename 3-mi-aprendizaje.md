# Reflexión y Aprendizajes de la Práctica con Docker Compose

## Antes de la práctica:
Antes de esta práctica, mi conocimiento sobre Docker y Docker Compose era limitado. Sabía que Docker se usa para contenedores, pero no tenía experiencia práctica configurando aplicaciones multi-contenedor con Docker Compose.

## Después de la práctica:
Ahora, después de completar la práctica, he aprendido:

1. **Configuración de `docker-compose.yaml`:**
   - Escribir y entender la estructura del archivo.
   - Definir servicios, redes y volúmenes.
   - Importancia de la indentación y la correcta declaración de cada parámetro.

2. **Gestión de Redes:**
   - Configurar redes de tipo bridge para la comunicación entre contenedores.

3. **Volúmenes y Persistencia de Datos:**
   - Configurar volúmenes para mantener datos persistentes.

4. **Healthchecks:**
   - Implementar pruebas de salud para asegurar que los servicios funcionan correctamente antes de que otros dependientes se inicien.

5. **Dependencias entre Servicios:**
   - Manejar dependencias con `depends_on` y `condition: service_healthy` para controlar el orden de inicio de los servicios.

## Problemas Resueltos:
Enfrenté un problema donde SonarQube no podía conectarse a PostgreSQL debido a un error en la URL de JDBC. Corregí este error revisando la sintaxis de la URL de conexión en el archivo `docker-compose.yaml`.

## Conclusión:
Esta práctica mejoró mi comprensión de Docker y Docker Compose. Los conocimientos adquiridos son aplicables en proyectos de desarrollo de software, configuraciones de entornos de pruebas, integración continua y despliegues automatizados. Esto fortalecerá mi capacidad para contribuir eficazmente en cualquier equipo de tecnología.
