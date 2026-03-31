# Teórica 4 (DAM2) - 10/2/2026

Clase virtual.

## MATERIAL DE LECTURA PRUEBA EVALUADA

* MMS_1: [MMS-FINAL-1-16](MMS-FINAL-1-16.pdf)
* MMs_2: [MMS-FINAL-17-58](MMS-FINAL-17-58.pdf)

---

## **Tema: “MMS” METODOLOGÍA PARA EL DISEÑO Y DESARROLLO DE APLICACIONES MÓVILES (MMS-FINAL-1-16)**
### **Capítulo 1: Introducción a MMS**
#### **Introducción y Necesidades del Software Móvil**
* **MMS (Modelo Mobile Sprint):** Es una metodología híbrida creada específicamente para el desarrollo de aplicaciones móviles con un enfoque ágil.
* **Origen:** Surge para cubrir necesidades primordiales del desarrollo móvil que las metodologías tradicionales o web no abordan.
* **Desafío de Calidad:** La calidad en móviles depende estrechamente del hardware del terminal (pantallas pequeñas, diversos procesadores).
* **Consumo de Recursos:** Factores clave para la valoración del usuario incluyen el consumo de energía, uso de datos y almacenamiento.
* **Optimización:** Se deben controlar procesos en segundo plano para optimizar el procesamiento y el acceso a internet.

#### **Objetivos y Características de MMS**
* **Modelo de Éxito:** Fortalecer el uso de **Sprints** como núcleo del desarrollo.
* **Buenas Prácticas:** Integrar características inherentes de dispositivos móviles en el ciclo de vida.
* **Usuario Final:** Integrar opiniones del usuario para mejorar la usabilidad mediante prototipos.
* **Modulariad:** Permite el desarrollo mediante módulos casi independientes, facilitando la escalabilidad.
* **Agilidad:** Enfoque basado en sprints que permite la obtención temprana de resultados funcionales.

#### **Actores y Arquitectura**
* **Fase Inicial:** En la primera fase intervienen únicamente el **Gerente de Proyecto** y el **Cliente**.
* **Responsabilidad:** El gerente gestiona recursos (humanos, tecnológicos, materiales) para satisfacer al cliente.
* **Involucramiento del Cliente:** El cliente define el alcance y aprueba entregables en diseño y planificación.
* **Equipo de Desarrollo:** Mantiene reuniones constantes (DSM) con el director para seguimiento técnico.

#### **Ciclo de Vida del Modelo**
* **Fases del Ciclo:** Consta de 5 fases principales: Planificación, Diseño, Ejecución, Pruebas y Lanzamiento.
* **Duración de Sprints:** Los ciclos cortos suelen durar de **2 a 4 semanas**.
* **Daily Sprint Meeting (DSM):** Reuniones diarias para exponer dificultades y sugerencias.
* **Final Sprint Meeting (FMS):** Reunión al terminar el sprint para discutir cambios antes de iniciar el siguiente.
* **Entregables:** Cada sprint debe generar un producto funcional y cambios registrados para mejora continua.

---

## **Tema: MMS-FINAL-17-58**
>Continuación del tema anterior

### **Capítulo 2: Fase de Planificación**
#### **Herramientas y Gestión**
* **Objetivo:** Estructurar procesos para asegurar una aplicación de calidad mediante gestión eficiente de recursos.
* **Análisis FODA:** Evalúa factores internos (Fortalezas/Debilidades) y externos (Oportunidades/Amenazas) de la empresa.
* **Factibilidad Operativa:** Evalúa si el recurso humano está capacitado para el proyecto asignado.
* **Factibilidad Técnica:** Analiza si la infraestructura de hardware y software es suficiente para el desarrollo.
* **Factibilidad Económica:** Identifica si los beneficios del software superan los costos de instalación y desarrollo.
* **Gestión de Stakeholders:** Define roles (Gerente, Analista, Equipo) y niveles de acceso a la información.
* **Acta de Constitución:** Documento que sintetiza la justificación, presupuesto inicial y aprobaciones del proyecto.

#### **Gestión del Alcance y Requerimientos**
* **Requerimientos Funcionales (RF):** Servicios o funciones que el software proveerá al usuario (Convención: RF-01).
* **Requerimientos No Funcionales (RNF):** Características generales, restricciones o atributos de calidad (éticos, legales, técnicos).
* **Historias de Usuario:** Cartillas con pasos entendibles que detallan qué y cómo se realizará una funcionalidad.
* **Sprint Backlog:** Planificación de requerimientos priorizados para una iteración específica.
* **EDT (Estructura de Desglose de Trabajo):** Jerarquía: Proyecto -> Fase -> Sprint -> Actividad.

#### **Tiempo, Costos y Calidad**
* **Gestión del Tiempo:** Incluye la priorización de sprints y la definición de **holgura** según la complejidad.
* **Estimación de Costos:** Se pueden usar modelos basados en líneas de código (SLOCS) como COCOMO o modelos no SLOCS.
* **Gestión de Cambios:** Las solicitudes de cambio deben ser evaluadas técnicamente por el gerente.
* **Estándar de Calidad:** MMS implementa la norma **ISO/IEC 25010** por su ajuste al contexto móvil.
* **Métricas Móviles:** Considera interfaz amigable, multiplataforma (iOS/Android) y seguridad de datos.

### **Capítulo 3: Fase de Diseño**
#### **Arquitectura y Modularidad**
* **Objetivo de Diseño:** Transformar requisitos en un modelo estructurado que defina la arquitectura del sistema.
* **Perspectivas de Análisis:** Considera flujo de datos, control de acciones, roles y procesos internos/externos.
* **Modelado de Datos:** Inicia con el Modelo Entidad-Relación (MER) y evoluciona al Modelo Relacional (MR).
* **Diccionario de Datos:** Describe campos, tipos de datos, tamaños, restricciones y relaciones de la base de datos.
* **DCU (Diseño Centrado en el Usuario):** Basado en las preguntas ¿Qué?, ¿Cómo? y ¿Cuándo? para validar usabilidad.
* **Pruebas de Usuario:** Se recomienda realizar 3 pruebas con 5 participantes cada una para mejorar iterativamente.
* **Diseño Modular:** Estructurado en módulos: Autenticación, Gestión de Datos, Coordinador, Usuarios, Contención y Servicios.
* **Módulo Coordinador:** Encargado del prototipado de la interfaz y la interacción satisfactoria del cliente.
* **Módulo de Servicios:** Gestiona funcionalidades de aplicaciones externas o APIs de terceros.
