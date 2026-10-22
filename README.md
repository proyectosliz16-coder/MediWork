# Mediwork

**Sistema integral de gestión médica | Desarrollo Full-Stack**

Mediwork es una plataforma web orientada a la gestión y digitalización de procesos médicos y administrativos. El sistema integra distintos módulos para centralizar operaciones, facilitar el manejo de información y optimizar los flujos de trabajo de una organización del sector salud.

El proyecto fue desarrollado durante mi experiencia profesional en **Laia Technologies**, donde participé como líder del proyecto y desarrolladora, trabajando en diferentes capas de la aplicación.

> **Estado del proyecto:** Código fuente disponible para consulta. La ejecución completa requiere configurar credenciales, variables de entorno y servicios externos que no forman parte de este repositorio.

## Funcionalidades principales

Entre los módulos y funcionalidades presentes en el código se encuentran:

- **Autenticación y usuarios:** acceso al sistema, gestión de usuarios y controles según roles.
- **Gestión de pacientes:** consulta y administración de información de pacientes.
- **Agenda médica:** herramientas para la gestión y seguimiento de citas.
- **Expedientes médicos:** organización de información y documentación relacionada con pacientes.
- **Recetas y exámenes médicos:** funcionalidades para gestionar información clínica.
- **Encuestas y formularios:** creación, configuración y captura de respuestas.
- **Empresas y portales:** funcionalidades para la administración de empresas y sus usuarios.
- **Inventario y punto de venta:** administración de productos, movimientos y operaciones comerciales.
- **Reportes:** herramientas para consultar y organizar información operativa.
- **Integraciones externas:** funcionalidades que dependen de servicios y credenciales configurados por entorno.

*La disponibilidad de cada funcionalidad depende de la configuración y de los servicios externos necesarios para ejecutarla.*

## Tecnologías

| Área | Tecnologías |
|---|---|
| Frontend | React, TypeScript, Vite |
| Backend | Node.js, Express, TypeScript |
| Base de datos | PostgreSQL |
| ORM y acceso a datos | Prisma |
| Infraestructura | Docker, Nginx |
| Desarrollo de interfaces | CSS y Tailwind CSS |

## Arquitectura general

Mediwork utiliza una arquitectura cliente-servidor que separa la interfaz de usuario, la lógica de negocio y la persistencia de datos.

```text
Mediwork
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── stores/
│   └── package.json
│
├── backend/
│   ├── src/
│   │   ├── middleware/
│   │   ├── routes/
│   │   ├── services/
│   │   └── scripts/
│   ├── prisma/
│   └── package.json
│
├── docker-compose.yml
├── Dockerfile.nginx
└── README.md
```

El frontend se comunica con el backend mediante servicios y rutas de API. El backend centraliza la lógica de negocio y utiliza Prisma para interactuar con PostgreSQL.

## Mi contribución

Durante el desarrollo de Mediwork participé en el liderazgo y la construcción técnica del sistema, trabajando en diferentes componentes de la solución:

- Desarrollo de interfaces y componentes del frontend.
- Implementación de funcionalidades y endpoints del backend.
- Diseño e integración de modelos de datos con PostgreSQL y Prisma.
- Desarrollo de funcionalidades de autenticación y gestión de usuarios.
- Implementación e integración de módulos administrativos y médicos.
- Integración de servicios externos y configuración de funcionalidades dependientes del entorno.
- Organización y evolución de la arquitectura de la aplicación.

Mi participación abarcó tanto el desarrollo de funcionalidades como la integración de los distintos componentes necesarios para construir una solución web integral.

## Estructura del repositorio

| Directorio o archivo | Descripción |
|---|---|
| `frontend/` | Aplicación web y componentes de interfaz. |
| `backend/` | API, lógica de negocio y servicios del sistema. |
| `backend/prisma/` | Esquema y recursos relacionados con la base de datos. |
| `docker-compose.yml` | Configuración de servicios para el entorno de desarrollo. |
| `docker-compose.prod.yml` | Configuración orientada al despliegue. |
| `nginx.conf` | Configuración de Nginx. |

## Configuración y ejecución

El proyecto requiere un entorno de desarrollo compatible con Node.js, PostgreSQL y las dependencias definidas por cada aplicación.

Para preparar un entorno local:

1. Clonar el repositorio.
2. Instalar las dependencias del frontend y del backend.
3. Configurar las variables de entorno a partir de los archivos `.env.example`.
4. Configurar una instancia de PostgreSQL y los servicios externos necesarios.
5. Aplicar las migraciones de base de datos que correspondan al esquema del proyecto.
6. Ejecutar el frontend y el backend siguiendo sus configuraciones respectivas.

**Nota:** Las instrucciones anteriores son una guía general. Los comandos concretos y las variables necesarias deben verificarse en los archivos de configuración del repositorio. No se incluyen credenciales de producción.

## Información adicional

Este repositorio se presenta como parte de mi portafolio profesional para mostrar experiencia en desarrollo web full-stack, integración de sistemas, diseño de bases de datos y construcción de aplicaciones modulares.

Algunas funcionalidades pueden requerir servicios externos, variables de entorno y credenciales que no están disponibles en este repositorio. Por ello, no se garantiza que la aplicación pueda ejecutarse completamente con una configuración local básica.

---

**Mediwork — Desarrollo web full-stack y gestión integral de procesos médicos.**
