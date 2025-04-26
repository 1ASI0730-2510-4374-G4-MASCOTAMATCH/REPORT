<div align="center">
  
# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS
   ![UPC Logo](https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png)
  
</div>


# 5.2. Landing Page, Services & Applications Implementation.

## 5.2.1. Sprint 1

### 5.2.1.1. Sprint Planning 1.

En el desarrollo del proyecto **Mascota Match**, se ha seguido una metodología ágil basada en **Scrum**, con el objetivo de construir de manera iterativa y colaborativa una solución que permita conectar dueños de mascotas con servicios confiables como paseos, grooming, atención veterinaria y emergencias. El Sprint Planning es una ceremonia clave que nos permite definir qué funcionalidades serán entregadas en cada iteración, organizando y priorizando el trabajo de forma estratégica. Durante el Sprint Planning, el equipo revisa el Product Backlog, establece los objetivos de Sprint, selecciona las User Stories y Technical Stories que se abordarán, estima la capacidad de trabajo (Velocity) y acuerda el Sprint Goal, siempre orientado a entregar valor tangible para los usuarios finales. La siguiente sección presenta la planificación detallada de los Sprints establecidos para el proyecto Mascota Match, incluyendo fecha, participantes, objetivos, historias seleccionadas y Story Points asociados.

| Campo | Información |
|:------|:------------|
| **Sprint #** | Sprint 1 |
| **Date** | 2024-04-18 |
| **Time** | 05:00 PM |
| **Location** | Virtual (Discord y Zoom) |
| **Prepared By** | Oscar Espinoza |
| **Attendees (to planning meeting)** | Miguel Vidal, Stephano Landaurí, Fabian Oliva, Gianfranco Durand, Erick Vasquez |
| **Sprint n – 1 Review Summary** | (Al ser el primer Sprint, no existe Sprint previo. No aplica resumen.) |
| **Sprint n – 1 Retrospective Summary** | (Al ser el primer Sprint, no existe retrospectiva previa. No aplica.) |
| **Sprint n Goal** | Nuestro foco está en habilitar el registro e inicio de sesión de usuarios para garantizar el acceso seguro a Mascota Match.<br><br>**Sprint Goal:**<br>Our focus is on secure user registration and login.<br>We believe it delivers confidence to our customers.<br>This will be confirmed when users can successfully register and log in to the platform. |
| **Sprint n Velocity** | Capacidad estimada de Sprint 1: **30 Story Points** |
| **Sprint Goal & User Stories** | **User Stories a desarrollar:**<br><br>1. HU14 - Pantalla de Login obligatoria (5 pts)<br>2. HU15 - Registrarse si no tiene cuenta (5 pts)<br>3. HU11 - Visualización del logo (1 pt)<br>4. HU12 - Menú de navegación (2 pts)<br>5. HU16 - Diseño uniforme (2 pts)<br>6. HU17 - Visualización responsiva (3 pts)<br>7. TS04 - POST Registro de usuarios (5 pts)<br>8. TS05 - POST Inicio de sesión (5 pts) |
| **Sum of Story Points** | **Total: 28 Story Points** |

#### 5.2.1.2. Aspect Leaders and Collaborators.

Para el desarrollo del Sprint 1 del proyecto Mascota Match , se definió una matriz de liderazgo y colaboración para organizar el trabajo de forma clara y eficiente.  
Cada aspecto principal dentro del alcance del Sprint cuenta con un líder (L) encargado de coordinar el trabajo en ese tema específico, y con colaboradores (C) que apoyan el cumplimiento de las tareas relacionadas.

Esta organización permite una mejor distribución de responsabilidades, facilita la comunicación interna y asegura que todos los miembros del equipo contribuyan al logro del Sprint Goal.

A continuación, se presenta la matriz de líderes y colaboradores:

> **L = Leader** (Responsable principal)  
> **C = Collaborator** (Apoya en la ejecución)

| Team Member | GitHub Username | Registro de Usuarios (L/C) | Inicio de Sesión (L/C) | Navegación Principal (L/C) | Diseño Uniforme (L/C) | Responsividad Móvil (L/C) |
|:-----------:|:----------------|:--------------------------:|:----------------------:|:--------------------------:|:--------------------:|:-------------------------:|
| Oscar Espinoza | OscarEspinoza5443 | L | C | C | C | C |
| Miguel Vidal | Gossk | C | L | C | C | C |
| Stephano Landaurí | Mayrzon02 | C | C | L | C | C |
| Fabian Oliva | FabulousFabStar | C | C | C | L | C |
| Gianfranco Durand | Azucarita | C | C | C | C | L |
| Erick Vasquez | erick580 | C | C | C | C | C |

La definición anticipada de líderes y colaboradores en el Sprint 1 permite fortalecer el trabajo en equipo y clarificar las responsabilidades individuales. Con esta organización, se asegura una mayor eficiencia en la ejecución de tareas, mejor comunicación entre los miembros y un enfoque claro en el cumplimiento del **Sprint Goal**. Esta matriz será revisada y ajustada en cada Sprint Planning, de acuerdo al avance del proyecto y a la evolución de las prioridades.

#### 5.2.1.3. Sprint Backlog 1.

Se enfoca en implementar la funcionalidad básica que permita a los usuarios registrarse, iniciar sesión y navegar en la plataforma de manera segura y visualmente coherente. Se han seleccionado User Stories esenciales y se han descompuesto en Work-Items/Tasks específicos para facilitar su ejecución, estimando el esfuerzo necesario y asignando responsables de cada tarea.

A continuación, se presenta la tabla de control de estado para el Sprint 1:

| User Story | Work-Item / Task | Description | Estimation (Hours) | Assigned To | Status (To-Do / In-Process / To-Review / Done) |
|:----------:|:----------------:|:-----------:|:------------------:|:-----------:|:---------------------------------------------:|
| HU14 - Login obligatorio | T1 | Diseñar la pantalla de Login | 4 | Stephano (Mayrzon02) | To-Do |
| HU14 - Login obligatorio | T2 | Implementar validación de credenciales | 5 | Miguel (Gossk) | To-Do |
| TS05 - POST Inicio de sesión | T3 | Programar llamada a API para login | 5 | Miguel (Gossk) | To-Do |
| HU15 - Registro de usuario | T4 | Diseñar la pantalla de registro | 3 | Stephano (Mayrzon02) | To-Do |
| TS04 - POST Registro usuario | T5 | Programar llamada a API para registro | 5 | Oscar (OscarEspinoza5443) | To-Do |
| HU11 - Visualizar logo | T6 | Integrar logo en navbar de todas las pantallas | 2 | Fabian (FabulousFabStar) | To-Do |
| HU12 - Menú de navegación | T7 | Crear el menú de navegación responsive | 4 | Gianfranco (Azucarita) | To-Do |
| HU16 - Diseño uniforme | T8 | Definir paleta de colores y aplicar estilo global | 3 | Fabian (FabulousFabStar) | To-Do |
| HU17 - Visualización responsiva | T9 | Ajustar CSS para dispositivos móviles | 4 | Gianfranco (Azucarita) | To-Do |


