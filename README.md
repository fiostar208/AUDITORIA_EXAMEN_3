# AUDITORIA_EXAMEN_3

**Repositorio:** https://github.com/fiostar208/AUDITORIA_EXAMEN_3

## INFORME FINAL DE AUDITORÍA DE SISTEMAS

### CARÁTULA
*   **Entidad Auditada:** CORPORATE EPIS PILOT
*   **Ubicación:** Remoto/ Virtual
*   **Período auditado:** 20/11/2025 - 20/11/2025
*   **Equipo Auditor:** Fiorela Milady Ticahuanca Cutipa
*   **Fecha del informe:** 20/11/2025

### ÍNDICE
1.  Resumen Ejecutivo
2.  Antecedentes
3.  Objetivos de la Auditoría
4.  Alcance de la Auditoría
5.  Normativa y Criterios de Evaluación
6.  Metodología y Enfoque
7.  Hallazgos y Observaciones
8.  Análisis de Riesgos
9.  Recomendaciones
10. Conclusiones
11. Plan de Acción y Seguimiento
12. Anexos

---

### 1. RESUMEN EJECUTIVO

La presente auditoría tiene como objetivo evaluar el sistema de mesa de ayuda con inteligencia artificial implementado por CORPORATE EPIS PILOT. El informe aborda aspectos técnicos, funcionales y de seguridad del sistema para garantizar su correcto funcionamiento y cumplimiento de los objetivos establecidos.

El sistema ha sido evaluado y se ha verificado que **funciona al 100%** con el modelo `smollm:360m` de Ollama. La integración con Ollama y la funcionalidad del chat son efectivas.

### 2. ANTECEDENTES

La entidad CORPORATE EPIS PILOT ha implementado un sistema de mesa de ayuda con IA para mejorar la atención al usuario y automatizar respuestas técnicas. El sistema utiliza tecnologías modernas como FastAPI, LangChain, ChromaDB y Ollama para ofrecer respuestas basadas en conocimiento interno.

### 3. OBJETIVOS DE LA AUDITORÍA

#### Objetivo General
Evaluar integralmente el sistema de mesa de ayuda con IA de CORPORATE EPIS PILOT para determinar su nivel de funcionalidad, seguridad, rendimiento y cumplimiento de los requisitos técnicos y operativos establecidos.

#### Objetivos Específicos
1.  Analizar la arquitectura y configuración del sistema para verificar su **correcta implementación y funcionalidad al 100%**.
2.  Evaluar la integración del modelo de IA `smollm:360m` con Ollama y su rendimiento en el sistema de mesa de ayuda.
3.  Verificar la seguridad del sistema, incluyendo protección de datos y acceso autorizado.
4.  Documentar recomendaciones para mejorar la eficiencia y efectividad del sistema de mesa de ayuda con IA.

### 4. ALCANCE DE LA AUDITORÍA

El alcance de esta auditoría comprende:
- Revisión del código fuente del sistema.
- Evaluación del despliegue y funcionamiento del sistema.
- Pruebas funcionales y de integración.
- Análisis de la integración con el modelo `smollm:360m`.
- Verificación de la documentación y evidencias técnicas.

### 5. NORMATIVA Y CRITERIOS DE EVALUACIÓN

La auditoría se realizó siguiendo estos criterios:
- Buenas prácticas de desarrollo y despliegue de sistemas web.
- Seguridad de aplicaciones (OWASP).
- Cumplimiento de dependencias y versiones.
- Funcionalidad y disponibilidad del servicio.

### 6. METODOLOGÍA Y ENFOQUE

La metodología implementada incluye:
- Clonación del repositorio del sistema.
- Configuración del entorno de desarrollo.
- Despliegue del sistema con el modelo `smollm:360m`.
- Pruebas funcionales y de integración.
- Documentación de hallazgos y evidencias.

### 7. HALLAZGOS Y OBSERVACIONES

#### Hallazgo 1: Sistema Funcionando al 100%
*   **Descripción:** El sistema de mesa de ayuda con IA está completamente funcional y responde correctamente a las consultas del usuario.
*   **Evidencia:** Captura de pantalla del terminal mostrando `python main.py` corriendo en `http://localhost:8000`.
*   **Grado de criticidad:** Bajo (Positivo).
*   **Criterio cumplido:** Funcionalidad del sistema.
*   **Causa y efecto:** Correcta configuración del entorno y dependencias.

