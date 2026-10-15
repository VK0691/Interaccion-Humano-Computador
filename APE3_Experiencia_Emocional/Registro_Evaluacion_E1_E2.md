# Registro de evaluación emocional — E1 y E2

> **Tutoría Fácil UTA** · APE3 Auditoría emocional de una interfaz digital
> Interacción Humano–Computador · Quinto «B» · Grupo 5
> **Responsable del registro:** Bryan Stalin Guatemal Avilez

---

## 1. Condiciones de la prueba

| | |
|---|---|
| **Prototipo evaluado** | Versión mejorada en [Figma Make](https://www.figma.com/make/pq9CHFHSQ0c5645wQdZ0lw/Tutor%C3%ADa-F%C3%A1cil-UTA-App) |
| **Consigna** | «Encuentra una tutoría de una asignatura, selecciona un horario y comprueba el estado de tu solicitud.» |
| **Escala** | −3 (muy negativa) · 0 (neutral) · +3 (muy positiva) |
| **Momento de registro** | Inmediatamente después de cada momento (M1 a M7) |
| **Anonimato** | Participantes identificados como E1 y E2; ambos autorizaron anotar observaciones |

## 2. Ficha de los participantes

| Campo | E1 | E2 |
|---|---|---|
| Fecha y hora | 14/10/2026 · 10:15 | 14/10/2026 · 10:40 |
| Dispositivo | Laptop | Laptop |
| Prototipo | Mejorado (Figma Make) | Mejorado (Figma Make) |
| ¿Completó el recorrido? | ✅ Sí | ✅ Sí |
| Frase textual | *«¿Y si quiero otro día?»* | *«Toqué las 9 y no pasó nada.»* |

## 3. Matriz de valoraciones

| Mom. | Acción | E1 | Emoción E1 | E2 | Emoción E2 | Media |
|:-:|---|:-:|---|:-:|---|:-:|
| M1 | Ingreso a la aplicación | +2 | Curiosidad | +1 | Interés | **+1.5** |
| M2 | Localización de tutorías | +2 | Confianza | +1 | Duda | **+1.5** |
| M3 | Búsqueda de asignatura | +3 | Satisfacción | +2 | Confianza | **+2.5** |
| M4 | Selección de horario | −1 | Duda | −2 | Frustración | **−1.5** 🔻 |
| M5 | Revisión de la reserva | +1 | Tranquilidad | 0 | Impaciencia | **+0.5** |
| M6 | Confirmación de reserva | +3 | Alivio | +3 | Satisfacción | **+3.0** 🔺 |
| M7 | Consulta de la tutoría agendada | 0 | Confusión | +1 | Tranquilidad | **+0.5** |

🔻 momento más bajo · 🔺 momento más alto. Los mismos datos están en [`Matriz_Emociones.csv`](Matriz_Emociones.csv).

## 4. Observaciones por momento

### M1 · Ingreso a la aplicación
- **E1 (+2, curiosidad):** pantalla de inicio limpia, saludo y accesos rápidos visibles. *«Se ve ordenado, ya sé por dónde empezar».*
- **E2 (+1, interés):** leyó los indicadores (Próximas, Completadas, Promedio) antes de actuar.

### M2 · Localización de tutorías
- **E1 (+2, confianza):** encontró «Reservar tutoría» en Acceso rápido en menos de 5 s, sin dudar.
- **E2 (+1, duda):** dudó entre «Materias» del menú y «Reservar tutoría»; ambos llevan a la misma pantalla. *«¿Cuál es la diferencia?».*

### M3 · Búsqueda de asignatura
- **E1 (+3, satisfacción):** escribió «Base» y la lista se filtró al instante a Base de Datos. *«Qué rápido filtra».*
- **E2 (+2, confianza):** usó el buscador sin problema; las tarjetas muestran docentes y «Disponibles hoy».

### M4 · Selección de horario
- **E1 (−1, duda):** la fecha viene fija (jueves 8 de octubre, ya pasada) y no hay selector de día. *«¿Y si quiero otro día?».*
- **E2 (−2, frustración):** tocó 09:00 (ocupado) y no pasó nada, sin mensaje. La etiqueta «Ocupado» tiene poco contraste. No pudo cambiar la fecha.

### M5 · Revisión de la reserva
- **E1 (+1, tranquilidad):** el resumen muestra docente, asignatura, fecha, hora y modalidad. Le extrañó la carga «Verificando…» de unos 3 s.
- **E2 (0, impaciencia):** esperó la carga «Consultando horarios / Verificando…». *«¿Se colgó?».* Luego revisó el resumen sin problema.

### M6 · Confirmación de reserva
- **E1 (+3, alivio):** pantalla verde «¡Tutoría confirmada!» con estado y recordatorio. *«Listo, quedó clarísimo».*
- **E2 (+3, satisfacción):** confirmación clara, con estado CONFIRMADA y nota de cancelación con 2 h de anticipación.

### M7 · Consulta de la tutoría agendada
- **E1 (0, confusión):** en «Mis tutorías» la nueva reserva (jueves 10:00) coincide con Matemáticas a la misma hora y la app no avisa. Solo muestra el día, no la fecha.
- **E2 (+1, tranquilidad):** vio su tutoría con etiqueta «Confirmada». Notó que ya existía otra de Base de Datos «Pendiente» el lunes.

## 5. Dificultades y retrocesos

| | E1 | E2 |
|---|---|---|
| **Dificultad principal** | M4: fecha fija sin opción de cambiar el día; en M7 no se avisa del choque con otra tutoría a la misma hora. | M4: tocar un horario ocupado no da retroalimentación, «Ocupado» se lee mal y no se puede elegir otra fecha. |
| **Retrocesos / dudas** | Sin retrocesos. Una duda en M4 (buscó un selector de fecha) y otra en M7 (dos tutorías el jueves a las 10:00). | Un intento repetido en M4 (tocó 09:00 dos veces), duda en M2 entre «Materias» y «Reservar tutoría», y pensó que la carga de M5 se había colgado. |

## 6. Análisis

- **Momento más bajo — M4, selección de horario (media −1.5).** Fecha fija y ya pasada, sin selector de día; los horarios ocupados no responden al tocarlos y «Ocupado» tiene bajo contraste.
- **Momento más alto — M6, confirmación (media +3.0).** El mensaje «¡Tutoría confirmada!» es claro, usa color verde, muestra el estado y ofrece un recordatorio.
- **Diferencias entre E1 y E2.** E1 fue más positivo al inicio (rápido y seguro); E2 dudó en M2 y se frustró más en M4. E1 detectó el choque de horarios en M7, mientras que E2 terminó más tranquilo.

### Hallazgos para la propuesta de mejora

| Momento | Hallazgo | Principio HCI |
|:-:|---|---|
| M2 | Dos entradas («Materias» y «Reservar tutoría») llevan al mismo destino y generan duda | Consistencia |
| M4 | Sin selector de fecha ni respuesta al tocar un horario ocupado | Visibilidad del estado · Prevención de errores |
| M5 | La carga «Verificando…» sin indicador de progreso se percibe como bloqueo | Visibilidad del estado del sistema |
| M7 | No se advierte el choque de horarios y solo se muestra el día, no la fecha | Prevención de errores |

## 7. Limitaciones

- Prototipo de Figma Make con datos simulados: no existe reserva real ni backend.
- Solo dos participantes, evaluados en la misma sesión y en laptop; los resultados son señales para el rediseño, no porcentajes representativos.
- Los puntajes son autodeclarados por cada participante.
