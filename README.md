# Actividad 7: Simulación de trabajo en equipo remoto

## Presentación

| **Universidad** | Universidad San Carlos de Guatemala |
| **Facultad** | Facultad de Ingeniería |
| **Escuela** | Escuela de Ingeniería en Ciencias y Sistemas |
| **Curso** | LABORATORIO COMUNICACION ASERTIVA Sección A |
| **Actividad** | Actividad 7 – Simulación de trabajo en equipo remoto |
| **Fecha** | 21 de marzo de 2026 |

---

## Instrucciones de la actividad

1. Organizarse en grupos de **3 a 4 personas**.
2. Seleccionar un mini-proyecto brindado por el auxiliar.
3. Simular un entorno de trabajo remoto utilizando:
   - Chat o correo electrónico (aplicando netiqueta profesional)
   - Issues / PRs en un repositorio (GitHub)
   - Documento compartido (Google Docs)
4. Asignar roles dentro del equipo: **Moderador**, **Timekeeper**, **Notetaker**.
5. Durante la simulación, enfrentar un evento imprevisto (pérdida de conexión de un integrante) y aplicar un procedimiento de *fallback*.
6. Consolidar un documento final con los entregables:
   - Registro de comunicación
   - Lista de tareas completadas
   - Documento final del mini-proyecto
7. Presentar al final la organización, comunicación, dificultades y estrategias utilizadas.

---

## Datos del grupo

| **Rol** | **Nombre completo** | **Carnet** |
|---------|---------------------|-----------|
| Moderador | Cesar Emmanuel Cipriano López | 202506978 |
| Timekeeper | Wagner Maximiliano Ley Monroy | 202502811 |
| Notetaker | Daniel Estuardo Chicoj Bolaños | 202500165 |

**Mini-proyecto seleccionado:**  
**Mini-Proyecto 1: Sistema de Gestión de Tareas Académicas**

---

# Simulación de trabajo en equipo remoto  
## Mini Proyecto 1: Sistema de Gestión de Tareas Académicas  

---

## 1. Organización del equipo  

| Rol | Responsabilidad |
|-----|-----------------|
| **Moderador** | Coordinar la comunicación, asegurar que se sigan los acuerdos y guiar la simulación. |
| **Timekeeper** | Controlar los tiempos de cada tarea según el cronograma establecido. |
| **Notetaker** | Registrar acuerdos, conclusiones y consolidar el documento final. |

Todos los integrantes participaron en la definición de funcionalidades y en la redacción del documento final. Se utilizó un documento compartido en Google Docs para la edición colaborativa en tiempo real.

---

## 2. Registro de comunicación (netiqueta profesional)  

A continuación se muestran ejemplos de mensajes enviados durante la simulación, utilizando un chat grupal.

| Hora | Participante | Mensaje |
|------|--------------|---------|
| 10:05 | Moderador | **Buenos días equipo.** Doy inicio a la actividad. Por favor confirmen su disponibilidad. Usaremos este chat para coordinación y el documento compartido para trabajar. |
| 10:07 | Timekeeper | Buenos días. Confirmo, estaré atento al tiempo. |
| 10:08 | Notetaker | Buenos días. Listo, me encargo de tomar notas. |
| 10:12 | Moderador | **Acuerdo:** Para cada tarea del mini-proyecto crearemos un issue en el repositorio y asignaremos un responsable. Usaremos el documento compartido para el borrador final. |
| 10:15 | Notetaker | **Pregunta:** ¿El documento final debe incluir el flujo de uso en diagrama o solo en texto? |
| 10:17 | Moderador | Solo texto, pero con claridad. Timekeeper, ¿cuánto tiempo tenemos por tarea? |
| 10:18 | Timekeeper | Tenemos 35 min en total. Propongo: 10 min para definir problema y funcionalidades, 10 min para roles y flujo, 10 min para consolidar y 5 min para revisión. |
| 10:20 | Moderador | De acuerdo. Voy a crear los issues ahora mismo. |
| ... | ... | ... |
| 10:45 | *Evento* | **Se simula pérdida de conexión del Timekeeper.** |
| 10:46 | Moderador | **Aviso:** El Timekeeper ha perdido conexión. Aplicamos procedimiento de *fallback*: redistribuimos sus tareas pendientes. Notetaker, ¿puedes encargarte de revisar los roles del sistema y el flujo de uso? Yo ajustaré los tiempos. |
| 10:48 | Notetaker | Sí, tomo la tarea. Actualizaré el issue correspondiente. |
| 10:50 | Moderador | Redistribución registrada. Continuamos. |
| ... | ... | ... |

*Se mantuvo un tono cordial, mensajes con estructura clara (saludo, propósito, cierre) y respeto a los turnos.*

---

## 3. Lista de tareas completadas (Issues / PRs)  

Se crearon issues en el repositorio GitHub del equipo. Cada tarea fue asignada y marcada como completada.

| Issue | Descripción | Responsable | Estado |
|-------|-------------|-------------|--------|
| #1 | Definir el problema a resolver | Notetaker | ✅ Completado |
| #2 | Establecer funcionalidades principales (mínimo 4) | Moderador | ✅ Completado |
| #3 | Definir roles del sistema (usuarios) | Timekeeper → Notetaker (por fallback) | ✅ Completado |
| #4 | Describir el flujo de uso | Timekeeper → Notetaker (por fallback) | ✅ Completado |
| #5 | Consolidar documento final | Notetaker (con apoyo de todos) | ✅ Completado |

