# SysLabs blog
Blog de la comunidad SysLabs. Cualquier aporte de contenido que se desee hacer deberá contar con la autorización de los moderadores del canal de discord. 

[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/M7r658tE)

## Iniciar proyecto
Instala [hugo](https://gohugo.io/installation/).

> [!NOTE]
> Si tiene planeado clonar el proyecto para hacer aportaciones de contenido, es recomendable que previo a ello haga fork al proyecto. [Sobre la contribución](#crear-contenido)

Después de clonar el repositorio, ingresa al directorio del proyecto y clona el tema del blog:

```bash
cd SysLabs && git submodule update --init --recursive
```

Ejecuta el servidor de desarrollo:

```bash
hugo server -D
```

Esto debería encender el servidor web en [http://localhost:1313](http://localhost:1313).

## Crear contenido
Para esta breve guía, lo único que necesitará conocer es el lenguaje markdown, no es requerido saber de HUGO para crear contenido. Puede aprender sobre markdown (aquí.)[https://en.wikipedia.org/wiki/Markdown]

La contribución de contenido, funciona de manera similar a la contribución de código en proyectos open source. Si tiene planeado honrar a nuestra comunidad, haciendola el primer sitio donde haga una aportación y no sabe por dónde empezar, esta lectura puede ser de utilidad: [Contribuir a un proyecto](https://docs.github.com/es/get-started/exploring-projects-on-github/contributing-to-a-project).

### Crear un post
Crear un nuevo post se logra fácilmente ejecutando el siguiente comando:

```bash
hugo new content posts/mi-primer-post.md
```

Esto creará un nuevo archivo `.md` en el directorio `content/posts` con la siguiente estructura:

```markdown
+++
title = "Mi Primer Post"
date = "2026-10-01T22:49:09-06:00"
#dateFormat = "2006-01-02" # This value can be configured for per-post date formatting
author = ""
authorTwitter = "" #do not include @
cover = ""
tags = ["", ""]
keywords = ["", ""]
description = ""
showFullContent = false
readingTime = false
hideComments = false
+++

El contenido de tu blog va **aquí!** :D
```

Dudas adicionales en el canal general de discord.