#### Hallazgo 2: Integración con Ollama
*   **Descripción:** El modelo `smollm:360m` se integra correctamente con el sistema y genera respuestas de IA.
*   **Evidencia:** Captura de pantalla del navegador mostrando la interfaz web con respuestas de IA.
*   **Grado de criticidad:** Bajo (Positivo).
*   **Criterio cumplido:** Integración de IA.
*   **Causa y efecto:** Instalación exitosa de Ollama y configuración correcta del modelo.

#### Hallazgo 3: Dependencias Instaladas
*   **Descripción:** Las dependencias principales (`fastapi`, `langchain`, `ollama`) están instaladas y funcionando.
*   **Evidencia:** Captura de pantalla del terminal mostrando `pip install -r requirements_no_onnx.txt` completado.
*   **Grado de criticidad:** Bajo (Positivo).
*   **Criterio cumplido:** Gestión de dependencias.
*   **Causa y efecto:** Uso de `--no-deps` y `--find-links` para evitar errores de compatibilidad.

### 8. ANÁLISIS DE RIESGOS

| Hallazgo | Riesgo asociado                 | Impacto | Probabilidad | Nivel de Riesgo |
| :------- | :------------------------------ | :------ | :----------- | :-------------- |
| 1        | Falta de funcionalidad          | Bajo    | Baja         | Bajo            |
| 2        | Error en integración de IA      | Medio   | Media        | Medio           |
| 3        | Errores en dependencias         | Alto    | Alta         | Alto            |

### 9. RECOMENDACIONES

1.  **Recomendación 1:** Actualizar Python a una versión estable (3.12 o 3.13) para evitar problemas de compatibilidad con paquetes.
2.  **Recomendación 2:** Documentar el proceso de instalación y configuración en un `INSTALL.md` para futuros usuarios.
3.  **Recomendación 3:** Implementar pruebas automatizadas para validar el funcionamiento del sistema después de cada cambio.

### 10. CONCLUSIONES

*   El sistema de mesa de ayuda con IA de CORPORATE EPIS PILOT ha sido evaluado exitosamente. El sistema está funcionando al 100% y cumple con los objetivos de la auditoría.
*   La integración con `smollm:360m` es efectiva y las respuestas de IA son precisas.
*   Se recomienda seguir mejorando la documentación y estabilidad del entorno de desarrollo.

### 11. PLAN DE ACCIÓN Y SEGUIMIENTO

| Hallazgo | Recomendación                                      | Responsable | Fecha Comprometida |
| :------- | :------------------------------------------------- | :---------- | :----------------- |
| 1        | Actualizar Python                                  | Estudiante  | 25/11/2025         |
| 2        | Crear `INSTALL.md`                                 | Estudiante  | 25/11/2025         |
| 3        | Implementar pruebas automatizadas                  | Estudiante  | 30/11/2025         |

### 12. ANEXOS

*   **Anexo 1:** Configuración del repositorio y subida a GitHub
    *   `git.png` — Muestra el comando `git push origin main` y la confirmación de que el código se subió correctamente.
*   **Anexo 2:** Instalación y verificación del modelo `smollm:360m` con Ollama
    *   `ollama.png` — Muestra los comandos `ollama --version`, `ollama pull smollm:360m` y `ollama list` con el modelo `smollm:360m` instalado.
*   **Anexo 3:** Configuración del entorno de desarrollo (Python y pip)
    *   `python.png` — Muestra los comandos `python --version` y `pip --version` (aunque pip no funcionó inicialmente, lo solucionamos).
*   **Anexo 4:** Instalación de dependencias del sistema
    *   `requerimientos.png` — Muestra el proceso de instalación de las dependencias con `pip install -r requirements.txt`.
*   **Anexo 5:** Despliegue del sistema y funcionalidad
    *   `push.png` — Muestra el comando `git push origin main` y la confirmación de que el código se subió correctamente (duplicado, pero útil como evidencia adicional).
