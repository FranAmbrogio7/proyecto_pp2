# ERP Campeones

Sistema de gestión para Campeones: catálogo de productos con variantes, stock, clientes y ventas, con usuarios por rol.

Proyecto integrador de Práctica Profesionalizante II, Tecnicatura Superior en Desarrollo de Software (2026).

> En construcción. Este README se completa a lo largo del proyecto con arquitectura, variables de entorno, ejecución local y tests.

## Equipo

| Integrante | GitHub |
| --- | --- |
| Francisco Ambrogio | [@FranAmbrogio7](https://github.com/FranAmbrogio7) |
| Nicolas Lacroix | [@lacroixdvs](https://github.com/lacroixdvs) |
| Ignacio | [@ignacio-pineiro](https://github.com/ignacio-pineiro) |

## Stack

- Backend: Flask, SQLAlchemy, Flask-Migrate, Flask-JWT-Extended, Marshmallow
- Base de datos: MySQL 8
- Frontend: React, Vite, Tailwind
- Tests: pytest
- Despliegue: Docker Compose, Nginx y HTTPS en VPS

## Forma de trabajo

- `main` está protegida: todo cambio entra por Pull Request con la aprobación de otro integrante.
- Una rama por tarjeta de Trello: `feature/<n>-<descripcion>` o `bugfix/<n>-<descripcion>`.
- Commits con [Conventional Commits](https://www.conventionalcommits.org/es/v1.0.0/): `feat(productos): agrega baja lógica (#12)`.