Adicionalmente, se creó un **Pull Request** con la versión final del documento, revisado por el Moderador y aprobado por el equipo.

---

## 4. Documento final consolidado  

### **Sistema de Gestión de Tareas Académicas**  

#### 4.1 Problema a resolver  
Los estudiantes tienen dificultades para organizar sus tareas académicas debido a la falta de una herramienta sencilla que permita priorizar actividades, visualizar el progreso y mantener un registro claro de las entregas. Se requiere una solución básica que mejore la planificación y reduzca la acumulación de trabajo pendiente.

#### 4.2 Funcionalidades principales  
1. **Registro de tareas:** Permitir agregar nuevas tareas con título, descripción, fecha límite y materia.  
2. **Asignación de prioridad:** Clasificar tareas como *Alta*, *Media* o *Baja* prioridad.  
3. **Visualización de progreso:** Mostrar un porcentaje de avance global y por materia.  
4. **Notificaciones recordatorias:** Enviar alertas simples (por correo o dentro del sistema) antes de la fecha límite.  

#### 4.3 Roles del sistema  
| Rol | Descripción |
|-----|-------------|
| **Estudiante** | Usuario principal que puede crear, editar y eliminar sus propias tareas, así como visualizar su progreso. |
| **Administrador (opcional)** | En una versión extendida, podría gestionar materias y usuarios, pero para la propuesta inicial no se incluye. |

#### 4.4 Flujo de uso  
1. El estudiante inicia sesión y accede a su panel principal.  
2. Desde el panel, puede **agregar una nueva tarea** ingresando título, descripción, materia, fecha límite y prioridad.  
3. La tarea aparece en la lista con su prioridad resaltada.  
4. El estudiante puede **marcar tareas como completadas**; el sistema actualiza automáticamente el porcentaje de progreso.  
5. El sistema **envía recordatorios** 24 horas antes de la fecha límite para tareas no completadas.  

---

## 5. Manejo de la situación simulada (pérdida de conexión)  

Durante la simulación, se presentó el evento de “pérdida de conexión” de un integrante (Timekeeper). El equipo aplicó el procedimiento de *fallback* establecido previamente:

1. **Detección:** El Moderador notó la ausencia de respuesta del Timekeeper después de 2 minutos sin actividad.  
2. **Activación del plan:** Se anunció en el chat la activación del plan de contingencia.  
3. **Redistribución de tareas:** Las tareas pendientes del Timekeeper (roles del sistema y flujo de uso) fueron reasignadas al Notetaker, quien actualizó los issues correspondientes.  
4. **Registro:** El Notetaker documentó la redistribución en el acta de la reunión.  
5. **Continuidad:** El equipo continuó trabajando sin interrupciones, ajustando los tiempos para no afectar el cronograma.

---

## 6. Reflexión sobre el trabajo remoto  

### Cómo nos organizamos  
Utilizamos un documento compartido como espacio central de trabajo. Definimos roles al inicio y acordamos usar issues en GitHub para dar seguimiento a las tareas. El chat sirvió para comunicación inmediata y para resolver dudas rápidas.

### Gestión de la comunicación  
Aplicamos los principios de **netiqueta profesional**:  
- Saludos iniciales y despedidas claras.  
- Mensajes con asunto o propósito definido.  
- Uso de lenguaje respetuoso y conciso.  
- Confirmación de acuerdos por escrito en el chat.

### Dificultades enfrentadas  
- **Coordinación en tiempo real:** Al trabajar de forma remota, hubo un breve retraso en la respuesta inicial de un integrante. Se solucionó con una breve llamada de voz para alinear la estrategia.  
- **Redistribución repentina:** La pérdida de conexión simulada obligó a reasignar tareas rápidamente; sin embargo, el plan de contingencia permitió mantener el rumbo.  
- **Sincronización de versiones:** En el documento compartido, se generó un conflicto de edición momentáneo; lo resolvimos usando la función de sugerencias y asignando un editor por sección.

### Estrategias utilizadas para resolver problemas  
- Establecimiento de un plan de *fallback* desde el inicio.  
- Uso de issues para asignar responsabilidades claras.  
- Revisión periódica de avances (cada 5 minutos).  
- Documentación inmediata de acuerdos para evitar malentendidos.  

---

## 7. Presentación final (resumen)

El equipo demostró una organización efectiva, comunicación profesional y capacidad de adaptación ante imprevistos. Se logró consolidar el documento final del mini-proyecto dentro del tiempo establecido, cumpliendo con todos los puntos solicitados. La experiencia refuerza la importancia de la planificación, el uso adecuado de herramientas colaborativas y la aplicación de netiqueta en entornos virtuales.

---

## 8. Distribución de trabajo (contribuciones por integrante)

| Integrante  | Secciones / Bloques elaborados |
|------------------|-------------------------------|
| **Wagner Maximiliano Ley Monroy** | Sección 1 (Organización del equipo), Sección 2 (Registro de comunicación – mensajes iniciales y coordinación), Sección 5 (Manejo de la situación simulada – liderazgo en fallback), revisión final del documento. |
| **Daniel Estuardo Chicoj Bolaños** | Sección 2 (definición de tiempos en el chat), Sección 6 (Reflexión sobre trabajo remoto – redacción de dificultades y estrategias), apoyo en definición de funcionalidades. |
| **Cesar Emmanuel Cipriano López** | Sección 3 (Lista de tareas completadas), Sección 4 (Documento final consolidado completo), Sección 7 (Presentación final – resumen), consolidación del documento en formato Markdown. |
