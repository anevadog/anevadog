# Alexander Nevado García

**Desarrollador backend Java en formación · 8 años en soporte IT · Estudiante de DAM**

📍 Dos Hermanas, Sevilla · Busco prácticas o un puesto junior de backend Java · Abierto a remoto y a reubicación en Suecia

[Web / CV](https://anevadog.github.io) · [LinkedIn](https://www.linkedin.com/in/alexandernevado) · [alex06ng@gmail.com](mailto:alex06ng@gmail.com)

---

## ⭐ Proyecto principal: [cocina](https://github.com/anevadog/cocina)

**API REST para la cocina de un restaurante:** qué hay en el almacén, cuánto cuesta de verdad cada plato y qué hay que producir hoy.

<a href="https://anevadog.github.io/cocina/"><img src="https://raw.githubusercontent.com/anevadog/cocina/main/docs/img/recorrido-receta.png" alt="Recorrido visual de cocina: la versión 1 de una receta conserva su coste por ración y la versión 2 sube tras encarecerse el tomate" width="100%"></a>

- **Stock que cuadra con varios cocineros a la vez:** el descuento es atómico y el almacén nunca queda en negativo.
- **Coste por ración congelado** en cada versión de receta: si sube un proveedor, el histórico no cambia.
- **Seguridad y trazabilidad:** JWT con refresh rotatorio, 4 roles y auditoría append-only protegida por trigger.

`Java 25` `Spring Boot 4` `PostgreSQL` `Flyway` `JWT` `Testcontainers` `Docker` `GitHub Actions` · **247 tests**

**[▶ Ver el recorrido](https://anevadog.github.io/cocina/)** · [Código](https://github.com/anevadog/cocina) · [Revisión técnica](https://github.com/anevadog/cocina/blob/main/docs/revision-tecnica.md) · [Decisiones (ADR)](https://github.com/anevadog/cocina/blob/main/docs/decisiones.md)

## Otros proyectos

| Proyecto | Qué resuelve | Stack | Pruébalo |
|---|---|---|---|
| **[softhard-al](https://github.com/anevadog/softhard-al)** | Taller de reparación con tienda online: presupuestos, fichajes, cobros, facturación simulada y dashboard de ingresos. | Next.js · TypeScript · PostgreSQL · Prisma · **715 tests** | [Demo](https://softhard-al.vercel.app) |
| **[pendla](https://github.com/anevadog/pendla)** | API para seguir mi búsqueda de empleo en Suecia con ofertas reales de JobTech. | Java · Spring Boot · PostgreSQL · JWT · **77 tests** | [Swagger](https://pendla.onrender.com/swagger-ui.html) ¹ |

<sub>¹ Plan gratuito: la primera petición puede tardar alrededor de un minuto en despertar el servidor.</sub>

## Lo que he aprendido construyéndolos

- **Transacciones y concurrencia:** dos compras simultáneas no pueden llevarse la misma última unidad.
- **Dinero sin errores de redondeo:** importes en `BigDecimal` o en céntimos, nunca con `double`.
- **Seguridad básica bien hecha:** contraseñas hasheadas, roles comprobados en el servidor y secretos fuera del repositorio.
- **Tests contra una base de datos real** y CI en GitHub Actions en cada push.
- **Documentar decisiones (ADR):** por qué elegí una opción y qué alternativas descarté.

## Cómo trabajo

Uso agentes de IA (Claude Code, OpenCode) como herramienta, no como piloto automático: defino el alcance por fases, reviso el código, lo pruebo y tomo las decisiones. Cada proyecto documenta sus decisiones y lo que queda pendiente.

## Tecnologías

- **Backend:** Java · Spring Boot · SQL / PostgreSQL · JUnit · Testcontainers
- **También he usado:** TypeScript · Next.js · React
- **Herramientas:** Git · GitHub Actions · Docker
- **Sistemas (8 años):** Windows Server · Active Directory · redes · copias de seguridad · soporte a usuarios

---

### 🇬🇧 In English

Backend Java developer in training with 8 years of IT support experience (Service Desk, then my own repair business). Currently studying Multiplatform Application Development (DAM, Spain). Looking for an internship or a junior backend role; open to remote work and relocation to Sweden. My main project is [cocina](https://github.com/anevadog/cocina), a Spring Boot REST API with 247 tests. English: A2, actively improving.
