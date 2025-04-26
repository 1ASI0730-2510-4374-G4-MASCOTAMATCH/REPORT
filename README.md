<div align="center">
  
# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS
   ![UPC Logo](https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png)
  
</div>


# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

**Requirements Management**

**User Experience Design (UX/UI)**

**Project Managment**

1. Discord y WhatsApp: Estas plataformas fueron esenciales para la comunicación interna del equipo, siendo WhatsApp especialmente útil por su facilidad para gestionar grupos de trabajo.

2. Trello: Se utilizó para planificar y dar seguimiento al avance del proyecto mediante tableros que representaban el backlog del producto y otras tareas organizativas.

**Product UX/UI**


1. Figma: Herramienta principal para el diseño de wireframes y prototipos, tanto en versiones de escritorio como móviles.

2. Miro: Apoyo en la creación de los escenarios mapping y escenario mapping en ambos casos para ambos segmentos del objetivo en el desarrollo del proyecto.


**Software Development**

1. Visual Studio Code: Editor principal utilizado para programar el landing page.

2. Github y Git bash: Se emplearon para el control de versiones y el desarrollo colaborativo del repositorio del proyecto.

3.HTML y CSS: Lenguajes fundamentales utilizados para la estructura (HTML) y el diseño visual (CSS) del landing page.

**Software Documentation**

1. Google Drive: Plataforma utilizada para el almacenamiento compartido de documentación e informes colaborativos.
   
2. Google Meets y Zoom: Se usó Google Meets más que nada para las videoconferencias de reunión del equipo y el Zoom para las grabaciones de las entrevistas, y las presentaciones del trabajo en el desarrollo de este.
   
3. LucidChart: Herramienta utilizada para diagramas de flujo y modelado visual del diseño de la aplicación, incluyendo diagramas de clases.
   
4. Structuriz: Permite la creación del modelo C4 en sus tres niveles (contexto, contenedores, componentes), también trabajado en conjunto con Visual Studio Code.
   
5. Vertabello: Se empleó para el diseño de la base de datos y sus respectivos diagramas lógicos.


### 5.1.2. Source Code Management

Para el desarrollo de MascotaMatch, se implementará el modelo GitFlow como estándar de control de versiones, utilizando GitHub como plataforma central. Esta metodología permitirá una organización clara y sistemática del trabajo en equipo, facilitando la colaboración, el control de cambios y la integración continua. A continuación, se describe cómo se aplicará GitFlow dentro del proyecto y los enlaces relevantes a los repositorios de GitHub.

**GitFlow Workflow:**

- Ramas principales: main (para versiones estables de producción) y develop (para integrar el desarrollo en curso).
  
- Ramas de características (features): Cada nueva funcionalidad de MascotaMatch será desarrollada en una rama específica, siguiendo un esquema de nombres como feature/nombre-de-la-funcionalidad.
  
- Rama develop:  Es la rama base para el desarrollo de nuevas funcionalidades. Todo el trabajo en curso se integra primero en develop, y solo después de ser validado, se pasa a main.

**Repositorios de GitHub:**

- Enlace a la organización en GitHub: https://github.com/orgs/Open-Source-SW56-Group-2-EcoMovil/repositories
  
- Enlace al repositorio de la **Landing Page**: https://open-source-sw56-group-2-ecomovil.github.io/Landing-Page-EcoMovil/

![gitflow](assets/chapter-5/gitflow.png)

**Estructura de Ramas (Branches) en GitFlow:**

1. **Rama main (Principal):** Es la rama principal del proyecto, contiene la versión más reciente y estable de MascotaMatch, apta para producción.
   
2. **Rama Develop (Desarrollo):** Su función es mantener el progreso continuo del proyecto. Aglutina el trabajo diario del equipo de desarrollo, sirviendo de base para integrar nuevas funcionalidades antes de su despliegue final.
   
3. **Ramas de Funcionalidad (Feature branches):** Cada funcionalidad nueva (por ejemplo, "registro de mascotas" o "búsqueda de adopciones") se trabajará en una rama independiente, la cual se fusionará en develop una vez completada y verificada.

**Convenciones de Commits:**

En el repositorio de GitHub del proyecto MascotaMatch, se siguió el estándar de convenciones de commits versión 1.1.0. Esta convención establece una sintaxis clara para los mensajes de commit con el siguiente formato:

<tipo>[alcance opcional]: <descripción>

1. Tipo: indica la naturaleza del cambio, como feat para nuevas funcionalidades, fix para correcciones, o docs para modificaciones en la documentación.


2. Alcance (opcional): especifica el área del código afectada por el cambio.


3. Descripción: resume brevemente lo que se ha hecho en ese commit.


### 5.1.3. Source Code Style Guide & Conventions

