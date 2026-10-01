# Tema 2 · Claude Code y Arquitectura de Proyectos

Segundo tema del curso **[Claude Code .NET](https://www.trainingit.es/producto/claude-code-net/)** de TrainingIT.

Empezamos a trabajar con un proyecto ASP.NET Core real, que usa SQL Server en Docker y se prueba desde Scalar. Claude Code lo analiza sin tocar el código: capas, patrones, flujo de peticiones, acceso a datos y seguridad, y lo resume todo en un ARCHITECTURE.md. Después subimos el proyecto a GitHub y vemos los fundamentos de la línea de comandos de Claude Code.

## Qué contiene este repositorio

| Carpeta o archivo | Descripción |
|---|---|
| `proyecto-base/` | El proyecto .NET con el que trabajarás durante el curso |
| `analisis/prompts.md` | Los seis prompts de solo lectura del vídeo 2.2 |
| `analisis/ARCHITECTURE.md` | El documento que genera Claude al final del vídeo 2.2, para que lo compares con el tuyo |

## Cómo empezar

1. Pulsa el botón verde **Code** de esta página y elige **Download ZIP**.
2. Descomprime el archivo y copia la carpeta `proyecto-base` a `C:\net`, como en el vídeo 2.1.
3. Sigue el vídeo 2.1 para levantar SQL Server con Docker Compose y arrancar la API.

Descarga el ZIP en lugar de clonar el repositorio: en el vídeo 2.3 crearás tu propio repositorio en GitHub y subirás allí el proyecto.

## Vídeos del tema

**2.1 Proyectos .NET con Claude Code.** Puesta en marcha del proyecto: SQL Server con Docker Compose, la API con `dotnet run` y prueba de endpoints desde Scalar.

**2.2 Análisis de proyecto con Claude Code.** Prompts de solo lectura para entender un proyecto desconocido y un ARCHITECTURE.md como memoria reutilizable.

**2.3 Creando el repositorio en GitHub.** Repositorio privado en GitHub y primer push del proyecto con `git init`, commit y remote origin.

**2.4 Navegando en Claude Code CLI.** Comandos esenciales (`/init`, `/statusline`, `/clear`, `/help`, `/usage`) y una status line personalizada.

**2.5 Comandos y archivos en Claude Code.** La `@` añade archivos o carpetas como contexto, y la `!` ejecuta comandos como `dotnet build` directamente.

---

Curso **Claude Code .NET** · [TrainingIT](https://www.trainingit.es/producto/claude-code-net/)
