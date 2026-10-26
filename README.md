# Proyecto Web: Migración de Bitácora Excel a HTML5

## 📋 Descripción del Proyecto
Este proyecto forma parte de las actividades de apropiación y transferencia del programa **Tecnología en Análisis y Desarrollo de Software (ADSO)** del SENA (Ficha 3381732). Su objetivo es transformar los libros y pestañas de la plantilla de control de trabajo diario en una aplicación web interactiva, estructurada y accesible.

## 👥 Integrantes del Equipo
* **Carlos Alberto Ordóñez Jaimes** (Líder / Arquitecto - `@carlos25232722`)[cite: 1]
* **Esteban Santiago Jaimes Ayala** (Desarrollador - `@estebanjaimesayala53gold`)
* **Jesús David Quiñones Bernal** (Desarrollador - `@jesusdavidquinones650-art`)

## 🗂️ Estructura de las Tres Vistas Independientes
El sistema web se divide en tres páginas HTML interconectadas mediante un menú de navegación semántico (`<nav>`):
1. **`index.html` (Vista - Información):** Contiene los datos generales del programa de formación, competencia, autor, ficha y periodo actual del sprint[cite: 1].
2. **`vista2.html` (Vista - Reglas y Guía):** Documenta las normas de responsabilidad única, prohibición de adjetivos subjetivos, inmutabilidad de registros y la guía detallada de llenado por columna[cite: 2].
3. **`vista3.html` (Vista - Trazabilidad):** Aloja la tabla principal de seguimiento diario de actividades, timestamps, objetos técnicos, evidencias de ejecución y planes de acción correctiva[cite: 3].

## ♿ Prácticas de Semántica y Accesibilidad (a11y) Aplicadas
* **Estructura Semántica Estricta:** Uso correcto de etiquetas HTML5 como `<header>`, `<nav>`, `<main>`, `<section>`, `<table>`, `<thead>`, `<tbody>`, y `<footer>`.
* **Accesibilidad Web (a11y):** 
  * Atributo `lang="es"` en la etiqueta raíz.
  * Tablas accesibles utilizando etiquetas `<caption>` y el atributo `scope="col"` en los encabezados de las columnas.
  * Enlaces de navegación con control de estado actual.