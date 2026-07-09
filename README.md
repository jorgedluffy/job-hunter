# Job Hunter — Monitor de ofertas tech

> 🚧 **En construcción** — este proyecto está actualmente en desarrollo. La descripción de abajo refleja el objetivo final de la aplicación, no su estado actual.

Aplicación Java que rastrea ofertas de empleo de desarrollador en Infojobs de forma automática, filtra las más relevantes y envía un informe diario por email en formato CSV.

Construida como proyecto personal durante mi búsqueda de primer empleo como desarrollador — literalmente una herramienta para mi propio problema.

---

## ¿Qué hace?

1. Se ejecuta automáticamente cada 24 horas
2. Extrae ofertas de desarrollo de Infojobs
3. Filtra por palabras clave (junior, Angular, React, Java, Node.js...)
4. Elimina duplicados respecto al día anterior
5. Genera un CSV con las ofertas nuevas
6. Lo envía por email automáticamente

---

## Stack inicial

| Tecnología              | Para qué                             |
| ----------------------- | ------------------------------------ |
| Java 17 + Spring Boot 3 | Base de la aplicación                |
| Jsoup                   | Extracción de datos de Infojobs      |
| Spring Scheduler        | Ejecución automática diaria          |
| JavaMailSender          | Envío del informe por email          |
| Docker Compose          | Despliegue local con un solo comando |
| JUnit + Mockito         | Tests unitarios                      |

\*\*Este stack podría variar durante el desarrollo
