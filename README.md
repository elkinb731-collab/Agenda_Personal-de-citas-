# Agenda Personal de Citas

# Descripción General
La **Agenda Personal de Citas** es una aplicación diseñada para organizar, registrar y gestionar citas personales o profesionales. El sistema permite crear, consultar, modificar y eliminar citas con una estructura sencilla y orientada a la productividad.

---


# **Objetivo General**
Desarrollar un sistema funcional que permita la administración eficiente de citas, garantizando orden, accesibilidad y claridad en la información registrada.

# **Objetivos Específicos**
- Registrar citas con datos relevantes (fecha, hora, tipo y descripción).
- Facilitar la búsqueda y filtrado por distintos criterios.
- Permitir la actualización o eliminación de citas.
- Presentar la información de forma clara.
- Mantener la integridad de los datos almacenados.

---

## Requerimientos Funcionales

| ID | Requerimiento | Descripción |
|----|--------------|-------------|
| RF01 | Registrar cita | Permite ingresar una nueva cita. |
| RF02 | Consultar citas | Muestra citas filtradas por fecha, palabra clave o categoría. |
| RF03 | Editar cita | Modifica información de una cita existente. |
| RF04 | Eliminar cita | Elimina una cita definitivamente. |
| RF05 | Filtrado | Búsquedas avanzadas por fecha, tipo o texto. |
| RF06 | Recordatorios (opcional) | Generación de alertas de citas próximas. |

---

# Requerimientos No Funcionales

| ID | Categoría | Descripción |
|----|-----------|-------------|
| RNF01 | Usabilidad | Interfaz simple y fácil de usar. |
| RNF02 | Rendimiento | Respuestas rápidas sin retrasos visibles. |
| RNF03 | Seguridad | Los datos deben mantenerse íntegros. |
| RNF04 | Portabilidad | Compatible con varios sistemas (dependiendo de la implementación). |

---

# Tecnologías Utilizadas
- Lenguaje de programación *(completar según tu implementación)*  
- Base de datos o método de almacenamiento  
- Entorno de desarrollo  
- Librerías o frameworks  

---

## Ejemplo de Registro de Cita

```json
{
  "titulo": "Reunión académica",
  "fecha": "2025-03-10",
  "hora": "14:00",
  "tipo": "Trabajo",
  "descripcion": "Revisión de avances del proyecto"
}


