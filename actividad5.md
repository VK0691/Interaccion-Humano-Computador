# Actividad 5: Aplicación de Metáforas en la Interfaz de Usuario

## Integrante: Guatemal Avilez Bryan Stalin

### 1. Análisis y Definición del Modelo Mental

Se analizaron las formas en que los usuarios entienden naturalmente el proceso de gestión de citas. Se utilizaron conceptos conocidos del contexto de un consultorio, como una agenda, una reserva y un calendario.

**Tarea T1: Consultar disponibilidad de horarios**
- **Prompt a IA:** ¿Cómo esperan los pacientes y el personal de un centro de rehabilitación consultar los horarios disponibles? ¿Qué conceptos familiares utilizan cuando buscan una cita y cómo interpretan una agenda de consultorio?
- **Resultado:** Los usuarios esperan encontrar un calendario o agenda donde puedan identificar rápidamente los días y horarios disponibles. Los conceptos más familiares son "agenda", "horario", "disponible", "ocupado", "fecha" y "fisioterapeuta".
- **Modelo mental:** Inicio → Agenda → Fecha → Fisioterapeuta → Horario disponible
- **Metáfora:** Agenda Física de Consultorio
- **Problema:** En el proceso actual el paciente no observa directamente todos los horarios disponibles.
- **Hallazgo:** La consulta depende de la comunicación con el personal, aumentando el tiempo requerido.
- **Heurísticas:** Visibilidad del estado del sistema, Reconocimiento en lugar de recuerdo, Consistencia y estándares.
- **Perspectiva lingüística:** Uso de palabras como "Agenda", "Disponible", "Ocupado", "Fecha" y "Horario".
- **Perspectiva computacional:** Estructura de calendario o grid de horarios. Cada bloque posee un estado como Disponible, Ocupado o Seleccionado.

**Tarea T2: Registrar una cita**
- **Prompt a IA:** ¿Cómo hablan y piensan los pacientes y recepcionistas cuando reservan una cita? ¿Qué esperan que ocurra después de seleccionar un horario disponible?
- **Resultado:** Los usuarios utilizan conceptos como "reservar", "cita", "paciente", "hora", "fisioterapeuta" y "confirmar". Esperan que una vez seleccionado el horario puedan revisar la información antes de finalizar.
- **Modelo mental:** Horario disponible → Reservar → Datos → Revisar → Confirmar
- **Metáfora:** Tarjeta de Reserva
- **Problema:** Una reserva realizada sin un resumen previo puede provocar que el usuario confirme datos incorrectos.
- **Hallazgo:** La revisión previa reduce errores y permite que el usuario mantenga el control.
- **Heurísticas:** Prevención de errores, Control y libertad del usuario, Visibilidad del estado del sistema.
- **Perspectiva lingüística:** Términos "Reservar", "Revisar", "Confirmar" y "Cita".
- **Perspectiva computacional:** El sistema debe validar que el horario continúe disponible antes de registrar la cita. Una vez almacenada, el estado del bloque debe cambiar a "Ocupado".

**Tarea T3: Modificar, cancelar o reprogramar una cita**
- **Prompt a IA:** ¿Cómo entienden los pacientes y el personal administrativo el proceso de cambiar, cancelar o mover una cita? ¿Qué elementos de una agenda física representan mejor estas acciones?
- **Resultado:** Los usuarios comprenden una reprogramación como el movimiento de una cita desde un horario hacia otro. También esperan que una cancelación libere nuevamente el espacio ocupado.
- **Modelo mental:** Mis citas → Seleccionar cita → Modificar / Cancelar / Reprogramar → Confirmar
- **Metáfora:** Calendario con Bloques Móviles
- **Problema:** En el proceso actual cualquier modificación vuelve a depender de la comunicación con el personal.
- **Hallazgo:** Permitir que el usuario gestione directamente las operaciones básicas reduce tiempo y cantidad de interacciones.
- **Heurísticas:** Control y libertad del usuario, Prevención de errores, Consistencia, Feedback.
- **Perspectiva lingüística:** Términos "Modificar", "Cancelar", "Reprogramar" y "Confirmar".
- **Perspectiva computacional:** El sistema debe validar la disponibilidad del nuevo horario. Una reprogramación debe liberar el horario anterior y ocupar el nuevo.

### 2. Inventario Comentado de Metáforas

**Tarea T1: Consultar disponibilidad**

| Categoría | Concepto Digital | Metáfora | Justificación |
|-----------|------------------|----------|---------------|
| Familiar | Calendario | Agenda física | Representa el instrumento tradicional utilizado para organizar citas. |
| Organizacional | Horarios | Bloques de tiempo | Permite identificar rápidamente espacios libres y ocupados. |
| Navegación | Seleccionar horario | Seleccionar bloque | Relaciona la acción digital con escoger un espacio de la agenda. |

**Tarea T2: Registrar una cita**

| Categoría | Concepto Digital | Metáfora | Justificación |
|-----------|------------------|----------|---------------|
| Familiar | Formulario de reserva | Tarjeta de cita | Representa el comprobante que contiene los datos de una cita. |
| Organizacional | Resumen | Comprobante | Agrupa la información antes de confirmar. |
| Navegación | Confirmar | Reservar | Utiliza un término familiar asociado con obtener un espacio. |

**Tarea T3: Administrar una cita**

| Categoría | Concepto Digital | Metáfora | Justificación |
|-----------|------------------|----------|---------------|
| Familiar | Gestión de cita | Calendario | Permite ubicar visualmente la cita existente. |
| Organizacional | Reprogramar | Mover bloque | Representa el cambio de una cita hacia otro espacio. |
| Navegación | Cancelar | Liberar espacio | Representa que el horario vuelve a quedar disponible. |

### 3. Conclusión Parcial

Las metáforas propuestas permiten que los usuarios comprendan el sistema sin necesidad de conocimientos técnicos, aprovechando su experiencia previa con agendas físicas y comprobantes de reserva.
