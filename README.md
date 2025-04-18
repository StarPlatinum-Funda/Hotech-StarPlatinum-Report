# Hotech-StarPlatinum-Report

<h1 style="text-align: center;"> Informe del Trabajo Final </h1>
<h3 style="text-align: center;"> Universidad Peruana de Ciencias Aplicadas </h3>

<tr>
  <div align='center'>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"width="150" height="150">
    </div>
</tr>

<h5 style="text-align: center"> Ingeniería de Software 2025-01 </h5>

<h5 style="text-align: center"> Fundamentos de Arquitectura de Software - 1ASI0657 </h5>

<h5 style="text-align: center"> NRC: 3588 </h5>

<h5 style="text-align: center"> Docente: Ernesto Campos Tello </h5>

<h5 style="text-align: center"> Startup: StarPlatinum </h5>

<h5 style="text-align: center"> Producto: Hotech </h5>

## Team members:

|               Nombre               |  Código  |
| :--------------------------------: | :--------: |
|            |        |
| More Rondon, Christopher Sebastian | U202212199 |
|            |        |
|            |        |

<h5 style="text-align: center"> Abril 2025 </h5>

### Registro de Versiones del Informe

| Versión | Fecha       | Autor                              | Descripción                                            | Estado     |
| -------- | ----------- | ---------------------------------- | ------------------------------------------------------- | ---------- |
| 1.0      | 16/04/2025  | More Rondon, Christopher Sebastian | Creación del documento. | Completado |
|       |  |     |         | --         |

### Studen Outcome

| **Criterio específico**                                                                  | **Acciones realizadas** | **Conclusiones** |
| ----------------------------------------------------------------------------------------------- | ----------------------------- | ---------------------- |
| Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.| ---                           | ---                    |
| Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.| ---                           | ---                    |

## Capítulo I: Introducción.

### 1.1 **Startup Profile.**

#### 1.1.1   Descripción del startup

#### 1.1.2   Perfiles de integrantes del equipo

### 1.2 **Solution Profile.**

#### 1.2.1   Nombre del producto

#### 1.2.2   Antecedentes y problemática

#### 1.2.3   Lean UX Process.

#### 1.2.3.1 Lean UX Problem Statements

#### 1.2.3.2 Lean UX Assumptions.

#### 1.2.3.3 Lean UX Hypothesis.

#### 1.2.3.4 Lean UX Canvas.

### 1.3 **Segmentos Objetivos.**

## Capítulo II: Requirements & Analysis.

### 2.1 **Competidores.**

### 2.2 **Entrevistas**

### 2.3 **Needfinding.**

#### 2.3.1   User Personas.

#### 2.3.2   User Task Matrix.

#### 2.3.3   Empathy Mapping.

#### 2.3.4   As-is scenario mapping

## Capítulo III: Requirements Specification.

### 3.1 **To-Be Scenario Mapping.**

Segmento 1:

| Fases    |                                                                                                    |                                                                                  |                                                                                  |                                                                                    |
|----------|----------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| Doing    | Utilizando la herramienta web para verificar el estado de los cuartos y el inventario              | Asignando tareas al personal de limpieza a través de la plataforma               | Monitoreando el progreso del personal y comunicándose directamente con ellos     | Revisando las sugerencias de mejora proporcionadas por la herramienta              |
| Thinking | Considerando cómo optimizar la asignación de tareas y la gestión del inventario con la herramienta | Evaluando la eficacia de la comunicación y supervisión a través de la plataforma | Reflexionando sobre las mejoras implementadas y la efectividad de la herramienta | Identificando nuevas oportunidades de mejora en la gestión de habitaciones y stock |
| Feeling  | Satisfecho con la eficiencia y precisión en la gestión de cuartos e inventario                     | Valorando la comunicación directa y efectiva con el personal                     | Motivado por las mejoras implementadas y el impacto positivo en la operación     | Esperanzado por las nuevas oportunidades de mejora identificadas                   |

Segmento 2:

