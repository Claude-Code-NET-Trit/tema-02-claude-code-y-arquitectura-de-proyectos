Prompt 1 — Reconocimiento inicial (mapa del terreno)

```
Este es un proyecto backend en ASP.NET Core que no conozco. No modifiques 
ningún archivo, solo explora y explícame.

Dame primero una vista general: la solución (.sln), qué proyectos la 
componen, cómo se organizan las carpetas principales y qué responsabilidad 
tiene cada proyecto/capa. Al final dime qué patrón arquitectónico crees que 
sigue y por qué.
```

Prompt 2 — El flujo de una petición

```
Ahora explícame el flujo completo de una petición HTTP, de principio a fin: 
desde el endpoint o controller, pasando por servicios y repositorios, hasta 
la base de datos y de vuelta. Usa un ejemplo real que encuentres en el código.
```

Prompt 3 — Configuración y arranque

```
Revisa Program.cs (y Startup.cs si existe). Explícame cómo está configurada 
la inyección de dependencias, el pipeline de middleware, y cómo se registran 
los servicios. Dime también cómo se maneja la configuración (appsettings.json, 
variables de entorno).
```

Prompt 4 — Capa de datos

```
Céntrate en el acceso a datos. Dime qué usa (Entity Framework Core, Dapper, 
etc.), cómo está definido el DbContext y las entidades, cómo se hacen las 
migraciones, y cómo se conecta a la base de datos.
```

Prompt 5 — Seguridad y dependencias externas

```
Explícame cómo maneja la autenticación y autorización, y qué dependencias 
externas tiene el proyecto: bases de datos, colas, cache, APIs de terceros. 
Señala también cualquier configuración de seguridad relevante.
```

Prompt 6 — Documentar lo aprendido

```
Con todo lo que hemos analizado, crea un archivo ARCHITECTURE.md en la raíz 
del proyecto con un resumen de la arquitectura, las capas, el flujo de datos 
y las decisiones de diseño clave. Incluye un diagrama en Mermaid de las capas 
y el flujo de una petición.
```