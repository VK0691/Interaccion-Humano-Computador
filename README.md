# 🖥️ Interacción Humano-Computador (IHC) - Proyecto de Equipo

Bienvenido al repositorio oficial del equipo para la materia de **Interacción Humano-Computador**.  
Aquí documentaremos nuestro proceso de diseño, desarrollo y pruebas de usabilidad para crear experiencias digitales centradas en el usuario.

---

## 👥 Equipo de Trabajo

| Rol | Nombre | Responsabilidad |
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

# Informe de Práctica APE 3: Fase 1 – Evaluación y Rediseño de Interfaz GITT

Repositorio académico que contiene la documentación en $\LaTeX$, bocetos vectoriales y análisis ergonómico correspondientes a la **Fase 1 (Planificar y Conceptualizar)** del sistema institucional **GITT (Gestión de Inventario Talleres Tecnológicos - UTA)** para la asignatura de **Interacción Humano / Computador**.

---

## 📌 Datos Informativos

* **Institución:** Universidad Técnica de Ambato (UTA)
* **Facultad:** Facultad de Ingeniería en Sistemas, Electrónica e Industrial (FISEI)
* **Carrera:** Ingeniería de Software
* **Asignatura:** Interacción Humano / Computador
* **Nivel y Paralelo:** Quinto - B
* **Docente:** Ing. Jose Ruben Caiza Caizabuano, Mg.
* **Ciclo Académico:** 2026

### Integrantes (Orden Alfabético)

* Bejarano Masabanda Carlos Fabian
* Guatemal Avilez Bryan Stalin
* Molina Nuñez Karen Valeria
* Solis Salinas Mario Tomas

---

## 🎯 Alcance de la Fase 1

En concordancia con el marco metodológico de evaluación de interfaces, esta fase aborda la caracterización del contexto de uso, identificación de cuellos de botella en tareas críticas y el prototipado conceptual preliminar centrado en:

1. **Heurística de Control y Libertad del Usuario (Nielsen #3):**
* Incorporación de salidas de emergencia no destructivas (`Descartar / Cancelar`).
* Mecanismos de recuperación y reversibilidad en flujos transaccionales.


2. **Diagnóstico y Correcciones Clave en GITT:**
* **Selector de Ubicación Padre:** Reemplazo del `<select>` nativo estático por un componente reactivo con autocompletado y filtrado predictivo (*Searchable Combobox*) para manejar escenarios con más de 20 a 40 registros jerárquicos.
* **Paginación Normalizada:** Inclusión de controles de avance, retroceso y tamaño de página en listas extensas (Ubicaciones y Tipos de Ítems) para mitigar la sobrecarga visual y el desplazamiento infinito.
* **Restricción de Longitud de Cadenas:** Implementación de un límite estricto de 250 caracteres con retroalimentación visual en los inputs de búsqueda para evitar desbordamientos visuales y saturación en peticiones al servidor.


3. **Ley de Continuidad (Gestalt) & Scanpath:**
* Organización del formulario sobre un eje vertical continuo para disminuir saltos sacádicos desordenados.
* Mapeo de la trayectoria visual esperada del operario (*Scanpath* en patrón F/Z).




---

## 🛠️ Tecnologías y Herramientas

* **Tipografía y Documentación:** $\LaTeX$, `tikz`, `amsmath`, plantilla institucional de guías APE de la FISEI.
* **Auditoría UI/UX:** Entorno intranet GITT (`172.21.123.153`).
* **Diseño y Prototipado:** TikZ (vectorial nativo) / Figma (wireframes de baja fidelidad).

---
