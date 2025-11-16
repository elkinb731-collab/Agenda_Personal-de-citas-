Agenda_Personal de citas
# 📅 Agenda Personal de Citas

La **Agenda Personal de Citas** es un sistema diseñado para gestionar citas de manera simple, organizada y accesible. Permite registrar, editar, eliminar y consultar citas, evitando conflictos de horarios y proporcionando una experiencia clara para el usuario.

---

## 📘 1. Descripción del Caso de Uso  
Este sistema permite a un usuario administrar sus citas personales.  
El usuario puede registrar una cita especificando fecha, hora, descripción y opcionalmente una categoría.  
También puede consultar la lista completa de citas, editar registros y eliminarlos cuando ya no sean necesarios.

---

## 🎯 2. Objetivos del Sistema  
- Facilitar la creación y organización de citas personales.  
- Evitar choques de fecha y hora mediante validaciones.  
- Proveer una visualización ordenada de todas las citas.  
- Garantizar una interfaz simple y fácil de utilizar.  

---

## 🧭 3. Requerimientos del Sistema  

### ✔ Requerimientos Funcionales  
1. Registrar una cita con fecha, hora y descripción.  
2. Editar citas existentes.  
3. Eliminar citas registradas.  
4. Listar citas en orden cronológico.  
5. Validar que no existan dos citas en la misma fecha y hora.  
6. (v2) Agregar categoría opcional a las citas.  
7. (v2) Implementar búsqueda por palabra clave o categoría.

### ✔ Requerimientos No Funcionales  
1. Interfaz de fácil uso y comprensión.  
2. Tiempo de respuesta menor a 2 segundos por acción.  
3. Compatibilidad con navegadores modernos.  
4. Diseño responsivo para uso en móvil y escritorio.  
5. Seguridad básica para evitar pérdida de datos.

---

## 🧪 4. Tabla de Pruebas Funcionales  

| ID | Caso de Prueba | Entrada | Resultado Esperado | Estado |
|----|----------------|---------|--------------------|--------|
| CP01 | Registrar cita válida | Fecha + hora + descripción | La cita se registra correctamente | ✔ |
| CP02 | Intentar registrar cita en horario ocupado | Fecha + hora existente | Mostrar mensaje: “Horario no disponible” | ✔ |
| CP03 | Editar cita existente | Nuevos datos válidos | La cita actualiza su información | ✔ |

Más detalles disponibles en:  
➡ `pruebas/PlanPruebas.md`

---

## 🛠 5. Tipo de Mantenimiento Propuesto  
Se propone **mantenimiento perfectivo**, enfocado en mejorar:

- La experiencia de usuario (UI/UX).  
- La búsqueda y filtrado de citas.  
- Notificaciones recordatorias para citas próximas.  
- Mejor tiempo de respuesta.  

Más información en:  
➡ `mantenimiento/Propuesta_Mantenimiento.md`

---

## 📚 6. Investigación sobre Markdown  
El proyecto utiliza **Markdown (.md)** para documentar requerimientos, pruebas y mantenimiento debido a:

- Su facilidad de lectura.  
- Su compatibilidad con GitHub.  
- Su sintaxis simple para tablas, enlaces, listas y encabezados.  
- Su capacidad para mantenerse versionado junto con el código.  


