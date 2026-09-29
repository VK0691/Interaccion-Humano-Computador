# 🖥️ Interacción Humano-Computador (IHC) - Proyecto de Equipo

Bienvenido al repositorio oficial del equipo para la materia de **Interacción Humano-Computador**.  
Aquí documentamos nuestro proceso de diseño, desarrollo y pruebas de usabilidad para crear experiencias digitales centradas en el usuario.

---
## 🔗 Enlaces del Proyecto

| Recurso | Descripción | Enlace |
|---------|-------------|--------|
| 🎨 **Prototipo antiguo** | Primer acercamiento de diseño en Figma (versión inicial). | [Ver prototipo antiguo](https://www.figma.com/design/29MZTBqWJW2xWDvboivtpg/Sin-t%C3%ADtulo?node-id=0-1&t=5OulkeUW89JfXMRc-1) |
| ✨ **Prototipo nuevo** | Versión final con las decisiones de diseño, Gestalt y guía de estilo aplicadas. | [Ver prototipo nuevo](https://www.figma.com/make/pq9CHFHSQ0c5645wQdZ0lw/Tutor%C3%ADa-F%C3%A1cil-UTA-App?t=wXCHPI8yQtGGOSMW-1) |
| 💻 **Repositorio GitHub** | Código fuente y documentación del proyecto. | [Ver repositorio](https://github.com/VK0691/Interaccion-Humano-Computador) |
## 👥 Equipo de Trabajo

| Rol | Nombre | Responsabilidad |
|-----|--------|-----------------|
| 🚀 **Auditor de accesibilidad** | **Bryan Guatemal** | Visión estratégica y gestión del caos. |
| ⚙️ **Coordinador** | **Carlos Bejarano** | Puente entre la lógica del código y la psicología del usuario. |
| 🎨 **Auditor de usabilidad** | **Karen Molina** | Crea interfaces que son un placer usar (y mirar). |
| 🧠 **QA** | **Tomás Solís** | Cuestiona cada clic y hace que el diseño tenga sentido humano. |

**Responsable del documento:** Bryan Guatemal  
**Asignatura:** Interacción Humano / Computador  
**Docente:** Ing. Jose Ruben Caiza Caizabuano, Mg.  
**Ciclo Académico:** Agosto - Diciembre 2026  
**Nivel y Paralelo:** Quinto - B

---

## 🧩 Objetivo del Proyecto

Diseñar y evaluar una interfaz interactiva que resuelva una necesidad real, aplicando principios de:

- **Usabilidad** (eficiencia, facilidad de aprendizaje, satisfacción).
- **Accesibilidad** (diseño inclusivo para todos los usuarios).
- **Diseño Centrado en el Usuario** (investigación, prototipado y pruebas).

### Objetivo General

Traducir las necesidades identificadas en el caso en decisiones de diseño visibles y consistentes para **Tutoría Fácil UTA**. Para ello se aplican metáforas, affordance, mapeo, manipulación directa, retroalimentación, reducción de la carga cognitiva, leyes Gestalt y una guía mínima de estilo.

### Objetivos Específicos

- Seleccionar metáforas y comportamientos de interacción coherentes con los modelos mentales de los estudiantes (E9).
- Aplicar y justificar al menos tres leyes Gestalt visibles en el prototipo.
- Definir tipografía, colores, componentes y reglas de consistencia para las cuatro pantallas.

---

## 📂 Estructura del Repositorio

```plaintext
/
├── docs/               # Documentación del proyecto (investigación, entrevistas, etc.)
├── prototypes/         # Prototipos (baja/alta fidelidad)
├── tests/              # Resultados de pruebas de usabilidad
├── src/                # Código fuente (si aplica)
└── README.md           # Este archivo
```

---

## 🛠️ Materiales y Recursos

**Equipos y materiales generales:**

- Computador portátil y navegador web.
- Documento del examen y evidencias E1 a E10.
- FigJam, Figma Design y GitHub.

**TAC (Tecnologías para el Aprendizaje y Conocimiento) empleados:**

- ☐ Plataformas educativas
- ☐ Simuladores y laboratorios virtuales
- ☑️ Aplicaciones educativas: FigJam y Figma Design
- ☐ Recursos audiovisuales
- ☐ Gamificación
- ☑️ Inteligencia Artificial: apoyo en la redacción y el formato
- **Otros:** GitHub

---

## 🎨 Decisiones de Diseño

### Metáforas

Se emplean dos metáforas que los estudiantes ya reconocen (E9):

- **Calendario.** Representa las fechas y la disponibilidad del docente. Aprovecha un modelo mental conocido, porque las personas asocian naturalmente un calendario con fechas y planificación.
- **Tarjeta de tutoría.** Agrupa en un solo objeto el docente, la asignatura, la fecha, la hora, la modalidad y el estado. Funciona como una cita en una agenda física: el estudiante la consulta en *Mis tutorías* sin buscarla entre mensajes (E5).

### Affordance

Los horarios disponibles tienen una apariencia claramente seleccionable: borde de color, área táctil de al menos 44 × 44 px y texto explícito.

```
09:00 -- Disponible
```

Los horarios ocupados aparecen en gris, con texto, y no se pueden accionar. De esta forma se evitan los intentos de reservar horarios ya ocupados observados en E3.

```
11:00 -- Ocupado
```

### Mapeo

La relación entre acción y resultado es directa. Cuando el estudiante toca `12:00 -- Disponible`, el mismo elemento cambia a `12:00 -- Seleccionado ✓` y el botón *Continuar* se habilita justo debajo. El resultado se muestra en el mismo elemento sobre el que se actuó, y la acción siguiente aparece en la dirección natural de lectura.

### Manipulación Directa

El estudiante selecciona y modifica el horario actuando directamente sobre el elemento visible, sin escribir ninguna hora. Para corregir, basta con tocar otro horario. En la reprogramación, la acción *Reprogramar* abre el mismo calendario con la cita actual marcada, de modo que se usa el mismo modelo de interacción. Esta decisión responde a E10.

### Retroalimentación

La aplicación informa en todo momento qué está ocurriendo, siempre con texto:

- **Carga:** *Consultando horarios…*, con el botón deshabilitado mientras se espera (E8).
- **Selección:** *Horario seleccionado: jueves 15 de octubre, 12:00*.
- **Confirmación:** *Tutoría CONFIRMADA*, junto con la tarjeta de la cita (E3, E5).
- **Error:** *No pudimos cargar los horarios*, con el botón *Intentar nuevamente* (E8).

### Reducción de la Carga Cognitiva

El proceso se divide en etapas con un indicador de progreso (*Paso 1 de 2*): búsqueda, selección, revisión y confirmación.

- Solo se muestran los horarios del día elegido y como máximo cinco días a la vez. Así se limitan las opciones simultáneas, en línea con la ley de Hick-Hyman y la capacidad de la memoria de trabajo (Miller).
- Se aplica el principio de reconocimiento sobre recuerdo: los datos de la cita se repiten antes y después de confirmar, así que el estudiante no tiene que memorizarlos.

Esta decisión se relaciona con E4 y E5.

### Riesgo Cultural

No se depende exclusivamente de colores, iconos o símbolos aislados. Por ejemplo, en lugar de mostrar solo un símbolo de verificación se presenta:

```
✓ Tutoría CONFIRMADA
```

Cada horario incluye además su etiqueta textual: *Disponible*, *Ocupado* o *Seleccionado*. Las fechas se escriben completas (*jueves 15 de octubre*) para evitar formatos ambiguos. Esto responde a E2 y E9.

---

## 📊 Matriz de Decisiones

| Concepto | Decisión aplicada | Evid. | Pantalla |
|----------|-------------------|-------|----------|
| Metáfora | Calendario para fechas y tarjeta para representar una tutoría. | E9 | P2, P4 |
| Affordance | Horarios disponibles seleccionables; ocupados en gris, con texto y deshabilitados. | E3, E9 | P2 |
| Mapeo | El horario seleccionado cambia de estado en el mismo lugar y *Continuar* se habilita debajo. | E3, E9 | P2 |
| Manipulación directa | Selección y cambio actuando sobre el horario visible, también al reprogramar. | E10 | P2, P4 |
| Retroalimentación | Estados de carga, selección, confirmación y error con texto. | E3, E5, E8 | P2–P4 |
| Carga cognitiva | Pasos progresivos, pocas opciones a la vez y resumen visible. | E4, E5 | P2, P3 |
| Riesgo cultural | Ningún estado depende solo de iconos, símbolos o colores. | E2, E9 | Todas |

---

## 🧠 Aplicación de Leyes Gestalt

### Proximidad
Docente, fecha, hora y modalidad se agrupan dentro de la misma tarjeta, con 8 px de separación interna y 24 px entre bloques distintos. La cercanía permite entender que todos esos datos pertenecen a la misma tutoría (E5).

### Semejanza
Los horarios que comparten estado tienen la misma forma y estilo; los disponibles se distinguen de los ocupados por el estilo y también por el texto (E3, E9). Además se mantiene la consistencia entre botones principales, botones secundarios, tarjetas y mensajes de estado.

### Figura–Fondo
Las tarjetas, los resúmenes y las confirmaciones se destacan sobre el fondo gris mediante contraste, espacio y contenedores blancos. Mientras el sistema carga, una capa oscurece el fondo. Así la atención se dirige a los datos que el estudiante debe verificar.

### Leyes Complementarias
- **Continuidad:** el flujo es vertical (docente → fecha → horario → Continuar).
- **Cierre:** el carrusel de días muestra el último día cortado, lo que invita a desplazarse.

---

## 🎨 Guía de Estilo

**Frame móvil de 390 × 844 px.**

| Elemento | Definición |
|----------|------------|
| Título principal | 24 px, semibold. |
| Subtítulo | 18 px, semibold. |
| Texto de cuerpo | 16 px, regular. |
| Texto auxiliar | 14 px, regular (nunca menor). |
| Acción principal | `#0057B8` con texto blanco. |
| Fondo | `#F7F8FA`; tarjetas en `#FFFFFF`. |
| Texto principal | `#1F2937`. |
| Éxito | `#198754`, siempre acompañado de icono y texto (*CONFIRMADA*). |
| Error | `#DC3545`, siempre acompañado de un mensaje que explica la corrección. |
| Foco | Contorno de 3 px, visible en todos los controles. |
| Componentes | Botón principal (48 px de alto y ancho completo), botón secundario, campo con etiqueta, horario en tres variantes (disponible, ocupado y seleccionado), tarjeta de tutoría y mensaje de estado. |
| Etiquetas fijas | *Ver horarios*, *Mis tutorías*, *Continuar*, *Confirmar tutoría*, *Cambiar horario*, *Reprogramar* y *Volver al inicio*. |
| Consistencia | La acción principal va siempre abajo; *Volver* siempre arriba a la izquierda; se mantienen las mismas jerarquías y respuestas del sistema en las cuatro pantallas. |

### Estándares de Iure que Fundamentan la Guía

- **ISO 9241-11:** orienta la calidad de uso en un contexto especificado mediante la efectividad, la eficiencia y la satisfacción.
- **ISO 9241-210:** orienta el proceso iterativo de diseño centrado en las personas.

Esta guía de estilo concreta ambas orientaciones en reglas consistentes y verificables para el proyecto.

---

## ✅ Resultados Obtenidos

- Se obtuvo una matriz de decisiones que relaciona los principios del parcial con necesidades concretas del caso, cada una con su evidencia y la pantalla donde se verifica.
- Se justificaron tres leyes Gestalt principales (proximidad, semejanza y figura-fondo) y dos complementarias (continuidad y cierre).
- Se definió una guía de estilo mínima que se aplica directamente en Figma y mantiene la consistencia de las cuatro pantallas.

---

## 🤝 Habilidades Blandas Empleadas

- ☐ Liderazgo
- ☑️ Trabajo en equipo
- ☑️ Comunicación asertiva
- ☐ La empatía
- ☑️ Pensamiento crítico
- ☑️ Flexibilidad
- ☐ La resolución de conflictos
- ☑️ Adaptabilidad
- ☑️ Responsabilidad

---

## 💡 Conclusiones

- Las metáforas de calendario y tarjeta aprovechan modelos mentales conocidos por los estudiantes y reducen la necesidad de explicar la interfaz.
- La retroalimentación textual y el mapeo directo disminuyen la ambigüedad al seleccionar y confirmar horarios, que era el principal problema del proceso actual (E3).
- Las leyes Gestalt organizan visualmente los elementos y reducen la carga perceptiva en una pantalla pequeña.
- La guía de estilo convierte criterios generales en reglas visuales concretas y reutilizables.

---

## 📌 Recomendaciones

- Aplicar los mismos componentes en las cuatro pantallas.
- No cambiar la etiqueta de una misma acción a lo largo del flujo.
- Verificar que todo estado con color incluya también texto.
- Comparar el prototipo final con la matriz de decisiones antes de la prueba cruzada.

---

## 📚 Referencias

- Universidad Técnica de Ambato, FISEI, "Examen práctico integrador del primer parcial: Diseño desde cero de un sistema web para reservar tutorías," Interacción Humano Computador, Ambato, Ecuador, 2026.
- International Organization for Standardization, *ISO 9241-11:2018 Ergonomics of human-system interaction — Part 11: Usability: Definitions and concepts*. Ginebra, Suiza: ISO, 2018.
- International Organization for Standardization, *ISO 9241-210:2019 Ergonomics of human-system interaction — Part 210: Human-centred design for interactive systems*. Ginebra, Suiza: ISO, 2019.

---

## 📎 Anexos

- Captura de la guía de estilo y de los componentes en Figma.
- Prototipos de las cuatro pantallas (P1–P4).
- Evidencias E1 a E10 del caso de estudio.
