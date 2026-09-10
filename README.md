# 🖥️ Interacción Humano-Computador (IHC) - Proyecto de Equipo

Bienvenido al repositorio oficial del equipo para la materia de **Interacción Humano-Computador**.  
Aquí documentaremos nuestro proceso de diseño, desarrollo y pruebas de usabilidad para crear experiencias digitales centradas en el usuario.

---

## 👥 Equipo de Trabajo

| Rol | Nombre | Superpoder |
|-----|--------|------------|
| 🚀 **Auditor de accesibilidad** | **Bryan Guatemal** | Visión estratégica y gestión del caos. |
| ⚙️ **Coordinador** | **Carlos Bejarano** | Puente entre la lógica del código y la psicología del usuario. |
| 🎨 **Auditor de usabilidad** | **Karen Molina** | Crea interfaces que son un placer usar (y mirar). |
| 🧠 **QA** | **Tomás Solís** | Cuestiona cada clic y hace que el diseño tenga sentido humano. |

---

## 🧩 Objetivo del Proyecto

Diseñar y evaluar una interfaz interactiva que resuelva una necesidad real, aplicando principios de:

- **Usabilidad** (eficiencia, facilidad de aprendizaje, satisfacción).
- **Accesibilidad** (diseño inclusivo para todos los usuarios).
- **Diseño Centrado en el Usuario** (investigación, prototipado y pruebas).
# 🖥️ Interacción Humano-Computador (IHC) - Proyecto de Equipo

Bienvenido al repositorio oficial del equipo para la materia de **Interacción Humano-Computador**.  
Aquí documentaremos nuestro proceso de diseño, desarrollo y pruebas de usabilidad para crear experiencias digitales centradas en el usuario.

---


## 🧩 Objetivo del Proyecto

Diseñar y evaluar una interfaz interactiva que resuelva una necesidad real, aplicando principios de:

- **Usabilidad** (eficiencia, facilidad de aprendizaje, satisfacción).
- **Accesibilidad** (diseño inclusivo para todos los usuarios).
- **Diseño Centrado en el Usuario** (investigación, prototipado y pruebas).

---

## 📂 Estructura del Repositorio

/
├── docs/               # Documentación del proyecto (investigación, entrevistas, etc.)
├── prototypes/         # Prototipos (baja/alta fidelidad)
├── tests/              # Resultados de pruebas de usabilidad
├── src/                # Código fuente (si aplica)
└── README.md           # Este archivo


## 📋 Artefactos Generados en la Prueba Práctica - Unidad 1

A continuación se detallan los artefactos desarrollados durante la prueba práctica, con la asignación de responsabilidades por integrante del equipo según su rol.

---

### 1. 🔍 Flujo AS-IS (Situación Actual)

**Descripción:**  
Documentación del flujo de trabajo actual del sistema de gestión de GABO'S Readaptación y Movimiento, identificando las tareas críticas y los problemas existentes en la interacción usuario-sistema.

**Tareas analizadas:**
- T1: Agendar una cita para un paciente
- T2: Consultar el historial clínico del paciente
- T3: Registrar el progreso de una sesión de terapia

**Responsable:** 🚀 **Bryan Guatemal** (Auditor de accesibilidad)

---

### 2. 👤 Usuarios y Necesidades

**Descripción:**  
Identificación y definición de los principales usuarios objetivo del sistema, considerando sus características, necesidades y contexto de uso.

**Perfiles definidos:**
| Usuario | Rol | Necesidad principal |
|---------|-----|---------------------|
| Fisioterapeuta | Profesional de la salud | Gestionar citas, historiales y registrar progreso de pacientes |
| Personal Administrativo | Soporte operativo | Apoyar en la logística de citas y organización |
| Paciente | Usuario final | Agendar citas y dar seguimiento a su tratamiento |

**Responsable:** 🚀 **Bryan Guatemal** (Auditor de accesibilidad)

---

### 3. 📊 Comparación de Mecanismos (Matriz de Mapeo)

**Descripción:**  
Matriz que relaciona los elementos del mundo real con sus equivalentes digitales, incluyendo etiquetas, comportamientos y riesgos identificados.

