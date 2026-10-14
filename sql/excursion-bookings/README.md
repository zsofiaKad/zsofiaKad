# SQL — Excursion Bookings

*Proyecto de diseño propio · Self-designed project*

---

## *VERSIÓN EN ESPAÑOL*

### Contexto

Ejercicio de SQL de invención propia sobre una empresa online de venta de **excursiones**. El objetivo era practicar SQL de nivel intermedio-avanzado mientras se analizaba el comportamiento de clientes, guías y reservas para mejorar la oferta de excursiones.

### Datos

Base de datos relacional con cinco tablas:

- **Excursions** — catálogo de excursiones (precio, fecha, categoría, disponibilidad, guía).
- **Guides** — guías de las excursiones.
- **Categories** — categorías (aventura, cultural, naturaleza, entre otras).
- **Customers** — clientes.
- **Bookings** — reservas (cliente, excursión y fechas).

### Análisis

Más de treinta consultas organizadas por tabla y por nivel de dificultad, que incluyen:

- Agregaciones y rankings, como la excursión más cara por categoría o el guía con más excursiones.
- Subconsultas y comparaciones contra la media.
- Totales acumulados.
- Consultas avanzadas: reservas por encima de la media, excursiones reservadas por todos los clientes y categorización por rango de precio.

### Resultado

Un conjunto de consultas que responde preguntas de negocio sobre el catálogo, los guías, las categorías y las reservas de la plataforma de excursiones.

### Conclusión

El ejercicio demuestra dominio de SQL (joins, subconsultas, funciones de ventana y agregaciones) aplicado a un caso de negocio realista diseñado desde cero.

**Stack:** SQL

### Archivos

- `Excursion_bookings.sql` — todas las consultas.
- `SQL_questions.md` — enunciado de las preguntas.
- `Proyect_description.md` — descripción del esquema de la base de datos.

---

## *ENGLISH VERSION*

### Context

A self-designed SQL exercise about an online **excursion** sales company. The goal was to practice intermediate-advanced SQL while analyzing customer, guide and booking behaviour to improve the excursion offering.

### Data

A relational database with five tables:

- **Excursions** — excursion catalogue (price, date, category, availability, guide).
- **Guides** — excursion guides.
- **Categories** — categories (adventure, cultural, nature, among others).
- **Customers** — customers.
- **Bookings** — bookings (customer, excursion and dates).

### Analysis

More than thirty queries organized by table and difficulty, including:

- Aggregations and rankings, such as the most expensive excursion per category or the guide with the most excursions.
- Subqueries and comparisons against the average.
- Running totals.
- Advanced queries: bookings above the average, excursions booked by every customer and price-range categorization.

### Result

A query set answering business questions about the catalogue, guides, categories and bookings of the excursion platform.

### Conclusion

The exercise demonstrates SQL skills (joins, subqueries, window functions and aggregations) applied to a realistic business case built from scratch.

**Stack:** SQL

### Files

- `Excursion_bookings.sql` — all queries.
- `SQL_questions.md` — question brief.
- `Proyect_description.md` — database schema description.