| Fases    |                                                                                             |                                                                                             |                                                                                       |                                                                                                   |
|----------|---------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------|
| Doing    | Utilizando la herramienta web para recibir y completar tareas asignadas                     | Notificando al supervisor a través de la plataforma cuando las tareas están completas       | Actualizando el estado del stock de elementos de limpieza y toallas en la herramienta | Comunicándose con el supervisor a través de la plataforma sobre cualquier problema o solicitud    |
| Thinking | Reflexionando sobre la eficacia de las tareas asignadas y la comunicación con el supervisor | Evaluando la necesidad de mejorar la gestión de tareas y la comunicación con la herramienta | Considerando cómo mejorar la eficiencia en la gestión de inventario y comunicación    | Pensando en soluciones para optimizar el proceso de trabajo y la colaboración con el supervisor   |
| Feeling  | Comprometido con la calidad y eficiencia en la ejecución de tareas asignadas                | Satisfecho al completar las tareas de manera efectiva y comunicarlas al supervisor          | Preocupado por la disponibilidad y gestión adecuada del inventario                    | Interesado en mejorar la comunicación y colaboración con el supervisor a través de la herramienta |


### 3.2 **User Stories.**



| HUX/EPX | Historia de Usuario / Epica                                   | Descripción                                                                                                                                            | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                          | Relacionado con (Epic ID) |
|---------|---------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------|
| EP01    | Información del producto                                      | Como visitante del sitio web, quiero obtener información relacionada al producto que se ofrece.                                                        | Given estoy interesado en el producto <br> When ingreso al sitio web <br> Then observo la información del producto que se está ofreciendo <br> And tengo una mejor visión de qué ofrece la empresa <br> And obtengo información útil.                                                                                                            |                           | 
| HU01    | Conseguir información de la empresa                           | Como visitante del sitio web, quiero obtener más información sobre la empresa a cargo del producto.                                                    | Given estoy interesado en conocer información de la empresa <br> When navego en la sección principal del sitio web <br> Then observo la información relevante sobre la empresa <br> And me intereso en saber más del producto                                                                                                                    | EP01                      | 
| HU02    | Informarse sobre los beneficios del producto                  | Como visitante del sitio web, quiero informarme sobre los beneficios del producto ofrecido.                                                            | Given que se han establecido umbrales de inventario y preferencias de notificación <br> When los niveles de inventario caen por debajo de los umbrales establecidos <br> Then se envían notificaciones automáticas <br> And las notificaciones incluyen detalles sobre los suministros con bajo inventario.                                      | EP01                      |
| HU03    | Conocer los testimonios de los clientes pasados               | Como visitante, quiero acceder a testimonios de clientes anteriores para evaluar la experiencia y el desempeño del personal.      | Given que existe la opción de acceder a testimonios de clientes anteriores <br> When selecciono los testimonios que deseo revisar <br> Then puedo evaluar la experiencia y desempeño del personal basado en los comentarios de clientes previos.                                                                               | EP01                      |
| HU04    | Informarse sobre los diferentes planes de precio del producto | Como visitante, quiero conocer los diferentes planes de precio disponibles para el producto ofrecido. | Given que hay una lista de planes de precios disponibles <br> When visualizo los diferentes planes <br> Then puedo entender las opciones disponibles y tomar decisiones informadas sobre el producto.                                                                                                    | EP01                      |
| HU05    | Contactar con la empresa                                      | Como visitante, quiero poder contactarme fácilmente con la empresa desde la página de inicio.                 | Given que accedo a la página de inicio <br> When deseo contactar a la empresa <br> Then encuentro opciones claras y accesibles para hacerlo.                                                                                       |EP01
| EP02    | Crear cuenta                                                  | Como gerente del hotel/hostal quiero crear una cuenta para utilizar InnControl (aplicación).                                                           | Given que para ingresar debo loguearme o crear una cuenta <br> When ingreso mis datos como correo, nombre de hotel, habitaciones y número de empleados <br> Then se me presentará con el plan que se acomoda mejor a las necesidades del negocio <br> And realizo el pago.                                                                       | -                         |
| HU01    | Crear cuenta empleado                                         | Como empleado, quiero utilizar el código de gerente para crear mi cuenta de empleado.                                                                  | Given que cuando el gerente crea una cuenta se le da una clave de gerente <br> When creo mi cuenta empleado <br> And ingreso el código de gerente <br> And ingreso mis datos <br> Then se me mostrará un mensaje de bienvenida <br> And se mostrará mi dashboard de empleado.                                                                    | EP02                      |
| HU02    | Crear cuenta gerente                                          | Como gerente, quiero crear mi cuenta de gerente para poder darles mi código de gerente a mis empleados.                                                | Given que cuando se paga el plan me solicitan crear una clave de gerente <br> When realizo los procesos de autenticación <br> Then se mostrará el código para compartirselo a mis empleados <br> And les permitirá crear sus cuentas personales.                                                                                                 | EP02                      |
| EP03    | Gestionar Habitaciones del Hotel                              | Como gerente, quiero poder revisar el estado de las habitaciones.                                                                                      | Given que existen habitaciones ya generadas <br> When reviso la sección de Habitaciones <br> And reviso las habitaciones en su página <br> Then puedo ver los estados, reservaciones, el tipo de habitación, el número de habitación y el cliente <br> And se me muestra también un botón para cambiar el estado y otro para crear habitaciones. | -                         
| HU01    | Cambiar estado de habitación                                  | Como gerente, quiero realizar un cambio al estado de la habitación.                                                                                    | Given que hay un botón para cambiar el estado de la habitación <br> When uso el botón <br> And selecciono uno de los estados en el popup <br> Then el estado de la habitación en la tabla se actualiza.                                                                                                                                          | EP03                      
| HU02    | Cambiar estado de habitación                                  | Como empleado, quiero cambiar el estado de la habitación de mi tarea para notificar que ya terminé mi tarea.                                           | Given que mis tareas muestran las habitaciones asignadas <br> When termino con mi tarea <br> Then uso el botón para cambiar el estado de la habitación <br> And se manda un aviso al gestor de mis tareas.                                                                                                                                       | EP03                      
| HU03    | Crear habitaciones                                            | Como gerente, quiero crear nuevas habitaciones en el sistema.                                                                                          | Given que tengo acceso para crear nuevas habitaciones <br> When ingreso los detalles de la habitación (tipo, número, etc.) <br> Then la habitación se añade al sistema y se refleja en la lista de habitaciones.                                                                                                                                 | EP03                      
| EP04    | Gestionar Inventario                                          | Como gestor, quiero gestionar el inventario del hotel.                                                                                                 | Given que tengo acceso al sistema de gestión de inventario <br> When reviso los niveles de inventario <br> Then puedo agregar, actualizar o eliminar elementos del inventario <br> And se reflejan los cambios en tiempo real.                                                                                                                   | -                         
| HU01    | Crear Item                                                    | Como gestor, quiero agregar un nuevo ítem al inventario.                                                                                               | Given que tengo acceso para agregar ítems al inventario <br> When ingreso los detalles del nuevo ítem (nombre, cantidad, etc.) <br> Then el ítem se añade al inventario                                                                                                                                                                          | EP04                      
| HU02    | Actualizar Item                                               | Como gestor, quiero actualizar la información de un ítem en el inventario.                                                                             | Given que tengo acceso para actualizar la información de un ítem <br> When selecciono el ítem a actualizar <br> Then puedo modificar sus detalles (cantidad, descripción, etc.) <br> And los cambios se reflejan en el inventario.                                                                                                               | EP04                      |
| HU03    | Eliminar Item                                                 | Como gestor, quiero eliminar un ítem del inventario.                                                                                                   | Given que tengo acceso para eliminar ítems del inventario <br> When selecciono el ítem a eliminar <br> Then el ítem se elimina del inventario.                                                                                                                                                                                                   | EP04                      |
| HU04    | Actualizar Item                                               | Como empleado, quiero actualizar la información de un ítem en el inventario asignado a mi tarea.                                                       | Given que mis tareas están asociadas a ítems del inventario <br> When necesito actualizar un ítem asignado <br> Then puedo modificar sus detalles <br> And los cambios se reflejan en el sistema de gestión de inventario.                                                                                                                       | EP04                      |
| EP05    | Gestionar Tareas                                              | Como Gerente, quiero gestionar las tareas asignadas a los empleados.                                                                                   | Given que tengo acceso para crear, editar, finalizar o eliminar tareas <br> When reviso la lista de tareas <br> Then puedo realizar las acciones necesarias para gestionarlas.                                                                                                                                                                   | -                         |
| HU01    | Crear Tarea                                                   | Como gerente, quiero crear una nueva tarea para asignar a un empleado.                                                                                 | Given que tengo acceso para crear nuevas tareas <br> When defino los detalles de la tarea (descripción, empleado asignado, fecha límite, etc.) <br> Then la tarea se añade a la lista de tareas.                                                                                                                                                 | EP05                      |
| HU02    | Finalizar Tarea                                               | Como empleado, quiero marcar una tarea como completada una vez que la haya finalizado.                                                                 | Given que tengo tareas asignadas <br> When termino una tarea <br> Then la marco como completada en el sistema.                                                                                                                                                                                                                                   | EP05                      |
| HU03    | Eliminar Tarea                                                | Como gerente, quiero eliminar una tarea que ya no sea necesaria.                                                                                       | Given que tengo tareas asignadas <br> When decido eliminar una tarea <br> Then la elimino del sistema.                                                                                                                                                                                                                                           | EP05                      |
| HU04    | Asignar/Editar Tarea                                          | Como gerente, quiero asignar o editar tareas para distribuir las responsabilidades entre los empleados.                                                | Given que tengo acceso para asignar o editar tareas <br> When selecciono una tarea existente <br> Then la asigno a un empleado específico o edito los detalles según sea necesario.                                                                                                                                                              | EP05                      |
| EP06    | Gestionar Mensajes                                            | Como gerente, quiero gestionar los mensajes enviados entre empleados y clientes.                                                                       | Given que tengo acceso para crear, revisar o eliminar mensajes <br> When accedo al sistema de mensajes <br> Then puedo realizar las acciones necesarias para gestionarlos.                                                                                                                                                                       | -                         |
| HU01    | Crear Mensaje                                                 | Como gerente, quiero enviar un mensaje a un cliente o empleado.                                                                                        | Given que tengo acceso para redactar mensajes <br> When redacto y envío un mensaje <br> Then el mensaje se envía con éxito.                                                                                                                                                                                                                      | EP06                      |
| HU02    | Crear Mensaje                                                 | Como empleado, quiero enviar un mensaje a un cliente o colega.                                                                                         | Given que tengo acceso para redactar mensajes <br> When redacto y envío un mensaje <br> Then el mensaje se envía con éxito.                                                                                                                                                                                                                      | EP06                      |
| HU03    | Revisar Mensaje                                               | Como gerente, quiero revisar los mensajes recibidos de clientes o empleados.                                                                           | Given que tengo acceso para revisar mensajes <br> When accedo al sistema de mensajes <br> Then puedo ver los mensajes recibidos y sus detalles.                                                                                                                                                                                                  | EP06                      |
| HU04    | Revisar Mensaje                                               | Como Empleado, quiero revisar los mensajes recibidos del gerente.                                                                                      | Given que tengo acceso para revisar mensajes <br> When accedo al sistema de mensajes <br> Then puedo ver los mensajes recibidos y sus detalles.                                                                                                                                                                                                  | EP06                      |
| HU05    | Eliminar Mensaje                                              | Como gerente, quiero eliminar un mensaje específico de la bandeja de entrada.                                                                          | Given que tengo acceso para eliminar mensajes <br> When decido eliminar un mensaje <br> Then el mensaje se elimina correctamente.                                                                                                                                                                                                                | EP06                      |
| HU06    | Eliminar Mensaje                                              | Como Empleado, quiero eliminar un mensaje específico de la bandeja de entrada.                                                                         | Given que tengo acceso para eliminar mensajes <br> When decido eliminar un mensaje <br> Then el mensaje se elimina correctamente.                                                                                                                                                                                                                | EP06                        |
| EP07    | Uso de APIs/BD                                                | Como developer de InnControl, quiero tener acceso a la información de la base de datos para poder realizar las operaciones CRUD.                       | Given que necesito realizar operaciones CRUD <br> When realizo modificaciones <br> Then se aplican los cambios en la base de datos.                                                                                                                                                                                                              |                           |
| HU01    | API de Pago                                                   | Como developer, quiero integrar la API de pago en InnControl para procesar transacciones.                                                              | Given que deseo integrar la API de pago <br> And tengo acceso a mi cuenta de empleado <br> When ingreso mis credenciales de inicio de sesión <br> Then se requiere verificación adicional por teléfono o correo.                                                                                                                                 | EP07                      |
| HU02    | API de Autenticación                                          | Como developer, quiero utilizar la API de autenticación en InnControl para gestionar el inicio de sesión de usuarios.                                  | Given que deseo utilizar la API de autenticación <br> And tengo acceso a mi cuenta de empleado <br> When ingreso mis credenciales de inicio de sesión <br> Then se solicita verificación adicional por teléfono o correo.                                                                                                                        | EP07                      |
| HU03    | API de Verificación Clave Gerente                                          | Como developer, quiero incorporar la API de verificación en InnControl para asegurar la autenticidad de los usuarios para que ingresen la clave de gerente.                                  | Given que deseo incorporar la API de verificación <br> And tengo acceso a mi cuenta de empleado <br> When ingreso mis credenciales de inicio de sesión <br> Then se solicita verificación de clave de gerente.                                                                                                                       | EP07                      |
| EP08    | Seguridad de datos                                            | Como Gerente, quiero que la informacion del hotel este asegurada asi como mi cuenta.                                                                   | Given que tengo una cuenta <br> When decido ingresar a la aplicacion <br> Then se me pide realizar una verificacion ya sea por correo o celular.                                                                                                                                                                                                 | -                         |
| HU01    | Seguridad de empleado                                         | Como Empleado, quiero ingresar a InnControl con mi cuenta de empleado                                                                                  | Given que tengo mi cuenta <br>And mi clave de gerente <br> When agrego mis datos de login <br> Then me solicitan que verifique por telefono o correo.                                                                                                                                                                                            | EP08                      |