| Elemento real | Elemento digital | Etiqueta/Ícono | Comportamiento | Riesgo |
|---------------|------------------|----------------|----------------|--------|
| Agenda Física | Grid de horarios | "Reservar", "Paciente" | Al hacer clic, abre modal de registro | Mostrar horarios confusos |
| Expediente Físico | Página de detalle | "Historial", "Diagnóstico" | Muestra info organizada en pestañas | No tener etiquetas claras |
| Bloc de Notas | Campo de texto | "Guardado a las..." | Se guarda automáticamente al escribir | Perder datos si se recarga la página |

**Responsable:** ⚙️ **Carlos Bejarano** (Coordinador)

---

### 4. 📈 Indicadores y Métricas de Evaluación

**Descripción:**  
Definición de indicadores y métricas para medir la efectividad, eficiencia y satisfacción de los fisioterapeutas durante la realización de las tareas.

**Métricas definidas:**
| Indicador | Métrica | Tarea asociada |
|-----------|---------|----------------|
| Efectividad | Tasa de éxito en la tarea | T1, T2, T3 |
| Eficiencia | Tiempo de ejecución | T1, T2, T3 |
| Satisfacción | Comentarios y percepción del usuario | T1, T2, T3 |

**Responsable:** 🧠 **Tomás Solís** (Relator)

---

### 5. 🎭 Metáforas de Interfaz

**Descripción:**  
Definición de metáforas visuales y conceptuales para cada tarea, basadas en el modelo mental de los usuarios (fisioterapeutas).

| Tarea | Metáfora Propuesta | Justificación |
|-------|-------------------|---------------|
| T1: Agendar cita | **Agenda Física de Consultorio** | Relaciona la agenda digital con el libro físico de citas que usa el médico |
| T2: Consultar historial | **Expediente Físico del Paciente** | Simula la carpeta física que el doctor saca del archivador |
| T3: Registrar notas | **Bloc de Notas Clínicas con Autoguardado** | El médico escribe sus observaciones en un papel que se archiva automáticamente |

**Responsable:** 🎨 **Karen Molina** (Auditor de usabilidad)

---

### 6. 🖌️ Prototipo (Bocetos y Vectorizado en Figma)

**Descripción:**  
Diseño de interfaces mediante bocetos en papel y vectorización en Figma, incluyendo análisis de microinteracciones y affordances.

**Entregables:**
- Bocetos en papel para las 3 tareas
- Vectorizados en Figma (vistas de agenda, expediente y bloc de notas)
- Análisis de affordances (indicadores visuales de interacción)

**Responsables:** 🎨 **Karen Molina** (Auditor de usabilidad) + ⚙️ **Carlos Bejarano** (Vectorizado técnico)

---

### 7. 📝 Protocolo de Validación (Prueba con Usuarios)

**Descripción:**  
Registro de pruebas de usabilidad realizadas con usuarios reales (fisioterapeutas y administrativos), documentando tiempos, errores y comentarios.

| Participante | Tarea | Éxito | Tiempo | Errores | Comentario |
|--------------|-------|-------|--------|---------|------------|
| P1 (Fisioterapeuta) | Agendar cita | Sí | 40 seg | 0 | "Los bloques están claros" |
| P2 (Fisioterapeuta) | Consultar historial | Sí | 1 min | 1 | "Me gusta que esté en pestañas" |
| P3 (Administrativo) | Registrar notas | Sí | 25 seg | 0 | "El autoguardado me da tranquilidad" |

**Responsable:** 🧠 **Tomás Solís** (Relator) + 🚀 **Bryan Guatemal** (Coordinación)

---

### 8. 📋 Matriz de Evidencia (Problemas de Usabilidad)

**Descripción:**  
Documentación de los problemas de usabilidad identificados en el sistema actual, con priorización según su impacto.

| Pantalla/Tarea | Usuario | Evidencia | Efecto | Prioridad |
|----------------|---------|-----------|--------|-----------|
| Agendar cita | Fisioterapeuta | No hay feedback de confirmación | Incertidumbre si la cita fue registrada | **Alta** |
| Historial | Fisioterapeuta | Archivos desordenados en Drive | Pérdida de tiempo buscando datos | Media |
| Notas | Fisioterapeuta | Falta autoguardado | Pérdida de datos clínicos críticos | **Alta** |

**Responsable:** 🧠 **Tomás Solís** (Relator)
