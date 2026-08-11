# Sebastián Khazzaka

**Full-Stack Developer** · Java 21 + Spring Boot · Next.js 16 + React 19 · SaaS en producción
[![Portfolio](https://img.shields.io/badge/github-repo-blue?logo=github)](https://sebakhazzaka-dev.vercel.app/#proyectos])
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sebastián_Khazzaka-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/sebastian-khazzaka)
[![Email](https://img.shields.io/badge/Email-contacto-D14836?style=flat&logo=gmail)](mailto:khazzaka2008@hotmail.com)

---

## Proyectos

### 🦷 [consultorio-odontologico](https://github.com/sebakhazzaka2/consultorio-odontologico)
SaaS de gestión para clínica odontológica · **En producción · Cliente activo desde mayo 2026**

`Java 17` `Spring Boot 3` `Angular 19` `PostgreSQL` `Docker` `GitHub Actions` `Hetzner` `Caddy`

- Sistema live en [`neodentalmaster.turnosuy.com`](https://neodentalmaster.turnosuy.com)
- CI/CD con GitHub Actions, deploy en Hetzner con Caddy + SSL/TLS
- Accesibilidad WCAG validada con WAVE
- Deuda técnica documentada en el README: JWT en localStorage → cookie HttpOnly (corregido en FrontPet)

---

### 🐾 [Frontpet](https://github.com/sebakhazzaka2/Frontpet)
SaaS para tienda de mascotas · **En desarrollo activo · Cliente piloto con propuesta comercial firmada · Hito de cobro: 05/09/2026**

`Java 21` `Spring Boot 3` `Next.js 16` `React 19` `TypeScript` `Tailwind CSS 4` `shadcn/ui` `PostgreSQL 16` `Docker` `Coolify` `Cloudflare`

- Arquitectura por feature (`catalog` / `booking` / `identity` / `orders`) en lugar de por capa
- **17 ADRs versionados** en `docs/decisions/` — cada decisión de arquitectura documentada con contexto, alternativas y plan de migración
- **JWT en cookie HttpOnly** desde el primer commit — corrigiendo la deuda identificada en el consultorio
- **JUnit 5 + Testcontainers** para tests de integración
- UUID v7 para entidades públicas, BIGSERIAL para internas
- Rate limiting en login y órdenes
- Logback con JSON output para observabilidad
- Multi-tenant ready: toda tabla del dominio lleva `tenant_id`
- ROADMAP con presupuesto de horas, análisis de slack por sprint y gates de entrega

---

## Stack

**Backend**
`Java 17 / 21` `Spring Boot 3` `Spring Security` `JWT (HttpOnly cookies)` `JPA / Hibernate`
`Maven` `Lombok` `Flyway` `PostgreSQL 16` `MySQL 8` `UUID v7`

**Frontend**
`Angular 19` `Angular Material` `Next.js 16 (App Router)` `React 19` `TypeScript (strict)`
`Tailwind CSS 4` `shadcn/ui` `TanStack Query` `React Hook Form` `Zod` `Framer Motion` `SCSS`

**Testing y calidad**
`JUnit 5` `Testcontainers` `Jest` `ESLint` `Prettier` `Accesibilidad WCAG / WAVE`

**DevOps e infraestructura**
`Docker` `Docker Compose` `GitHub Actions (CI/CD)` `Caddy` `Coolify`
`Hetzner Cloud` `Cloudflare (DNS / CDN / R2)` `Linux` `Bash` `SSL/TLS` `GHCR`

**Proceso**
`Git` `PR-based delivery` `Conventional Commits` `Squash merge`
`ADRs (Architecture Decision Records)` `Agile / Sprints` `GitHub Projects`

---

## Sobre mí

Estudiante de Licenciatura en Sistemas (Uruguay) con dos clientes con contrato, uno en producción.

Lo que me diferencia de la mayoría de los juniors no es el stack — es el proceso:

- **Documento las decisiones, no solo el código.** 17 ADRs en FrontPet. Cada decisión de arquitectura tiene su contexto, sus alternativas y su plan de migración.
- **Ninguna migración aplicada a mano en producción.** Flyway versionado desde el día uno en los dos proyectos.
- **Corrijo lo que documento como deuda.** En el consultorio el JWT quedó en localStorage y lo registré como deuda técnica. En FrontPet arranca en cookie HttpOnly.
- **Estimo, mido y corrijo.** Presupuesté 19 horas para el backend de booking. Me llevó 26,5. Está registrado en el ROADMAP con la razón del error.

Trilingüe (ES · PT · EN) con CPF brasileño.

---

<details>
<summary>📚 Proyectos académicos archivados</summary>

Repositorios de cursada, archivados. Incluidos por transparencia, no por relevancia profesional.

- `Algoritmos-y-Estructuras-de-Datos` — Java, estructuras clásicas
- `Programacion-Orientada-a-Objetos` — POO en Java
- `Base-de-Datos` — SQL, modelado relacional
- `Desarrollo-Web` — HTML, CSS, JavaScript vanilla
- `Sistemas-Operativos` — C, procesos y memoria
- `Arquitectura-de-Computadoras` — Assembly

</details>
