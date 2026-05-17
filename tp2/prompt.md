# prompt.md

```md
Necesito un archivo `openapi.yaml` utilizando especificación OpenAPI 3.1 para una API de gestión de proyectos y usuarios.

Recursos:

Project {
  id,
  name
}

User {
  id,
  name,
  birthdate?,
  project_id
}

Endpoints requeridos:

GET /projects
POST /projects
GET /projects/{id}/users
POST /projects/{id}/users -> debe contemplar respuestas 201 / 400 / 401
DELETE /projects/{id}/users/{userId}

Requisitos:
- Utilizar OpenAPI 3.1
- Definir schemas reutilizables
- Incluir ejemplos
- Agregar responses de error básicas
- Mantener estructura compatible con Swagger Editor
- Utilizar buenas prácticas de modelado REST
```

---

# README.md

```md
# Segundo Trabajo Práctico
## Introducción a Ingeniería de Software Asistida por IA

### Alumno
Gustavo Julián Rivas

### Descripción
Este proyecto forma parte de la entrega correspondiente al segundo Trabajo Práctico de la materia "Introducción a Ingeniería de Software Asistida por IA".

El objetivo principal de esta actividad es utilizar herramientas de Inteligencia Artificial Generativa para asistir en el diseño y definición de especificaciones técnicas de APIs utilizando el estándar OpenAPI 3.1.

En este caso se desarrolló una especificación YAML para una API REST orientada a la gestión de proyectos y usuarios asociados a dichos proyectos.

### Recursos modelados
- Project
- User

### Funcionalidades implementadas
- Obtener proyectos
- Crear proyectos
- Obtener usuarios de un proyecto
- Crear usuarios asociados a un proyecto
- Eliminar usuarios de un proyecto

### Tecnologías y estándares utilizados
- OpenAPI 3.1
- YAML
- Swagger Editor
- REST API Design

### Objetivos académicos
- Comprender el modelado de APIs REST.
- Utilizar IA como herramienta de asistencia en ingeniería de software.
- Aprender a estructurar especificaciones OpenAPI.
- Generar documentación técnica reutilizable y mantenible.

### Archivos incluidos
- `openapi.yaml`: especificación principal de la API.
- `prompt.md`: prompt utilizado para generar la especificación mediante IA.
- `README.md`: documentación general del trabajo práctico.

### Observaciones
La especificación generada puede ser importada directamente en Swagger Editor para visualizar y validar la API.
```