En el desarrollo de nuestra Landing Page, hemos seguido las mejores prácticas de diseño web, empleando HTML y CSS para estructurar y
estilizar el contenido de manera eficaz. Para organizar la información, utilizamos etiquetas HTML de encabezado, como "h1" para los 
títulos y "p" para los párrafos. Para personalizar el estilo visual, aplicamos el atributo styles.css en HTML, ajustando propiedades 
como el color, el tamaño de la fuente y el tipo de letra. Para resaltar ciertos elementos, usamos "strong" en el footer para énfasis 
adicional. En cuanto a la navegación, diseñamos una barra horizontal con css, lo que contribuye a una experiencia de usuario más fluida 
al explorar la página. Para hacer la página más interactiva, agregamos botones con efectos de hover utilizando css, tanto en secciones 
como planes y botones para register y login. Para facilitar el acceso entre diferentes secciones de productos también usamos css. Por 
último, en el pie de página, incluimos un formulario para contactarse con nuestro soporte, brindando a los usuarios una forma sencilla y 
directa de conectarse con nosotros y por nuestra parte estar al tanto de ellos.

**HTML Style Guide and Coding Conventions**

1. Se emplea una indentación de dos espacios para mantener una estructura clara y legible.


2. Las etiquetas HTML se escriben en minúsculas, al igual que sus atributos.


3. Se insertan comentarios breves y precisos en el código para facilitar su entendimiento por parte del equipo de desarrollo.

**CSS Style Guide (Based on Google HTML/CSS Style Guide)**

1. Las clases siguen el formato de guiones medios (por ejemplo, .main-container).


2. Las líneas de código se limitan a un máximo de 80 caracteres para mantener la legibilidad.


3. Se utilizan nombres descriptivos para clases e identificadores, facilitando la comprensión de su propósito.

**JavaScript Style Guide**

1. Las variables y funciones se nombran utilizando camelCase.


2. Se usa una indentación de dos espacios para mantener la uniformidad.


3. Las comillas simples (' ') son el estándar para definir strings.


4. Se incluyen comentarios explicativos para aclarar el comportamiento de las funciones y bloques clave.

**Gherkin Conventions for Readable Specifications**

1. Se redactan escenarios en lenguaje claro y comprensible, siguiendo la estructura Given - When - Then, para documentar de forma efectiva el comportamiento esperado del sistema.


### 5.1.4. Software Deployment Configuration. 

Para el alojamiento de nuestra Landing Page, utilizaremos GitHub Pages. Subiremos los archivos necesarios (como HTML y CSS) a un repositorio público en GitHub, de modo que la página sea accesible en línea y pueda ser visitada por cualquier usuario.

## 5.2. Landing Page, Services & Applications Implementation


# 5.2. Landing Page, Services & Applications Implementation.

## 5.2.1. Sprint 1

### 5.2.1.1. Sprint Planning 1.

El Sprint Planning 1 establece la organización inicial del equipo para desarrollar el MVP de Mascota Match. Se definen el objetivo del Sprint, las User Stories que serán trabajadas, la capacidad del equipo, y los entregables esperados. Este proceso permite una planificación clara y el alineamiento de todo el equipo hacia un mismo objetivo para la entrega de valor.

| Campo | Información |
|:------|:------------|
| **Sprint #** | Sprint 1 |
| **Date** | 2024-04-18 |
| **Time** | 05:00 PM |
| **Location** | Virtual (Discord y Zoom) |
| **Prepared By** | Oscar Espinoza, Miguel Vidal, Stephano Landaurí, Fabian Oliva, Gianfranco Durand, Erick Vasquez |
| **Attendees (to planning meeting)** | Oscar Espinoza, Miguel Vidal, Stephano Landaurí, Fabian Oliva, Gianfranco Durand, Erick Vasquez |
| **Sprint n – 1 Review Summary** | No aplica (Primer Sprint del proyecto Mascota Match). |
| **Sprint n – 1 Retrospective Summary** | No aplica (Primer Sprint del proyecto Mascota Match). |
| **Sprint n Goal** | Finalizar la primera versión de Mascota Match, incluyendo registro de usuarios, login, navegación general, publicación de servicios, planes de suscripción, sección de FAQ, agendamiento de citas y perfil de usuario.<br><br>**Sprint Goal:**<br>Our focus is on launching Mascota Match MVP.<br>We believe it delivers essential functionality and first user experience.<br>This will be confirmed when users can register, navigate, consult services, choose a plan, and book an appointment successfully. |
| **Sprint n Velocity** | 82 Story Points |
| **Sprint Goal & User Stories** | **User Stories:**<br>HU01, HU02, HU03, HU04, HU05, HU06, HU07, HU08, HU09, HU10, HU11, HU12, HU13, HU14, HU15, HU16, HU17, HU18, TS01, TS02, TS03, TS04, TS05, TS06, TS07, TS08 |
| **Sum of Story Points** | **82 Story Points** |

