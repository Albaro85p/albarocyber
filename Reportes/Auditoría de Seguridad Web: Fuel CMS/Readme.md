# Auditoría de Seguridad Web - FUEL CMS Sistema de Gestión de Contenidos.

Este repositorio contiene el reporte ejecutivo y técnico de la auditoría realizada sobre...

##  Descarga del Informe Completo
 [**Descargar el Reporte Ejecutivo y Técnico en PDF](./Informe_Pentest_v1.pdf)**

---

##  Resumen Ejecutivo (Informe sin tecnicismo)
* **Alcance:** Aplicación Web de Gestión Documental.
* **Nivel de Riesgo Global:** ALTO
* **Hallazgos Principales:** Se identificaron vulnerabilidades que comprometen la confidencialidad de los datos personales, constituyendo un incumplimiento de la normativa de protección de datos (GDPR/LOPD). Esta situación expone a la organización a sanciones económicas cuantiosas y a un severo daño reputacional.

### Matriz de Riesgos
| Severidad | Cantidad |
| Categoría | Total |
| :--- | :--- |
| 🔴 Crítica | 1 |
| 🟠 Alta | 2 |
| 🟡 Media | 1 |

---

##  Hallazgos Destacados (Para Perfil Técnico)
- **Vulnerabilidad 1:** SQL Injection en el módulo de login (CVSS 9.8)
- **Vulnerabilidad 2:** Insecure Direct Object References (IDOR) en la descarga de contratos (CVSS 7.5)

*(Consulte la sección 4 del PDF para ver los Proof of Concept y código de remediación).*
