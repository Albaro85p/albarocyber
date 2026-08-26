#  Técnico en Recuperación de Datos y Análisis Forense Digital

##  Descripción del Proyecto
Este repositorio contiene la documentación técnica y el procedimiento operativo aplicado durante el caso práctico de **recuperación de datos y análisis forense** sobre una unidad de almacenamiento dañada. 

El objetivo principal de la intervención fue diagnosticar, preservar la evidencia original y extraer la información crítica solicitada por el cliente, aplicando buenas prácticas del estándar forense para asegurar la integridad de los datos rescatados.

---

## Metodología y Procedimiento Técnico

El proceso de recuperación y análisis se desarrolló en las siguientes fases documentadas:

1. **Diagnóstico Inicial e Triage:**
   * Evaluación de la salud del disco mediante parámetros S.M.A.R.T.
   * Identificación de la naturaleza del fallo (daño lógico / sectores defectuosos).

2. **Adquisición Forense (Preservación de Evidencia):**
   * Creación de una imagen bit a bit (*raw image*) de la unidad afectada para evitar la degradación del hardware original.
   * Generación y verificación de hashes de integridad (`MD5` / `SHA-256`) pre y post clonado.

3. **Análisis y Extracción (*Data Carving*):**
   * Reconstrucción de la estructura de tablas de particiones y sistema de archivos.
   * Talla de archivos basada en firmas (*headers/footers*) para rescatar datos no enlazados.

4. **Validación e Entrega:**
   * Verificación de la integridad operacional de los archivos restaurados.
   * Organización y empaquetado del árbol de directorios para el cliente.

---
