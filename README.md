<div align="center">
  
# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS
   ![UPC Logo](https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png)
  
</div>

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.

<div align="center">

-Dueños de Mascotas (Usuario):

![image](https://github.com/user-attachments/assets/71f9ccc9-a107-4367-8852-00065efc151c)

</div>

-Proveedores Certificados (Veterinarios, Groomers, Paseadores)

<div align="center">
  
![image](https://github.com/user-attachments/assets/f75b03ed-61ca-4242-8d4b-1ff0772cf109)

</div>

## 3.2. User Stories 

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic) |
|:----------------|:-------|:------------|:------------------------|:-----------------------|
| EPIC01 | Landing Page: Portada y Servicios | **Como** visitante nuevo,<br>**Quiero** ver una portada atractiva y entender de inmediato de qué trata el sitio,<br>**Para** decidir navegar en los servicios ofrecidos. |  | - |
| EPIC02 | Planes de Suscripción | **Como** visitante interesado,<br>**Quiero** conocer y comparar los distintos planes de servicio,<br>**Para** elegir el más adecuado para las necesidades de mi mascota. |  | - |
| EPIC03 | Sección de Preguntas Frecuentes (FAQ) | **Como** usuario con dudas,<br>**Quiero** acceder fácilmente a preguntas frecuentes organizadas y claras,<br>**Para** resolver mis dudas rápidamente sin necesidad de asistencia adicional. |  | - |
| EPIC04 | Navegación y estructura general | **Como** visitante del sitio,<br>**Quiero** navegar de manera intuitiva entre secciones principales como Home, Services y FAQ,<br>**Para** encontrar fácilmente lo que busco. |  | - |
| EPIC05 | Registro y Login | **Como** nuevo usuario o visitante,<br>**Quiero** poder registrarme y hacer login de manera sencilla,<br>**Para** proteger el acceso a la landing page y personalizar mi experiencia. |  | - |
| EPIC06 | Diseño Visual y Responsividad | **Como** visitante desde diferentes dispositivos,<br>**Quiero** que el sitio se adapte visualmente a computadoras, tablets y celulares,<br>**Para** tener una experiencia agradable y cómoda desde cualquier lugar. |  | - |
| HU01 | Mensaje de bienvenida visible | Como visitante, quiero ver un mensaje de bienvenida en la portada que me explique qué es MascotaMatch, para entender rápidamente el propósito del sitio. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces el visitante ve un título principal que resume el propósito del sitio.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces el sistema muestra un texto explicativo debajo. | EPIC01 |
| HU02 | Botón See Services | Como visitante, quiero hacer clic en el botón "See Services" en la portada para ir directamente a la sección de servicios. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces ve el botón debajo del mensaje principal.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces al hacer clic, va a la sección de servicios. | EPIC01 |
| HU03 | Visualizar tarjetas de servicios | Como visitante, quiero visualizar tarjetas de servicios para conocer opciones disponibles para mi mascota. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces el sistema muestra 4 servicios claros (paseos, grooming, emergencias, recordatorios).<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces las tarjetas contienen imagen, título y descripción breve. | EPIC01 |
| HU04 | Descripción clara de servicios | Como visitante, quiero leer una breve descripción debajo de cada servicio para entender qué incluye y decidir si es relevante para mí. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces cada tarjeta contiene un texto de resumen comprensible.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces el sistema se enfoca en el beneficio directo para el cliente. | EPIC01 |
| HU05 | Imágenes representativas en servicios | Como visitante, quiero que cada servicio tenga una imagen visual que lo represente para reconocerlo rápidamente sin leer demasiado texto. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces todas las tarjetas tienen íconos claros.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces las imágenes están relacionadas con el servicio. | EPIC01 |
| HU06 | Ver planes de suscripción | Como visitante, quiero visualizar los distintos planes (VIP, Completo, Mini) para comparar opciones y elegir el mejor para mi mascota. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces el sistema muestra 3 tarjetas de planes con nombre, imagen y contenido.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces cada plan está diferenciado visualmente. | EPIC02 |
| HU07 | Beneficios por plan en lista | Como visitante, quiero ver los beneficios de cada plan organizados en listas para entender claramente qué incluye cada uno. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces cada plan tiene viñetas con beneficios claros.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces las listas permiten comparar fácilmente. | EPIC02 |
| HU08 | Imagen por plan | Como visitante, quiero que cada plan tenga una imagen para diferenciarlo visualmente de los demás. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces cada tarjeta de plan tiene una imagen distinta.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces la imagen se ubica en la parte superior de cada plan. | EPIC02 |
| HU09 | Botón Read more en cada plan | Como visitante, quiero hacer clic en un botón 'Read more' para ver una página con información completa sobre ese plan. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces debajo de cada plan hay un botón funcional.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces al hacer clic se accede a plan_vip.html, plan_complete.html o plan_mini.html. | EPIC02 |
| HU10 | Acceso a sección FAQ | Como visitante, quiero ver una sección de preguntas frecuentes (FAQ) con íconos y respuestas simples para resolver dudas rápidamente. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces hay 6 preguntas frecuentes en tarjetas organizadas.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces cada tarjeta incluye un ícono representativo y texto explicativo. | EPIC03 |
| HU11 | Visualización del logo | Como visitante, quiero ver el logo de MascotaMatch en la parte superior izquierda para confirmar que estoy en el sitio correcto. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces el logo está visible en el header.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces el logo se mantiene en todas las páginas. | EPIC04 |
| HU12 | Menú de navegación | Como visitante, quiero tener acceso a un menú con secciones como Home, Services, Plans y FAQ para moverme rápidamente por el sitio. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces el menú está en la parte superior.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces cada enlace funciona como ancla a la sección respectiva. | EPIC04 |
| HU13 | Footer con contacto y secciones | Como visitante, quiero ver en el pie de página opciones de contacto, ayuda, distritos y un formulario de correo para comunicarme si necesito más información. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces el footer incluye tres columnas con información.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces hay campo para ingresar correo. | EPIC04 |
| HU14 | Pantalla de login obligatoria | Como visitante, quiero iniciar sesión en una pantalla previa para poder ingresar a la landing page y que el contenido esté protegido. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces el login está en index.html y es obligatorio.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces no se puede acceder a la landing sin estar logueado. | EPIC05 |
| HU15 | Registrarme si no tengo cuenta | Como visitante, quiero registrarme fácilmente si aún no tengo una cuenta para poder acceder al contenido del sitio. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces el login incluye la opción 'register here'.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces el registro permite luego acceder a la landing. | EPIC05 |
| HU16 | Diseño uniforme visualmente agradable | Como visitante, quiero navegar por un sitio con una tipografía, paleta de colores y estilo visual uniforme para sentir confianza y comodidad. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces todo el sitio usa fondo degradado azul.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces los botones verdes son consistentes. | EPIC06 |
| HU17 | Visualización responsiva | Como visitante, quiero que el sitio se vea bien en mi computadora o celular para poder explorarlo cómodamente. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces el sitio adapta los contenidos a diferentes tamaños.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces las secciones están alineadas y centradas. | EPIC06 |
| HU18 | Acceso a páginas de detalle por plan | Como visitante, quiero poder acceder a una página individual con todos los detalles del plan VIP, Completo o Mini desde su botón “Read more”. | **ESCENARIO 1:**<br> Dado que el usuario accede correctamente.<br> Cuando realiza la acción esperada.<br> Entonces cada plan tiene su página independiente.<br><br>**ESCENARIO 2:**<br> Dado que el usuario aún no ha interactuado.<br> Cuando lo intenta por primera vez.<br> Entonces se incluye imagen grande, descripción extensa y lista de beneficios. | EPIC02 |

| User Story ID | Título | Descripción | Criterios de Aceptación |
|:---|:---|:---|:---|
| TS01 | GET servicios disponibles | **Como** desarrollador, **quiero** conectar con la API para obtener los servicios disponibles **para** que el usuario pueda ver las opciones de MascotaMatch. | **Escenario 1:**<br>Dado que accedo a los servicios,<br>Cuando solicito la información,<br>Entonces veo los servicios cargados.<br><br>**Escenario 2:**<br>Dado que no hay servicios,<br>Cuando solicito la información,<br>Entonces veo un mensaje indicando que no hay servicios disponibles. |
| TS02 | GET planes de suscripción | **Como** desarrollador, **quiero** conectar con la API para obtener los planes disponibles **para** que el usuario pueda elegir el mejor plan. | **Escenario 1:**<br>Dado que accedo a los planes,<br>Cuando solicito la información,<br>Entonces veo todos los planes disponibles.<br><br>**Escenario 2:**<br>Dado que no existen planes,<br>Cuando solicito la información,<br>Entonces recibo un mensaje informativo. |
| TS03 | GET preguntas frecuentes | **Como** desarrollador, **quiero** conectar con la API para obtener las preguntas frecuentes **para** resolver las dudas comunes de los usuarios. | **Escenario 1:**<br>Dado que accedo a las preguntas,<br>Cuando solicito la información,<br>Entonces veo todas las preguntas y respuestas.<br><br>**Escenario 2:**<br>Dado que no hay preguntas,<br>Cuando solicito la información,<br>Entonces veo un mensaje indicando que no hay preguntas disponibles. |
| TS04 | POST registro de usuarios | **Como** desarrollador, **quiero** enviar información a la API para registrar nuevos usuarios **para** que puedan crear su cuenta en MascotaMatch. | **Escenario 1:**<br>Dado que un usuario llena sus datos correctamente,<br>Cuando envía su información,<br>Entonces su cuenta se registra exitosamente.<br><br>**Escenario 2:**<br>Dado que un usuario llena datos incorrectos,<br>Cuando intenta registrarse,<br>Entonces recibe un mensaje de error. |
| TS05 | POST inicio de sesión de usuarios | **Como** desarrollador, **quiero** enviar información a la API para permitir que los usuarios inicien sesión **para** acceder a sus servicios personalizados. | **Escenario 1:**<br>Dado que un usuario ingresa datos correctos,<br>Cuando envía su acceso,<br>Entonces puede ingresar correctamente.<br><br>**Escenario 2:**<br>Dado que un usuario ingresa datos incorrectos,<br>Cuando intenta acceder,<br>Entonces recibe un error de acceso. |
| TS06 | GET perfil de usuario | **Como** desarrollador, **quiero** obtener desde la API la información del perfil del usuario autenticado **para** mostrar sus datos personales en la página. | **Escenario 1:**<br>Dado que el usuario ya ingresó,<br>Cuando accede a su perfil,<br>Entonces ve su nombre, correo y mascotas registradas.<br><br>**Escenario 2:**<br>Dado que el usuario no ha ingresado,<br>Cuando intenta ver su perfil,<br>Entonces se le pide iniciar sesión. |
| TS07 | POST agendar citas | **Como** desarrollador, **quiero** enviar información a la API para registrar una cita de servicio para la mascota **para** facilitar la organización de los servicios. | **Escenario 1:**<br>Dado que el usuario llena los datos de cita,<br>Cuando envía la información,<br>Entonces su cita queda registrada.<br><br>**Escenario 2:**<br>Dado que el usuario llena los datos de manera incorrecta,<br>Cuando intenta enviar,<br>Entonces ve un mensaje de error. |
| TS08 | GET citas agendadas | **Como** desarrollador, **quiero** obtener desde la API la lista de citas agendadas del usuario **para** que pueda ver sus próximas reservas. | **Escenario 1:**<br>Dado que el usuario tiene citas agendadas,<br>Cuando accede a sus citas,<br>Entonces puede verlas listadas.<br><br>**Escenario 2:**<br>Dado que no tiene citas,<br>Cuando accede,<br>Entonces ve un mensaje indicando que no tiene citas. |

## 3.3 Impact Mapping

![Impact map 1](https://github.com/user-attachments/assets/e10660e6-3bed-4e57-82b4-1089468dbe21)

## 3.4. Product Backlog.

# 📋 Product Backlog - Mascota Match

| # Orden | User Story ID | Título | Descripción | Story Points (1/2/3/5/8) |
|:-------:|:-------------:|:------:|:------------|:------------------------:|
| 1 | HU14 | Pantalla de Login obligatoria | Como visitante, deseo iniciar sesión en una pantalla previa para acceder al contenido protegido. | 5 |
| 2 | HU15 | Registrarse si no tiene cuenta | Como visitante, deseo registrarme fácilmente si aún no tengo cuenta para ingresar al contenido. | 5 |
| 3 | HU01 | Mensaje de bienvenida | Como visitante, deseo ver un mensaje de bienvenida para entender rápidamente el propósito del sitio. | 3 |
| 4 | HU02 | Botón See Services | Como visitante, deseo hacer clic en "See Services" para ir directamente a la sección de servicios. | 3 |
| 5 | HU03 | Visualizar tarjetas de servicios | Como visitante, deseo visualizar las tarjetas de servicios ofrecidos para conocer las opciones disponibles. | 5 |
| 6 | HU04 | Descripción clara de servicios | Como visitante, deseo leer una breve descripción debajo de cada servicio para entender qué incluye. | 3 |
| 7 | HU05 | Imágenes representativas de servicios | Como visitante, deseo que cada servicio tenga una imagen visual para reconocerlo rápidamente. | 2 |
| 8 | HU06 | Ver planes de suscripción | Como visitante, deseo visualizar los distintos planes para comparar opciones y elegir el mejor. | 5 |
| 9 | HU07 | Beneficios organizados en lista | Como visitante, deseo ver los beneficios de cada plan organizados en listas para entender qué incluye cada uno. | 3 |
| 10 | HU09 | Botón Read More en cada plan | Como visitante, deseo hacer clic en un botón "Read More" para ver una página con información completa. | 2 |
| 11 | HU18 | Acceso a páginas de detalle por plan | Como visitante, deseo poder acceder a una página individual con todos los detalles del plan. | 3 |
| 12 | HU10 | Acceso a sección FAQ | Como visitante, deseo ver una sección de preguntas frecuentes con íconos y respuestas simples para resolver dudas. | 3 |
| 13 | HU11 | Visualización del logo | Como visitante, deseo ver el logo de MascotaMatch en la parte superior izquierda para confirmar que estoy en el sitio correcto. | 1 |
| 14 | HU12 | Menú de navegación | Como visitante, deseo tener acceso a un menú con secciones principales para moverme rápidamente por el sitio. | 2 |
| 15 | HU13 | Footer con contacto | Como visitante, deseo ver en el pie de página opciones de contacto y ayuda para comunicarme si necesito información. | 2 |
| 16 | HU16 | Diseño uniforme | Como visitante, deseo navegar en un sitio con diseño uniforme para sentir confianza y comodidad. | 2 |
| 17 | HU17 | Visualización responsiva | Como visitante, deseo que el sitio se vea bien en mi computadora o celular para poder explorarlo cómodamente. | 3 |
| 18 | HU08 | Imagen por plan | Como visitante, deseo que cada plan tenga una imagen para diferenciarlo visualmente. | 2 |
| 19 | TS04 | POST Registro de usuario | Como desarrollador, deseo enviar información a la API para registrar nuevos usuarios. | 5 |
| 20 | TS05 | POST Inicio de sesión | Como desarrollador, deseo enviar información a la API para permitir el inicio de sesión. | 5 |
| 21 | TS01 | GET Servicios disponibles | Como desarrollador, deseo conectar con la API para obtener los servicios disponibles. | 3 |
| 22 | TS02 | GET Planes disponibles | Como desarrollador, deseo conectar con la API para obtener los planes de suscripción. | 3 |
| 23 | TS03 | GET Preguntas frecuentes | Como desarrollador, deseo conectar con la API para obtener las preguntas frecuentes. | 2 |
| 24 | TS07 | POST Agendar citas | Como desarrollador, deseo enviar información a la API para registrar una cita de servicio. | 5 |
| 25 | TS08 | GET Citas agendadas | Como desarrollador, deseo obtener desde la API la lista de citas agendadas del usuario. | 3 |
| 26 | TS06 | GET Perfil de usuario | Como desarrollador, deseo obtener desde la API la información del perfil del usuario autenticado. | 3 |