### 5.2.1.2. Aspect Leaders and Collaborators

Para asegurar una ejecución eficiente del Sprint 1, se definieron líderes y colaboradores responsables de las principales áreas del proyecto. Cada miembro del equipo lidera o apoya aspectos específicos como el desarrollo de páginas, integración de funcionalidades, diseño visual y animaciones. Esta matriz garantiza una asignación clara de tareas y fomenta el trabajo colaborativo.

| Team Member | GitHub Username | Home | Index | Plan Complete | Plan Mini | Plan VIP | FAQ / Perfil / Agendamiento / Animaciones |
|:-----------:|:----------------|:----:|:-----:|:-------------:|:---------:|:--------:|:----------------------------------------:|
| Oscar Espinoza | OscarEspinoza5443 | L | C | C | C | C | C |
| Miguel Vidal | Gossk | C | L | C | C | C | C |
| Fabian Oliva | FabulousFabStar | C | C | L | C | C | C |
| Stephano Landaurí | Mayrzon02 | C | C | C | L | C | C |
| Gianfranco Durand | Azucarita | C | C | C | C | L | C |
| Erick Vasquez | erick580 | C | C | C | C | C | L |

### 5.2.1.2. Sprint Backlog 1 

El Sprint Backlog 1 consolida todas las funcionalidades principales de Mascota Match, enfocándose en completar toda la experiencia de usuario inicial: registro, login, navegación, servicios, planes de suscripción, sección FAQ, agendamiento de citas y consulta de perfiles.

| User Story | Work-Item / Task | Description | Estimation (Hours) | Assigned To | Status |
|:----------:|:----------------:|:-----------:|:------------------:|:-----------:|:------:|
| HU14 | T1 | Crear pantalla de Login | 5 | Stephano (Plan Mini) | Done |
| HU15 | T2 | Crear pantalla de Registro | 5 | Oscar (Home) | Done |
| TS04 | T3 | Programar POST registro API | 5 | Oscar (Home) | Done |
| TS05 | T4 | Programar POST login API | 5 | Miguel (Index) | Done |
| HU11 | T5 | Visualizar logo en navbar | 1 | Fabian (Plan Complete) | Done |
| HU12 | T6 | Menú de navegación principal | 2 | Miguel (Index) | Done |
| HU16 | T7 | Aplicar diseño uniforme | 2 | Fabian (Plan Complete) | Done |
| HU17 | T8 | Adaptar responsividad móvil | 3 | Erick (Animaciones) | Done |
| HU01 | T9 | Crear sección bienvenida | 3 | Oscar (Home) | Done |
| HU02 | T10 | Programar botón See Services | 3 | Miguel (Index) | Done |
| HU03 | T11 | Diseñar tarjetas de servicios | 5 | Miguel (Index) | Done |
| HU04 | T12 | Agregar descripción de servicios | 3 | Erick (Animaciones) | Done |
| HU05 | T13 | Insertar imágenes en servicios | 2 | Erick (Animaciones) | Done |
| TS01 | T14 | GET servicios disponibles API | 3 | Miguel (Index) | Done |
| HU06 | T15 | Crear tarjetas planes VIP, Completo, Mini | 5 | Fabian, Stephano, Gianfranco | Done |
| HU07 | T16 | Listar beneficios por plan | 3 | Fabian, Stephano, Gianfranco | Done |
| HU08 | T17 | Imagen única por plan | 2 | Erick (Animaciones) | Done |
| TS02 | T18 | GET planes de suscripción API | 3 | Miguel (Index) | Done |
| HU09 | T19 | Botón "Read More" en cada plan | 2 | Stephano (Plan Mini) | Done |
| HU18 | T20 | Crear páginas detalle de planes | 3 | Oscar (Home) | Done |
| HU10 | T21 | Crear sección FAQ | 3 | Erick (Animaciones) | Done |
| TS03 | T22 | GET preguntas frecuentes API | 2 | Miguel (Index) | Done |
| HU13 | T23 | Footer contacto y ayuda | 2 | Fabian (Plan Complete) | Done |
| TS06 | T24 | GET perfil de usuario API | 3 | Miguel (Index) | Done |
| TS07 | T25 | POST agendar cita API | 5 | Gianfranco (Plan VIP) | Done |
| TS08 | T26 | GET citas agendadas API | 3 | Gianfranco (Plan VIP) | Done |

 URL del Board Trello 

-->

### 5.2.1.4. Development Evidence for Sprint Review

### 5.2.1.5. Development Evidence for Sprint Review

### 5.2.1.6. Development Evidence for Sprint Review

### 5.2.1.7. Development Evidence for Sprint Review

### 5.2.1.8. Team Collaboration Insights during Sprint