### 3.3 **Impact Mapping.**

<img src="assets/Impact-mapping/Impact map manager.png" alt="User Manager" width="1000" height="900">

<img src="assets/Impact-mapping/impact map employee" alt="User Manager" width="1000" height="900">

### 3.4 **Product Backlog.**

https://trello.com/invite/b/VKcGEXxg/ATTI53870853c3d20c6c6e0471d9086963148FEDED5D/product-backlog

| #Orden | User Story ID | Titulo                                                        | Descripción                                                                                                                                            | Story Points (1/2/3/5/8) |
|--------|---------------|---------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------|
| 1      | EP01          | Información del producto                                      | Como visitante del sitio web, quiero obtener información relacionada al producto que se ofrece.                                                        | 3                        |
| 2      | HU01          | Conseguir información de la empresa                           | Como visitante del sitio web, quiero obtener más información sobre la empresa a cargo del producto.                                                    | 3                        |
| 3      | HU02          | Informarse sobre los beneficios del producto                  | Como visitante del sitio web, quiero informarme sobre los beneficios del producto ofrecido.                                                            | 2                        |
| 4      | HU03          | Conocer los testimonios de los clientes pasados               | Como gerente, quiero generar informes de desempeño del personal para evaluar el rendimiento de los empleados y tomar decisiones basadas en datos.      | 5                        |
| 5      | HU04          | Informarse sobre los diferentes planes de precio del producto | Como gerente, quiero visualizar la ocupación de habitaciones en tiempo real para gestionar eficazmente la disponibilidad y asignación de habitaciones. | 3                        |
| 6      | HU05          | Contactar con la empresa                                      | Como gerente, quiero ver el estado de las habitaciones para poder revisar si están listas para su uso después del proceso de limpieza.                 | 2                        |
| 7      | EP02          | Crear cuenta                                                  | Como gerente del hotel/hostal quiero crear una cuenta para utilizar InnControl (aplicación).                                                           | 5                        |
| 8      | HU01          | Crear cuenta empleado                                         | Como empleado, quiero utilizar el código de gerente para crear mi cuenta de empleado.                                                                  | 3                        |
| 9      | HU02          | Crear cuenta gerente                                          | Como gerente, quiero crear mi cuenta de gerente para poder darles mi código de gerente a mis empleados.                                                | 3                        |
| 10     | EP03          | Gestionar Habitaciones del Hotel                              | Como gerente, quiero poder revisar el estado de las habitaciones.                                                                                      | 8                        |
| 11     | HU01          | Cambiar estado de habitación                                  | Como gerente, quiero realizar un cambio al estado de la habitación.                                                                                    | 2                        |
| 12     | HU02          | Cambiar estado de habitación                                  | Como empleado, quiero cambiar el estado de la habitación de mi tarea para notificar que ya terminé mi tarea.                                           | 3                        |
| 13     | HU03          | Crear habitaciones                                            | Como gerente, quiero crear nuevas habitaciones en el sistema.                                                                                          | 5                        |
| 14     | EP04          | Gestionar Inventario                                          | Como gestor, quiero gestionar el inventario del hotel.                                                                                                 | 8                        |
| 15     | HU01          | Crear Item                                                    | Como gestor, quiero agregar un nuevo ítem al inventario.                                                                                               | 3                        |
| 16     | HU02          | Actualizar Item                                               | Como gestor, quiero actualizar la información de un ítem en el inventario.                                                                             | 3                        |
| 17     | HU03          | Eliminar Item                                                 | Como gestor, quiero eliminar un ítem del inventario.                                                                                                   | 2                        |
| 18     | HU04          | Actualizar Item                                               | Como empleado, quiero actualizar la información de un ítem en el inventario asignado a mi tarea.                                                       | 3                        |
| 19     | EP05          | Gestionar Tareas                                              | Como Gerente, quiero gestionar las tareas asignadas a los empleados.                                                                                   | 8                        |
| 20     | HU01          | Crear Tarea                                                   | Como gerente, quiero crear una nueva tarea para asignar a un empleado.                                                                                 | 3                        |
| 21     | HU02          | Finalizar Tarea                                               | Como empleado, quiero marcar una tarea como completada una vez que la haya finalizado.                                                                 | 2                        |
| 22     | HU03          | Eliminar Tarea                                                | Como gerente, quiero eliminar una tarea que ya no sea necesaria.                                                                                       | 2                        |
| 23     | HU04          | Asignar/Editar Tarea                                          | Como gerente, quiero asignar o editar tareas para distribuir las responsabilidades entre los empleados.                                                | 5                        |
| 24     | EP06          | Gestionar Mensajes                                            | Como gerente, quiero gestionar los mensajes enviados entre empleados y clientes.                                                                       | 8                        |
| 25     | HU01          | Crear Mensaje                                                 | Como gerente, quiero enviar un mensaje a un cliente o empleado.                                                                                        | 3                        |
| 26     | HU02          | Crear Mensaje                                                 | Como empleado, quiero enviar un mensaje a un cliente o colega.                                                                                         | 3                        |
| 27     | HU03          | Revisar Mensaje                                               | Como gerente, quiero revisar los mensajes recibidos de clientes o empleados.                                                                           | 2                        |
| 28     | HU04          | Revisar Mensaje                                               | Como Empleado, quiero revisar los mensajes recibidos del gerente.                                                                                      | 2                        |
| 29     | HU05          | Eliminar Mensaje                                              | Como gerente, quiero eliminar un mensaje específico de la bandeja de entrada.                                                                          | 2                        |
| 30     | HU06          | Eliminar Mensaje                                              | Como Empleado, quiero eliminar un mensaje específico de la bandeja de entrada.                                                                         | 2                        |
| 31     | EP07          | Uso de APIs/BD                                                | Como developer de InnControl, quiero tener acceso a la información de la base de datos para realizar operaciones CRUD.                                 | 5                        |
| 32     | HU01          | API de Pago                                                   | Como developer, quiero integrar la API de pago en InnControl para procesar transacciones.                                                              | 3                        |
| 33     | HU02          | API de Autenticación                                          | Como developer, quiero utilizar la API de autenticación en InnControl para gestionar el inicio de sesión de usuarios.                                  | 3                        |
| 34     | HU03          | API de Verificación                                           | Como developer, quiero incorporar la API de verificación en InnControl para asegurar la autenticidad de los usuarios por medio de la clave de gerente.                                  | 5                        |
| 35     | EP08          | Seguridad de datos                                            | Como Gerente, quiero que la información del hotel esté asegurada así como mi cuenta.                                                                   | 5                        |
| 36     | HU01          | Seguridad de empleado                                         | Como Empleado, quiero ingresar a InnControl con mi cuenta de empleado.                                                                                 | 3                        |


