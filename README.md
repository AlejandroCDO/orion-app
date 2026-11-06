# ORION – Aplicación móvil de gestión integral de cine

ORION es una aplicación móvil Full Stack desarrollada como Trabajo de Fin de Grado del Ciclo Formativo de Grado Superior en Desarrollo de Aplicaciones Multiplataforma (DAM).

El proyecto tiene como objetivo centralizar la gestión de un cine en una única plataforma, conectando a los clientes con los administradores mediante una aplicación móvil intuitiva y funcional.

## Repositorios del proyecto

El proyecto está dividido en dos repositorios independientes:

| Componente | Tecnologías | Repositorio |
|---|---|---|
| Frontend | Ionic 8, Angular 20, TypeScript | [orion-frontend](https://github.com/AlejandroCDO/orion-frontend) |
| Backend | NestJS, Node.js, MongoDB | [orion-backend](https://github.com/AlejandroCDO/orion-backend) |

## Funcionalidades principales

### Cliente
- Registro e inicio de sesión con autenticación JWT.
- Consulta y búsqueda de películas en cartelera.
- Visualización de información detallada de las películas.
- Selección de sesiones, tipos de entrada y asientos.
- Gestión de reservas y cancelaciones.
- Gestión de películas favoritas y lista de seguimiento.
- Valoración de películas y publicación de reseñas.
- Consulta y edición del perfil personal.

### Administrador
- Gestión de películas (crear, modificar y eliminar).
- Gestión de sesiones y horarios.
- Consulta y gestión de usuarios registrados.
- Administración de reseñas.
- Acceso protegido mediante código de administrador.

## Tecnologías utilizadas

**Frontend**
- Ionic 8
- Angular 20
- TypeScript
- Capacitor
- Ionicons

**Backend**
- NestJS
- Node.js
- TypeScript
- MongoDB
- Mongoose
- JWT (JSON Web Tokens)
- Passport
- bcryptjs
- class-validator

## Arquitectura

ORION utiliza una arquitectura cliente-servidor basada en una API REST.

El frontend se comunica con el backend para consultar y gestionar los datos de la aplicación. La autenticación y el control de acceso según los roles de usuario se realizan mediante tokens JWT y rutas protegidas.

## Posibles mejoras futuras

- Integración de una pasarela de pago real (Stripe o PayPal).
- Implementación de notificaciones push.
- Sistema de recomendaciones de películas.
- Generación de entradas PDF con códigos QR.
- Panel de estadísticas para administradores.
- Ampliación para gestionar múltiples cines.

## Autor

**Alejandro Company del Olmo**

Ciclo Formativo de Grado Superior en Desarrollo de Aplicaciones Multiplataforma (DAM).

Curso académico 2025-2026.
