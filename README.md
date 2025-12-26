# 🗺️ Metamapa — Mapa de alertas y hechos

Este proyecto es una **aplicación web en Java** enfocada en la **gestión, búsqueda y visualización de hechos (eventos) geolocalizados** con estadísticas y filtros avanzados. Está implementada con **arquitectura MVC** y permite experimentar con patrones de diseño y lógica de negocio compleja.

---

## 📌 ¿Qué es Metamapa?

Metamapa es una aplicación web que:

- Permite **cargar y consultar hechos** desde fuentes de datos en formato CSV.
- Ofrece **búsqueda avanzada** de hechos por criterios como texto libre, ubicación y rangos de fecha.
- Genera **estadísticas dinámicas** (cantidad por categoría, hora pico, máximos por provincia, etc.).
- Tiene una interfaz web con plantillas **Handlebars** para mostrar resultados y dashboards.
- Incluye lógica de negocio modular y reutilizable para la manipulación de datos.

---

## 🧱 Tecnologías usadas

- **Java 17 / OpenJDK** – Lenguaje principal  
- **Javalin** – Framework web liviano para Servlets  
- **Handlebars** – Motor de plantillas HTML  
- **Maven** – Gestión de dependencias y build  
- **CSS personalizado** – Para estilos visuales  
- **Dockerfile** – Preparado para contenerizar  
- **JUnit** – Testing de unidades y validación de lógica

---

## 📂 Estructura del proyecto

```text
src/
├─ main/java/…/controllers       # Controladores HTTP
├─ main/java/…/model             # Entidades y lógica de negocio
├─ main/java/…/repositories       # Clases para persistencia CSV/mock
├─ main/resources/templates      # Vistas Handlebars
├─ main/resources/assets         # Estilos CSS
src/test/java/…                  # Tests automatizados

## UI Web

## Demo video


## Deploy
- ** Render https://tpa-entrega-final.onrender.com/home
