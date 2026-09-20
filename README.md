<div align = "center">
 <h1>Universidad Peruana de Ciencias Aplicadas</h1>
 <img style="height: 200px" src="assets/chapter01/upc.png">
  <h2>Carrera: Ingeniería de Software</h2>
  <h2>Periodo: 2026-20</h2>
<br>
  <h2>Curso: Desarolllo de soluciones IOT</h2>
  <h2>Codigo del Curso: 1ASI0572</h2>
  <h2>NRC: 8740</h2>
  <h2>Profesor: David Carlos Olivera</h2>
<br>
 <h1>Informe del Avance 1</h1>
  <h2>Startup: Frostshield </h2>
  <h2>Producto: IceTrack </h2>
<br>
  <h2>Integrantes</h2>
 
<div align="center">
 
| <div style="width:500px">Alumno</div> | <div style="width:200px">Código</div> |
| :-----------------------------------: | :-----------------------------------: |
|  Arostegui Alzamora, Cesar Augusto    |  U202114548                           |
|  Cuentas Peña, Joaquin Alberto        |  U20201f788                           |
|  Guillen Galindo, Julio Adolfo        |  U20241a352                           |
|  Jiménez Guerra, Gianmarco Fabian     |  U202123843                           |
|  Tenorio Medina, Piero Francesco      |  U202318731                           |
|  Quijada Magro, Jeremy Alexander      |  U202219657                           |
|  Fajardo Monrroy, Walter Luis         |  u202221632                           |

</div>

<br>

   <h3>Septiembre 2026</h3>

</div>

## Registro de Versiones del Informe

<div align="center">
 
| Versión | Fecha      | Autor                 | Descripción de modificación                                                       |
| :-----: | :--------: | :-------------------: | :-------------------------------------------------------------------------------- |
| 1.1     | 15/04/2026 | Jeremy Quijada        | Desarrollo del Capitulo I Enfocado en la solución IOT                             |
| 1.1     | 11/09/2026 | Walter Fajardo        | Desarrollo de las partes 2.3, 2.3.1, 2.3.2, 2.3.3                                 |
| 1.2     | 14/09/2026 | Piero Tenorio         | Primera Versión del User Flow Diagram y el Bounded Context Canvas                 |
| 1.3     | 19/09/2026 | Piero Tenorio         | Versión Actualizada del Bounded Context Canvas y User Flow                        |
| 1.4     | 19/09/2026 | Gianmarco Jiménez     | Versión Actualizada del Big Picture Event Storming con todos los Bounded Contexts |
| 1.5     | 19/09/2026 | Gianmarco Jiménez     | Versión Actualizada del Ubiquitous Language                                       |
| 1.6     | 20/09/2026 | Cesar Arostegui       | Desarrollo del Software Architecture y Tactical-Level Domain-Driven Design        |
| 1.7     | 20/09/2026 | Joaquin Cuentas       | Desarrollo del Software Architecture y C4 diagrams       |


</div>

## Project Report Collaboration Insights

- **URL de la organización del proyecto:** 
  https://github.com/IceTrack-IoT/Report-IceTrack_Iot
  <br>

- **URL del repositorio del reporte:** 
  https://github.com/IceTrack-IoT/Report-IceTrack
  <br>
  
- **URL del repositorio de la Landing Page:**
  https://github.com/IceTrack-IoT/Landing-Page-IceTrack
  <br>

- **URL del repositorio del Frontend:** 
  https://github.com/IceTrack-IoT/Frontend-IceTrack
  <br>

- **URL del repositorio del Backend:** 
  https://github.com/IceTrack-IoT/Platform-IceTrack

## Contenido

- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process.](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo.](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
    - [2.4.1. Identity and Access Management](#241-identity-and-access-management)
    - [2.4.2. Asset Management](#242-asset-management)
    - [2.4.3. Monitoring](#243-monitoring)
    - [2.4.4. Service Request Management](#244-service-request-management)
    - [2.4.5. Technician Management](#245-technician-management)
    - [2.4.6. Notifications](#246-notifications)
    - [2.4.7. Feedback](#247-feedback)
    - [2.4.8. Dashboard](#248-dashboard)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories.](#31-user-stories)
  - [3.2. Impact Mapping.](#32-impact-mapping)
  - [3.3. Product Backlog.](#33-product-backlog)

- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1. Design-Level EventStorming](#411-design-level-eventstorming)
      - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
      - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
      - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      - [4.1.3.3. Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
      - [4.1.3.4. Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
    - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
      - [4.2.1. Bounded Context: Identity and Access Management](#421-bounded-context-identity-and-access-management)
        - [4.2.1.1. Domain Layer](#4211-domain-layer)
        - [4.2.1.2. Interface Layer](#4212-interface-layer)
        - [4.2.1.3. Application Layer](#4213-application-layer)
        - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
        - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
          - [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
          - [4.2.1.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)
      - [4.2.2. Bounded Context: Profiles and Preferences Management](#422-bounded-context-profiles-and-preferences-management)
        - [4.2.2.1. Domain Layer](#4221-domain-layer)
        - [4.2.2.2. Interface Layer](#4222-interface-layer)
        - [4.2.2.3. Application Layer](#4223-application-layer)
        - [4.2.2.4. Infrastructure Layer](#4224-infrastructure-layer)
        - [4.2.2.5. Bounded Context Software Architecture Component Level Diagrams](#4225-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.2.6. Bounded Context Software Architecture Code Level Diagrams](#4226-bounded-context-software-architecture-code-level-diagrams)
          - [4.2.2.6.1. Bounded Context Domain Layer Class Diagrams](#42261-bounded-context-domain-layer-class-diagrams)
          - [4.2.2.6.2. Bounded Context Database Design Diagram](#42262-bounded-context-database-design-diagram)
      - [4.2.3. Bounded Context: Monitoring and Alerting](#423-bounded-context-monitoring-and-alerting) 
        - [4.2.3.1. Domain Layer](#4231-domain-layer)
        - [4.2.3.2. Interface Layer](#4232-interface-layer)
        - [4.2.3.3. Application Layer](#4233-application-layer)
        - [4.2.3.4. Infrastructure Layer](#4234-infrastructure-layer)
        - [4.2.3.5. Bounded Context Software Architecture Component Level Diagrams](#4235-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.3.6. Bounded Context Software Architecture Code Level Diagrams](#4236-bounded-context-software-architecture-code-level-diagrams)
          - [4.2.3.6.1. Bounded Context Domain Layer Class Diagrams](#42361-bounded-context-domain-layer-class-diagrams)
          - [4.2.3.6.2. Bounded Context Database Design Diagram](#42362-bounded-context-database-design-diagram)
      - [4.2.4. Bounded Context: Assets Management](#424-bounded-context-assets-management)
        - [4.2.4.1. Domain Layer](#4241-domain-layer)
        - [4.2.4.2. Interface Layer](#4242-interface-layer)
        - [4.2.4.3. Application Layer](#4243-application-layer)
        - [4.2.4.4. Infrastructure Layer](#4244-infrastructure-layer)
        - [4.2.4.5. Bounded Context Software Architecture Component Level Diagrams](#4245-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.4.6. Bounded Context Software Architecture Code Level Diagrams](#4246-bounded-context-software-architecture-code-level-diagrams)
          - [4.2.4.6.1. Bounded Context Domain Layer Class Diagrams](#42461-bounded-context-domain-layer-class-diagrams)
          - [4.2.4.6.2. Bounded Context Database Design Diagram](#42462-bounded-context-database-design-diagram)
      - [4.2.5. Bounded Context: Device Management](#425-bounded-context-device-management)
        - [4.2.5.1. Domain Layer](#4251-domain-layer)
        - [4.2.5.2. Interface Layer](#4252-interface-layer)
        - [4.2.5.3. Application Layer](#4253-application-layer)
        - [4.2.5.4. Infrastructure Layer](#4254-infrastructure-layer)
        - [4.2.5.5. Bounded Context Software Architecture Component Level Diagrams](#4255-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.5.6. Bounded Context Software Architecture Code Level Diagrams](#4256-bounded-context-software-architecture-code-level-diagrams)
          - [4.2.5.6.1. Bounded Context Domain Layer Class Diagrams](#42561-bounded-context-domain-layer-class-diagrams)
          - [4.2.5.6.2. Bounded Context Database Design Diagram](#42562-bounded-context-database-design-diagram)
      - [4.2.6. Bounded Context: Service Request Management](#426-bounded-context-service-request-management)
        - [4.2.6.1. Domain Layer](#4261-domain-layer)
        - [4.2.6.2. Interface Layer](#4262-interface-layer)
        - [4.2.6.3. Application Layer](#4263-application-layer)     
        - [4.2.6.4. Infrastructure Layer](#4264-infrastructure-layer)
        - [4.2.6.5. Bounded Context Software Architecture Component Level Diagrams](#4265-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.6.6. Bounded Context Software Architecture Code Level Diagrams](#4266-bounded-context-software-architecture-code-level-diagrams)
          - [4.2.6.6.1. Bounded Context Domain Layer Class Diagrams](#42661-bounded-context-domain-layer-class-diagrams)
          - [4.2.6.6.2. Bounded Context Database Design Diagram](#42662-bounded-context-database-design-diagram)
      - [4.2.7. Bounded Context: Notification Management](#427-bounded-context-notification-management)
        - [4.2.7.1. Domain Layer](#4271-domain-layer)     
        - [4.2.7.2. Interface Layer](#4272-interface-layer)
        - [4.2.7.3. Application Layer](#4273-application-layer)
        - [4.2.7.4. Infrastructure Layer](#4274-infrastructure-layer)
        - [4.2.7.5. Bounded Context Software Architecture Component Level Diagrams](#4275-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.7.6. Bounded Context Software Architecture Code Level Diagrams](#4276-bounded-context-software-architecture-code-level-diagrams)
          - [4.2.7.6.1. Bounded Context Domain Layer Class Diagrams](#42761-bounded-context-domain-layer-class-diagrams)
          - [4.2.7.6.2. Bounded Context Database Design Diagram](#42762-bounded-context-database-design-diagram)
      - [4.2.8. Bounded Context: Reporting and Analytics](#428-bounded-context-reporting-and-analytics)
        - [4.2.8.1. Domain Layer](#4281-domain-layer)
        - [4.2.8.2. Interface Layer](#4282-interface-layer)
        - [4.2.8.3. Application Layer](#4283-application-layer)
        - [4.2.8.4. Infrastructure Layer](#4284-infrastructure-layer)
        - [4.2.8.5. Bounded Context Software Architecture Component Level Diagrams](#4285-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.8.6. Bounded Context Software Architecture Code Level Diagrams](#4286-bounded-context-software-architecture-code-level-diagrams)
          - [4.2.8.6.1. Bounded Context Domain Layer Class Diagrams](#42861-bounded-context-domain-layer-class-diagrams)
          - [4.2.8.6.2. Bounded Context Database Design Diagram](#42862-bounded-context-database-design-diagram)


- [Conclusiones](#conclusiones)
  - [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
  - [Recursos y enlaces del proyecto](#recursos-y-enlaces-del-proyecto)

## Student Outcome
El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 5**

**Criterio**: *La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 5.

| Criterio específico | Acciones realizadas | Conclusiones |
| :------------------ | :------------------ | :----------- |
| Trabaja en equipo para proporcionar liderazgo en forma conjunta | **Piero Francesco Tenorio Medina** <br> **AV1**: Dentro de esta entrega se desarrolló la refactorización del curso en términos de la solución implementada. Se informó a cada integrante sobre posibles mejoras a los diagramas como tambien de los servicios que se implementarán dentro del proyecto.<br>**Gianmarco Fabian Jiménez Guerra** <br> **AV1**: Dentro de esta entrega pude contribuir en el trabajo en equipo definiendo mejor los bounded contexts y creando el Big Picture Event Storming de cada uno. Adicionalmente, como grupo, nos pudimos dividir la asignación de entrevistas.<br>**Cesar Augusto Arostegui Alzamora** <br> **AV1**: Dentro de esta entrega asumí el liderazgo del diseño de la arquitectura de software y del diseño táctico del dominio. Definí los diagramas de paisaje del sistema, contexto, contenedores y despliegue. Detallé cada contexto en sus capas de dominio, interfaz, aplicación e infraestructura. Elaboré los diagramas de componentes, clases y base de datos. Coordiné con el equipo la alineación entre contextos y la protección de la integración. Orienté a compañeros en decisiones de arquitectura para mantener coherencia en el modelo. <br> **Julio Adolfo Guillen Galindo** <br> **AV1**: Dentro de esta entrega contribuí en el desarrollo de los competidores y definiendo estrategias y tácticas. Asimismo, participé en el desarrollo de las entrevistas mediante su diseño, registro y posterior análisis. Coordiné estas actividades con los demás integrantes para asegurar que la información obtenida estuviera alineada con los segmentos objetivo y sirviera como base para la definición de los requerimientos de la solución.<br>**Joaquin Alberto Cuentas Peña** <br> **AV1**: Dentro de esta entrega contribuí en el desarrollo de los diagramas C4, en el nivel de components y deploy. Coordiné estas actividades con los demás integrantes para asegurar que la arquitectura del futuro proyecto tenga una base sólida sobre la cual desarrollarla.<br>**Walter Luis Fajardo Monrroy** <br> **AV1**: Dentro de esta entrega asumí el liderazgo en la fase de análisis de usuarios (Needfinding). A partir de la información recopilada por el equipo, dirigí la creación de los User Personas, el User Task Matrix y el User Journey Mapping. Coordiné constantemente con mis compañeros para asegurar que los perfiles desarrollados y los puntos de dolor mapeados reflejaran fielmente la problemática de la cadena de frío, guiando así la visión del equipo hacia las necesidades reales del mercado. | **AV1**: Se logro liderazgo conjunto al distribuir responsabilidades según fortalezas y alinear decisiones de arquitectura, eventos y flujos entre contextos. La integración de aportes permitió cerrar y con coherencia técnica. |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | **Piero Francesco Tenorio Medina** <br> **AV1**: Dentro de esta entrega se estableció metas para algunos de los integrantes del grupo que se vean implicados en ciertos puntos del trabajo en los que me veía implicado. <br> **Gianmarco Fabian Jiméenz Guerra** <br> **AV1**: Para esta entrega cada integrante del grupo contó con una tarea y una fecha de entrega. En mi caso, mi tarea era la de crear el Big Picture Event Storming basado en la lógica del prorgama y los flujos y tenía que conseguir una entrevista para el segmento objetivo número 2. Todo este aporte dentro del plazo establecido.<br>**Cesar Augusto Arostegui Alzamora** <br> **AV1**: Planifiqué el trabajo por bloques de avance y mantuve comunicación constante con el equipo para validar dependencias entre contextos. Aporté en un entorno de respeto e inclusión, atendiendo sugerencias y compartiendo avances de forma clara. Así contribuí al cumplimiento de los objetivos comunes del informe. <br>**Julio Adolfo Guillen Galindo** <br> **AV1**: Para esta entrega organicé la información recopilada, establecí los aspectos que debían analizarse para cada competidor y coordiné el diseño y registro de las entrevistas con los segmentos objetivo. Finalmente, analicé los resultados obtenidos y compartí los principales hallazgos con el equipo para contribuir al cumplimiento de los objetivos establecidos para el avance.<br>**Joaquin Alberto Cuentas Peña** <br> **AV1**: Dentro de esta entrega se estableció metas para el desarrollo del proyecto. En primer lugar la para la versión web y en segundo lugar para la versión móvil.<br>**Walter Luis Fajardo Monrroy** <br> **AV1**: Para cumplir con esta sección del informe, planifiqué el desarrollo de los artefactos de Needfinding estableciendo metas y fechas internas. Compartí los borradores de los arquetipos y mapas de experiencia con el equipo, fomentando un espacio inclusivo donde todos pudieron brindar retroalimentación o sugerir cambios. Finalmente, entregué el User Task Matrix y los diagramas pulidos dentro de los plazos establecidos para no retrasar la fase de ideación e Impact Mapping. | **AV1**: Se creo un entorno colaborativo e inclusivo con metas claras, tareas asignadas y fechas de entrega cumplidas. La comunicación constante y el respeto por los avances de cada integrante permitieron cumplir los objetivos del avance y sentar bases sólidas para el proyecto. |

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Nuestra startup ofrece una plataforma de Inteligencia de Datos orientada a optimizar la gestión, monitoreo y mantenimiento de equipos de refrigeración en negocios que dependen de la cadena de frío. La plataforma permite recopilar y centralizar información proveniente de sensores IoT instalados en los equipos, así como integrarse con los controladores y sistemas de monitoreo existentes en los negocios, transformando los datos obtenidos en información útil para la toma de decisiones.

Las funcionalidades clave de la plataforma incluyen el monitoreo en tiempo real de variables como temperatura, consumo energético y tiempo de funcionamiento de los equipos. Además, genera alertas automáticas ante anomalías o posibles fallos, ofrece informes técnicos detallados, historiales de rendimiento y permite gestionar y programar mantenimientos de manera inteligente. Estas herramientas permiten a empresas, técnicos y proveedores supervisar continuamente el estado de los equipos, mejorar la eficiencia operativa, prevenir pérdidas ocasionadas por fallos inesperados y mantener un registro completo de su funcionamiento y mantenimiento.

**Misión:** Ofrecer una solución tecnológica inteligente que permita a las empresas proteger su inventario y optimizar la gestión, monitoreo y mantenimiento de sus equipos de refrigeración. Asimismo, proporcionar herramientas especializadas que faciliten el trabajo de técnicos y proveedores, mejorando su eficiencia y capacidad de respuesta.

**Visión:** Ser la empresa líder en gestión, monitoreo y mantenimiento inteligente de equipos de refrigeración en el mercado peruano, comenzando por consolidar nuestra presencia y posicionamiento en Lima.


### 1.1.2. Perfiles de integrantes del equipo

<div align="center">

| **Integrante**            | **Quijada Magro Jeremy Alexander**        									                   |
| :------------------------ | :----------------------------------------------------------------------------- |
| **Código del Estudiante** | u202219657                                   									            	   |
| **Carrera**               | Ingeniería de Software                       									                 |
| **Descripción**           | Mi nombre es Jeremy Alexander Quijada Magro, tengo 21 años y curso la carrera de Ingeniería de Software. Me considero una persona ordenada y responsable. Me centro en conocmiento en C#, Kva y el uso del front con Vue, Angular y React. En este proyecto apoyaré con todos los conocimientos que he adquirido en los cursos pasados con la meta de aprender a realizar pruebas de calidad sobre este proyecto  										                                                                            		|
| **Foto**                  | <img src="assets/chapter01/Jeremy.jpeg" alt="Jeremy" width="150" height="200"> |

---

| **Integrante**            | **Guillen Galindo Julio Adolfo**                                     						 |
| :------------------------ | :------------------------------------------------------------------------------- |
| **Código del Estudiante** | u20241a352                       						                      				  	   |
| **Carrera**               | Ingeniería de Software                                                           |
| **Descripción**           | Actualmente curso la carrera de Ingeniería de Software en la UPC. Me considero una persona discreta, pero responsable y enfocada en cumplir los proyectos dentro de los plazos establecidos. Poseo conocimientos en C++ y Python; disfruto trabajar en equipo cuando existe colaboración y apoyo mutuo. Además, me motiva aplicar lo aprendido para afrontar los desafíos que puedan surgir en los próximos ciclos.                                                                          |
| **Foto**                  | <img src="assets/chapter01/julio_logo.jpg" alt="Julio" width="200" height="200"> |

---

| **Integrante**            | **Gianmarco Fabian Jiménez Guerra**                                        	            |
| :------------------------ | :-------------------------------------------------------------------------------------- |
| **Código del Estudiante** | u202123843																	                                            |
| **Carrera**               | Ingeniería de Software														                                      |
| **Descripción**           | Estudiante de Ingeniería de Software con conocimiento sobre desarrollo de aplicaciones web y análisis de datos. Estoy motivado por aprender nuevos temas relacionados a Software y por trabajar en equipo. Considero que mi conocimiento sobre las tecnologías: Java, Python, Angular y C# me permitirá desempeñarme de manera correcta para apoyar en este proyecto.|
| **Foto**                  | <img src="assets/chapter01/gianmarco.png" alt="Gianmarco" width="200" height="200">     |

---

| **Integrante**            | **Piero Francesco Tenorio Medina**                                        	            |
| :------------------------ | :-------------------------------------------------------------------------------------- |
| **Código del Estudiante** | u202318731																	                                            |
| **Carrera**               | Ingeniería de Software														                                      |
| **Descripción**           | Estudiante de la carrera de Ingeniería de Software con conocimiento sobre desarrollo de aplicaciones web, especialmente en el entorno Backend. Tengo conocimientos sobre las tecnologías: Java,Vue, Angular y C#. Como integrante de un equipo, me gusta trabajar y comunicarme con los integrantes para poder cumplir los objetivos del proyecto. Estoy abierto a aprender nuevas herramientas que me permitan desempeñar mejor dentro de mi carrera.|
| **Foto**                  | <img src="assets/chapter01/piero.png" alt="Piero" height="200">     |

---

| **Integrante**            | **Cesar Augusto Arostegui Alzamora**                                  |
| :------------------------ | :----------------------------------------------------------------------------------- |
| **Código del Estudiante** | u202114548                                                                           |
| **Carrera**               | Ingeniería de Software                                                               |
| **Descripción**           | - Estudiante de la carrera de Ingeniería de Software, actualmente tengo 22 años. Mi lenguaje de programación más utilizado y favorito es TypeScript. Actualmente me encuentro desarrollando habilidades en áreas como DevOps y frameworks de desarrollo móvil. También me interesan las tecnologías de inteligencia artificial y su aplicación en soluciones empresariales.                                                            |
| **Foto**                  | <img src="assets/chapter01/cesar.png" alt="Cesar" height="200">                      |

---

| **Integrante**            | **Joaquin Alberto Cuentas Peña**                                                    |
| :------------------------ | :----------------------------------------------------------------------------------- |
| **Código del Estudiante** | u20201f788                                                                          |
| **Carrera**               | Ingeniería de Software                                                            |
| **Descripción**           | Soy estudiante de la carrera de ingeniería de software con afición orientada al apartado backend y microcontroladores. Cuento con experiencia desarrollando aplicaciones web, móviles y automatizaciones. Espero ampliar mis conocimientos para añadir los microservicios a mi abanico de conocimientos.
| **Foto**                  | <img src="assets/chapter01/fotojoaquin.jpg" alt="Joaquin" height="200">  |

</div>

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

| **5W & 2H**                                                 | **Descripcion**                                                                 |
| :---------------------------------------------------------- | :------------------------------------------------------------------------------ |
| **What: ¿Cuál es el problema?**                 			      | Los negocios que dependen de la cadena de frío enfrentan vulnerabilidades operativas críticas debido a la falta de telemetría y control en tiempo real. Esta carencia provoca fallas mecánicas inesperadas, incrementos dramáticos en el consumo eléctrico —la refrigeración puede representar entre el 30% y el 60% del gasto energético total en plantas de procesamiento (Dawsongroup, 2024)— y un mantenimiento puramente reactivo. A nivel nacional, el deficiente manejo de la cadena de frío es responsable de la pérdida de más del 33% de los alimentos producidos (FAO, citado en Agraria, 2019), causando un severo impacto financiero. 	   	            |
| **When: ¿Cuándo sucede este problema?**         			      | Es una amenaza constante durante la operación 24/7 de las cámaras térmicas. El riesgo se agudiza en horarios no laborables, durante picos de producción estacional, o frente a anomalías climáticas como las olas de calor advertidas por entidades como Osinergmin, que elevan la exigencia térmica. La situación se torna crítica ante la ausencia de un monitoreo automatizado que notifique desviaciones de temperatura (ej. quiebres de los -18°C en congelación) antes de que el deterioro químico y biológico del producto sea irreversible (Zabarburu, 2026).					                 |
| **Where: ¿Dónde se produce este suceso?**      			        | El problema tiene alcance nacional en el Perú, impactando a supermercados, laboratorios y plantas agroindustriales. No obstante, el impacto es crítico en Lima, el principal nodo logístico del país. La limitada infraestructura refrigerada y las brechas logísticas en estas zonas incrementan el riesgo en la cadena de suministro alimentaria y médica (Agroperú, 2026). Además, afecta directamente a las empresas contratistas de mantenimiento que operan en diversas sedes sin capacidad de gestión centralizada de los equipos.           |
| **Who: ¿Quiénes están involucrados?**          			        | Involucra principalmente a dos actores: Los dueños y operadores comerciales (retail, agroexportación, clínicas) que asumen directamente los costos de mermas, sobrecostos energéticos y daños reputacionales. Las empresas de servicio técnico, que operan en desventaja al tener que atender emergencias sin datos de diagnóstico preventivo, lo que reduce su eficiencia operativa y aumenta los tiempos de respuesta (Seguas, 2024). 	  |
| **Why: ¿Cuál es la causa del problema?**        			      | La causa raíz es la falta de digitalización y la fragmentación de datos técnicos en "silos de información". Los parámetros vitales operan atrapados en controladores electrónicos aislados que no transmiten información a un sistema en la nube. Esta falta de visibilidad en línea impide detectar ineficiencias tempranas —como aislamientos defectuosos o desgaste de compresores— obligando a una gestión reactiva que actúa solo cuando el componente ya falló o el producto se dañó (Dawsongroup, 2024).  |
| **How: ¿Qué llevó a la persona a llegar a esta situación?** | La situación actual deriva de una histórica falta de inversión tecnológica y dependencia de esquemas de mantenimiento correctivo ("apagar incendios"). En lugar de adoptar plataformas IoT para el monitoreo, las organizaciones han operado a ciegas, esperando que el problema se manifieste físicamente. Este enfoque ha prolongado un ciclo de ineficiencias, elevados Costos Totales de Propiedad (TCO) y un desgaste acelerado de infraestructura que una estrategia de mantenimiento predictivo habría evitado.    |
| **How Much: ¿Cuánto es el impacto financiero?** 			      | El impacto económico es devastador y cuantificable. A nivel nacional, las deficiencias y fallas en la gestión de la cadena de frío provocan que el Perú pierda más del 33% de los alimentos que produce anualmente (Agraria.pe, 2019). Además, en sectores críticos como el de la salud, una sola interrupción no detectada en los sistemas de refrigeración ha generado pérdidas de hasta S/ 14 millones por lotes malogrados debido a la ruptura térmica (La Noticia Perú, 2023). A estos valores directos se suma el sobreconsumo eléctrico constante y los altos costos del mantenimiento correctivo de emergencia. |

### 1.2.2. Lean UX Process.

#### 1.2.2.1. Lean UX Problem Statements.

El estado actual del sector de la refrigeración comercial se caracteriza por una gestión principalmente reactiva de los equipos, especialmente en negocios que dependen de la cadena de frío, como restaurantes, supermercados y laboratorios, así como en técnicos especializados y proveedores de equipos que brindan servicios de mantenimiento. Estos actores enfrentan problemas relacionados con fallas inesperadas, pérdidas de inventario, consumo energético elevado, dificultad para realizar un seguimiento continuo del estado de los equipos y falta de información centralizada para gestionar los servicios de mantenimiento.

Aunque algunos negocios cuentan con sensores, controladores o sistemas de monitoreo, la información suele encontrarse aislada entre diferentes equipos, fabricantes o herramientas, dificultando su interpretación y aprovechamiento para la toma de decisiones. Asimismo, los técnicos y proveedores requieren información histórica y herramientas que les permitan organizar sus actividades, diagnosticar problemas y brindar un servicio más eficiente.

Lo que las soluciones existentes no abordan completamente es la necesidad de contar con una plataforma especializada que centralice la información de los equipos de refrigeración y, al mismo tiempo, permita obtener datos directamente mediante sensores IoT, independientemente de los sistemas existentes en el negocio. Este vacío limita la capacidad de los usuarios para detectar anomalías oportunamente, anticiparse a posibles fallas, analizar el rendimiento de los equipos y mantener un historial unificado de su funcionamiento y mantenimiento.

Nuestro producto, IceTrack, abordará este vacío mediante una plataforma de Inteligencia de Datos especializada en equipos de refrigeración. La solución permitirá conectar sensores IoT para recopilar información en tiempo real, integrar datos provenientes de controladores y sistemas de monitoreo existentes, centralizar dicha información y transformarla en indicadores, alertas y recomendaciones útiles. Además, proporcionará herramientas para la gestión de mantenimientos, historial técnico, seguimiento de servicios y análisis del rendimiento de los equipos.

Nuestro enfoque inicial estará dirigido a negocios de Lima que dependen de la cadena de frío y necesitan reducir los riesgos asociados a fallas en sus equipos, así como a técnicos y proveedores de servicios de refrigeración que buscan mejorar la gestión y eficiencia de sus operaciones.

Sabremos que tendremos éxito cuando los negocios utilicen de manera recurrente el monitoreo de sus equipos, respondan oportunamente a las alertas generadas por la plataforma, reduzcan las fallas críticas y las pérdidas asociadas a problemas de refrigeración, y mejoren su eficiencia energética. Asimismo, consideraremos exitoso el producto cuando técnicos y proveedores utilicen la plataforma para gestionar sus servicios, reduzcan sus tiempos de atención y mantengan una mayor continuidad en sus relaciones con los clientes.

#### 1.2.2.2. Lean UX Assumptions.

##### Business Assumptions

- Creemos que existe una oportunidad de mercado para una solución especializada en la gestión y monitoreo inteligente de equipos de refrigeración.
- Creemos que los negocios que dependen de la cadena de frío están dispuestos a invertir en una solución que permita reducir pérdidas y mejorar el control de sus equipos..
- Creemos que la incorporación de sensores IoT como parte de la solución permitirá diferenciarnos de las plataformas genéricas de gestión de mantenimiento.
- Creemos que establecer alianzas con proveedores y técnicos especializados facilitará la entrada de IceTrack al mercado.
- Creemos que iniciar operaciones en Lima permitirá validar el modelo de negocio antes de ampliar la solución a otras regiones del Perú.

##### Business Outcome Assumptions

- Creemos que la adopción de IceTrack permitirá reducir las pérdidas económicas ocasionadas por fallas en los sistemas de refrigeración.
- Creemos que el monitoreo continuo permitirá disminuir la frecuencia y el impacto de fallas críticas.
- Creemos que la identificación de ineficiencias permitirá reducir el consumo energético de los equipos monitoreados.
- Creemos que la gestión centralizada permitirá reducir los costos asociados al mantenimiento correctivo y las reparaciones de emergencia.
- Creemos que la mejora en la gestión de servicios permitirá incrementar la productividad de los técnicos y proveedores.
- Creemos que una experiencia de servicio más transparente y proactiva permitirá aumentar la satisfacción y retención de los clientes.

##### User Assumptions

- Creemos que los negocios que dependen de la cadena de frío serán usuarios principales de la plataforma y utilizarán el sistema para supervisar el estado de sus equipos.
- Creemos que los responsables de los negocios necesitarán visualizar información de temperatura, consumo energético, tiempo de funcionamiento y alertas.
- Creemos que los técnicos especializados en refrigeración utilizarán la plataforma para gestionar servicios, consultar información de los equipos y revisar su historial técnico.
- Creemos que los proveedores de equipos utilizarán la plataforma como una herramienta para mejorar y diferenciar sus servicios postventa.
- Creemos que algunos usuarios tendrán conocimientos tecnológicos limitados, por lo que necesitarán una interfaz sencilla y procesos de configuración intuitivos.
- Creemos que los usuarios requerirán acceso a la plataforma desde diferentes ubicaciones y dispositivos para supervisar equipos y gestionar servicios.

##### User Outcome and Benefit Assumptions

- Creemos que los negocios desean conocer en tiempo real el estado de sus equipos para detectar problemas antes de que ocasionen pérdidas.
- Creemos que los negocios desean recibir alertas oportunas que les permitan actuar ante variaciones anormales de temperatura u otras condiciones críticas.
- Creemos que los responsables de los negocios desean reducir sus costos operativos mediante un menor consumo energético y una mejor planificación del mantenimiento.
- Creemos que los técnicos desean disponer de información histórica y actualizada de cada equipo para diagnosticar problemas y realizar servicios con mayor eficiencia.
- Creemos que los técnicos desean organizar sus tareas, visitas y mantenimientos desde una única plataforma.
- Creemos que los proveedores desean contar con información centralizada que les permita ofrecer un servicio postventa más rápido, transparente y eficiente.
- Creemos que todos los usuarios desean contar con un historial confiable de los equipos para facilitar el seguimiento de su rendimiento y mantenimiento.

##### Feature Assumptions

- Creemos que la conexión de sensores IoT a los equipos permitirá recopilar automáticamente datos de temperatura y otras variables relevantes en tiempo real.
- Creemos que la integración con controladores y sistemas de monitoreo existentes permitirá centralizar información sin depender exclusivamente de una única fuente de datos.
- Creemos que un sistema de monitoreo en tiempo real permitirá a los usuarios visualizar el estado actual de sus equipos desde la plataforma.
- Creemos que un sistema de alertas automáticas permitirá notificar oportunamente a los usuarios cuando se detecten valores anormales o condiciones que puedan indicar una falla.
- Creemos que el historial técnico de cada equipo permitirá a los usuarios consultar su comportamiento, incidencias y mantenimientos anteriores para facilitar la toma de decisiones.
- Creemos que un módulo de gestión y programación de mantenimientos permitirá a técnicos y proveedores organizar sus actividades y reducir mantenimientos reactivos.
- Creemos que los informes de rendimiento permitirán identificar tendencias, anomalías e ineficiencias en los equipos.
- Creemos que el análisis de consumo energético permitirá identificar oportunidades para reducir el uso innecesario de energía.
- Creemos que una interfaz web y móvil permitirá a los usuarios consultar información y gestionar sus actividades tanto desde sus oficinas como desde el campo.

#### 1.2.2.3. Lean UX Hypothesis Statements.

**Hipótesis 1: Conexión mediante sensores IoT**

Creemos que lograremos aumentar la adopción y el valor percibido de IceTrack al proporcionar datos confiables y continuos sobre los equipos de refrigeración.

Si los responsables de negocios que dependen de la cadena de frío y los técnicos especializados obtienen información automática y actualizada sobre el estado de los equipos con la conexión de sensores IoT que recopilen datos directamente desde los sistemas de refrigeración.

Sabremos que hemos tenido éxito cuando los usuarios mantengan sus equipos conectados y consulten regularmente los datos recopilados por los sensores para supervisar su funcionamiento.

**Hipótesis 2: Monitoreo en tiempo real**

Creemos que lograremos reducir la ocurrencia e impacto de fallas críticas relacionadas con los equipos de refrigeración.

Si los responsables de negocios que dependen de la cadena de frío pueden conocer en tiempo real el estado y las principales variables de funcionamiento de sus equipos con un módulo de monitoreo en tiempo real conectado a sensores IoT y otras fuentes de datos.

Sabremos que hemos tenido éxito cuando los usuarios consulten regularmente el estado de sus equipos y detecten anomalías antes de que generen una falla crítica o una pérdida de inventario.

**Hipótesis 3: Alertas automáticas**

Creemos que lograremos reducir las pérdidas ocasionadas por fallas o condiciones anormales de los equipos.

Si los responsables de negocios y técnicos especializados pueden recibir una notificación oportuna ante una anomalía o condición crítica con un sistema de alertas automáticas basado en los datos recopilados por la plataforma.

Sabremos que hemos tenido éxito cuando los usuarios reciban las alertas, actúen ante ellas y logren resolver o mitigar incidentes antes de que produzcan pérdidas significativas.

**Hipótesis 4: Historial técnico**

Creemos que lograremos mejorar la eficiencia del diagnóstico y mantenimiento de los equipos.

Si los técnicos y proveedores de servicios de refrigeración pueden consultar el comportamiento histórico, incidencias y mantenimientos realizados en cada equipo con un historial técnico centralizado y asociado a cada activo.

Sabremos que hemos tenido éxito cuando los técnicos consulten el historial durante sus servicios y reduzcan el tiempo necesario para identificar las causas de los problemas.

**Hipótesis 5: Gestión y programación de mantenimientos**

Creemos que lograremos reducir los costos asociados al mantenimiento reactivo y mejorar la productividad de los técnicos.

Si los técnicos y proveedores de servicios de refrigeración pueden planificar, organizar y realizar seguimiento de sus actividades de mantenimiento con un módulo de programación y gestión de mantenimientos.

Sabremos que hemos tenido éxito cuando aumente el porcentaje de mantenimientos planificados y disminuya el tiempo promedio empleado en gestionar y atender servicios.

**Hipótesis 6: Informes de rendimiento**

Creemos que lograremos mejorar la toma de decisiones relacionada con el funcionamiento de los equipos.

Si los responsables de negocios y proveedores pueden analizar el rendimiento de sus equipos mediante información histórica y reportes comprensibles con un módulo de generación de informes de rendimiento.

Sabremos que hemos tenido éxito cuando los usuarios consulten los informes periódicamente y utilicen la información obtenida para realizar acciones de mantenimiento, optimización o reemplazo de equipos.

**Hipótesis 7: Análisis del consumo energético**

Creemos que lograremos disminuir los costos operativos asociados al consumo energético de los equipos de refrigeración.

Si los responsables de negocios pueden identificar equipos con un consumo energético elevado o comportamientos ineficientes con un módulo de monitoreo y análisis del consumo energético.

Sabremos que hemos tenido éxito cuando los usuarios identifiquen oportunidades de ahorro y se observe una reducción del consumo energético en los equipos intervenidos.

**Hipótesis 8: Gestión de usuarios, roles y ubicaciones**

Creemos que lograremos facilitar la administración de equipos en organizaciones con múltiples usuarios o establecimientos.

Si los responsables de negocios y proveedores que gestionan múltiples usuarios, equipos o ubicaciones pueden controlar el acceso a la información según las responsabilidades de cada persona con un sistema de gestión de usuarios, roles y ubicaciones.

Sabremos que hemos tenido éxito cuando las organizaciones puedan administrar diferentes usuarios y equipos desde una misma cuenta sin comprometer la seguridad ni la organización de la información.

**Hipótesis 9: Plataforma multiplataforma**

Creemos que lograremos aumentar la frecuencia de uso de IceTrack y facilitar la supervisión de los equipos fuera de las oficinas.

Si los responsables de negocios y técnicos pueden consultar información y gestionar sus actividades desde diferentes ubicaciones con una plataforma disponible mediante interfaces web y móvil.

Sabremos que hemos tenido éxito cuando los usuarios accedan a la plataforma tanto desde sus lugares de trabajo como durante sus actividades en campo.

#### 1.2.2.4. Lean UX Canvas.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter01/lean-ux-canvas.png"
       alt="Lean UX Canvas:"
       style="max-width: 80%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Lean UX Canvas.
  </figcaption>
</figure>

## 1.3. Segmentos objetivo.

**Segmento Objetivo 1: Heladerias con equipos de refrigeración**

**Aspectos demográficos:**
- **Tipo de negocio:** Medianas empresas.
- **Nivel de necesidad:** Alta dependencia de sistemas de refrigeración.

**Aspectos geográficos:**
- **Nacionalidad:** Peruana.
- **Zona geográfica:** Urbana.
- **Departamento:** Lima.

**Aspectos psicográficos:**
- **Motivación:** Evitar pérdidas económicas por fallas en la refrigeración y reducir costos operativos.
- **Valores:** La eficiencia, la calidad del inventario y el control de las operaciones.
- **Intereses:** La adopción de tecnología para optimizar la gestión y asegurar la tranquilidad en la operación diaria.

---

**Segmento Objetivo 2: Técnicos y empresas de mantenimiento**

**Aspectos demográficos:**
- **Tipo de negocio:** Compañías de servicio técnico.
- **Rubro:** Mantenimiento y reparación de equipos de refrigeración.
- **Nivel de necesidad:** Alta demanda de organización y eficiencia en sus procesos.

**Aspectos geográficos:**
- **Nacionalidad:** Peruana.
- **Zona geográfica:** Urbana.
- **Departamento:** Lima.

**Aspectos psicográficos:**
- **Motivación:** Incrementar la productividad, reducir el tiempo en tareas administrativas y mejorar la calidad de su servicio.
- **Valores:** La profesionalidad, la eficiencia y la tecnología como herramienta para facilitar su trabajo.
- **Intereses:** Contar con una plataforma que centralice la información, automatice la generación de reportes y mejore la comunicación con sus clientes.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores


**Competidor 1: Loratech** <br>
Loratech es una empresa peruana especializada en soluciones de Internet de las Cosas (IoT) que ofrece sistemas de monitoreo para cámaras y equipos de refrigeración. Su solución permite supervisar variables como temperatura, humedad, apertura de puertas y consumo energético, generando alertas ante condiciones anormales. Asimismo, permite monitorear el funcionamiento del compresor y sus ciclos de trabajo para identificar comportamientos anómalos, facilitando la planificación del mantenimiento y la prevención de fallas que puedan ocasionar pérdidas de productos refrigerados.

---

**Competidor 2: JChip – iControl** <br>
JChip es una empresa peruana que ofrece soluciones de telemetría e Internet de las Cosas mediante su plataforma iControl. Su tecnología permite recopilar y centralizar información proveniente de sensores y equipos para realizar el monitoreo remoto de variables operativas. Sus soluciones pueden aplicarse a sistemas de refrigeración y cadena de frío, permitiendo supervisar parámetros como temperatura y consumo energético, así como generar alertas y analizar el comportamiento de los equipos para facilitar la detección de anomalías y apoyar las actividades de mantenimiento.

---

**Competidor 3: SafeSense** <br>
SafeSense es una plataforma peruana de monitoreo IoT desarrollada por SIMS Technology, orientada al control de temperatura en procesos que requieren mantener condiciones térmicas controladas. La solución utiliza sensores conectados a una plataforma web y móvil para visualizar información en tiempo real, configurar alertas automáticas y consultar historiales de mediciones. Asimismo, permite administrar múltiples sensores desde un dashboard centralizado y generar reportes, facilitando la detección temprana de desviaciones de temperatura y la prevención de pérdidas asociadas a fallas en la cadena de frío.

### 2.1.1. Análisis competitivo

<table> <tr> <th colspan="6">Competitive Analysis Landscape</th> </tr>

<tr>
  <td colspan="2">¿Por qué llevar a cabo este análisis?</td>
  <td colspan="4">Con el objetivo de evaluar y comparar las funcionalidades, tecnologías, modelos de negocio y estrategias de los principales competidores relacionados con el monitoreo de sistemas de refrigeración e IoT, con el propósito de identificar fortalezas y debilidades, detectar oportunidades de negocio y determinar aspectos que permitan diferenciar a IceTrack de las soluciones existentes en el mercado.</td>
</tr>
  <tr>
  <td colspan="2"></td>
  <td>IceTrack <br> <img src="assets/chapter02/icetrack-logo.png"></img></td>
  <td>Loratech <br> <img src="assets/chapter02/lora-logo.jpg"></img></td>
  <td>JChip - iControl <br> <img src="assets/chapter02/jchip-logo.jpg"></img></td>
  <td>SafeSense <br> <img src="assets/chapter02/safesense-logo.jpg"></img></td>
  </tr>

<tr>
  <td rowspan="2">Perfil</td>
  <td>Overview</td>
  <td>IceTrack es una plataforma de monitoreo y gestión orientada a equipos de refrigeración. Integra información obtenida mediante sensores IoT para supervisar el funcionamiento de los equipos y facilitar su mantenimiento, conectando las necesidades de los negocios con el trabajo de técnicos especializados.</td>
  <td>Loratech es una empresa peruana especializada en soluciones IoT. Entre sus aplicaciones ofrece sistemas para el monitoreo de cámaras de frío mediante sensores y redes administrables en la nube, permitiendo supervisar variables ambientales y el funcionamiento de componentes como el compresor.</td>
  <td>JChip ofrece soluciones de telemetría e IoT mediante herramientas orientadas al monitoreo remoto y centralización de información obtenida de dispositivos y sensores.</td>
  <td>SafeSense es una solución peruana de SIMS Technology orientada al monitoreo IoT de temperatura y cadena de frío. Integra sensores, una plataforma web y una aplicación móvil para supervisar condiciones térmicas y generar alertas.</td>
</tr>

<tr>
  <td>Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
  <td>Busca integrar en una misma plataforma el monitoreo de equipos de refrigeración, alertas automáticas, análisis del consumo energético, historial técnico y gestión de mantenimientos, proporcionando herramientas tanto a los negocios como a los técnicos responsables de los equipos.</td>
  <td>Combina monitoreo ambiental con información sobre el funcionamiento del equipo. Puede supervisar temperatura, humedad, apertura de puertas, consumo energético y ciclos de trabajo del compresor, permitiendo detectar patrones anómalos y apoyar el mantenimiento predictivo.</td>
  <td>Permite utilizar tecnologías IoT y telemetría para obtener información de equipos de manera remota, reduciendo la dependencia de inspecciones exclusivamente presenciales.</td>
  <td>Ofrece una solución IoT con hardware y software integrados, monitoreo continuo, alertas configurables, historial y reportes, además de soporte local en diferentes ciudades del Perú.</td>
</tr>

<tr>
  <td rowspan="2">Perfil de Marketing</td>
  <td>Mercado Objetivo</td> <td>Inicialmente, heladerías medianas ubicadas en Lima que dependen de equipos de refrigeración para conservar sus productos. También se dirige a técnicos y empresas dedicadas al mantenimiento y reparación de equipos de refrigeración.</td>
  <td>Empresas peruanas que requieren soluciones IoT para monitorear procesos y activos. Su oferta para cámaras de frío puede ser utilizada por organizaciones que necesitan conservar productos bajo condiciones controladas.</td>
  <td>Empresas que requieren soluciones de telemetría, automatización y monitoreo remoto mediante tecnologías IoT.</td>
  <td>Principalmente empresas de agroindustria, laboratorios, almacenamiento y logística que necesitan monitorear temperatura y mantener trazabilidad de sus procesos de cadena de frío.</td>
</tr>

<tr> 
  <td>Estrategias de Marketing</td>
  <td>Marketing digital dirigido inicialmente a heladerías y empresas de mantenimiento de Lima, demostraciones de la plataforma, presencia en redes sociales y alianzas con técnicos y proveedores de equipos de refrigeración.</td>
  <td>Marketing B2B mediante presencia digital y oferta de soluciones IoT personalizadas para diferentes sectores empresariales, destacando aplicaciones específicas como cámaras de frío e Industria 4.0.</td>
  <td>Promoción de soluciones tecnológicas y servicios de telemetría orientados principalmente al mercado empresarial.</td>
  <td>Marketing B2B mediante demostraciones empresariales, casos de uso por industria, presencia digital y contacto directo con empresas interesadas en implementar monitoreo IoT.</td>
</tr>

<tr>
  <td rowspan="3">Perfil de Producto</td>
  <td>Productos & Servicios</td>
  <td>Monitoreo en tiempo real de equipos de refrigeración, sensores IoT, alertas automáticas, historial técnico, gestión y programación de mantenimientos, informes de rendimiento, análisis de consumo energético y administración de usuarios, equipos y ubicaciones.</td>
  <td>Monitoreo IoT de cámaras de frío, temperatura, humedad, apertura de puertas, consumo energético y ciclos de funcionamiento del compresor. Incluye alertas y funcionalidades orientadas al mantenimiento predictivo.</td>
  <td>Soluciones de telemetría e IoT para recopilar, transmitir y visualizar información proveniente de equipos y sensores.</td>
  <td>Sensores IoT de temperatura, monitoreo en tiempo real, dashboard web, aplicación móvil, alertas automáticas, historial de mediciones y reportes exportables.</td>
</tr>

<tr>
  <td>Precios & Costos</td>
  <td>Modelo de precios aún por definir. Se contempla un esquema que considere el uso de la plataforma y los dispositivos IoT necesarios para conectar y monitorear los equipos.</td>
  <td>Los precios de implementación y operación no se encuentran publicados de manera abierta y dependen de la solución IoT requerida por cada empresa.</td>
  <td>Los precios no se encuentran disponibles públicamente y requieren cotización según las necesidades del proyecto.</td>
  <td>Cuenta con un modelo de hardware más suscripción. Publica un precio referencial de S/ 200 + IGV por sensor y S/ 20 mensuales por sensor para el acceso a la plataforma.</td>
</tr>

<tr> 
  <td>Canales de distribución (Web y/o Móvil)</td>
  <td>Plataforma web y aplicación móvil.</td>
  <td>Soluciones IoT administrables mediante plataformas en la nube.</td>
  <td>Plataformas y soluciones digitales de monitoreo y telemetría.</td>
  <td>Dashboard web y aplicación móvil para monitoreo y recepción de alertas.</td>
</tr>

<tr>
  <td rowspan="4">Análisis SWOT</td>
  <td>Fortalezas</td>
  <td>Integra monitoreo IoT con funcionalidades orientadas específicamente a la gestión del mantenimiento. Considera tanto las necesidades de las heladerías como las de técnicos y empresas de mantenimiento.</td>
  <td>Experiencia en soluciones IoT en Perú, monitoreo de múltiples variables, uso de tecnología LoRaWAN y capacidad para analizar el consumo energético y los ciclos del compresor para mantenimiento predictivo.</td>
  <td>Experiencia en soluciones de telemetría y monitoreo remoto aplicables a diferentes contextos empresariales.</td>
  <td>Solución desarrollada en Perú con sensores IoT, monitoreo en tiempo real, alertas, plataforma web, aplicación móvil, reportes y un modelo de precios públicamente disponible.</td>
</tr>

<tr> 
  <td>Debilidades</td>
  <td>Al ser una nueva solución, inicialmente carece de posicionamiento, cartera de clientes y datos históricos suficientes para validar el impacto de sus funcionalidades. Además, requiere la instalación e integración de sensores IoT en los equipos.</td>
  <td>Su propuesta abarca numerosos sectores y aplicaciones IoT, por lo que no está enfocada exclusivamente en las necesidades operativas y de gestión de las heladerías ni en la administración integral del trabajo de técnicos de refrigeración.</td>
  <td>La información pública disponible sobre funcionalidades específicas, precios y aplicaciones especializadas para refrigeración comercial es limitada.</td>
  <td>Su enfoque actual está principalmente orientado al monitoreo de temperatura y trazabilidad en agroindustria, laboratorios y logística, y no a la gestión integral del mantenimiento de equipos de refrigeración comercial.</td>
</tr>

<tr> 
  <td>Oportunidades</td>
  <td>Especialización inicial en heladerías de Lima, incorporación progresiva de nuevas funciones de mantenimiento predictivo y posibilidad de expansión posterior hacia restaurantes, minimarkets, supermercados y otros negocios dependientes de refrigeración.</td>
  <td>Expansión de soluciones IoT hacia más negocios que dependen de refrigeración comercial y crecimiento de aplicaciones de mantenimiento predictivo y eficiencia energética.</td>
  <td>Crecimiento de la adopción de tecnologías IoT y telemetría en empresas que buscan digitalizar el monitoreo de sus equipos y procesos.</td>
  <td>Expansión de su solución hacia nuevos sectores comerciales que requieren control térmico, así como incorporación de nuevos tipos de sensores y funcionalidades analíticas.</td>
</tr>

<tr> 
  <td>Amenazas</td> 
  <td>Ingreso o expansión de proveedores IoT ya establecidos hacia el segmento de refrigeración comercial, reducción de precios de soluciones competidoras y resistencia de pequeñas y medianas empresas a invertir inicialmente en sensores y suscripciones.</td>
  <td>Aparición de proveedores IoT de menor costo y soluciones especializadas que ofrezcan funcionalidades similares específicamente para determinados nichos de mercado.</td>
  <td>Competencia creciente de proveedores nacionales e internacionales de plataformas IoT y telemetría con soluciones especializadas.</td>
  <td>Competencia de plataformas IoT con sensores de menor costo o con funcionalidades adicionales de mantenimiento predictivo y gestión técnica.</td> 
</tr> 
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

Con el fin de posicionar a IceTrack en el mercado de monitoreo y gestión de equipos de refrigeración comercial, se plantean estrategias orientadas a diferenciar la propuesta frente a las soluciones IoT existentes, considerando inicialmente las necesidades de las heladerías y empresas encargados del mantenimiento de sus equipos.

1. **Estrategias de Diferenciación:**

#### Solución integral para equipos de refrigeración comercial <br>
La plataforma permitirá supervisar variables como temperatura, consumo energético y tiempo de funcionamiento, generar alertas ante anomalías y centralizar la información de los equipos. A diferencia de soluciones enfocadas principalmente en el monitoreo de variables mediante sensores.

####  Historial técnico centralizado por equipo <br>
Cada equipo de refrigeración contará con un historial que reúna sus mediciones, incidencias y mantenimientos realizados. Esto permitirá que los técnicos dispongan de información previa antes de realizar una intervención y que los responsables de las heladerías puedan consultar el comportamiento y mantenimiento de sus equipos a lo largo del tiempo.

#### Integración entre negocios y técnicos de mantenimiento <br>
La información generada por los sensores podrá ser utilizada no solo para supervisar los equipos, sino también para facilitar el diagnóstico, planificación y seguimiento de las actividades de mantenimiento.

#### Interfaz intuitiva y multiplataforma <br>
La disponibilidad mediante interfaces web y móvil permitirá que administradores y técnicos accedan a la información tanto desde el establecimiento como durante sus actividades en campo.

2. **Tácticas de Marketing:**

#### Marketing digital dirigido a heladerías <br>
Durante la etapa inicial, las campañas digitales estarán orientadas principalmente a heladerías medianas de Lima. La comunicación se enfocará en problemas concretos del negocio, como la pérdida de productos por fallas de refrigeración, la detección tardía de variaciones de temperatura y los costos asociados al consumo energético y mantenimiento correctivo.

#### Demostraciones y pruebas piloto <br>
Se buscará implementar pruebas piloto con heladerías seleccionadas para demostrar el funcionamiento de los sensores y de la plataforma en condiciones reales. Estas experiencias permitirán obtener retroalimentación de los usuarios, validar las funcionalidades propuestas y generar casos de uso que posteriormente puedan emplearse para promocionar IceTrack.

3. **Estrategias de Precios:**

#### Prueba inicial de la solución: <br>
Se podrá ofrecer un periodo de implementación piloto que permita al negocio conocer el funcionamiento de IceTrack y evaluar los beneficios del monitoreo antes de contratar el servicio de manera permanente.

#### Transparencia en los costos <br>
La propuesta comercial buscará presentar de manera clara los costos correspondientes al hardware IoT, instalación y uso de la plataforma, facilitando que los clientes puedan evaluar la inversión requerida y compararla con los posibles costos derivados de fallas, pérdidas de productos y mantenimientos correctivos.

4. **Expansión y Adaptabilidad:**

#### Colaboraciones con proveedores locales <br>
Se buscarán acuerdos con técnicos especializados, empresas de mantenimiento, distribuidores de equipos y proveedores de soluciones de refrigeración. Estas alianzas permitirán desarrollar una red local que facilite la instalación de sensores, soporte técnico y atención de los equipos conectados a IceTrack.

#### Enfoque inicial en Lima y expansión progresiva <br>
IceTrack concentrará inicialmente sus esfuerzos en heladerías ubicadas en Lima, permitiendo validar la propuesta en un segmento y territorio específicos. Una vez comprobado el funcionamiento del modelo, se podrá evaluar su expansión hacia otras ciudades del Perú que dependan de equipos de refrigeración comercial.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

Las entrevistas tienen como finalidad conocer cómo se realiza actualmente el monitoreo y mantenimiento de los equipos de refrigeración, identificar los principales problemas que enfrentan los usuarios y evaluar el interés en una solución digital que facilite la supervisión, prevención de fallas y gestión del mantenimiento.

Los resultados obtenidos permitirán validar las hipótesis planteadas y orientar el diseño de las funcionalidades de IceTrack de acuerdo con las necesidades reales de sus potenciales usuarios.

**Preguntas para el Segmento Objetivo 1 - Heladerías con equipos de refrigeración:**

1. ¿Qué tipos de equipos de refrigeración utilizan actualmente? Por ejemplo, congeladoras, vitrinas refrigeradas o cámaras de frío.

2. Aproximadamente, ¿cuántos equipos de refrigeración tienen en funcionamiento por local?

3. ¿Cómo supervisan actualmente que los equipos estén funcionando correctamente y mantengan la temperatura adecuada?

4. ¿Alguna vez han tenido una falla en un equipo de refrigeración que haya ocasionado pérdida de helados, insumos u otros productos? ¿Qué ocurrió y qué impacto tuvo para el negocio?

5. Cuando un equipo presenta una falla, ¿cómo se enteran normalmente y cuánto tiempo suele pasar hasta que un técnico pueda revisarlo?

6. ¿Cómo llevan actualmente el registro de los mantenimientos, reparaciones o fallas anteriores de cada equipo?

7. ¿Supervisan actualmente el consumo eléctrico de sus equipos de refrigeración? ¿Han identificado alguna vez un aumento de consumo relacionado con un equipo funcionando de manera ineficiente?

8. ¿Utilizan actualmente sensores, aplicaciones o algún sistema digital para monitorear sus equipos? En caso afirmativo, ¿qué utilizan y qué aspectos consideran que podrían mejorar?

9. Si pudiera recibir una alerta en su celular cuando un equipo presente una temperatura anormal o un posible problema de funcionamiento, ¿en qué situaciones considera que sería más útil?

10. ¿Qué información le gustaría poder consultar sobre cada equipo desde una plataforma? Por ejemplo, temperatura actual, consumo energético, historial de fallas, mantenimientos realizados o próximas fechas de mantenimiento.

11. ¿Qué factores serían importantes para que considere implementar una solución de monitoreo en sus equipos? Por ejemplo, precio, facilidad de instalación, precisión de las alertas, facilidad de uso o soporte técnico.

12. Si una solución de este tipo demostrara que puede ayudar a detectar problemas antes de que ocasionen pérdidas, ¿consideraría pagar una suscripción mensual? ¿Qué modalidad de pago le resultaría más conveniente?

---

**Preguntas para el Segmento Objetivo 2 - Técnicos y empresas de mantenimiento de refrigeración:**

1. ¿Qué tipos de equipos de refrigeración atiende con mayor frecuencia?

2. ¿Trabaja actualmente con heladerías? En caso afirmativo, ¿qué problemas encuentra con mayor frecuencia en sus equipos?

3. ¿Cómo recibe y organiza actualmente las solicitudes de mantenimiento de sus clientes?

4. ¿Cómo programa los mantenimientos preventivos y las visitas técnicas?

5. ¿Lleva un historial de las reparaciones y mantenimientos realizados a cada equipo? ¿Cómo registra actualmente esta información?

6. ¿Cuáles son las principales dificultades que enfrenta al diagnosticar una falla en un equipo de refrigeración?

7. ¿Utiliza actualmente alguna aplicación, software o herramienta digital para gestionar clientes, equipos, mantenimientos o reportes? En caso afirmativo, ¿cuál y qué limitaciones encuentra?

8. ¿Considera que recibir alertas sobre posibles anomalías en los equipos de sus clientes podría ayudarle a realizar mantenimientos de manera más preventiva? ¿Por qué?

9. ¿Qué información debería contener el historial técnico de un equipo para que sea realmente útil durante un diagnóstico o mantenimiento?

10. ¿Qué tan útil sería generar automáticamente un reporte después de cada mantenimiento para compartirlo con el cliente?

11. Si pudiera administrar desde una misma plataforma los equipos de diferentes clientes y establecimientos, ¿cómo podría beneficiar esto a su trabajo o empresa?

12. ¿Qué funcionalidades considera indispensables en una plataforma de monitoreo y gestión de mantenimiento para que realmente la incorporara a su trabajo?

### 2.2.2. Registro de entrevistas

## Segmento objetivo #1: Heladerías con equipos de refrigeración

#### Entrevistas:

- **Nombres y apellidos:** Sonia De la Torre
- **Edad:** 59
- **Distrito:** Lima

![Interview-1-segment-1.png](assets/chapter02/entrevista1-segmento1.png)

- **Inicio:** 00:00 min
- **Duración:** 06:03 min
- **URL:** [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a352_upc_edu_pe/IQDtPmZWk-kPSL7Hk4eeGOo3AVHl5d9OkXV4RKNw_Aqf10U?e=aDtP0g&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7fX0%3D`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a352_upc_edu_pe/IQDtPmZWk-kPSL7Hk4eeGOo3AVHl5d9OkXV4RKNw_Aqf10U?e=aDtP0g&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7fX0%3D)

- **Resumen:** La entrevistada es propietaria de una heladería ubicada en Lima, donde utiliza congeladoras para conservar los diferentes sabores y presentaciones de helados que ofrece a sus clientes. Durante la entrevista comentó que ha tenido inconvenientes con sus equipos de refrigeración, llegando a perder parte de sus productos cuando se presentaron fallas inesperadas. Actualmente, revisa manualmente la temperatura de las congeladoras y coordina mantenimientos cada cierto tiempo para prevenir problemas. Sin embargo, considera que este proceso podría mejorar mediante el uso de tecnología. La entrevistada mostró interés en recibir notificaciones automáticas cuando un equipo presente alguna anomalía, así como disponer de un registro de los mantenimientos y reparaciones realizadas. También señaló que estaría dispuesta a pagar por IceTrack si la aplicación le ayuda a detectar problemas con anticipación, proteger sus productos y disminuir las pérdidas ocasionadas por fallas en las congeladoras.

---

#### Entrevista 2:

- **Nombres y apellidos:** Diego Avalos
- **Edad:** 21
- **Distrito:** Callao

![Entrevista-2-segmento1.png](assets/chapter02/Entrevista2-Segmento1.png)

- **Inicio:** 06:04 min
- **Duración:** 08:26 min
- **URL:** [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a352_upc_edu_pe/IQDtPmZWk-kPSL7Hk4eeGOo3AVHl5d9OkXV4RKNw_Aqf10U?e=qe5Asn&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MzY0LjM4fX0%3D`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a352_upc_edu_pe/IQDtPmZWk-kPSL7Hk4eeGOo3AVHl5d9OkXV4RKNw_Aqf10U?e=qe5Asn&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MzY0LjM4fX0%3D)

- **Resumen:** El entrevistado llego a perder parte de sus productos cuando se presentaron fallas inesperadas. Actualmente, revisa manualmente la temperatura de las congeladoras y coordina mantenimientos cada cierto tiempo para prevenir problemas. Sin embargo, considera que este proceso podría mejorar mediante el uso de tecnología. El entrevistado mostró interés en recibir notificaciones automáticas cuando un equipo presente alguna anomalía, así como disponer de un registro de los mantenimientos y reparaciones realizadas. También señaló que estaría dispuesta a pagar por IceTrack si la aplicación le ayuda a detectar problemas con anticipación, proteger sus productos y disminuir las pérdidas ocasionadas por fallas en las congeladoras.


---

#### Entrevista 3:

- **Nombre:** Gabrielle Coronel
- **Edad:** 22 años
- **Distrito:** San Isidro

![Entrevista-3-segmento1.png](assets/chapter02/entrevista3-segmento1.png)

- **Inicio:** 14:31 min
- **Duración:** 07:09 min
- **URL:** [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a352_upc_edu_pe/IQDtPmZWk-kPSL7Hk4eeGOo3AVHl5d9OkXV4RKNw_Aqf10U?e=A3pSiG&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6ODcxLjAyfX0%3D`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a352_upc_edu_pe/IQDtPmZWk-kPSL7Hk4eeGOo3AVHl5d9OkXV4RKNw_Aqf10U?e=A3pSiG&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6ODcxLjAyfX0%3D)

- **Resumen:** La entrevistada mencionó que anteriormente ha sufrido pérdidas debido a problemas en la cadena de frío, situación que afectó parte de los helados almacenados. Para prevenir estos inconvenientes, realiza revisiones semanales y programa el mantenimiento de sus equipos mensualmente. Además, ya utiliza algunas herramientas digitales para controlar la temperatura. La entrevistada considera muy útil recibir alertas automáticas cuando se detecte alguna anomalía, además de contar con un historial técnico y reportes específicos de cada congeladora. Indicó que preferiría acceder a esta información desde una computadora o tablet y que estaría dispuesto a pagar por IceTrack, de preferencia mediante un pago único, siempre que la aplicación contribuya a disminuir las pérdidas de su heladería. Sin embargo, dejaría de utilizarla si presenta fallas frecuentes, un soporte técnico deficiente o costos que no se justifiquen.

---

## Segmento Objetivo 2 - Técnicos y empresas de mantenimiento de refrigeración:

**Entrevista 1:**

- **Nombres y apellidos:** Pablo Ramos
- **Edad:** 22
- **Distrito:** Los Olivos

![Entrevista-1-segmento2.png](assets/chapter02/Entrevista1-Segmento2.png)

- **Inicio:** 21:41 min
- **Duración:** 10:40 min
- **Url:** [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a352_upc_edu_pe/IQDtPmZWk-kPSL7Hk4eeGOo3AVHl5d9OkXV4RKNw_Aqf10U?e=5g3ck8&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MTMwMS42Mn19`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a352_upc_edu_pe/IQDtPmZWk-kPSL7Hk4eeGOo3AVHl5d9OkXV4RKNw_Aqf10U?e=5g3ck8&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MTMwMS42Mn19)

- **Resumen:** El entrevistado comenta una de las principales dificultades que identifica es la organización de los mantenimientos, debido a que algunos clientes olvidan realizar revisiones periódicas de sus congeladoras y equipos de refrigeración, lo que puede ocasionar fallas más graves con el tiempo. Asimismo, señaló que no disponer de un historial técnico organizado dificulta conocer rápidamente los problemas y reparaciones anteriores de cada equipo. El entrevistado considera útil contar con una plataforma centralizada que almacene esta información, permita generar reportes de manera automática y envíe alertas sobre mantenimientos o posibles fallas. Desde su perspectiva, una herramienta como IceTrack podría ayudarlo a organizar mejor sus visitas, reducir el tiempo dedicado a tareas administrativas y mantener una comunicación más eficiente con las heladerías que atiende.

---

**Entrevista 2:**

- **Nombres y apellidos:** Alessandro Castillo
- **Edad:** 22
- **Distrito:** Jesus Maria

![Entrevista-2-segmento2.png](assets/chapter02/entrevista2-segmento2.png)

- **Inicio:** 32:40 min
- **Duración:** 08:35 min
- **Url:** [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a352_upc_edu_pe/IQDtPmZWk-kPSL7Hk4eeGOo3AVHl5d9OkXV4RKNw_Aqf10U?e=rxoLfr&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MTk0Mi4zMn19`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a352_upc_edu_pe/IQDtPmZWk-kPSL7Hk4eeGOo3AVHl5d9OkXV4RKNw_Aqf10U?e=rxoLfr&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MTk0Mi4zMn19)

- **Resumen:** El entrevistado se encuentran la organización de los reportes de mantenimiento mediante Excel y la coordinación de las rutas y visitas que deben realizar los técnicos. Actualmente, gran parte de estas actividades se gestionan de forma manual y con apoyo de aplicaciones móviles, lo que puede dificultar el seguimiento de la información. Durante la entrevista señaló que una plataforma como IceTrack podría facilitar la organización de los servicios al reunir en un mismo lugar los datos de las congeladoras y otros equipos atendidos. También considera importante que los técnicos puedan registrar directamente desde el lugar de atención los trabajos realizados, reduciendo errores y agilizando la actualización de la información. Asimismo, destacó la utilidad de recibir alertas automáticas para anticipar mantenimientos y responder con mayor rapidez ante posibles inconvenientes. Para el entrevistado, implementar una herramienta de este tipo permitiría organizar mejor las operaciones y mejorar la calidad del servicio brindado a las heladerías.

#### Entrevista 3:

- **Nombre:** Gabriel Mimbela
- **Edad:** 24
- **Distrito:** Los Olivos

![Entrevista-3-segmento2.png](assets/chapter02/entrevista3-segmento2.png)

- **Inicio:** 32:40 min
- **Duración:** 07:25 min
- **Url:** [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a352_upc_edu_pe/IQDtPmZWk-kPSL7Hk4eeGOo3AVHl5d9OkXV4RKNw_Aqf10U?e=WiACqp&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MjQ3NS43M319`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241a352_upc_edu_pe/IQDtPmZWk-kPSL7Hk4eeGOo3AVHl5d9OkXV4RKNw_Aqf10U?e=WiACqp&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6MjQ3NS43M319)

- **Resumen:** El entrevistado comentó que trabajar con información distribuida en diferentes medios suele generar desorden y tareas repetitivas, especialmente cuando existen cambios de horario, no dispone de información previa sobre una congeladora o debe organizar manualmente las rutas de atención. El entrevistado considera que una aplicación móvil sencilla y disponible en español facilitaría considerablemente su trabajo. Entre las funciones que considera más importantes se encuentran consultar los equipos de cada heladería, recibir alertas ante posibles fallas, tomar fotografías durante las visitas, registrar los trabajos realizados y generar reportes técnicos automáticamente. Asimismo, mencionó que anteriormente dejó de utilizar una plataforma debido a que era complicada, estaba disponible en otro idioma y tenía un costo elevado. Por ello, considera importante que IceTrack sea una solución práctica, accesible y fácil de utilizar durante sus servicios técnicos.

### 2.2.3. Análisis de entrevistas

## Segmento objetivo #1: Heladerías con equipos de refrigeración

**Análisis:** Las entrevistas realizadas muestran que uno de los principales problemas de las heladerías es la dependencia de sus equipos de refrigeración para conservar adecuadamente sus productos. Una falla inesperada puede ocasionar pérdidas de mercadería y generar gastos adicionales por reparaciones. Actualmente, los entrevistados realizan revisiones periódicas de sus congeladoras y coordinan mantenimientos preventivos; sin embargo, gran parte de este control continúa realizándose de manera manual, lo que dificulta detectar problemas con anticipación.

De manera general, los entrevistados mostraron interés en contar con alertas automáticas que les permitan conocer rápidamente cualquier anomalía en sus equipos sin necesidad de supervisarlos constantemente. Asimismo, consideran importante disponer de un historial técnico por equipo y reportes de los mantenimientos realizados, ya que esto facilitaría el seguimiento de las fallas y reparaciones anteriores. También existe disposición a pagar por una solución como IceTrack siempre que contribuya a reducir las pérdidas económicas y sea confiable y sencilla de utilizar. Por ello, para este segmento, las funcionalidades más relevantes serían el monitoreo del estado de los equipos, las alertas automáticas, el historial de mantenimiento y la generación de reportes.

## Segmento Objetivo 2 - Técnicos y empresas de mantenimiento de refrigeración:

**Análisis:** En este segmento se identificó que las principales dificultades están relacionadas con la organización y gestión de los servicios técnicos. Los entrevistados utilizan herramientas como WhatsApp, llamadas, Excel, calendarios digitales, fotografías y anotaciones manuales para coordinar visitas y registrar los trabajos realizados. Al encontrarse la información distribuida en diferentes medios, pueden generarse problemas como pérdida de información, dificultad para consultar intervenciones anteriores, cambios de horarios y mayor tiempo destinado a la elaboración de reportes.

Los entrevistados consideran favorable contar con una plataforma centralizada que permita consultar el historial de cada equipo, organizar las visitas técnicas y registrar directamente en campo las actividades realizadas. También valoran la posibilidad de adjuntar fotografías, recibir alertas sobre posibles fallas y generar reportes técnicos automáticamente. Además, la facilidad de uso aparece como un factor importante para la adopción de la solución, especialmente para los técnicos que necesitan acceder rápidamente a la información mientras realizan una atención. En conjunto, las entrevistas muestran que IceTrack podría contribuir a reducir tareas manuales, mejorar la planificación de los servicios y facilitar la comunicación entre los técnicos y las heladerías atendidas.

## 2.3. Needfinding

### 2.3.1. User Personas

Este apartado expone los arquetipos de User Persona, elaborados a partir del análisis de las entrevistas realizadas a nuestros segmentos objetivo. Estas representaciones sintetizan de manera estratégica los objetivos, destrezas, motivaciones y principales puntos de dolor de los usuarios, integrando sus necesidades reales con las tendencias del sector para detectar oportunidades de mercado y construir una solución a su medida.

**Segmento Objetivo 1: Heladerias con equipos de refrigeración**

![UserPersona-Segmento1](assets/chapter02/UserPersona-Segmento1.png)

<br>

**Segmento Objetivo 2: Técnicos y empresas de mantenimiento**

![UserPersona-Segmento1](assets/chapter02/UserPersona-Segmento2.png)

### 2.3.2. User Task Matrix

En esta sección se presenta el User Task Matrix, realizado en base a los User Persona que representan a los dos segmentos clave identificados:

Segmento 1: Heladerías con equipos de refrigeración (representado por Alicia Vargas).

Segmento 2: Técnicos y empresas de mantenimiento (representado por Luis Paredes).

Las tareas se determinaron mediante el análisis cualitativo de las entrevistas, valorando luego su periodicidad e impacto crítico para cada perfil.

<table>
  <tr>
    <th rowspan="2">Tarea / Task</th>
    <th colspan="2">Alicia Vargas</th>
    <th colspan="2">Luis Paredes</th>
  </tr>
  <tr>
    <th>Frecuencia</th>
    <th>Importancia</th>
    <th>Frecuencia</th>
    <th>Importancia</th>
  </tr>
  <tr>
    <td>Verificar temperatura de vitrinas y congeladoras</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Registrar consumo energético</td>
    <td>Media</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Coordinar servicios de mantenimiento</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Contactar técnicos o proveedores</td>
    <td>Media</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Realizar o solicitar mantenimiento preventivo</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Revisar estado físico y estético de los equipos</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Generar reportes técnicos</td>
    <td>Baja</td>
    <td>Baja</td>
    <td>Media</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Organizar agenda de mantenimientos</td>
    <td>Baja</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Supervisar cumplimiento de normas sanitarias</td>
    <td>Media</td>
    <td>Alta</td>
    <td>Baja</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Controlar calidad y textura del inventario de helados</td>
    <td>Alta</td>
    <td>Alta</td>
    <td>-</td>
    <td>-</td>
  </tr>
  <tr>
    <td>Comunicar incidencias a clientes o equipo</td>
    <td>-</td>
    <td>-</td>
    <td>Alta</td>
    <td>Alta</td>
  </tr>
</table>

<br>

**Análisis:**

El User Task Matrix permite contrastar la frecuencia y relevancia de las actividades en cada segmento analizado para orientar las decisiones de diseño. Las tareas prioritarias y recurrentes para ambos perfiles son el control térmico, la gestión del mantenimiento, la inspección física de las unidades y la solicitud de revisiones preventivas, lo que confirma un interés mutuo en la prevención operativa. No obstante, las prioridades difieren según el rol: Alicia Vargas se enfoca críticamente en la conservación de la textura y calidad de sus helados, requiriendo un control estricto de las vitrinas exhibidoras y congeladoras para evitar mermas totales, especialmente por cortes de energía fuera del horario comercial. Por su parte, Luis Paredes atiende los diagnósticos técnicos, los informes de servicio y el reporte de averías. A pesar de estas diferencias, ambos perfiles demandan una herramienta que facilite la supervisión de los activos a distancia, anticipe fallos y optimice sus procesos diarios.

### 2.3.3. User Journey Mapping

En esta sección se presentan los User Journey Maps de los dos segmentos objetivo: Alicia Vargas, propietaria de una heladería con equipos de refrigeración y Luis Paredes, técnico especializado en refrigeración. Cada mapa refleja el recorrido actual que estos usuarios realizan para cumplir sus objetivos sin contar aún con una solución tecnológica integrada, mostrando los puntos críticos, emociones, tareas clave y oportunidades de mejora. Estos recorridos nos permiten entender los desafíos que enfrentan los usuarios día a día.

<br>

**Segmento Objetivo 1: Heladerías con equipos de refrigeración**

![UserJourneyMapping-Segmento1](assets/chapter02/UserJourneyMapping-Segmento1.png)

<br>

**Segmento Objetivo 2: Técnicos y empresas de mantenimiento**

![UserJourneyMapping-Segmento2](assets/chapter02/UserJourneyMapping-Segmento2.png)

### 2.3.4. Empathy Mapping

En esta sección se presentan los Empathy Maps. Estos nos ayudarán a comprender las experiencias, emociones y pensamientos que expresan los usuarios de cada segmento objetivo.

<br>

**Segmento Objetivo 1: Heladerías con equipos de refrigeración**

![UserJourneyMapping-Segmento1](assets/chapter02/EmpathyMap-Segmento1.png)

<br>

**Segmento Objetivo 2: Técnicos y empresas de mantenimiento**

![UserJourneyMapping-Segmento2](assets/chapter02/EmpathyMap-Segmento2.png)

## 2.4. Big Picture Event Storming

En esta sección se presenta el Big Picture Event Storming de IceTrack IoT. El análisis permitió identificar y delimitar los bounded contexts que componen la plataforma, así como los actores, comandos, eventos de negocio y políticas que intervienen en cada uno de ellos.

Los diagramas representan los principales cambios de estado del sistema: la gestión de usuarios, sitios y equipos; la atención de solicitudes de servicio; la administración de técnicos; las notificaciones de mantenimiento; la evaluación del servicio y la personalización del dashboard. Esta representación facilita la comprensión del dominio, la definición de responsabilidades y la identificación de dependencias entre los procesos del negocio.

La siguiente leyenda se aplica a todos los diagramas: los bloques verdes representan bounded contexts, los celestes representan comandos, los naranjas representan eventos de dominio, los morados representan políticas o reglas de negocio y los amarillos identifican a los actores responsables de cada acción.

## 1. IAM

El bounded context de Identity and Access Management gestiona el acceso de los usuarios a la plataforma. Incluye el registro de nuevas cuentas, la validación del nombre de usuario y la contraseña, así como el inicio de sesión.

El proceso puede finalizar con una autenticación exitosa o fallida.

![IAM](assets/chapter02/BigPictureEventStorming/iam.png)

## 2. Profiles and Preferences

Este bounded context administra la información de perfil y las preferencias de los usuarios. Permite crear perfiles para Owners y Technicians, actualizar la información personal y consultar el dashboard actual.

También permite añadir y eliminar tarjetas de información del dashboard según las preferencias del usuario.

![Profiles and Preferences](assets/chapter02/BigPictureEventStorming/profile_preferences.png)

## 3. Assets Management

El bounded context de Assets Management gestiona los sitios pertenecientes a un Owner. Incluye el registro, edición y eliminación de sitios.

Antes de registrar un sitio, el sistema valida la información proporcionada, como el nombre, la dirección, el responsable y el número telefónico. Si la información no es válida, el registro puede fallar.

Además, desde este contexto se inicia el proceso de incorporación de equipos a un sitio, generando los eventos correspondientes al registro y actualización de la información del equipo.

![Assets Management](assets/chapter02/BigPictureEventStorming/asset_management.png)

## 4. Device Management

Device Management controla la relación entre los dispositivos y el sistema. Sus operaciones principales son consultar la información de un dispositivo, asociarlo y desvincularlo.

El Owner puede emparejar un dispositivo con la plataforma o retirarlo cuando ya no debe formar parte del sistema.

![Device Management](assets/chapter02/BigPictureEventStorming/device_management.png)

## 5. Service Request and Feedback Management

Este bounded context representa el flujo principal de atención de servicios técnicos.

El Owner inicia una solicitud cuando necesita asistencia para un equipo. Posteriormente, el Provider revisa la solicitud y puede aceptarla o rechazarla. Si la solicitud es aceptada, el Provider asigna un técnico, quien registra la intervención realizada.

Finalmente, el Owner puede calificar el servicio recibido. Por ello, este contexto integra tanto la gestión de solicitudes como la evaluación del servicio técnico.

![Service Request and Feedback Management](assets/chapter02/BigPictureEventStorming/service_feedback.png)

## 6. Notifications Management

El bounded context de Notifications Management gestiona las notificaciones generadas por el sistema.

Cuando ocurre un evento relevante, como la contratación o creación de un servicio, el sistema puede generar una notificación para el Owner. Posteriormente, el usuario puede descartar o eliminar la notificación.

![Notifications Management](assets/chapter02/BigPictureEventStorming/notifications.png)

## 7. Reporting and Analysis Management

Reporting and Analysis Management permite al usuario generar reportes y consultar indicadores relevantes de la plataforma.

El usuario puede crear un reporte, aplicar filtros sobre la información disponible y consultar los principales KPIs del sistema. Este contexto facilita el análisis del estado de los sitios, dispositivos y servicios registrados.

![Reporting and Analysis Management](assets/chapter02/BigPictureEventStorming/reporting.png)

## 8. Monitoring and Alerting Management

Este bounded context administra el monitoreo de los equipos y la gestión de alertas.

Permite registrar, editar y eliminar equipos, además de gestionar las alertas asociadas a su funcionamiento. El Owner puede descartar una alerta cuando deja de ser relevante o resolverla cuando la situación reportada ha sido atendida.

![Monitoring and Alerting Management](assets/chapter02/BigPictureEventStorming/monitoring_alerting.png)



## 2.5. Ubiquitous Language

1. **User Profile (Perfil de Usuario):** Información asociada a un usuario de la plataforma, incluyendo su identidad, rol y datos personales.

2. **Owner (Propietario):** Usuario responsable de administrar sitios, equipos, solicitudes de servicio y preferencias de la plataforma.

3. **Provider (Proveedor):** Usuario encargado de gestionar solicitudes de servicio y asignar técnicos para su atención.

4. **Technician (Técnico):** Persona encargada de ejecutar y registrar las intervenciones técnicas solicitadas por un Provider.

5. **Smart Dashboard (Panel Inteligente):** Interfaz central donde el usuario consulta indicadores, reportes, alertas y tarjetas configurables.

6. **Dashboard Card (Tarjeta del Panel):** Elemento configurable del dashboard que presenta información resumida, como equipos monitoreados, alertas o reportes.

7. **Report (Reporte):** Representación organizada de información operativa para analizar el estado de los equipos, servicios y actividades registradas.

8. **KPI (Indicador Clave de Rendimiento):** Métrica utilizada para resumir y analizar información relevante del sistema.

9. **Site (Sitio):** Establecimiento o ubicación física donde se encuentran instalados los equipos administrados por un Owner.

10. **Asset (Activo):** Recurso físico registrado en la plataforma, principalmente sitios y equipos asociados.

11. **Equipment (Equipo):** Unidad de refrigeración registrada en un sitio, con información como nombre, modelo, tipo, serie, estado y conectividad.

12. **Equipment Status (Estado del Equipo):** Condición operativa actual de un equipo, por ejemplo encendido, apagado, disponible o fuera de línea.

13. **Device Pairing (Asociación de Dispositivo):** Proceso mediante el cual un dispositivo se vincula con la plataforma o con un equipo registrado.

14. **Device Unpairing (Desvinculación de Dispositivo):** Proceso mediante el cual se elimina la asociación entre un dispositivo y la plataforma.

15. **Service Request (Solicitud de Servicio):** Petición creada por un Owner para solicitar atención técnica sobre un equipo.

16. **Service Request Status (Estado de la Solicitud):** Situación actual de una solicitud, como pendiente, aceptada, rechazada, en progreso, completada o cancelada.

17. **Service Request Type (Tipo de Solicitud):** Clasificación de la atención solicitada, por ejemplo mantenimiento preventivo o correctivo.

18. **Intervention (Intervención):** Trabajo técnico realizado sobre un equipo dentro del contexto de una solicitud de servicio.

19. **Maintenance History (Historial de Mantenimiento):** Registro de solicitudes e intervenciones asociadas a un equipo.

20. **Service Feedback (Evaluación del Servicio):** Valoración realizada por el Owner sobre la atención recibida, considerando comunicación, eficiencia y profesionalidad.

21. **Maintenance Reminder Interval (Intervalo de Recordatorio de Mantenimiento):** Número de días configurado para determinar cuándo debe generarse un recordatorio de mantenimiento.

22. **Equipment Alert (Alerta del Equipo):** Aviso relacionado con una situación que requiere revisión o atención sobre un equipo.

23. **Alert Resolution (Resolución de Alerta):** Acción mediante la cual el Owner indica que una alerta fue atendida o dejó de ser relevante.

24. **Notification (Notificación):** Mensaje generado por el sistema para informar sobre eventos relevantes, como recordatorios de mantenimiento.

25. **Report Filter (Filtro de Reporte):** Criterio utilizado para limitar o seleccionar la información mostrada en un reporte.

26. **Authentication (Autenticación):** Proceso mediante el cual el sistema valida las credenciales de un usuario.

27. **Access Token (Token de Acceso):** Credencial generada después de una autenticación exitosa para permitir el acceso a las funcionalidades autorizadas.



# Capítulo III: Requirements Specification

## 3.1. User Stories.

Las historias de usuario para este proyecto se crearon enfocándose en las necesidades principales de tres tipos de usuarios: los clientes, que son dueños de equipos de refrigeración; los proveedores de servicios y equipos; y el técnico en campo, que opera principalmente desde la aplicación móvil multiplataforma integrada con la API RESTful.

Para mantener la organización, las historias se agruparon en épicas según sus funcionalidades. Los criterios de aceptación de cada historia se definieron utilizando la sintaxis Gherkin, asegurando que el equipo comprendiera el problema desde la perspectiva del usuario final.

| **Epic ID** | **Título de la Épica** | **Descripción** |
| --- | --- | --- |
| EP-01 | Gestión de Cuentas de Usuario | Esta epic se centra en todo lo necesario para que los usuarios puedan crear, acceder y administrar sus perfiles de forma segura en la plataforma. |
| EP-02 | Gestión y Monitoreo de Equipos e IoT | Esta epic abarca la funcionalidad para que los clientes agreguen, editen, enlacen dispositivos físicos ESP32 y monitoreen sus equipos de refrigeración mediante sensores. |
| EP-03 | Proceso de Solicitudes de Servicio | Esta epic cubre el ciclo completo de las solicitudes de servicio, desde que un cliente pide una reparación o mantenimiento hasta que el trabajo se completa, incluyendo la generación automatizada por alertas de sensores. |
| EP-04 | Análisis e Informes de Datos y Telemetría | Esta epic se encarga de la generación de reportes clave sobre el rendimiento de los equipos, el consumo energético, la telemetría en tiempo real y la eficiencia de los servicios. |
| EP-05 | Mecanismo de Evaluación del Servicio | Esta epic se enfoca en la funcionalidad que permite a los clientes calificar los servicios recibidos, proporcionando retroalimentación valiosa para el equipo. |
| EP-06 | Página de Aterrizaje y Experiencia Inicial | Esta epic cubre el desarrollo de la página de aterrizaje (landing page), asegurando que los visitantes entiendan rápidamente la propuesta de valor y puedan contactar al equipo comercial con facilidad. |
| EP-07 | Aplicación Móvil de Campo e Integración con API | Esta épica cubre la aplicación móvil multiplataforma (cross-platform) para el técnico en campo, integrada con la API RESTful, que permite recibir asignaciones, registrar intervenciones, actualizar estados y atender alertas push en tiempo real, incluso con conectividad intermitente. |

Además, para facilitar la planificación, el seguimiento y la priorización de las tareas, el equipo utilizó la plataforma Trello.

| **Epic / Story ID** | **Título** | **Descripción** | **Criterios de Aceptación** | **Relacionado con (Epic ID)** |
| --- | --- | --- | --- | --- |
| US-01 | Registro de usuario | Como nuevo usuario, quiero registrarme para acceder a la plataforma y empezar a gestionar mis equipos de refrigeración. | **Escenario 1: Crear cuenta exitosamente**<br>Dado que el nuevo usuario accede al formulario de registro,<br>Cuando ingresa un nombre de usuario, una contraseña y selecciona su rol,<br>Entonces el sistema crea la cuenta exitosamente y redirige al usuario a la plataforma.<br><br>**Escenario 2: Intento de registro con nombre de usuario ya existente**<br>Dado que el usuario intenta registrarse con un nombre de usuario que ya está registrado en el sistema,<br>Cuando envía el formulario,<br>Entonces el sistema muestra un mensaje de error indicando que el nombre de usuario no está disponible.<br><br>**Escenario 3: Validación de formato de contraseña**<br>Dado que el usuario ingresa una contraseña que no cumple con las políticas de seguridad requeridas,<br>Cuando intenta registrarse,<br>Entonces el sistema muestra un mensaje de advertencia indicando los requisitos mínimos. | EP-01 |
| US-02 | Inicio de sesión | Como usuario, quiero iniciar sesión con mi cuenta para acceder a la plataforma. | **Escenario 1: Iniciar sesión correctamente**<br>Dado que el usuario tiene una cuenta activa,<br>Cuando ingresa sus datos correctamente,<br>Entonces accede a su panel de control.<br><br>**Escenario 2: Intento de iniciar sesión con datos incorrectos**<br>Dado que el usuario ingresa datos incorrectos,<br>Cuando intenta iniciar sesión,<br>Entonces el sistema muestra un mensaje de error. | EP-01 |
| US-03 | Gestionar equipos de refrigeración físicos y virtuales | Como cliente, quiero gestionar mis equipos de refrigeración y asociarles sus identificadores de dispositivos de monitoreo en la plataforma para mantener un registro y control detallado de cada activo. | **Escenario 1: Registro de un nuevo equipo con sensor IoT**<br>Dado que el cliente tiene los detalles de un nuevo equipo e ID de su hardware de monitoreo,<br>Cuando los ingresa en el sistema,<br>Entonces el equipo se registra y queda enlazado correctamente al dispositivo físico.<br><br>**Escenario 2: Actualización de la información de un equipo**<br>Dado que el cliente desea modificar los datos de un equipo ya registrado,<br>Cuando realiza los cambios,<br>Entonces la información del equipo se actualiza. | EP-02 |
| US-04 | Solicitar y gestionar servicios de mantenimiento y reparación | Como cliente, quiero solicitar servicios de mantenimiento (preventivo) y reparación (correctivo) para mis equipos, para asegurar su óptimo funcionamiento y recibir confirmación de mi solicitud. | **Escenario 1: Solicitud de servicio exitosa**<br>Dado que el cliente requiere un servicio para uno de sus equipos,<br>Cuando el sistema le permite seleccionar el tipo de servicio y detallar la solicitud,<br>Entonces la solicitud se registra en el sistema y se le notifica al cliente.<br><br>**Escenario 2: Recepción de confirmación**<br>Dado que la solicitud del cliente ha sido enviada,<br>Cuando el sistema procesa la solicitud,<br>Entonces el cliente recibe una confirmación de la recepción de su solicitud con un resumen de los detalles. | EP-03 |
| US-05 | Dar seguimiento al progreso del servicio | Como cliente, quiero seguir el avance de mi servicio solicitado para saber en qué etapa se encuentra y cuándo estará completado. | **Escenario 1: Visualización del estado del servicio**<br>Dado que el cliente tiene una solicitud de servicio activa,<br>Cuando accede a su información de servicios,<br>Entonces se le presenta el estado actualizado de su solicitud.<br><br>**Escenario 2: Actualización de estado del servicio**<br>Dado que una solicitud de servicio está en curso,<br>Cuando su estado cambia (por ejemplo, de "En espera" a "En progreso"),<br>Entonces el sistema refleja el nuevo estado para el cliente. | EP-03 |
| US-06 | Realizar seguimiento a solicitudes de servicio | Como empresario, quiero realizar un seguimiento detallado a las solicitudes de servicio de mis técnicos, para saber cómo van. | **Escenario 1: Ver estado de la solicitud de servicio**<br>Dado que el empresario tiene acceso a solicitudes,<br>Cuando ingresa al sistema,<br>Entonces puede ver el estado actualizado de cada solicitud de servicio.<br><br>**Escenario 2: Actualización del estado de la solicitud**<br>Dado que el empresario quiere seguir el progreso,<br>Cuando un técnico actualiza el estado de la solicitud,<br>Entonces el sistema muestra el estado en tiempo real. | EP-03 |
| US-07 | Registrar y gestionar técnicos | Como empresario, quiero registrar técnicos en la plataforma para incluirlos en mi equipo de trabajo y gestionar sus perfiles. | **Escenario 1: Registro exitoso de un técnico**<br>Dado que el empresario completa todos los datos requeridos de un técnico,<br>Cuando guarda la información,<br>Entonces el técnico queda registrado exitosamente.<br><br>**Escenario 2: Intento de registro con datos faltantes**<br>Dado que el empresario intenta registrar un técnico sin completar todos los campos obligatorios,<br>Cuando intenta guardar el registro,<br>Entonces no se permite la operación hasta que se completen los campos requeridos. | EP-01 |
| US-08 | Consultar el perfil de un técnico | Como empresario, quiero ver el perfil de cada técnico, incluyendo sus datos y métricas de rendimiento, para poder evaluar su desempeño. | **Escenario 1: Acceso a la información completa de un técnico**<br>Dado que el empresario selecciona un técnico,<br>Cuando accede a su perfil,<br>Entonces puede visualizar sus datos personales, historial de servicios y calificaciones.<br><br>**Escenario 2: Visualización de perfil sin evaluaciones**<br>Dado que un técnico no ha recibido evaluaciones,<br>Cuando se consulta su perfil,<br>Entonces las métricas de desempeño no son visibles. | EP-01 |
| US-09 | Asignar técnicos a servicios | Como empresario, quiero asignar un técnico a una solicitud de servicio para asegurar que se realice el trabajo adecuadamente. | **Escenario 1: Asignación de técnico**<br>Dado que el empresario ha recibido una solicitud de servicio,<br>Cuando selecciona un técnico,<br>Entonces el técnico es asignado a la solicitud.<br><br>**Escenario 2: Notificación de asignación**<br>Dado que un técnico ha sido asignado a un servicio,<br>Cuando el empresario confirma la asignación,<br>Entonces el técnico recibe una notificación con los detalles. | EP-03 |
| US-10 | Visualizar clientes y servicios asociados | Como empresario, quiero ver un listado de clientes y los servicios que han solicitado para organizar de manera eficaz el trabajo de los técnicos. | **Escenario 1: Acceso a la información de clientes**<br>Dado que el empresario necesita ver los clientes con servicios pendientes,<br>Cuando accede a la funcionalidad de clientes,<br>Entonces puede visualizar a los clientes y sus servicios relacionados.<br><br>**Escenario 2: Filtrado de servicios por estado**<br>Dado que el empresario quiere enfocarse en servicios específicos,<br>Cuando aplica un filtro por el estado del servicio,<br>Entonces la lista se actualiza mostrando solo los servicios que coinciden con el filtro. | EP-04 |
| US-11 | Visualizar equipos asignados a clientes | Como empresario, quiero ver un listado de los equipos que han sido entregados a los clientes para darles un seguimiento adecuado. | **Escenario 1: Acceso a la lista de equipos por cliente**<br>Dado que el empresario quiere consultar los equipos de sus clientes,<br>Cuando accede al listado de equipos,<br>Entonces puede visualizar los equipos asignados a cada cliente.<br><br>**Escenario 2: Filtrado de equipos**<br>Dado que el empresario necesita encontrar equipos específicos,<br>Cuando aplica filtros por estado o tipo de equipo,<br>Entonces la lista de equipos se actualiza mostrando los resultados correspondientes a los filtros aplicados. | EP-02 |
| US-12 | Evaluar un servicio completado | Como cliente, quiero evaluar un servicio una vez que ha finalizado para expresar mi satisfacción con el trabajo realizado. | **Escenario 1: Envío de la evaluación**<br>Dado que el cliente ha recibido un servicio,<br>Cuando envía una calificación,<br>Entonces la evaluación es registrada.<br><br>**Escenario 2: Modificación de la evaluación**<br>Dado que el cliente desea cambiar una evaluación ya enviada,<br>Cuando actualiza la calificación dentro del plazo establecido,<br>Entonces la nueva calificación reemplaza a la anterior. | EP-05 |
| US-13 | Visualizar la propuesta de valor principal | Como visitante, quiero conocer la propuesta de valor de la plataforma para entender si se ajusta a mis necesidades. | **Escenario 1: Propuesta visible al ingresar**<br>Dado que un visitante llega a la página principal,<br>Cuando la página carga,<br>Entonces se le presenta una frase que explica claramente la propuesta de valor.<br><br>**Escenario 2: Contenido orientado a la gestión de refrigeración**<br>Dado que el visitante pertenece al segmento de gestión de equipos,<br>Cuando revisa la propuesta de valor,<br>Entonces encuentra conceptos relacionados con gestión inteligente y monitoreo de equipos. | EP-06 |
| US-14 | Explorar soluciones específicas para mi rubro | Como visitante, quiero conocer las soluciones que ofrece la plataforma para mi tipo de negocio para saber si se ajusta a mis necesidades. | **Escenario 1: Información para negocios de refrigeración**<br>Dado que un visitante explora las soluciones ofrecidas,<br>Cuando revisa el contenido disponible,<br>Entonces encuentra descripciones dirigidas a negocios que utilizan o gestionan equipos de refrigeración.<br><br>**Escenario 2: Información para empresas proveedoras de servicios**<br>Dado que un visitante explora las soluciones ofrecidas,<br>Cuando revisa el contenido disponible,<br>Entonces encuentra información dirigida a empresas proveedoras de equipos o servicios de mantenimiento. | EP-06 |
| US-15 | Comprender las funcionalidades clave | Como visitante, quiero entender las funcionalidades principales de la plataforma para evaluar si se adaptan a mi operación. | **Escenario 1: Acceso a funcionalidades principales**<br>Dado que un visitante consulta las características de la plataforma,<br>Cuando revisa la lista de funcionalidades,<br>Entonces puede identificar opciones clave como monitoreo en tiempo real, automatización de alertas y gestión remota.<br><br>**Escenario 2: Descripciones orientadas al valor**<br>Dado que un visitante lee las descripciones de las funcionalidades,<br>Cuando evalúa cada una,<br>Entonces comprende el beneficio que aporta para su operación de refrigeración o mantenimiento. | EP-06 |
| US-16 | Conocer la misión y visión | Como visitante, quiero conocer la misión y visión de la empresa para entender su enfoque y propuesta de valor. | **Escenario 1: Acceso a la misión de la empresa**<br>Dado que un visitante accede a la información institucional,<br>Cuando revisa el contenido corporativo,<br>Entonces encuentra una descripción clara de la misión.<br><br>**Escenario 2: Acceso a la visión de la empresa**<br>Dado que un visitante accede a la información institucional,<br>Cuando revisa el contenido estratégico,<br>Entonces encuentra una descripción clara de la visión a futuro. | EP-06 |
| US-17 | Acceder a la plataforma web (Call to Action) | Como usuario registrado, quiero acceder fácilmente a la plataforma web desde la página de inicio para gestionar mis operaciones y equipos. | **Escenario 1: Visibilidad del acceso a la plataforma**<br>Dado que un usuario registrado visita la página principal,<br>Cuando busca cómo ingresar a su cuenta,<br>Entonces encuentra una opción clara para acceder a la plataforma.<br><br>**Escenario 2: Redirección a la plataforma web**<br>Dado que el usuario selecciona la opción para acceder a la plataforma,<br>Cuando es redirigido,<br>Entonces llega a la página de inicio de sesión de la plataforma web. | EP-06 |
| US-18 | Consultar equipos registrados | Como usuario operador, quiero visualizar los equipos registrados para monitorear su estado operativo. | **Escenario 1: Listado de equipos**<br>Dado que el usuario accede al módulo Equipments,<br>Cuando carga la pantalla,<br>Entonces visualiza modelo, tipo, serial y estado de cada equipo.<br><br>**Escenario 2: Ver detalle**<br>Dado que existe un equipo registrado,<br>Cuando selecciona "Equipment Detail",<br>Entonces el sistema muestra la información detallada del equipo. | EP-02 |
| US-19 | Visualizar dashboard principal con telemetría en tiempo real | Como usuario propietario del sistema, quiero visualizar un dashboard con métricas resumidas y flujos de temperatura en tiempo real provenientes de los sensores IoT, para conocer rápidamente el estado general de la operación. | **Escenario 1: Visualización de métricas y telemetría**<br>Dado que el usuario ingresa al dashboard,<br>Cuando carga la pantalla principal,<br>Entonces visualiza la cantidad de equipos monitoreados, temperatura en tiempo real por sensor, alertas abiertas y reportes recientes.<br><br>**Escenario 2: Actualización en vivo de datos de sensores**<br>Dado que el usuario mantiene abierto el dashboard,<br>Cuando los dispositivos ESP32 envían nuevas lecturas vía API,<br>Entonces los gráficos y estados se actualizan automáticamente sin recargar la página. | EP-04 |
| US-20 | Registrar nuevos sitios | Como usuario, quiero registrar nuevos sitios para organizar las ubicaciones donde operan los equipos. | **Escenario 1: Registro de sitio**<br>Dado que el administrador desea crear una nueva sede,<br>Cuando selecciona "Register New Site" e ingresa los datos requeridos,<br>Entonces el sistema registra el sitio exitosamente.<br><br>**Escenario 2: Visualización de sitios**<br>Dado que existen sitios registrados,<br>Cuando accede al módulo Sites,<br>Entonces visualiza nombre, dirección, contacto y teléfono. | EP-02 |
| US-21 | Crear solicitudes de servicio | Como cliente, quiero registrar solicitudes de servicio técnico para reportar incidencias o mantenimientos. | **Escenario 1: Nueva solicitud**<br>Dado que el usuario necesita soporte técnico,<br>Cuando selecciona "New Request" e ingresa la información requerida,<br>Entonces el sistema registra la solicitud correctamente.<br><br>**Escenario 2: Visualización de solicitudes**<br>Dado que existen solicitudes registradas,<br>Cuando accede al módulo Services,<br>Entonces visualiza número de orden, fecha, equipo, sede, proveedor, tipo y estado. | EP-03 |
| US-22 | Buscar reportes por filtros | Como administrador, quiero buscar reportes por nombre, tipo o estado para localizar información rápidamente. | **Escenario 1: Buscar por nombre**<br>Dado que existen múltiples reportes,<br>Cuando escribe un nombre en el buscador,<br>Entonces el sistema muestra coincidencias relacionadas.<br><br>**Escenario 2: Filtrar por tipo o estado**<br>Dado que el usuario necesita segmentar información,<br>Cuando selecciona filtros de tipo o estado,<br>Entonces se actualiza el listado con los resultados correctos. | EP-04 |
| US-23 | Cambiar idioma del sistema | Como usuario internacional, quiero cambiar el idioma del sistema para usar la plataforma en mi idioma preferido. | **Escenario 1: Cambio a español**<br>Dado que el usuario selecciona ES,<br>Cuando confirma la acción,<br>Entonces la interfaz se muestra en español.<br><br>**Escenario 2: Cambio a inglés**<br>Dado que el usuario selecciona EN,<br>Cuando confirma la acción,<br>Entonces la interfaz se muestra en inglés. | EP-01 |
| US-24 | Ver reporte de servicio realizado | Como cliente, quiero ver el reporte de servicio detallado para saber qué reparaciones se hicieron en mi equipo. | **Escenario 1: Generación del reporte de servicio**<br>Dado que el servicio ha sido completado,<br>Cuando el técnico termina,<br>Entonces el sistema genera un reporte detallado.<br><br>**Escenario 2: Enviar reporte al cliente por correo**<br>Dado que el reporte ha sido generado,<br>Cuando se ha finalizado el servicio,<br>Entonces el sistema envía el reporte al cliente. | EP-04 |
| US-25 | Visualizar métricas del sistema | Como usuario propietario del sistema, quiero visualizar un dashboard con métricas resumidas para conocer rápidamente el estado general de la operación. | **Escenario 1: Visualización de métricas**<br>Dado que el usuario ingresa al dashboard,<br>Cuando carga la pantalla principal,<br>Entonces visualiza la cantidad de sitios, equipos monitoreados y servicios recientes.<br><br>**Escenario 2: Actualización de datos**<br>Dado que el usuario necesita información reciente,<br>Cuando selecciona el botón "Refresh Dashboard",<br>Entonces el sistema actualiza los indicadores mostrados. | EP-04 |
| TS-01 | Creación de solicitudes de mantenimiento (API) | Como desarrollador, quiero implementar una API que me permita crear solicitudes de mantenimiento para que los negocios reporten necesidades de soporte técnico. | **Escenario 1: Creación exitosa de solicitud**<br>Dado que se envía una solicitud POST a `/api/v1/service-requests` con los datos del equipo y la descripción del problema,<br>Cuando la solicitud es procesada,<br>Entonces se recibe una respuesta 201 y se guarda la solicitud en el sistema.<br><br>**Escenario 2: Datos incompletos en la solicitud**<br>Dado que se envía una solicitud a `/api/v1/service-requests` sin un campo obligatorio,<br>Cuando la solicitud es procesada,<br>Entonces se recibe una respuesta 400 con el mensaje "Invalid data". | EP-03 |
| TS-02 | Registro de intervenciones técnicas por API RESTful | Como desarrollador, quiero registrar las intervenciones técnicas realizadas a través de la API para llevar un seguimiento detallado del mantenimiento. | **Escenario 1: Registro exitoso**<br>Dado que se envía una solicitud POST a `/api/v1/interventions` con los datos del técnico y equipo,<br>Cuando la solicitud es procesada,<br>Entonces se recibe una respuesta 201 y el registro se almacena.<br><br>**Escenario 2: Registro con técnico no existente**<br>Dado que el ID del técnico no existe,<br>Cuando se realiza la solicitud POST a `/api/v1/interventions`,<br>Entonces se recibe una respuesta 404 con el mensaje "Technician not found". | EP-03 |
| TS-03 | Gestión de evaluaciones de servicio vía API | Como desarrollador, mi objetivo es implementar un endpoint que permita a los clientes registrar y actualizar una evaluación de servicio para reflejar su experiencia. | **Escenario 1: Evaluación inicial del servicio**<br>Dado que el cliente ha recibido un servicio,<br>Cuando se envía una solicitud POST a `/api/v1/reviews` con la puntuación (1-5),<br>Entonces se recibe una respuesta 201 y se almacena la evaluación asociada al servicio.<br><br>**Escenario 2: Edición dentro del plazo permitido**<br>Dado que el cliente ya evaluó un servicio y han pasado menos de 48 horas,<br>Cuando realiza una solicitud PUT a `/api/v1/reviews/{id}` con una nueva puntuación,<br>Entonces se recibe una respuesta 200 y la evaluación anterior se actualiza. | EP-05 |
| TS-04 | Registrar nuevo usuario a través de API RESTful | Como desarrollador, quiero exponer un endpoint para registrar nuevos usuarios en la plataforma, validando datos como correo único y formato de contraseña, para permitir el acceso seguro de nuevos usuarios. | **Escenario 1: Registro exitoso**<br>Dado que el endpoint `/api/v1/users` está disponible,<br>Cuando se envía una solicitud POST con datos válidos (nombre, email único, contraseña válida),<br>Entonces el sistema responde con 201 y devuelve el usuario registrado.<br><br>**Escenario 2: Registro con email existente**<br>Dado que existe un correo ya registrado en el sistema,<br>Cuando se intenta registrar nuevamente,<br>Entonces se devuelve un 400 con mensaje "Email already registered". | EP-01 |
| TS-05 | Consulta de estado de servicios por API | Como desarrollador, mi objetivo es crear un endpoint para que clientes y empresarios puedan consultar el estado de una solicitud de servicio en tiempo real. | **Escenario 1: Consulta exitosa del estado**<br>Dado que se envía una solicitud GET a `/api/v1/requests/{id}` con un ID válido,<br>Cuando la solicitud es procesada,<br>Entonces se recibe una respuesta 200 y se devuelve el estado actual de la solicitud.<br><br>**Escenario 2: Consulta con ID existente**<br>Dado que el ID de la solicitud no existe,<br>Cuando se realiza la consulta,<br>Entonces se recibe una respuesta 404 con el mensaje "Request not found". | EP-03 |
| US-26 | Programar dispositivo ESP32 para envío de telemetría IoT | Como desarrollador de hardware, quiero programar el microcontrolador ESP32 con sensores conectados para enviar datos de temperatura y variables operativas hacia la API en la nube, para asegurar la alimentación continua de telemetría. | **Escenario 1: Envío exitoso de datos de telemetría**<br>Dado que el dispositivo ESP32 está configurado con las credenciales de red y la URL del endpoint IoT,<br>Cuando el sensor registra una lectura de temperatura y el script ejecuta la solicitud HTTP POST hacia `/api/v1/telemetry` con una estructura de payload correcta,<br>Entonces el servidor responde con un código 201 Created y almacena los datos.<br><br>**Escenario 2: Reintento ante pérdida de conectividad**<br>Dado que el dispositivo ESP32 pierde la conexión a internet temporalmente,<br>Cuando intenta enviar las lecturas de los sensores,<br>Entonces el dispositivo almacena los paquetes en un búfer local y reintenta la transmisión de forma automática una vez restablecida la red. | EP-02 |
| US-27 | Visualización de datos de sensores IoT en tiempo real desde el dashboard | Como usuario propietario o técnico, quiero visualizar los datos de temperatura y variables operativas en tiempo real dentro del dashboard, para conocer el estado actual de los equipos de refrigeración. | **Escenario 1: Carga inicial de datos en tiempo real**<br>Dado que el usuario accede al dashboard principal de un equipo con sensor IoT activo,<br>Cuando la interfaz establece la conexión con el servicio de streaming o actualización periódica,<br>Entonces se visualizan las métricas de temperatura actuales actualizadas sin necesidad de recargar la página.<br><br>**Escenario 2: Gráfico de comportamiento histórico y actual**<br>Dado que el usuario selecciona un equipo monitoreado por ESP32,<br>Cuando visualiza el módulo de gráficos de rendimiento,<br>Entonces el sistema muestra una línea de tiempo continua que combina los datos históricos con las últimas lecturas de los sensores. | EP-04 |
| US-28 | Generación de alertas automáticas por anomalías térmicas en sensores | Como sistema, quiero generar alertas automáticas cuando los datos de los sensores IoT superen los umbrales configurados, para notificar inmediatamente una posible falla en la cadena de frío. | **Escenario 1: Detección de temperatura fuera de rango**<br>Dado que un sensor ESP32 reporta una temperatura superior al límite máximo permitido (ej. mayor a -15°C en congelación),<br>Cuando la API procesa la trama de telemetría recibida,<br>Entonces el sistema genera una alerta crítica automática en la plataforma y registra la incidencia.<br><br>**Escenario 2: Envío de notificación push o correo**<br>Dado que se ha generado una alerta automática por anomalía térmica,<br>Cuando el sistema procesa el evento de riesgo,<br>Entonces se envía una notificación inmediata al usuario propietario y a los técnicos asignados. | EP-02 |
| US-29 | Interpretación y actuación sobre datos de sensores IoT | Como usuario operador o administrador, quiero interpretar de forma clara los datos y alertas provenientes de los sensores IoT, para tomar decisiones operativas y gestionar acciones correctivas eficaces. | **Escenario 1: Visualización de estado de alerta en la interfaz**<br>Dado que un equipo presenta una alerta activa por anomalía en el sensor,<br>Cuando el usuario visualiza el listado o detalle del equipo,<br>Entonces el sistema resalta visualmente el estado con un indicador claro y muestra opciones sugeridas de actuación (como crear una orden de servicio correctivo).<br><br>**Escenario 2: Creación automatizada de orden de trabajo correctiva**<br>Dado que el usuario revisa una alerta crítica generada por el ESP32,<br>Cuando hace clic en el botón "Generar Orden de Servicio",<br>Entonces el sistema precarga los datos del equipo afectado en el formulario de nueva solicitud de mantenimiento. | EP-03 |
| US-30 | Recibir y aceptar asignación de servicio en la aplicación móvil | Como técnico en campo, quiero recibir y aceptar las asignaciones de servicio desde la aplicación móvil multiplataforma para organizar mis visitas sin depender de la plataforma web. | **Escenario 1: Recepción de asignación en la aplicación móvil**<br>Dado que el empresario ha asignado un servicio al técnico,<br>Cuando el técnico abre la aplicación móvil cross-platform sincronizada con la API RESTful,<br>Entonces visualiza la nueva orden con sede, equipo, fecha y prioridad.<br><br>**Escenario 2: Aceptación y cambio de estado**<br>Dado que el técnico visualiza una orden pendiente en la aplicación móvil,<br>Cuando pulsa "Aceptar servicio",<br>Entonces la aplicación consume el endpoint PUT `/api/v1/requests/{id}` y el estado cambia a "En progreso" tanto en el móvil como en la plataforma web. | EP-07 |
| US-31 | Registrar intervención técnica desde la aplicación móvil en campo | Como técnico en campo, quiero registrar la intervención realizada desde la aplicación móvil, incluso con conectividad intermitente, para dejar constancia inmediata del mantenimiento ejecutado. | **Escenario 1: Registro en línea de la intervención**<br>Dado que el técnico ha concluido el servicio en la sede del cliente,<br>Cuando completa el formulario móvil (diagnóstico, acciones, repuestos y evidencia fotográfica) y pulsa "Finalizar",<br>Entonces la aplicación envía un POST a `/api/v1/interventions` mediante la API RESTful y la intervención queda asociada al equipo y a la orden.<br><br>**Escenario 2: Registro diferido sin conexión**<br>Dado que el técnico no dispone de conexión a internet en la sede,<br>Cuando registra la intervención en la aplicación móvil,<br>Entonces la aplicación la almacena en la cola local segura y la sincroniza automáticamente con la API RESTful al restablecerse la red, sin duplicar registros. | EP-07 |
| US-32 | Recibir y atender alertas push de anomalías térmicas en la aplicación móvil | Como técnico en campo, quiero recibir notificaciones push de alertas críticas en la aplicación móvil para acudir oportunamente a los equipos con riesgo de ruptura de la cadena de frío. | **Escenario 1: Recepción de alerta push crítica**<br>Dado que el sistema ha generado una alerta crítica por anomalía térmica,<br>Cuando el servicio de notificaciones procesa el evento,<br>Entonces el técnico asignado recibe una notificación push en la aplicación móvil con el equipo, la sede, la temperatura registrada y el nivel de severidad.<br><br>**Escenario 2: Navegación contextual desde la alerta**<br>Dado que el técnico recibe una alerta push en la aplicación móvil,<br>Cuando pulsa sobre la notificación,<br>Entonces la aplicación abre directamente el detalle del equipo afectado, muestra la telemetría reciente obtenida vía API RESTful y ofrece la acción "Generar orden de servicio". | EP-07 |
| US-33 | Actualizar el estado del servicio y consultar telemetría desde la aplicación móvil | Como técnico en campo, quiero consultar el detalle del equipo y actualizar el estado del servicio desde la aplicación móvil para mantener la trazabilidad operativa durante el desplazamiento. | **Escenario 1: Consulta de equipo y telemetría en campo**<br>Dado que el técnico ha aceptado una orden en la aplicación móvil,<br>Cuando accede al detalle del equipo vinculado,<br>Entonces visualiza el historial técnico, la última telemetría de temperatura y las intervenciones previas consumidas desde la API RESTful.<br><br>**Escenario 2: Actualización de estado en campo**<br>Dado que el técnico se encuentra en camino o en sitio,<br>Cuando selecciona un nuevo estado ("En camino", "En sitio", "Completado"),<br>Entonces la aplicación sincroniza el cambio con la API RESTful y el nuevo estado queda visible inmediatamente para el empresario y el cliente. | EP-07 |
| US-34 | Iniciar sesión con Google mediante OAuth 2.0 (servicio externo de terceros) | Como nuevo usuario, quiero iniciar sesión o registrarme con mi cuenta de Google mediante OAuth 2.0 para acceder a la plataforma sin crear una contraseña adicional. | **Escenario 1: Autenticación exitosa con Google OAuth 2.0**<br>Dado que el usuario selecciona "Continuar con Google" en la plataforma web o en la aplicación móvil,<br>Cuando autoriza a IceTrack en la pantalla de consentimiento de Google y el servicio externo devuelve un ID Token válido,<br>Entonces el backend valida el token contra Google OAuth 2.0, crea o vincula la cuenta y otorga una sesión segura con JWT propio.<br><br>**Escenario 2: Autenticación rechazada o token inválido**<br>Dado que el usuario cancela el consentimiento o Google devuelve un token inválido o caducado,<br>Cuando la plataforma procesa la respuesta del servicio externo de terceros,<br>Entonces deniega el acceso, muestra un mensaje que indica que no fue posible autenticar con Google y conserva la opción de ingreso con credenciales tradicionales. | EP-01 |
| TS-06 | Integración de la aplicación móvil cross-platform con la API RESTful | Como desarrollador, quiero implementar la aplicación móvil multiplataforma (cross-platform) integrada con la API RESTful para que el técnico en campo opere con los mismos datos que la plataforma web. | **Escenario 1: Consumo autenticado de la API desde el móvil**<br>Dado que la aplicación móvil cross-platform dispone de un token JWT vigente (obtenido por credenciales o Google OAuth 2.0),<br>Cuando solicita GET a `/api/v1/requests/assigned` con el encabezado Authorization Bearer,<br>Entonces recibe una respuesta 200 con las órdenes asignadas y las presenta en el listado móvil.<br><br>**Escenario 2: Registro offline-first con sincronización**<br>Dado que la aplicación móvil pierde conectividad durante el registro de una intervención,<br>Cuando restablece la conexión e intenta sincronizar la cola local con POST a `/api/v1/interventions`,<br>Entonces la API responde 201 por cada registro pendiente, sin duplicados, y la aplicación confirma la sincronización al técnico. | EP-07 |

---

**Requisitos No Funcionales (RNF)**

| **RNF ID** | **Categoría** | **Descripción del Requisito No Funcional** |
| --- | --- | --- |
| RNF-01 | **Rendimiento y Disponibilidad** | La plataforma en la nube debe garantizar una disponibilidad continua (Uptime del 90% en el servicio SaaS) para la recepción de tramas de telemetría provenientes de los dispositivos ESP32. |
| RNF-02 | **Tiempo de Respuesta** | El dashboard principal y las vistas de telemetría en tiempo real deben actualizar las lecturas de los sensores con una latencia menor a 3 segundos tras la recepción del paquete HTTP POST. |
| RNF-03 | **Escalabilidad** | La arquitectura del backend debe ser capaz de soportar un incremento concurrente en el envío de datos de sensores IoT desde múltiples dispositivos distribuidos sin degradar el rendimiento general del sistema. |
| RNF-04 | **Seguridad y Cifrado** | Las comunicaciones entre los microcontroladores ESP32, la API RESTful y la interfaz web deben utilizar protocolos seguros de cifrado (HTTPS/TLS) para proteger la integridad de los datos de los usuarios y de la telemetría. |
| RNF-05 | **Resiliencia y Tolerancia a Fallos** | Los dispositivos de hardware (ESP32) deben contar con un mecanismo de almacenamiento local en búfer para reintentar el envío de datos de telemetría de forma automática ante cortes temporales de red. |
| RNF-06 | **Usabilidad y Accesibilidad** | La interfaz web y móvil debe contar con un diseño responsivo (mobile-first) e intuitivo, asegurando que los usuarios puedan interpretar las alertas críticas de temperatura sin requerir capacitación técnica compleja. |

## 3.2. Impact Mapping.
El equipo desarrolló un Impact Mapping en colaboración utilizando la herramienta UXPressia. Este mapa se creó para conectar los objetivos de negocio directamente con los requisitos funcionales de la plataforma.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter01/impactmap.png"
       alt="Diagrama de Impact Mapping: Objetivo, actores, impactos y entregables clave."
       style="max-width: 80%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Impact Mapping.
  </figcaption>
</figure>

## 3.3. Product Backlog.
Para el desarrollo de nuestra plataforma, hemos creado un Product Backlog que funciona como una lista completa de todas las funcionalidades, características e incluso tareas técnicas necesarias para avanzar en el proyecto.

Para mantener el proyecto organizado, usamos la escala de Fibonacci (1, 2, 3, 5, 8, 13, 21) para estimar el esfuerzo de cada tarea. Esta escala de Story Points nos ayuda a priorizar y planificar de la siguiente manera:

1: Tareas sencillas y rápidas.
2: Tareas de complejidad moderada.
3: Tareas que requieren más tiempo y esfuerzo.
5: Tareas complejas.
8: Tareas de alta complejidad que impactan varias áreas del proyecto.

<figure style="page-break-inside: avoid; text-align: center;">
  <img src="assets/chapter01/trello.png"
       alt="Diagrama de Product Backlog: Lista priorizada de funcionalidades y requisitos del producto."
       style="max-width: 95%; height: auto; display: block; margin: 0 auto;">
  <figcaption style="font-size: 0.9em; color: #555;">
    <strong>Figura 1:</strong> Product Backlog.
  </figcaption>
</figure>

| Orden | User Story ID | Titulo | Descripcion | Story Points |
| --- | --- | --- | --- | --- |
| 01 | US-13 | Visualizar la propuesta de valor principal | Como visitante, quiero conocer la propuesta de valor de la plataforma para entender si se ajusta a mis necesidades. | 2 |
| 02 | US-14 | Explorar soluciones específicas para mi rubro | Como visitante, quiero conocer las soluciones que ofrece la plataforma para mi tipo de negocio para saber si se ajusta a mis necesidades. | 2 |
| 03 | US-15 | Comprender las funcionalidades clave | Como visitante, quiero entender las funcionalidades principales de la plataforma para evaluar si se adaptan a mi operación. | 3 |
| 04 | US-16 | Conocer la misión y visión | Como visitante, quiero conocer la misión y visión de la empresa para entender su enfoque y propuesta de valor. | 2 |
| 05 | US-17 | Acceder a la plataforma web (Call to Action) | Como usuario registrado, quiero acceder fácilmente a la plataforma web desde la página de inicio para gestionar mis operaciones y equipos. | 2 |
| 06 | US-26 | Programar dispositivo ESP32 para envío de telemetría IoT | Como desarrollador de hardware, quiero programar el microcontrolador ESP32 con sensores conectados para enviar datos de temperatura y variables operativas hacia la API en la nube, para asegurar la alimentación continua de telemetría. | 8 |
| 07 | TS-04 | Registrar nuevo usuario a través de API RESTful | Como desarrollador, quiero exponer un endpoint para registrar nuevos usuarios en la plataforma, validando datos como correo único y formato de contraseña, para permitir el acceso seguro de nuevos usuarios. | 5 |
| 08 | TS-01 | Creación de solicitudes de mantenimiento (API) | Como desarrollador, quiero implementar una API que me permita crear solicitudes de mantenimiento para que los negocios reporten necesidades de soporte técnico. | 8 |
| 09 | TS-02 | Registro de intervenciones técnicas por API RESTful | Como desarrollador, quiero registrar las intervenciones técnicas realizadas a través de la API para llevar un seguimiento detallado del mantenimiento. | 5 |
| 10 | TS-03 | Gestión de evaluaciones de servicio vía API | Como desarrollador, mi objetivo es implementar un endpoint que permita a los clientes registrar y actualizar una evaluación de servicio para reflejar su experiencia. | 5 |
| 11 | TS-05 | Consulta de estado de servicios por API | Como desarrollador, mi objetivo es crear un endpoint para que clientes y empresarios puedan consultar el estado de una solicitud de servicio en tiempo real. | 8 |
| 12 | US-01 | Registro de usuario | Como nuevo usuario, quiero registrarme para acceder a la plataforma y empezar a gestionar mis equipos de refrigeración. | 5 |
| 13 | US-02 | Inicio de sesión | Como usuario, quiero iniciar sesión con mi cuenta para acceder a la plataforma. | 3 |
| 14 | US-20 | Registrar nuevos sitios | Como usuario, quiero registrar nuevos sitios para organizar las ubicaciones donde operan los equipos. | 5 |
| 15 | US-03 | Gestionar equipos de refrigeración físicos y virtuales | Como cliente, quiero gestionar mis equipos de refrigeración y asociarles sus identificadores de dispositivos de monitoreo en la plataforma para mantener un registro y control detallado de cada activo. | 5 |
| 16 | US-18 | Consultar equipos registrados | Como usuario operador, quiero visualizar los equipos registrados para monitorear su estado operativo. | 3 |
| 17 | US-11 | Visualizar equipos asignados a clientes | Como empresario, quiero ver un listado de los equipos que han sido entregados a los clientes para darles un seguimiento adecuado. | 3 |
| 18 | US-19 | Visualizar dashboard principal con telemetría en tiempo real | Como usuario propietario del sistema, quiero visualizar un dashboard con métricas resumidas y flujos de temperatura en tiempo real provenientes de los sensores IoT, para conocer rápidamente el estado general de la operación. | 8 |
| 19 | US-27 | Visualización de datos de sensores IoT en tiempo real desde el dashboard | Como usuario propietario o técnico, quiero visualizar los datos de temperatura y variables operativas en tiempo real dentro del dashboard, para conocer el estado actual de los equipos de refrigeración. | 8 |
| 20 | US-25 | Visualizar métricas del sistema | Como usuario propietario del sistema, quiero visualizar un dashboard con métricas resumidas para conocer rápidamente el estado general de la operación. | 8 |
| 21 | US-28 | Generación de alertas automáticas por anomalías térmicas en sensores | Como sistema, quiero generar alertas automáticas cuando los datos de los sensores IoT superen los umbrales configurados, para notificar inmediatamente una posible falla en la cadena de frío. | 8 |
| 22 | US-29 | Interpretación y actuación sobre datos de sensores IoT | Como usuario operador o administrador, quiero interpretar de forma clara los datos y alertas provenientes de los sensores IoT, para tomar decisiones operativas y gestionar acciones correctivas eficaces. | 5 |
| 23 | US-04 | Solicitar y gestionar servicios de mantenimiento y reparación | Como cliente, quiero solicitar servicios de mantenimiento (preventivo) y reparación (correctivo) para mis equipos, para asegurar su óptimo funcionamiento y recibir confirmación de mi solicitud. | 5 |
| 24 | US-21 | Crear solicitudes de servicio | Como cliente, quiero registrar solicitudes de servicio técnico para reportar incidencias o mantenimientos. | 5 |
| 25 | US-05 | Dar seguimiento al progreso del servicio | Como cliente, quiero seguir el avance de mi servicio solicitado para saber en qué etapa se encuentra y cuándo estará completado. | 3 |
| 26 | US-06 | Realizar seguimiento a solicitudes de servicio | Como empresario, quiero realizar un seguimiento detallado a las solicitudes de servicio de mis técnicos, para saber cómo van. | 3 |
| 27 | US-07 | Registrar y gestionar técnicos | Como empresario, quiero registrar técnicos en la plataforma para incluirlos en mi equipo de trabajo y gestionar sus perfiles. | 5 |
| 28 | US-08 | Consultar el perfil de un técnico | Como empresario, quiero ver el perfil de cada técnico, incluyendo sus datos y métricas de rendimiento, para poder evaluar su desempeño. | 3 |
| 29 | US-09 | Asignar técnicos a servicios | Como empresario, quiero asignar un técnico a una solicitud de servicio para asegurar que se realice el trabajo adecuadamente. | 8 |
| 30 | US-10 | Visualizar clientes y servicios asociados | Como empresario, quiero ver un listado de clientes y los servicios que han solicitado para organizar de manera eficaz el trabajo de los técnicos. | 5 |
| 31 | US-12 | Evaluar un servicio completado | Como cliente, quiero evaluar un servicio una vez que ha finalizado para expresar mi satisfacción con el trabajo realizado. | 5 |
| 32 | US-22 | Buscar reportes por filtros | Como administrador, quiero buscar reportes por nombre, tipo o estado para localizar información rápidamente. | 3 |
| 33 | US-23 | Cambiar idioma del sistema | Como usuario internacional, quiero cambiar el idioma del sistema para usar la plataforma en mi idioma preferido. | 3 |
| 34 | US-24 | Ver reporte de servicio realizado | Como cliente, quiero ver el reporte de servicio detallado para saber qué reparaciones se hicieron en mi equipo. | 3 |
| 35 | US-34 | Iniciar sesión con Google mediante OAuth 2.0 (servicio externo de terceros) | Como nuevo usuario, quiero iniciar sesión o registrarme con mi cuenta de Google mediante OAuth 2.0 para acceder a la plataforma sin crear una contraseña adicional. | 5 |
| 36 | US-30 | Recibir y aceptar asignación de servicio en la aplicación móvil | Como técnico en campo, quiero recibir y aceptar las asignaciones de servicio desde la aplicación móvil multiplataforma para organizar mis visitas sin depender de la plataforma web. | 5 |
| 37 | US-31 | Registrar intervención técnica desde la aplicación móvil en campo | Como técnico en campo, quiero registrar la intervención realizada desde la aplicación móvil, incluso con conectividad intermitente, para dejar constancia inmediata del mantenimiento ejecutado. | 8 |
| 38 | US-32 | Recibir y atender alertas push de anomalías térmicas en la aplicación móvil | Como técnico en campo, quiero recibir notificaciones push de alertas críticas en la aplicación móvil para acudir oportunamente a los equipos con riesgo de ruptura de la cadena de frío. | 5 |
| 39 | US-33 | Actualizar el estado del servicio y consultar telemetría desde la aplicación móvil | Como técnico en campo, quiero consultar el detalle del equipo y actualizar el estado del servicio desde la aplicación móvil para mantener la trazabilidad operativa durante el desplazamiento. | 5 |
| 40 | TS-06 | Integración de la aplicación móvil cross-platform con la API RESTful | Como desarrollador, quiero implementar la aplicación móvil multiplataforma (cross-platform) integrada con la API RESTful para que el técnico en campo opere con los mismos datos que la plataforma web. | 8 |

# Capítulo IV: Solution Software Design

En este capítulo presentamos el diseño de la solución de software de IceTrack. Primero aplicamos un enfoque estratégico de Domain-Driven Design, con el que identificamos los bounded contexts, sus relaciones y la arquitectura general del sistema. Luego bajamos al nivel táctico, donde detallamos las capas, los componentes y los modelos de cada contexto.

## 4.1. Strategic-Level Domain-Driven Design

En esta sección aplicamos el DDD estratégico para dividir el dominio de IceTrack en contextos con responsabilidades claras. Con el EventStorming a nivel de diseño descubrimos los bounded contexts y los flujos de mensajes entre ellos, los documentamos en los Bounded Context Canvases y definimos sus relaciones mediante el Context Mapping. Finalmente, representamos la arquitectura del sistema con los diagramas de System Landscape, Context, Container y Deployment.

### 4.1.1. Design-Level EventStorming

En esta sección se aplican las técnicas de EventStorming para poder identificar los distintos Bounded Context dentro del dominio de la aplicación, asi como las interacciones y dependencias entre ellos. Esto nos permite tener una visión clara de cómo se estructura los distintos componentes y cómo se comunican entre sí.

#### 4.1.1.1. Candidate Context Discovery

En esta sección aplicamos la técnica de Candidate Discovery para identificar y separar los posibles Bounded Context. Esto divide el trabajo en subramas donde se trabajan distintas funcionalidades por separado.

Con esto, nos llevó a crear los siguientes Bounded Context:

| Bounded Context | Descripción | Eventos Clave |
| :--- | :--- | :--- |
| IAM | Contexto donde se maneja la autenticación de los usuarios (dueños de negocio, proveedores de mantenimiento y técnicos), el registro de cuentas y la validación de credenciales mediante JWT. | Usuario Registrado, Sesión Iniciada |
| Profiles and Preferences Management | Contexto donde se administran los datos personales y profesionales de dueños y técnicos (nombre, contacto, especialidad), así como las preferencias de presentación de cada usuario: disposición y visibilidad de las tarjetas de su panel de control, rango de temperatura preferido e idioma de la interfaz. | Perfil Creado, Perfil Actualizado, Configuración de Dashboard Actualizada |
| Assets Management | Contexto donde se administran las sedes (Sites) de un dueño de negocio y el catálogo de equipos de refrigeración instalados en ellas, incluyendo el umbral de temperatura de cada equipo y su intervalo de mantenimiento preventivo. | Sitio Creado, Equipo Registrado, Umbral de Temperatura Actualizado |
| Monitoring and Alerting | Contexto núcleo del negocio. Ingiere la telemetría agregada enviada por los dispositivos IoT, mantiene el histórico de lecturas de cada equipo y gestiona el ciclo de vida completo de una alerta —térmica o de conectividad— desde que se detecta hasta que se resuelve. | Lectura Registrada, Alerta Generada, Alerta Resuelta |
| Device Management | Contexto donde se administra el ciclo de vida del hardware físico (placas IoT): registro, emparejamiento con un equipo, rotación de credenciales de acceso y baja del dispositivo. | Dispositivo Registrado, Dispositivo Emparejado, Dispositivo Dado de Baja |
| Service Request Management | Contexto donde se gestiona el ciclo de vida completo de una solicitud de mantenimiento —creación, aceptación, asignación de técnico, registro de intervenciones en campo y finalización—, así como la calificación que el cliente otorga al servicio recibido una vez completado. | Solicitud Creada, Solicitud Completada, Reseña Creada |
| Notifications | Contexto donde se generan y gestionan las notificaciones dirigidas a cada usuario, ya sea por mantenimiento vencido, alertas de monitoreo o actualizaciones de una solicitud de servicio. | Notificación Generada, Notificación Leída, Notificación Descartada |
| Reporting & Analytics | Contexto donde se calculan indicadores de negocio a partir de la información de los demás contextos: cumplimiento de mantenimiento, tiempo de actividad de los equipos y desempeño de los técnicos. | Reporte Generado |

#### 4.1.1.2. Domain Message Flows Modeling

El Domain Message Flow Modeling es una técnica que nos permite representar cómo fluyen los mensajes de dominios (comandos, eventos y consultas) entre los distintos Bounded Context. Esto se hace con el objetivo de especificar dentro de el entorno las dependencias y responsabilidades de cada uno de los contextos.

**Escenario 01: Registro y la Creación de Dashboard**

![Domain Message Flow - Escenario 1](assets/chapter04/userFlow/flow.png)

**Escenario 02: Crear/Registrar Equipo en el Sitio**
![Domain Message Flow - Escenario 2](assets/chapter04/userFlow/flow2.png)

**Escenario 03: Crear Solicitud de Servicio referenciando un Equipo**
![Domain Message Flow - Escenario 3](assets/chapter04/userFlow/flow3.png)

**Escenario 04: Generar Reporte de cumplimiento**
![Domain Message Flow - Escenario 4](assets/chapter04/userFlow/flow4.png)

**Escenario 05: Emparejar dispositivo IoT a un Equipo**
![Domain Message Flow - Escenario 5](assets/chapter04/userFlow/flow5.png)

#### 4.1.1.3. Bounded Context Canvases

El Bounded Context Canvas es una herramienta que se aplica dentro del marco del DDD (Domain-Driven Design) que nos permite representar de manera clara los límites, las responsabilidades e interacciones de cada contexto dentro de un sistema que pueda llegar a ser complejo.

En esta sección se representan los Bounded Context correspondientes a los contextos identificados dentro de la aplicación a trabajar:


**IAM (Identity and Access Management)**
![Bounded Context Canvas - IAM](assets/chapter04/canvas/canva1.png)

**Profiles and Preferences Management**
![Bounded Context Canvas - Profiles and Preferences Management](assets/chapter04/canvas/canva2.png)

**Assets Management**
![Bounded Context Canvas - Assets Management](assets/chapter04/canvas/canva3.png)

**Device Management**
![Bounded Context Canvas - Devices Management](assets/chapter04/canvas/canva4.png)

**Service Request Management**
![Bounded Context Canvas - Service Request Management](assets/chapter04/canvas/canva5.png)

**Notification Management**
![Bounded Context Canvas - Notification Management](assets/chapter04/canvas/canva6.png)

**Reporting and Analytics**
![Bounded Context Canvas - Reporting and Analysis Management](assets/chapter04/canvas/canva7.png)

**Monitoring and Alerting**
![Bounded Context Canvas - Monitoring and Alerting Management](assets/chapter04/canvas/canva8.png)

### 4.1.2. Context Mapping

El Context Mapping es la técnica de DDD estratégico que permite visualizar las relaciones e integraciones entre los Bounded Context identificados, así como con sistemas externos. Define quién es Upstream (U: proveedor del modelo/datos) y quién es Downstream (D: consumidor), y qué patrón de integración se aplica: Conformist (CF), Anticorruption Layer (ACL), Open Host Service (OHS) y Published Language (PL).

![Context Map de IceTrack - Relaciones entre Bounded Context](assets/chapter04/diagrams/contextMapping/ContextMapping.png)

En conjunto, el mapa muestra una arquitectura fuertemente centrada en **Monitoring como Core Domain**, con **Service como segundo núcleo operativo**, y con **Notification y Reporting como contextos de soporte o consumo** que dependen de casi todos los demás. **IAM y Google** actúan como contextos genéricos de soporte a la entrada del sistema, mientras **Asset y Device** forman la base física IoT. La elección homogénea de Conformist con ACL es coherente para un equipo único y una plataforma centralizada: simplifica la integración al imponer el modelo Upstream, pero delega en cada Downstream la responsabilidad de traducir y protegerse mediante ACL, lo que facilita la evolución independiente de cada Bounded Context.

### 4.1.3. Software Architecture

En esta sección se presentan los diagramas de arquitectura de software que representan la estructura y organización del sistema, incluyendo los componentes principales, sus relaciones y la forma en que interactúan entre sí.

#### 4.1.3.1. Software Architecture System Landscape Diagram

El System Landscape Diagram presenta una vista de alcance del sistema IceTrack y su entorno, delimitando lo que pertenece a la solución y lo que es externo a ella. 

![IceTrack System Landscape Diagram](assets/chapter04/diagrams/systemLandscape/IceTrackSystemLandscape.png)

En conjunto, el landscape justifica el alcance del MVP: adquisición propia con hardware ESP32 y DS18B20/DHT22, procesamiento Edge con resiliencia offline, plataforma Cloud para telemetría, alertas y servicios, Landing pública para adquisición y delegación de identidad a Google, dejando la integración con controladores legacy como roadmap.

#### 4.1.3.2. Software Architecture Context Level Diagrams

El Context Level Diagram muestra la relación entre el sistema IceTrack y los actores externos que interactúan con él, incluyendo usuarios, sistemas de terceros y dispositivos IoT.

![IceTrack Context Level Diagram](assets/chapter04/c4/context/IceTrackSystemContext.png)

#### 4.1.3.3. Software Architecture Container Level Diagrams

El Container Level Diagram muestra los contenedores de software que componen el sistema IceTrack, incluyendo aplicaciones web, servicios backend, bases de datos y otros componentes relevantes.

![IceTrack Container Level Diagram](assets/chapter04/c4/container/IceTrackContainer.png)

#### 4.1.3.4. Software Architecture Deployment Diagrams

El Deployment Diagram muestra la infraestructura de despliegue del sistema IceTrack, incluyendo nodos cloud, dispositivos IoT Edge (ESP32), base de datos y servicios externos como Google OAuth 2.0.

![IceTrack Deplyment Level Diagram](assets/chapter04/c4/Deployment.png)

## 4.2. Tactical-Level Domain-Driven Design

En esta sección se aplican las técnicas de DDD a nivel táctico para diseñar la arquitectura de software de cada uno de los Bounded Context identificados en la sección anterior. Esto incluye la definición de las capas de cada contexto, los componentes que lo conforman y cómo interactúan entre sí. También se incluyen diagramas de componentes y diagramas de código para cada contexto, lo que permite una mayor claridad en la implementación de cada uno de los contextos y su integración con el resto del sistema.

### 4.2.1. Bounded Context: Identity and Access Management

En el Bounded Context de IAM se manejan todas las funcionalidades relacionadas con la gestión de identidades, autenticación y autorización de los usuarios dentro del sistema. Esto incluye el registro de usuarios, la asignación de roles y permisos, y la verificación de credenciales para el acceso a la aplicación. Es un contexto de soporte genérico, Upstream de Profiles.

#### 4.2.1.1. Domain Layer.
La Domain Layer del bounded context **IAM** concentra las reglas de negocio de identidad y acceso, y es independiente de frameworks, base de datos y servicios externos. Su modelo gira en torno a un único aggregate, **User**, que representa a la persona registrada en la plataforma (dueño de negocio o proveedor de mantenimiento).

**Aggregate Root**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `User` | Aggregate Root / Entity | Representa a la persona registrada en el sistema. Es la única puerta de entrada para modificar el estado de una cuenta y garantiza sus invariantes. |

Atributos de `User`:

| Atributo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id` | `UUID` | Identificador único de la cuenta. |
| `username` | `String` | Nombre de usuario con el que la persona inicia sesión. |
| `passwordHash` | `String` | Hash de la contraseña. Nunca se almacena la contraseña en texto plano. |
| `role` | `String` | Rol asignado al usuario (`Owner` o `Provider`). |

Métodos de `User`:

| Método | Descripción |
| :--- | :--- |
| `authenticate(pass: String): boolean` | Verifica que la contraseña ingresada corresponda con el hash almacenado. Es la regla central para validar credenciales. |

**Value Objects y enumeraciones**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `Role` | Enum / Value Object | Define los roles válidos dentro del contexto: `Owner` (dueño o cliente de los equipos de refrigeración) y `Provider` (empresa de mantenimiento). El rol se asigna una sola vez, en el registro. |

**Comandos y consultas del dominio**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `SignUpCommand` | Command (record) | Solicita el registro de una cuenta nueva (username, contraseña y rol). |
| `SignInCommand` | Command (record) | Solicita la autenticación con credenciales. |
| `RefreshTokenCommand` | Command (record) | Solicita renovar el token de acceso. |
| `AssignRoleCommand` | Command (record) | Asigna el rol al usuario en el momento del registro. |
| `GetUserByIdQuery` | Query (record) | Consulta una cuenta por su identificador. |
| `GetUserByUsernameQuery` | Query (record) | Consulta una cuenta por su nombre de usuario. |

**Domain Events**

| Evento | Descripción |
| :--- | :--- |
| `UserRegisteredEvent` | Se emite cuando una cuenta se crea correctamente. Lo consumen otros contextos, principalmente Profiles and Preferences Management, para crear el perfil asociado. |

**Domain Services (interfaces)**

| Interfaz | Descripción |
| :--- | :--- |
| `UserCommandService` | Contrato de las operaciones que cambian el estado: registro (`SignUpCommand`) e inicio de sesión (`SignInCommand`). |
| `UserQueryService` | Contrato de las operaciones de lectura de cuentas (`GetUserByIdQuery`). |

**Repositories (interfaces)**

| Interfaz | Descripción |
| :--- | :--- |
| `UserRepository` | Abstracción de persistencia del aggregate `User`. El dominio solo conoce esta interfaz. Su implementación pertenece a la Infrastructure Layer. |

**Reglas de negocio del dominio**

- El `username` es único en todo el sistema.
- El `role` se asigna una sola vez, al registrarse, y no puede cambiarse después.
- La autorización es binaria: el acceso se concede o se deniega según la validez del JWT.
- La contraseña se almacena únicamente como hash.

**Factories:** no se requieren factories separadas. La creación del `User` se resuelve en el `UserCommandServiceImpl`, que aplica las reglas de registro antes de persistir el aggregate.

#### 4.2.1.2. Interface Layer.

La Interface Layer expone las capacidades del contexto IAM hacia el exterior. Recibe las solicitudes HTTP que el **API Gateway** enruta tras validar el JWT o la API key. Traduce los recursos REST a comandos y consultas del dominio, y devuelve las respuestas. Se organiza en cuatro subpaquetes: `controllers`, `resources`, `assemblers` y `acl`.

**Controllers**

| Clase | Descripción |
| :--- | :--- |
| `AuthenticationController` | Controlador REST de registro, inicio de sesión y renovación de token. Cubre las historias US-01 (Registro de usuario), US-02 (Inicio de sesión) y TS-04 (Registro de usuario vía API RESTful). Depende de `UserCommandService` y `UserQueryService`. |

Métodos de `AuthenticationController`:

| Método | Descripción |
| :--- | :--- |
| `signUp(res: SignUpResource): ResponseEntity<UserResource>` | Recibe los datos de registro, los convierte en un `SignUpCommand`, invoca al servicio de comandos y devuelve la cuenta creada. |
| `signIn(res: SignInResource): ResponseEntity<TokenResource>` | Recibe las credenciales, las convierte en un `SignInCommand` y devuelve el token de acceso. |

**Resources (records)**

| Clase | Descripción |
| :--- | :--- |
| `SignUpResource` | Datos de entrada para el registro (username, contraseña y rol). |
| `SignInResource` | Datos de entrada para el inicio de sesión (username y contraseña). |
| `UserResource` | Representación de una cuenta en las respuestas. No expone el hash de la contraseña. |
| `TokenResource` | Representación del token de acceso (JWT) devuelto tras autenticarse. |

**Assemblers**

| Clase | Método | Descripción |
| :--- | :--- | :--- |
| `AuthenticationAssembler` | `toCommandFromResource(resource: SignUpResource): SignUpCommand` | Transforma el recurso de registro en el comando del dominio. |
| `AuthenticationAssembler` | `toCommandFromResource(resource: SignInResource): SignInCommand` | Transforma el recurso de inicio de sesión en el comando del dominio. |
| `UserAssembler` | `toResourceFromEntity(entity: User): UserResource` | Convierte el aggregate `User` en el recurso de respuesta. |

**ACL / Facade (inbound services)**

| Clase | Descripción |
| :--- | :--- |
| `IamContextFacade` | Fachada que expone a los demás bounded contexts la consulta de cuentas y roles sin revelar el aggregate `User`. Depende de `UserQueryService`. |

Método de `IamContextFacade`:

| Método | Descripción |
| :--- | :--- |
| `fetchUserIdByUsername(username: String): Optional<UUID>` | Devuelve el identificador de un usuario a partir de su username, para que otros contextos referencien la cuenta sin acceder al modelo interno de IAM. |


#### 4.2.1.3. Application Layer.

La Application Layer orquesta los flujos del negocio del contexto IAM. Recibe los comandos y consultas de la Interface Layer, coordina al aggregate `User`, los repositorios y los servicios externos, y reacciona a eventos. No contiene reglas de negocio propias: las delega en el dominio. Implementa las capabilities del contexto: **registro de cuentas, autenticación con credenciales o Google OAuth 2.0, emisión de tokens y consulta de cuentas**.

**Command Services**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `UserCommandServiceImpl` | `UserCommandService` | Ejecuta los procesos que modifican el estado de las cuentas. |

Dependencias de `UserCommandServiceImpl`:

| Dependencia | Uso |
| :--- | :--- |
| `UserRepository` | Persistir y consultar el aggregate `User`. |
| `GoogleTokenService` | Validar el token de Google y obtener la identidad federada. |
| `HashingService` | Generar y verificar el hash de las contraseñas. |

Manejadores de comandos:

| Método | Flujo |
| :--- | :--- |
| `handle(cmd: SignUpCommand): Optional<User>` | 1) Verifica que el username no exista. 2) Genera el hash de la contraseña con `HashingService`. 3) Asigna el rol (`AssignRoleCommand`). 4) Crea y persiste el `User`. 5) Publica `UserRegisteredEvent`. Si el registro es con Google, valida antes la identidad con `GoogleTokenService`. |
| `handle(cmd: SignInCommand): Optional<TokenDTO>` | 1) Busca al usuario por username. 2) Valida las credenciales con `User.authenticate(pass)`, o el token de Google si el ingreso es federado. 3) Emite el JWT y lo devuelve en un `TokenDTO`. |
| `handle(cmd: RefreshTokenCommand)` | Renueva el token de acceso a partir de una sesión vigente. |

**Query Services**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `UserQueryServiceImpl` | `UserQueryService` | Resuelve las consultas de lectura sobre cuentas usando `UserRepository`. |

Manejadores de consultas:

| Método | Descripción |
| :--- | :--- |
| `handle(q: GetUserByIdQuery): Optional<User>` | Devuelve la cuenta que corresponde al identificador. |
| `handle(q: GetUserByUsernameQuery): Optional<User>` | Devuelve la cuenta que corresponde al username. Es la consulta que usa `IamContextFacade`. |

**Event Handlers**

| Clase | Descripción |
| :--- | :--- |
| `UserRegisteredEventHandler` | Escucha `UserRegisteredEvent` (`on(event: UserRegisteredEvent): void`) y solicita al contexto **Profiles and Preferences Management** la creación del perfil y las preferencias iniciales del usuario. Así se cumple el flujo de registro y creación de dashboard, sin acoplar IAM al modelo de Profiles. |

**Outbound Services (ACL)**

| Clase | Descripción |
| :--- | :--- |
| `ProfilesExternalService` | Anti-Corruption Layer que solicita al contexto Profiles la creación del perfil una vez que la cuenta existe. |
| `GoogleIdentityExternalService` | Anti-Corruption Layer que traduce los claims del token de Google OAuth 2.0 al modelo de identidad de la plataforma, sin filtrar detalles del proveedor al dominio. |

#### 4.2.1.4. Infrastructure Layer.

La Infrastructure Layer contiene las clases que acceden a recursos técnicos externos: la base de datos y los servicios de terceros. Implementa las abstracciones definidas en el dominio, de modo que el modelo no dependa de tecnologías concretas.

**Persistencia (Repositories)**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `SpringDataJpaUserRepository` | `UserRepository` | Implementación con Spring Data JPA del repositorio del aggregate `User`. Opera sobre el esquema `iam` de la instancia PostgreSQL v18 (Platform Database), que mantiene un esquema por bounded context. |

Responsabilidades de `SpringDataJpaUserRepository`:

- Guardar, actualizar y consultar cuentas de usuario.
- Buscar usuarios por identificador y por username.
- Verificar la unicidad del username antes del registro.

**Servicios de seguridad**

| Clase | Descripción |
| :--- | :--- |
| `HashingService` (implementación) | Genera y verifica el hash de las contraseñas usando un algoritmo de hashing de Spring Security. Lo consume `UserCommandServiceImpl`. |
| Servicio de tokens JWT | Firma y valida los JWT emitidos tras la autenticación. El API Gateway los valida en cada solicitud antes de enrutarla al controlador. |

**Integraciones con servicios externos**

| Clase | Descripción |
| :--- | :--- |
| `GoogleTokenService` (implementación) | Se comunica por HTTPS con **Google Identity Platform** para validar el token OAuth 2.0 y recuperar la identidad federada del usuario. Es el adaptador técnico que usa `GoogleIdentityExternalService`. |
| Adaptador hacia Profiles | Implementa la comunicación con el contexto Profiles and Preferences Management, para la creación del perfil tras el registro. |

**Resumen de dependencias externas**

| Recurso externo | Tipo | Uso en IAM |
| :--- | :--- | :--- |
| PostgreSQL v18 (esquema `iam`) | Base de datos relacional | Persistencia de cuentas de usuario. |
| Google Identity Platform | Proveedor de identidad OAuth 2.0 | Registro e inicio de sesión con cuenta de Google. |
| Profiles and Preferences Management | Bounded context interno | Creación del perfil una vez registrada la cuenta. |

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams.

En el siguiente diagrama de componentes mostramos cómo organizamos internamente el bounded context Identity and Access Management. Se observa el Authentication Controller que recibe las solicitudes desde el API Gateway, los servicios de comandos y consultas de usuario, el aggregate User con su repositorio y la fachada que expone la información de cuentas y roles a los demás contextos. También se muestran las integraciones con Google Identity Platform y con Profiles and Preferences Management, ambas protegidas mediante capas anticorrupción, y el esquema `iam` de la base de datos.

![IceTrack Bounded Context Component Level Diagram - IAM](assets/chapter04/c4/component/iamComponent.png)

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams.

En esta sección presentamos los diagramas de nivel de código del bounded context Identity and Access Management. Estos diagramas bajan al detalle de implementación: el diagrama de clases de la capa de dominio y el diseño de la base de datos que respalda el modelo.

##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams.

El siguiente diagrama de clases representa la estructura del contexto IAM organizada por capas. En el dominio se encuentra el aggregate `User` con sus atributos y la regla de autenticación, junto con las interfaces de servicios y del repositorio. Sobre ellas se ubican los servicios de comandos y consultas y el manejador del evento de usuario registrado en la capa de aplicación, los controladores, assemblers, recursos y la fachada en la capa de interfaces, y la implementación JPA del repositorio en la capa de infraestructura.

![IceTrack Bounded Context Domain Layer Class Diagram - IAM](assets/chapter04/diagrams/class/iamDiagramClass.png)

##### 4.2.1.6.2. Bounded Context Database Design Diagram.

El siguiente diagrama presenta el diseño de la base de datos del esquema `iam`, donde persistimos las cuentas de usuario junto con su nombre de usuario, el hash de la contraseña y el rol asignado.

![IceTrack Bounded Context Database Design Diagram - IAM](assets/chapter04/diagrams/database/iamDiagramDatabase.png)

---

### 4.2.2. Bounded Context: Profiles and Preferences Management

En el bounded context Profiles and Preferences Management administramos los datos personales y profesionales de los dueños de negocio y de los técnicos, así como las preferencias de presentación de cada usuario: la disposición de las tarjetas del dashboard, el rango de temperatura preferido y el idioma de la interfaz. Es un contexto de soporte que recibe la información de la cuenta desde IAM, y que a su vez sirve datos de contacto y de disponibilidad de técnicos a Notification Management y a Service Request Management.

#### 4.2.2.1. Domain Layer.
La Domain Layer del bounded context **Profiles and Preferences Management** contiene el modelo de los datos personales y profesionales de dueños y técnicos, y el de las preferencias de presentación de cada usuario. Está organizada en dos aggregates independientes: **Profile**, con sus especializaciones `OwnerProfile` y `TechnicianProfile`, y **DashboardConfig**, que agrupa la configuración del panel de control y del idioma. Ambos se asocian al usuario de IAM mediante `userId`, sin depender del modelo interno de ese contexto.

**Aggregate Roots**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `Profile` | Aggregate Root (clase abstracta) | Representa los datos descriptivos de una persona dentro de la plataforma. Es abstracta y se especializa según el rol asignado en IAM. |
| `OwnerProfile` | Entity (especialización de `Profile`) | Perfil del dueño de negocio (cliente). Agrega el RUC del negocio. |
| `TechnicianProfile` | Entity (especialización de `Profile`) | Perfil del técnico. Agrega su especialidad y su número de certificación, y se vincula al perfil del proveedor al que pertenece. |
| `DashboardConfig` | Aggregate Root | Configuración de presentación de un usuario: tarjetas del dashboard con su orden y visibilidad, rango de temperatura preferido e idioma de la interfaz. Existe una configuración por usuario. |

Atributos de `Profile`:

| Atributo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id` | `UUID` | Identificador único del perfil. |
| `userId` | `UUID` | Referencia a la cuenta de usuario del contexto IAM. |
| `fullName` | `String` | Nombre completo de la persona. |
| `email` | `Email` (Value Object) | Correo de contacto. |
| `phone` | `Phone` (Value Object) | Teléfono de contacto. |
| `address` | `Address` (Value Object) | Dirección de la persona o del negocio. |

Atributos específicos de las especializaciones:

| Clase | Atributo | Descripción |
| :--- | :--- | :--- |
| `OwnerProfile` | `ruc` | Registro Único de Contribuyente del negocio del dueño. |
| `TechnicianProfile` | `speciality` | Especialidad técnica del técnico (por ejemplo, refrigeración comercial). |
| `TechnicianProfile` | `certificationNumber` | Número de certificación del técnico. |
| `TechnicianProfile` | `providerProfileId` | Referencia al perfil del proveedor al que pertenece el técnico. |

Atributos de `DashboardConfig`:

| Atributo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id` | `UUID` | Identificador único de la configuración. |
| `userId` | `UUID` | Usuario propietario de la configuración. |
| `layout` | `String` | Disposición de las tarjetas del dashboard (orden y visibilidad). |
| `temperatureRange` | `TemperatureRange` | Rango de temperatura preferido por el usuario. |
| `locale` | `Locale` | Idioma de la interfaz (ES o EN). |

**Value Objects**

| Clase | Descripción |
| :--- | :--- |
| `Email` | Correo electrónico validado. |
| `Phone` | Número de teléfono de contacto. |
| `Address` | Dirección postal o de ubicación. |
| `TemperatureRange` | Rango de temperatura mínima y máxima preferido para visualizar los equipos. |
| `Locale` | Idioma de la interfaz de usuario (US-23). |
| `DashboardCard` | Tarjeta del panel, con su orden y su visibilidad dentro del layout. |

**Commands y Queries del dominio**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `CreateProfileCommand` | Command (record) | Crea el perfil de un usuario recién registrado. |
| `UpdateProfileInfoCommand` | Command (record) | Actualiza los datos descriptivos del perfil. |
| `AddCardCommand` | Command (record) | Agrega una tarjeta al dashboard. |
| `RemoveCardCommand` | Command (record) | Quita una tarjeta del dashboard. |
| `ChangeVisibilityCommand` | Command (record) | Muestra u oculta una tarjeta. |
| `UpdateDashboardLayoutCommand` | Command (record) | Actualiza la disposición y el orden de las tarjetas. |
| `ChangeLocaleCommand` | Command (record) | Cambia el idioma de la interfaz. |
| `GetProfileByUserIdQuery` | Query (record) | Obtiene el perfil asociado a un usuario. |
| `GetProfileByIdQuery` | Query (record) | Obtiene un perfil por su identificador. |
| `GetAvailableTechniciansBySpecialityQuery` | Query (record) | Lista los técnicos disponibles según su especialidad. |
| `GetDashboardConfigByUserIdQuery` | Query (record) | Obtiene la configuración del dashboard de un usuario. |

**Domain Services y Factories**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `UserProfileFactory` | Factory / Domain Service | Construye un `OwnerProfile` o un `TechnicianProfile` a partir de los datos de registro, según el rol asignado en IAM. Encapsula la decisión de qué especialización crear. |
| `ProfileCommandService` | Domain Service (interfaz) | Contrato de las operaciones que crean y actualizan perfiles. |
| `ProfileQueryService` | Domain Service (interfaz) | Contrato de las consultas de perfiles y de disponibilidad de técnicos. |
| `DashboardConfigCommandService` | Domain Service (interfaz) | Contrato de las operaciones que modifican la configuración del dashboard y del idioma. |

**Repositories (interfaces)**

| Interfaz | Descripción |
| :--- | :--- |
| `ProfileRepository` | Abstracción de persistencia del aggregate `Profile` y sus especializaciones. |
| `DashboardConfigRepository` | Abstracción de persistencia del aggregate `DashboardConfig`. |

**Domain Events**

| Evento | Descripción |
| :--- | :--- |
| `Perfil Creado` | Se emite cuando se crea el perfil de un usuario. |
| `Perfil Actualizado` | Se emite cuando cambian los datos descriptivos del perfil. |
| `Configuración de Dashboard Actualizada` | Se emite cuando el usuario modifica su dashboard o su idioma. |

**Reglas de negocio del dominio**

- Cada perfil pertenece a un único usuario de IAM (`userId`).
- El tipo de perfil (`OwnerProfile` o `TechnicianProfile`) se define por el rol asignado en IAM al registrarse.
- Un `OwnerProfile` requiere un RUC. Un `TechnicianProfile` requiere especialidad y número de certificación.
- Cada usuario tiene una única configuración de dashboard, asociada de manera individual.

#### 4.2.2.2. Interface Layer.

La Interface Layer expone las capacidades del contexto hacia el exterior. Recibe las solicitudes HTTP que el **API Gateway** enruta después de validar el JWT, y publica una fachada para los demás bounded contexts. Se organiza en los subpaquetes `controllers`, `resources`, `assemblers` y `acl`.

**Controllers**

| Clase | Descripción |
| :--- | :--- |
| `ProfileController` | Controlador REST del *Profile Endpoint* (GET, POST, PUT). Gestiona la creación y actualización de perfiles y cubre las historias US-07 (registro y gestión de técnicos) y US-08 (consulta del perfil de un técnico). Depende de `ProfileCommandService` y `ProfileQueryService`. |
| `PreferencesController` | Controlador REST del *Preferences Endpoint* (GET, POST, PUT). Gestiona la disposición del dashboard y el idioma de la interfaz, y cubre las historias US-23 (cambio de idioma) y US-25 (métricas del dashboard). Depende de los servicios de configuración del dashboard. |

Métodos principales:

| Clase | Método | Descripción |
| :--- | :--- | :--- |
| `ProfileController` | `createOwner(res: CreateOwnerProfileRequest): ResponseEntity<ProfileResponse>` | Recibe los datos del dueño, los convierte en un `CreateProfileCommand` y devuelve el perfil creado. |

**Resources (records)**

| Clase | Descripción |
| :--- | :--- |
| `CreateOwnerProfileRequest` | Datos de entrada para crear el perfil de un dueño. |
| `ProfileResponse` | Representación del perfil en las respuestas de la API. |

**Assemblers**

| Clase | Método | Descripción |
| :--- | :--- | :--- |
| `ProfileAssembler` | `toResourceFromEntity(entity: Profile): ProfileResponse` | Convierte el aggregate `Profile` en el recurso de respuesta. |
| `ProfileAssembler` | `toCommandFromResource(resource: CreateOwnerProfileRequest): CreateProfileCommand` | Transforma el recurso de creación en el comando del dominio. |

**ACL / Facade (inbound services)**

| Clase | Descripción |
| :--- | :--- |
| `ProfilesContextFacade` | Fachada que expone a otros bounded contexts la creación de perfiles, los datos de contacto y la disponibilidad de técnicos, sin revelar el modelo interno. Depende de `ProfileQueryService`. |

Método de `ProfilesContextFacade`:

| Método | Descripción |
| :--- | :--- |
| `isTechnicianAvailable(technicianId: UUID): boolean` | Indica si un técnico está disponible para ser asignado a una solicitud de servicio. |

Consumidores de la fachada:

| Contexto consumidor | Uso |
| :--- | :--- |
| Identity and Access Management | Solicita la creación del perfil cuando se registra una cuenta de usuario. |
| Notification Management | Resuelve los datos de contacto y el idioma del destinatario de una notificación. |
| Service Request Management | Consulta la especialidad y la disponibilidad de los técnicos al asignar una solicitud. |

#### 4.2.2.3. Application Layer.

La Application Layer orquesta los flujos del contexto. Recibe los comandos y consultas de la Interface Layer, coordina los aggregates y los repositorios, y delega en el dominio las reglas de negocio. Sus capabilities son **crear y actualizar perfiles, consultar perfiles y disponibilidad de técnicos, y administrar la configuración del dashboard y del idioma**.

**Command Services**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `ProfileCommandServiceImpl` | `ProfileCommandService` | Ejecuta los procesos de creación y actualización de perfiles. Depende de `ProfileRepository`. |
| `DashboardConfigCommandServiceImpl` | `DashboardConfigCommandService` | Ejecuta los procesos que modifican el dashboard y el idioma. Depende de `DashboardConfigRepository`. |

Manejadores de comandos:

| Clase | Método | Flujo |
| :--- | :--- | :--- |
| `ProfileCommandServiceImpl` | `handle(cmd: CreateProfileCommand): Optional<Profile>` | 1) Recibe los datos de registro y el rol del usuario. 2) Usa `UserProfileFactory` para construir el `OwnerProfile` o el `TechnicianProfile`. 3) Persiste el perfil. 4) Registra el evento `Perfil Creado`. |
| `ProfileCommandServiceImpl` | `handle(cmd: UpdateProfileInfoCommand)` | Busca el perfil, actualiza sus datos y emite `Perfil Actualizado`. |
| `DashboardConfigCommandServiceImpl` | `handle(cmd: UpdateDashboardLayoutCommand): void` | Actualiza la disposición y el orden de las tarjetas del usuario y emite `Configuración de Dashboard Actualizada`. |
| `DashboardConfigCommandServiceImpl` | `handle(cmd: AddCardCommand / RemoveCardCommand / ChangeVisibilityCommand)` | Agrega, quita o cambia la visibilidad de una tarjeta del dashboard. |
| `DashboardConfigCommandServiceImpl` | `handle(cmd: ChangeLocaleCommand)` | Cambia el idioma de la interfaz del usuario. |

**Query Services**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `ProfileQueryServiceImpl` | `ProfileQueryService` | Resuelve las consultas de lectura de perfiles y de disponibilidad de técnicos. |
| `DashboardConfigQueryService` | — | Resuelve la consulta de la configuración del dashboard de un usuario. |

Manejadores de consultas:

| Clase | Método | Descripción |
| :--- | :--- | :--- |
| `ProfileQueryServiceImpl` | `handle(q: GetProfileByIdQuery): Optional<Profile>` | Devuelve el perfil que corresponde al identificador. |
| `ProfileQueryServiceImpl` | `handle(q: GetProfileByUserIdQuery)` | Devuelve el perfil asociado a un usuario de IAM. |
| `ProfileQueryServiceImpl` | `handle(q: GetAvailableTechniciansBySpecialityQuery)` | Devuelve los técnicos disponibles de una especialidad. Lo usa Service Request Management para asignar técnicos. |
| `DashboardConfigQueryService` | `handle(q: GetDashboardConfigByUserIdQuery)` | Devuelve la configuración del dashboard del usuario. |

**Integración con otros contextos**

| Flujo | Descripción |
| :--- | :--- |
| Registro de usuario → creación de perfil | Cuando IAM registra una cuenta, solicita mediante `ProfilesContextFacade` la creación del perfil. Este contexto lo crea con el tipo correspondiente al rol y deja lista la configuración inicial del dashboard. |
| Notificaciones → datos del destinatario | Notification Management consulta la fachada para obtener los datos de contacto y el idioma del usuario que recibirá el mensaje. |
| Solicitudes de servicio → técnicos | Service Request Management consulta la especialidad y la disponibilidad de los técnicos antes de asignarlos. |

#### 4.2.2.4. Infrastructure Layer.

La Infrastructure Layer contiene las clases que acceden a la base de datos. Implementa las abstracciones de repositorio definidas en el dominio, de modo que el modelo no dependa de una tecnología concreta.

**Persistencia (Repositories)**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `SpringDataJpaProfileRepository` | `ProfileRepository` | Implementación con Spring Data JPA del repositorio de `Profile`, `OwnerProfile` y `TechnicianProfile`. |
| `SpringDataJpaDashboardConfigRepository` | `DashboardConfigRepository` | Implementación con Spring Data JPA del repositorio de `DashboardConfig`. |

Ambos repositorios operan sobre el esquema `profiles` de la instancia **PostgreSQL v18** (*Platform Database*), que mantiene un esquema por bounded context.

Responsabilidades de los repositorios:

- Guardar, actualizar y consultar perfiles por identificador y por `userId`.
- Consultar técnicos por especialidad y disponibilidad.
- Guardar y consultar la configuración del dashboard de cada usuario.

**Modelo de tablas del esquema `profiles`**

| Tabla | Columna | Tipo | Descripción |
| :--- | :--- | :--- | :--- |
| `Profile` | `profile_id` | `VARCHAR` (PK) | Identificador del perfil. |
| `Profile` | `full_name` | `VARCHAR(25)` | Nombre completo. |
| `Profile` | `email` | `VARCHAR(30)` | Correo de contacto. |
| `Profile` | `phone` | `CHAR` | Teléfono de contacto. |
| `Profile` | `user_id` | `VARCHAR` (FK) | Usuario de IAM asociado. |
| `OwnerProfile` | `profiles_id` | `VARCHAR` (PK/FK) | Referencia al perfil base. |
| `OwnerProfile` | `ruc` | `VARCHAR(10)` | RUC del negocio. |
| `TechnicianProfile` | `profile_id` | `VARCHAR` (PK/FK) | Referencia al perfil base. |
| `TechnicianProfile` | `speciality` | `VARCHAR(30)` | Especialidad del técnico. |
| `TechnicianProfile` | `certification_number` | `VARCHAR(30)` | Número de certificación. |
| `TechnicianProfile` | `provider_profiles_id` | `VARCHAR` | Perfil del proveedor al que pertenece. |

**Resumen de dependencias externas**

| Recurso | Tipo | Uso en Profiles and Preferences |
| :--- | :--- | :--- |
| PostgreSQL v18 (esquema `profiles`) | Base de datos relacional | Persistencia de perfiles y configuración de dashboard. |
| Identity and Access Management | Bounded context interno (Upstream) | Origen del `userId` y del rol que determina el tipo de perfil. |

#### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams.

En el siguiente diagrama de componentes mostramos cómo organizamos el contexto Profiles and Preferences en dos subdominios: Profile y DashboardConfiguration. Cada uno cuenta con su controlador, sus servicios de comandos y consultas, su aggregate y su repositorio. Se incluye también la fábrica que construye el perfil según el rol asignado, la fachada que expone el contexto a IAM, Notification y Service Request, y el esquema `profiles` de la base de datos.

![IceTrack Bounded Context Component Level Diagram - Profiles and Preferences Management](assets/chapter04/c4/component/profilesComponent.png)

#### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams.

En esta sección presentamos los diagramas de nivel de código del bounded context Profiles and Preferences Management: el diagrama de clases de la capa de dominio y el diseño de la base de datos del esquema `profiles`.

##### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams.

El siguiente diagrama de clases muestra el modelo de este contexto. El aggregate `Profile` es una clase abstracta que se especializa en `OwnerProfile` y `TechnicianProfile`, mientras que `DashboardConfig` agrupa la configuración del panel y del idioma de cada usuario. El diagrama incluye además los servicios de comandos y consultas, el controlador con su assembler y recursos, la fachada del contexto y los repositorios con su implementación JPA.

![IceTrack Bounded Context Domain Layer Class Diagram - Profiles and Preferences Management](assets/chapter04/diagrams/class/profileDiagramClass.png)

##### 4.2.2.6.2. Bounded Context Database Design Diagram.

El siguiente diagrama presenta el diseño de la base de datos del esquema `profiles`. La tabla `Profile` guarda los datos comunes de cada persona, y las tablas `OwnerProfile` y `TechnicianProfile` almacenan los datos propios de cada tipo de perfil, como el RUC del negocio o la especialidad y la certificación del técnico.

![IceTrack Bounded Context Database Design Diagram - Profiles and Preferences Management](assets/chapter04/diagrams/database/profileDiagramDatabase.png)

---

### 4.2.3. Bounded Context: Monitoring and Alerting

#### 4.2.3.1. Domain Layer.

La Domain Layer del bounded context **Monitoring and Alerting** contiene el modelo del **Core Domain** de IceTrack. Su función es recibir la telemetría de los dispositivos IoT, conservar el histórico de lecturas de cada equipo y gestionar el ciclo de vida completo de una alerta, ya sea térmica o de conectividad. El modelo se organiza en dos subdominios: **SensorReading**, para las lecturas, y **Alert**, para las alertas y sus reglas de evaluación.

**Aggregate Roots y Entities**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `Alert` | Aggregate Root | Representa una alerta sobre un equipo. Controla su ciclo de vida (`OPEN`, `ACKNOWLEDGED`, `RESOLVED`, `DISMISSED`) y garantiza las transiciones de estado válidas. |
| `SensorReading` | Entity (inmutable) | Lectura agregada enviada por un dispositivo. Una vez registrada no se modifica. |
| `AlertPolicy` | Entity | Política de evaluación configurada por equipo: define cuándo se abre o se cierra una alerta y cuándo se considera offline un dispositivo. |

Atributos de `Alert`:

| Atributo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id` | `UUID` | Identificador único de la alerta. |
| `equipmentId` | `UUID` | Equipo de refrigeración afectado (referencia al contexto Assets Management). |
| `severity` | `String` | Nivel de severidad de la alerta. |
| `status` | `String` | Estado actual: `OPEN`, `ACKNOWLEDGED`, `RESOLVED` o `DISMISSED`. |
| `type` | `AlertType` | Tipo de alerta: excursión térmica o `DEVICE_OFFLINE`. |
| `readingId` | `UUID` | Lectura que disparó la alerta. |
| `peakTemperature` | `Double` | Temperatura máxima alcanzada durante la excursión. |
| `excursionDuration` | `Integer` | Duración de la excursión, en minutos. |

Atributos de `SensorReading`:

| Atributo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id` | `UUID` | Identificador de la lectura. Se usa para descartar duplicados. |
| `equipmentId` | `UUID` | Equipo al que pertenece la lectura. |
| `deviceId` | `UUID` | Dispositivo IoT que la envió. |
| `temperature` | `Double` | Temperatura registrada. La lectura agregada incluye mínimo, máximo y promedio. |
| `humidity` | `Double` | Humedad registrada. |
| `sampleCount` | `Integer` | Cantidad de muestras agregadas en la lectura. |
| `recordedAt` | `DateTime` | Momento en que el dispositivo tomó la lectura. |
| `receivedAt` | `DateTime` | Momento en que la plataforma la recibió. |

Atributos de `AlertPolicy`:

| Atributo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id` | `UUID` | Identificador de la política. |
| `equipmentId` | `UUID` | Equipo al que aplica. |
| `sustainedExcursionMinutes` | `Integer` | Minutos fuera de rango necesarios para abrir una alerta. |
| `hysteresisMarginCelsius` | `Double` | Margen en °C para considerar que la temperatura volvió a rango. |
| `missedSyncForOffline` | `Integer` | Ventanas de sincronización perdidas para declarar el dispositivo offline. |
| `isActive` | `Boolean` | Indica si la política está vigente. |

**Value Objects y enumeraciones**

| Clase | Descripción |
| :--- | :--- |
| `AlertStatus` | Enum con los estados del ciclo de vida de una alerta. |
| `AlertType` | Enum con el tipo de alerta (térmica o de conectividad). |
| `Severity` | Nivel de severidad de una alerta. |
| `TemperatureReading` | Conjunto de valores de temperatura (mínimo, máximo y promedio) de una lectura agregada. |

**Commands y Queries del dominio**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `RecordReadingBatchCommand` | Command (record) | Registra un lote de lecturas agregadas enviadas por un dispositivo. |
| `RaiseAlertCommand` | Command (record) | Genera una alerta. |
| `AcknowledgeAlertCommand` | Command (record) | Marca una alerta como reconocida por un usuario. |
| `ResolveAlertCommand` | Command (record) | Cierra una alerta cuando la condición se normaliza. |
| `DismissAlertCommand` | Command (record) | Descarta una alerta. |
| `GetLastReadingByEquipmentQuery` | Query (record) | Obtiene la última lectura de un equipo. |
| `GetReadingsInRangeQuery` | Query (record) | Obtiene las lecturas de un equipo en un rango de fechas. |
| `GetLiveReadingsQuery` | Query (record) | Obtiene las lecturas en vivo para el dashboard. |
| `GetOpenAlertsByOwnerQuery` | Query (record) | Lista las alertas abiertas de un dueño de negocio. |
| `GetAlertByIdQuery` | Query (record) | Obtiene el detalle de una alerta. |
| `GetAlertsByEquipmentQuery` | Query (record) | Lista las alertas de un equipo. |

**Domain Services**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `ThresholdEvaluationService` | Domain Service | Aplica la política de excursión sostenida con histéresis. Abre una alerta cuando la temperatura permanece fuera de rango durante 2 minutos y la cierra cuando vuelve a rango, con un margen de 0.5 °C, durante 2 minutos. |
| `DeviceSilenceDetector` | Domain Service | Se ejecuta de forma programada. Marca un dispositivo como offline tras tres ventanas de sincronización perdidas y genera una alerta `DEVICE_OFFLINE`. |
| `ReadingCommandService` | Interfaz | Contrato del registro de lecturas. |
| `ReadingQueryService` | Interfaz | Contrato de las consultas de lecturas. |
| `AlertCommandService` | Interfaz | Contrato de las operaciones del ciclo de vida de una alerta. |
| `AlertQueryService` | Interfaz | Contrato de las consultas y filtros de alertas. |

**Repositories (interfaces)**

| Interfaz | Descripción |
| :--- | :--- |
| `ReadingRepository` | Abstracción de persistencia de las lecturas de sensores. |
| `AlertRepository` | Abstracción de persistencia del aggregate `Alert`. |

**Domain Events**

| Evento | Descripción |
| :--- | :--- |
| `Lectura Registrada` | Se emite cuando una lectura es validada y almacenada. |
| `Alerta Generada` | Se emite cuando se abre una alerta. |
| `Alerta Resuelta` | Se emite cuando la condición se normaliza y la alerta se cierra. |

**Reglas de negocio del dominio**

- Las lecturas son inmutables y se identifican por un UUID. Una lectura ya registrada no se vuelve a procesar.
- Una alerta térmica se abre cuando la temperatura permanece fuera del umbral del equipo durante el tiempo sostenido definido en la política.
- Una alerta térmica se cierra solo cuando la temperatura vuelve al rango con el margen de histéresis durante el tiempo sostenido. Esto evita alertas intermitentes.
- Un dispositivo se declara offline tras tres ventanas de sincronización perdidas, y se genera una alerta `DEVICE_OFFLINE`.
- El ciclo de vida de una alerta sigue los estados `OPEN`, `ACKNOWLEDGED`, `RESOLVED` y `DISMISSED`.
- El umbral de temperatura de cada equipo se obtiene de Assets Management y no se define en este contexto.

#### 4.2.3.2. Interface Layer.

La Interface Layer expone las capacidades del contexto. Recibe la telemetría de los dispositivos, transmite el estado en vivo hacia el dashboard y permite gestionar alertas. También publica una fachada para otros bounded contexts. Las solicitudes llegan a través del **API Gateway**, que valida el JWT en el tráfico de usuario y la API key en el tráfico de dispositivos.

**Controllers**

| Clase | Descripción |
| :--- | :--- |
| `TelemetryController` | Controlador REST del *Telemetry Endpoint* (POST). Recibe lecturas agregadas y eventos de alerta prioritarios desde el Edge, autenticados con la API key del dispositivo. Cubre la historia US-26. |
| `TelemetryStreamController` | Endpoint de **Server-Sent Events** que envía al dashboard las lecturas en vivo y el estado de las alertas con una latencia menor a 3 segundos. Cubre US-19, US-27 y RNF-02. |
| `AlertController` | Controlador REST del *Alert Endpoint* (GET, PUT). Permite listar alertas, ver su detalle y reconocerlas. Cubre US-28 y US-29. |

Métodos principales:

| Clase | Método | Descripción |
| :--- | :--- | :--- |
| `TelemetryController` | `ingest(req: TelemetryRequest): ResponseEntity<Void>` | Recibe el lote de lecturas, lo convierte en un `RecordReadingBatchCommand` y lo delega a `ReadingCommandService`. |
| `AlertController` | `acknowledge(id: UUID): ResponseEntity<Void>` | Convierte la solicitud en un `AcknowledgeAlertCommand` y lo delega a `AlertCommandService`. |

**Resources (records)**

| Clase | Descripción |
| :--- | :--- |
| `TelemetryRequest` | Datos de entrada enviados por el dispositivo (identificador de lectura, valores de temperatura y humedad, cantidad de muestras y marca de tiempo). |
| `AlertResponse` | Representación de una alerta en las respuestas de la API (severidad, estado, temperatura pico y duración). |

**ACL / Facade (inbound services)**

| Clase | Descripción |
| :--- | :--- |
| `MonitoringContextFacade` | Fachada que expone a otros contextos el detalle de alertas y el historial de lecturas, sin revelar el aggregate `Alert`. Depende de `AlertQueryService`. |

Método de `MonitoringContextFacade`:

| Método | Descripción |
| :--- | :--- |
| `getAlertStatus(id: UUID): String` | Devuelve el estado actual de una alerta a partir de su identificador. |

Consumidores de la fachada:

| Contexto consumidor | Uso |
| :--- | :--- |
| Service Request Management | Recupera el contexto de la alerta para generar una orden de trabajo correctiva. |
| Reporting and Analytics | Lee el historial de telemetría y los registros de alertas para calcular indicadores. |

#### 4.2.3.3. Application Layer.

La Application Layer orquesta los flujos del contexto. Recibe los comandos y consultas de la Interface Layer, coordina los aggregates, los repositorios y los servicios externos, y delega las reglas de negocio en el dominio. Sus capabilities son **ingerir telemetría, evaluar umbrales, detectar dispositivos sin señal, gestionar el ciclo de vida de las alertas y notificar a otros contextos**.

**Command Services**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `ReadingCommandServiceImpl` | `ReadingCommandService` | Valida, deduplica y almacena las lecturas, y dispara la evaluación de umbrales. Depende de `ReadingRepository` y `AlertCommandService`. |
| `AlertCommandServiceImpl` | `AlertCommandService` | Gestiona el ciclo de vida de las alertas y notifica a los contextos interesados. Depende de `AlertRepository` y del servicio externo de notificaciones. |

Manejadores de comandos:

| Clase | Método | Flujo |
| :--- | :--- | :--- |
| `ReadingCommandServiceImpl` | `handle(cmd: RecordReadingBatchCommand): void` | 1) Verifica la API key del dispositivo y obtiene su equipo emparejado mediante Device Management. 2) Descarta lecturas duplicadas por UUID. 3) Obtiene el umbral del equipo desde Assets Management. 4) Persiste las lecturas y registra `Lectura Registrada`. 5) Solicita la evaluación de excursión sostenida a `ThresholdEvaluationService`. |
| `AlertCommandServiceImpl` | `handle(cmd: RaiseAlertCommand): Optional<Alert>` | 1) Crea el aggregate `Alert` en estado `OPEN`, con severidad, tipo, lectura disparadora y temperatura pico. 2) Lo persiste. 3) Solicita la notificación mediante Notification Management. 4) Envía el nuevo estado al dashboard por el flujo SSE. 5) Registra `Alerta Generada`. |
| `AlertCommandServiceImpl` | `handle(cmd: AcknowledgeAlertCommand)` | Cambia la alerta a `ACKNOWLEDGED`. |
| `AlertCommandServiceImpl` | `handle(cmd: ResolveAlertCommand)` | Cambia la alerta a `RESOLVED`, notifica y registra `Alerta Resuelta`. |
| `AlertCommandServiceImpl` | `handle(cmd: DismissAlertCommand)` | Cambia la alerta a `DISMISSED`. |

**Query Services**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `ReadingQueryServiceImpl` | `ReadingQueryService` | Resuelve las consultas de lecturas históricas y en vivo. Depende de `ReadingRepository`. |
| `AlertQueryServiceImpl` | `AlertQueryService` | Resuelve las consultas y filtros de alertas. Depende de `AlertRepository`. |

Manejadores de consultas:

| Clase | Método | Descripción |
| :--- | :--- | :--- |
| `ReadingQueryServiceImpl` | `handle(q: GetLastReadingByEquipmentQuery)` | Devuelve la última lectura de un equipo. |
| `ReadingQueryServiceImpl` | `handle(q: GetReadingsInRangeQuery)` | Devuelve el historial de lecturas de un equipo en un rango. |
| `ReadingQueryServiceImpl` | `handle(q: GetLiveReadingsQuery)` | Devuelve las lecturas en vivo para el dashboard. |
| `AlertQueryServiceImpl` | `handle(q: GetOpenAlertsByOwnerQuery)` | Devuelve las alertas abiertas de un dueño. |
| `AlertQueryServiceImpl` | `handle(q: GetAlertByIdQuery)` | Devuelve el detalle de una alerta. |
| `AlertQueryServiceImpl` | `handle(q: GetAlertsByEquipmentQuery)` | Devuelve las alertas de un equipo. |

**Flujos automáticos y eventos**

| Flujo | Descripción |
| :--- | :--- |
| Excursión térmica | Tras registrar una lectura, `ThresholdEvaluationService` aplica la política. Si la temperatura lleva 2 minutos fuera de rango, se emite un `RaiseAlertCommand`. Si vuelve a rango con el margen de histéresis durante 2 minutos, se emite un `ResolveAlertCommand`. |
| Dispositivo sin señal | `DeviceSilenceDetector` revisa periódicamente los dispositivos. Si detecta tres ventanas de sincronización perdidas, emite un `RaiseAlertCommand` de tipo `DEVICE_OFFLINE`. |
| Alerta generada o resuelta | Los eventos `Alerta Generada` y `Alerta Resuelta` se propagan a Notification Management y al dashboard mediante el flujo SSE. |
| Lectura registrada | El evento `Lectura Registrada` alimenta la evaluación de umbrales y el historial que consumen Reporting and Analytics y Service Request Management. |

**Outbound Services (ACL)**

| Clase | Contexto destino | Descripción |
| :--- | :--- | :--- |
| `DeviceManagementExternalService` | Device Management | ACL que verifica la API key del dispositivo y resuelve a qué equipo está emparejado. |
| `AssetManagementExternalService` | Assets Management | ACL que obtiene la identidad del equipo y su umbral de temperatura configurado. |
| `NotificationExternalService` | Notification Management | ACL que solicita el envío de notificaciones cuando una alerta se genera o se resuelve. |

#### 4.2.3.4. Infrastructure Layer.

La Infrastructure Layer contiene las clases que acceden a la base de datos y a los demás contextos. Implementa los repositorios definidos en el dominio y los adaptadores técnicos de los servicios externos.

**Persistencia (Repositories)**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `SpringDataJpaReadingRepository` | `ReadingRepository` | Implementación con Spring Data JPA del repositorio de lecturas de sensores. |
| `SpringDataJpaAlertRepository` | `AlertRepository` | Implementación con Spring Data JPA del repositorio del aggregate `Alert`. |

Ambos repositorios operan sobre el esquema `monitoring` de la instancia **PostgreSQL v18** (*Platform Database*), que mantiene un esquema por bounded context.

Responsabilidades de los repositorios:

- Guardar lecturas y verificar si una lectura ya fue registrada por su UUID.
- Consultar la última lectura y el historial de un equipo por rango de fechas.
- Guardar y actualizar alertas, y consultarlas por dueño, por equipo o por identificador.
- Persistir y consultar la política de alertas de cada equipo.

**Modelo de tablas del esquema `monitoring`**

| Tabla | Columna | Tipo | Descripción |
| :--- | :--- | :--- | :--- |
| `SensorReadings` | `read_id` | `VARCHAR` (PK) | Identificador de la lectura. |
| `SensorReadings` | `temperature` | `DOUBLE` | Temperatura registrada. |
| `SensorReadings` | `humidity` | `DOUBLE` | Humedad registrada. |
| `SensorReadings` | `recorded_at` | `DATETIME` | Momento de la medición en el dispositivo. |
| `SensorReadings` | `received_at` | `DATETIME` | Momento de recepción en la plataforma. |
| `SensorReadings` | `equipment_id` | `VARCHAR` (FK) | Equipo asociado. |
| `SensorReadings` | `device_id` | `VARCHAR` (FK) | Dispositivo emisor. |
| `Alert` | `alert_id` | `VARCHAR` (PK) | Identificador de la alerta. |
| `Alert` | `severity` | `VARCHAR(30)` | Severidad. |
| `Alert` | `status` | `VARCHAR(30)` | Estado del ciclo de vida. |
| `Alert` | `peak_temperature` | `DOUBLE` | Temperatura pico de la excursión. |
| `Alert` | `excursion_duration` | `INTEGER` | Duración de la excursión. |
| `Alert` | `equipment_id` | `VARCHAR` (FK) | Equipo afectado. |
| `Alert` | `read_id` | `VARCHAR` (FK) | Lectura que disparó la alerta. |
| `AlertPolicy` | `policy_id` | `VARCHAR` (PK) | Identificador de la política. |
| `AlertPolicy` | `sustained_excursion_minutes` | `INTEGER` | Minutos de excursión sostenida. |
| `AlertPolicy` | `hysteresis_margin_celsius` | `DOUBLE` | Margen de histéresis en °C. |
| `AlertPolicy` | `missed_sync_for_offline` | `INTEGER` | Ventanas perdidas para declarar offline. |
| `AlertPolicy` | `is_active` | `BOOLEAN` | Indica si la política está activa. |
| `AlertPolicy` | `equipment_id` | `VARCHAR` (FK) | Equipo al que aplica. |

**Adaptadores hacia otros contextos**

| Clase | Descripción |
| :--- | :--- |
| Adaptador de `DeviceManagementExternalService` | Comunicación con Device Management para verificar la API key y resolver el equipo emparejado. |
| Adaptador de `AssetManagementExternalService` | Comunicación con Assets Management para obtener el umbral de temperatura del equipo. |
| Adaptador de `NotificationExternalService` | Comunicación con Notification Management para solicitar el envío de notificaciones. |
| Programador de tareas del `DeviceSilenceDetector` | Ejecuta de forma periódica la detección de dispositivos sin señal. |

**Resumen de dependencias externas**

| Recurso | Tipo | Uso en Monitoring and Alerting |
| :--- | :--- | :--- |
| PostgreSQL v18 (esquema `monitoring`) | Base de datos relacional | Persistencia de lecturas, alertas y políticas. |
| Device Management | Bounded context interno | Verificación de API key y emparejamiento dispositivo–equipo. |
| Assets Management | Bounded context interno | Identidad del equipo y umbral de temperatura. |
| Notification Management | Bounded context interno | Envío de notificaciones de alertas. |

#### 4.2.3.5. Bounded Context Software Architecture Component Level Diagrams.

En el siguiente diagrama de componentes mostramos la organización del contexto Monitoring and Alerting, que es el núcleo del negocio de IceTrack. Se distinguen los subdominios SensorReading y Alert. El primero recibe la telemetría mediante el Telemetry Controller, la almacena y la transmite al dashboard en tiempo real con el Telemetry Stream Controller. El segundo evalúa los umbrales, detecta dispositivos sin señal y gestiona el ciclo de vida de las alertas. También se muestran las capas anticorrupción hacia Device Management, Assets Management y Notification Management, la fachada que consumen otros contextos y el esquema `monitoring` de la base de datos.


![IceTrack Bounded Context Component Level Diagram - Monitoring and Alerting](assets/chapter04/c4/component/monitoringComponent.png)

#### 4.2.3.6. Bounded Context Software Architecture Code Level Diagrams.

En esta sección presentamos los diagramas de nivel de código del bounded context Monitoring and Alerting: el diagrama de clases de la capa de dominio y el diseño de la base de datos del esquema `monitoring`.

##### 4.2.3.6.1. Bounded Context Domain Layer Class Diagrams.

El siguiente diagrama de clases representa la estructura del contexto organizada por capas. En el dominio se encuentra el aggregate `Alert` y las interfaces de los servicios de lecturas y alertas. En la capa de aplicación se ubican los servicios que registran lecturas y gestionan alertas, en la capa de interfaces los controladores de telemetría y de alertas junto con la fachada del contexto, y en infraestructura los repositorios JPA de lecturas y alertas.


![IceTrack Bounded Context Domain Layer Class Diagram - Monitoring and Alerting](assets/chapter04/diagrams/class/monitoringDiagramClass.png)

##### 4.2.3.6.2. Bounded Context Database Design Diagram.

El siguiente diagrama presenta el diseño de la base de datos del esquema `monitoring`. La tabla `SensorReadings` conserva el histórico de lecturas de cada equipo y dispositivo, la tabla `Alert` registra las alertas generadas con su severidad, estado y duración de la excursión, y la tabla `AlertPolicy` guarda las reglas de evaluación configuradas para cada equipo.

![IceTrack Bounded Context Database Design Diagram - Monitoring and Alerting](assets/chapter04/diagrams/database/monitoringDiagramDatabase.png)

---

### 4.2.4. Bounded Context: Assets Management

En el bounded context Assets Management administramos las sedes de cada dueño de negocio y el catálogo de equipos de refrigeración instalados en ellas, incluyendo el umbral de temperatura y el intervalo de mantenimiento preventivo de cada equipo. Es la base física del dominio IoT: los contextos de Device Management, Monitoring and Alerting y Service Request Management se apoyan en este contexto para identificar y validar los equipos.

#### 4.2.4.1. Domain Layer.

La Domain Layer del bounded context **Assets Management** contiene el modelo de la base física del negocio: las sedes donde opera cada dueño y los equipos de refrigeración instalados en ellas. Es el contexto que define la identidad, la pertenencia y el umbral de temperatura de cada equipo, por lo que los demás contextos lo consultan para identificar y validar los activos. Su modelo está organizado en dos aggregates: **Site**, que representa una sede, y **Equipment**, que representa un equipo de refrigeración. Ambos se asocian al dueño mediante su perfil, sin depender del modelo interno de otros contextos.

**Aggregate Roots**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `Site` | Aggregate Root | Representa una sede o establecimiento del dueño. Guarda su nombre, su dirección y sus datos de contacto. |
| `Equipment` | Aggregate Root | Representa un equipo de refrigeración instalado en una sede. Controla su identidad, su tipo, su estado, su umbral de temperatura y su intervalo de mantenimiento preventivo. |

Atributos de `Site`:

| Atributo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id` | `UUID` | Identificador único de la sede. |
| `ownerId` | `UUID` | Perfil del dueño al que pertenece la sede (referencia a Profiles). |
| `name` | `String` | Nombre de la sede. |
| `address` | `Address` (Value Object) | Dirección de la sede. |
| `contactName` | `String` | Nombre de la persona de contacto de la sede. |
| `phone` | `Phone` (Value Object) | Teléfono de contacto de la sede. |

Atributos de `Equipment`:

| Atributo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id` | `UUID` | Identificador único del equipo. |
| `siteId` | `UUID` | Sede donde está instalado el equipo. |
| `uid` | `String` | Identificador propio del equipo. |
| `name` | `String` | Nombre asignado al equipo. |
| `equipmentType` | `EquipmentType` | Tipo de equipo (por ejemplo, congeladora, vitrina o cámara). |
| `status` | `StatusEquipment` | Estado operativo actual del equipo. |
| `online` | `Boolean` | Indica si el equipo está conectado. |
| `temperatureThreshold` | `TemperatureThreshold` | Umbral de temperatura mínima y máxima permitido para el equipo. |
| `reminderIntervalDays` | `Integer` | Intervalo, en días, del mantenimiento preventivo. |
| `lastReadingAt` | `DateTime` | Fecha y hora de la última lectura recibida del equipo. |
| `lastKnownTemperature` | `Double` | Última temperatura conocida del equipo. |

**Value Objects y enumeraciones**

| Clase | Descripción |
| :--- | :--- |
| `TemperatureThreshold` | Value Object que agrupa la temperatura mínima y máxima permitidas. Garantiza que el mínimo sea menor que el máximo. |
| `EquipmentType` | Enum con el tipo de equipo de refrigeración. |
| `StatusEquipment` | Enum con los estados operativos del equipo. |
| `Address` | Dirección de la sede. |
| `Phone` | Teléfono de contacto de la sede. |

**Commands y Queries del dominio**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `RegisterSiteCommand` | Command (record) | Registra una nueva sede. |
| `UpdateSiteInfoCommand` | Command (record) | Actualiza los datos de una sede. |
| `RegisterEquipmentCommand` | Command (record) | Registra un equipo en una sede. |
| `UpdateEquipmentCommand` | Command (record) | Actualiza los datos de un equipo. |
| `ChangeThresholdCommand` | Command (record) | Cambia el umbral de temperatura de un equipo. |
| `ChangeStatusCommand` | Command (record) | Cambia el estado de un equipo. |
| `GetSitesByOwnerQuery` | Query (record) | Lista las sedes de un dueño. |
| `GetSiteByIdQuery` | Query (record) | Obtiene una sede por su identificador. |
| `GetEquipmentByIdQuery` | Query (record) | Obtiene un equipo por su identificador. |
| `GetEquipmentBySiteQuery` | Query (record) | Lista los equipos de una sede. |
| `GetEquipmentByOwnerQuery` | Query (record) | Lista los equipos de un dueño. |

**Domain Services (interfaces)**

| Interfaz | Descripción |
| :--- | :--- |
| `SiteCommandService` | Contrato de las operaciones que registran y actualizan sedes. |
| `SiteQueryService` | Contrato de las consultas de sedes. |
| `EquipmentCommandService` | Contrato de las operaciones que registran equipos, cambian su umbral y sus estados. |
| `EquipmentQueryService` | Contrato de las consultas y filtros de equipos. |

**Repositories (interfaces)**

| Interfaz | Descripción |
| :--- | :--- |
| `SiteRepository` | Abstracción de persistencia del aggregate `Site`. |
| `EquipmentRepository` | Abstracción de persistencia del aggregate `Equipment`. |

**Domain Events**

| Evento | Descripción |
| :--- | :--- |
| `Sitio Creado` | Se emite cuando se registra una nueva sede. |
| `Equipo Registrado` | Se emite cuando se registra un equipo en una sede. |
| `Umbral de Temperatura Actualizado` | Se emite cuando cambia el umbral de temperatura de un equipo. |

**Reglas de negocio del dominio**

- Cada sede pertenece a un único dueño, identificado por su perfil.
- Cada equipo pertenece a una sola sede y, por lo tanto, a un único dueño.
- El umbral de temperatura de un equipo debe tener un mínimo menor que el máximo.
- Cada equipo define su propio intervalo de mantenimiento preventivo.
- El umbral de cada equipo se define y se modifica solo en este contexto. Monitoring and Alerting lo consulta para evaluar las alertas.

#### 4.2.4.2. Interface Layer.

La Interface Layer expone las capacidades del contexto hacia el exterior. Recibe las solicitudes HTTP que el **API Gateway** enruta después de validar el JWT y publica una fachada para que otros contextos consulten la identidad, la pertenencia y el umbral de temperatura de los equipos. Se organiza en los subpaquetes `controllers`, `resources`, `assemblers` y `acl`.

**Controllers**

| Clase | Descripción |
| :--- | :--- |
| `SiteController` | Controlador REST del *Site Endpoint* (GET, POST, PUT). Gestiona el registro y el listado de sedes. Cubre la historia US-20 (registrar nuevos sitios). Depende de los servicios de comandos y consultas de sedes. |
| `EquipmentController` | Controlador REST del *Equipment Endpoint* (GET, POST, PUT). Gestiona el registro, la actualización, la configuración de umbrales y el listado de equipos. Cubre las historias US-03 (gestión de equipos), US-11 (equipos asignados a clientes) y US-18 (consulta de equipos registrados). Depende de `EquipmentCommandService` y `EquipmentQueryService`. |

Método principal:

| Clase | Método | Descripción |
| :--- | :--- | :--- |
| `EquipmentController` | `register(req: RegisterEquipmentRequest): ResponseEntity<EquipmentResponse>` | Recibe los datos del equipo, los convierte en un `RegisterEquipmentCommand`, invoca al servicio de comandos y devuelve el equipo registrado. |

**Resources (records)**

| Clase | Descripción |
| :--- | :--- |
| `RegisterEquipmentRequest` | Datos de entrada para registrar un equipo (sede, nombre, tipo, umbral e intervalo de mantenimiento). |
| `EquipmentResponse` | Representación del equipo en las respuestas de la API. |

**Assemblers**

| Clase | Método | Descripción |
| :--- | :--- | :--- |
| `EquipmentAssembler` | `toResource(entity: Equipment): EquipmentResponse` | Convierte el aggregate `Equipment` en el recurso de respuesta. |
| `EquipmentAssembler` | `toCommand(req: RegisterEquipmentRequest): RegisterEquipmentCommand` | Transforma el recurso de registro en el comando del dominio. |

**ACL / Facade (inbound services)**

| Clase | Descripción |
| :--- | :--- |
| `AssetContextFacade` | Fachada que expone a otros contextos la identidad del equipo, su pertenencia y su umbral de temperatura, sin revelar los aggregates internos. Depende de `EquipmentQueryService`. |

Método de `AssetContextFacade`:

| Método | Descripción |
| :--- | :--- |
| `getEquipmentThreshold(id: UUID): Optional<Double>` | Devuelve el umbral de temperatura configurado para el equipo indicado. |

Consumidores de la fachada:

| Contexto consumidor | Uso |
| :--- | :--- |
| Monitoring and Alerting | Recupera la identidad del equipo y su umbral de temperatura para evaluar las lecturas y generar alertas. |
| Device Management | Verifica que el equipo exista y pertenezca al dueño solicitante antes de emparejarlo con un dispositivo. |

#### 4.2.4.3. Application Layer.

La Application Layer orquesta los flujos del contexto. Recibe los comandos y consultas de la Interface Layer, coordina los aggregates y los repositorios, y delega las reglas de negocio en el dominio. Sus capabilities son **registrar y actualizar sedes, registrar y actualizar equipos, configurar el umbral de temperatura y el estado de cada equipo, y consultar sedes y equipos por dueño o por sede**.

**Command Services**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `SiteCommandServiceImpl` | `SiteCommandService` | Ejecuta los procesos que registran y actualizan sedes. Depende de `SiteRepository`. |
| `EquipmentCommandServiceImpl` | `EquipmentCommandService` | Ejecuta los procesos que registran equipos y modifican su umbral y su estado. Depende de `EquipmentRepository`. |

Manejadores de comandos:

| Clase | Método | Flujo |
| :--- | :--- | :--- |
| `SiteCommandServiceImpl` | `handle(cmd: RegisterSiteCommand): Optional<Site>` | Crea el aggregate `Site` asociado al perfil del dueño, lo persiste y registra `Sitio Creado`. |
| `SiteCommandServiceImpl` | `handle(cmd: UpdateSiteInfoCommand)` | Busca la sede, actualiza sus datos de ubicación y contacto, y persiste el cambio. |
| `EquipmentCommandServiceImpl` | `handle(cmd: RegisterEquipmentCommand): Optional<Equipment>` | Crea el aggregate `Equipment` en la sede indicada, con su tipo, su umbral y su intervalo de mantenimiento. Lo persiste y registra `Equipo Registrado`. |
| `EquipmentCommandServiceImpl` | `handle(cmd: UpdateEquipmentCommand)` | Busca el equipo, actualiza sus datos y persiste el cambio. |
| `EquipmentCommandServiceImpl` | `handle(cmd: ChangeThresholdCommand)` | Cambia el umbral de temperatura del equipo y registra `Umbral de Temperatura Actualizado`. |
| `EquipmentCommandServiceImpl` | `handle(cmd: ChangeStatusCommand)` | Cambia el estado del equipo mediante las transiciones permitidas por el dominio. |

**Query Services**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `SiteQueryServiceImpl` | `SiteQueryService` | Resuelve las consultas de sedes usando `SiteRepository`. |
| `EquipmentQueryServiceImpl` | `EquipmentQueryService` | Resuelve las consultas y filtros de equipos usando `EquipmentRepository`. |

Manejadores de consultas:

| Clase | Método | Descripción |
| :--- | :--- | :--- |
| `SiteQueryServiceImpl` | `handle(q: GetSitesByOwnerQuery)` | Devuelve las sedes de un dueño. |
| `SiteQueryServiceImpl` | `handle(q: GetSiteByIdQuery)` | Devuelve la sede que corresponde al identificador. |
| `EquipmentQueryServiceImpl` | `handle(q: GetEquipmentByIdQuery): Optional<Equipment>` | Devuelve el equipo que corresponde al identificador. |
| `EquipmentQueryServiceImpl` | `handle(q: GetEquipmentBySiteQuery)` | Devuelve los equipos de una sede. |
| `EquipmentQueryServiceImpl` | `handle(q: GetEquipmentByOwnerQuery)` | Devuelve los equipos de un dueño. |

**Flujos de integración**

| Flujo | Descripción |
| :--- | :--- |
| Registrar un equipo en un sitio | El dueño registra una sede y luego un equipo dentro de ella, con su tipo, umbral e intervalo de mantenimiento. Corresponde al Escenario 02 del Domain Message Flow. |
| Emparejamiento de dispositivo | Antes de emparejar una placa IoT, Device Management consulta la fachada para verificar que el equipo exista y pertenezca al dueño. |
| Evaluación de lecturas | Cuando Monitoring and Alerting recibe telemetría, consulta la fachada para obtener la identidad del equipo y su umbral de temperatura. |

Este contexto es Upstream de los demás. No depende de servicios externos de otros contextos para su operación.

#### 4.2.4.4. Infrastructure Layer.

La Infrastructure Layer contiene las clases que acceden a la base de datos. Implementa las abstracciones de repositorio definidas en el dominio, de modo que el modelo no dependa de una tecnología concreta.

**Persistencia (Repositories)**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `SpringDataJpaSiteRepository` | `SiteRepository` | Implementación con Spring Data JPA del repositorio del aggregate `Site`. |
| `SpringDataJpaEquipmentRepository` | `EquipmentRepository` | Implementación con Spring Data JPA del repositorio del aggregate `Equipment`. |

Ambos repositorios operan sobre el esquema `assets` de la instancia **PostgreSQL v18** (*Platform Database*), que mantiene un esquema por bounded context.

Responsabilidades de los repositorios:

- Guardar, actualizar y consultar sedes por identificador y por dueño.
- Guardar, actualizar y consultar equipos por identificador, por sede y por dueño.
- Persistir el umbral de temperatura, el estado y el intervalo de mantenimiento de cada equipo.

**Modelo de tablas del esquema `assets`**

| Tabla | Columna | Tipo | Descripción |
| :--- | :--- | :--- | :--- |
| `Site` | `site_id` | `VARCHAR` (PK) | Identificador de la sede. |
| `Site` | `name` | `VARCHAR(30)` | Nombre de la sede. |
| `Site` | `address` | `VARCHAR(50)` | Dirección de la sede. |
| `Site` | `contact_name` | `VARCHAR(30)` | Persona de contacto. |
| `Site` | `phone` | `CHAR` | Teléfono de contacto. |
| `Site` | `owner_profiles_id` | `VARCHAR` (FK) | Perfil del dueño de la sede. |
| `Equipment` | `equipment_id` | `VARCHAR` (PK) | Identificador del equipo. |
| `Equipment` | `equipment_uid` | `VARCHAR(30)` | Identificador propio del equipo. |
| `Equipment` | `name` | `VARCHAR(30)` | Nombre del equipo. |
| `Equipment` | `status` | `VARCHAR(50)` | Estado operativo. |
| `Equipment` | `equipment_type` | `VARCHAR(35)` | Tipo de equipo. |
| `Equipment` | `online` | `BOOLEAN` | Indica si el equipo está conectado. |
| `Equipment` | `reminder_interval_days` | `INTEGER` | Intervalo de mantenimiento preventivo, en días. |
| `Equipment` | `threshold_min_celsius` | `DOUBLE` | Temperatura mínima permitida. |
| `Equipment` | `threshold_max_celsius` | `DOUBLE` | Temperatura máxima permitida. |
| `Equipment` | `last_reading_at` | `DATETIME` | Fecha de la última lectura recibida. |
| `Equipment` | `last_known_temperature` | `DATETIME` | Última temperatura conocida. |
| `Equipment` | `site_id` | `VARCHAR` (FK) | Sede donde está instalado el equipo. |

**Resumen de dependencias externas**

| Recurso | Tipo | Uso en Assets Management |
| :--- | :--- | :--- |
| PostgreSQL v18 (esquema `assets`) | Base de datos relacional | Persistencia de sedes y equipos. |
| Profiles and Preferences Management | Bounded context interno (Upstream) | Origen del perfil del dueño al que pertenecen las sedes. |
| Monitoring and Alerting | Bounded context interno (consumidor) | Consulta la identidad y el umbral de temperatura de los equipos. |
| Device Management | Bounded context interno (consumidor) | Verifica la existencia y la pertenencia del equipo antes del emparejamiento. |

#### 4.2.4.5. Bounded Context Software Architecture Component Level Diagrams.

En el siguiente diagrama de componentes mostramos cómo organizamos el contexto Assets Management. Se observan el controlador que recibe las solicitudes desde el API Gateway, los servicios de comandos y consultas de sedes y equipos, sus aggregates y repositorios, y la fachada que expone los datos de los equipos a los demás contextos. También se muestra la relación con el esquema `assets` de la base de datos.

![IceTrack Bounded Context Component Level Diagram - Assets Management](assets/chapter04/c4/component/assetComponent.png)

#### 4.2.4.6. Bounded Context Software Architecture Code Level Diagrams.

En esta sección presentamos los diagramas de nivel de código del bounded context Assets Management: el diagrama de clases de la capa de dominio y el diseño de la base de datos del esquema `assets`.

##### 4.2.4.6.1. Bounded Context Domain Layer Class Diagrams.

El siguiente diagrama de clases representa el modelo de este contexto y su distribución en capas. Incluye los aggregates de sedes y equipos con sus reglas de negocio, las interfaces de servicios y repositorios del dominio, los servicios de la capa de aplicación, los controladores y la fachada de la capa de interfaces, y los repositorios JPA de la capa de infraestructura.

![IceTrack Bounded Context Domain Layer Class Diagram - Assets Management](assets/chapter04/diagrams/class/assetManagementDiagramClass.png)

##### 4.2.4.6.2. Bounded Context Database Design Diagram.

El siguiente diagrama presenta el diseño de la base de datos del esquema `assets`. Las sedes se asocian al perfil del dueño con sus datos de ubicación y contacto, y los equipos se vinculan a una sede y almacenan su umbral de temperatura y su intervalo de mantenimiento.

![IceTrack Bounded Context Database Design Diagram - Assets Management](assets/chapter04/diagrams/database/assetDiagramDatabase.png)

---

### 4.2.5. Bounded Context: Device Management

En el bounded context Device Management administramos el ciclo de vida del hardware físico de monitoreo, es decir, las placas IoT ESP32. Esto comprende su registro, su emparejamiento con un equipo de refrigeración, la rotación de sus credenciales de acceso y su baja. Otros contextos, en especial Monitoring and Alerting, consultan este contexto para verificar la API key de cada dispositivo antes de aceptar su telemetría.

#### 4.2.5.1. Domain Layer.

La Domain Layer del bounded context **Device Management** contiene el modelo del hardware físico de monitoreo (las placas IoT ESP32). Gestiona su ciclo de vida: registro, emparejamiento con un equipo de refrigeración, rotación de credenciales de acceso y baja. Su modelo gira en torno a un único aggregate, **Device**, que garantiza que cada dispositivo tenga una identidad, una credencial segura y, como máximo, un equipo asociado.

**Aggregate Root**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `Device` | Aggregate Root / Entity | Representa una placa IoT física. Controla su emparejamiento, su API key y sus transiciones de estado, y es la única vía para modificar esos datos. |

Atributos de `Device`:

| Atributo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id` | `UUID` | Identificador único del dispositivo dentro de la plataforma. |
| `serialNumber` (`device_uid`) | `String` | Identificador físico del dispositivo, grabado en la placa. |
| `boardModel` | `String` | Modelo de la placa (por ejemplo, ESP32). |
| `firmwareVersion` | `String` | Versión del firmware instalado en el dispositivo. |
| `apiKeyHash` | `String` | Hash de la API key con la que el dispositivo se autentica. La clave nunca se almacena en texto plano. |
| `status` | `DeviceStatus` | Estado operativo actual del dispositivo. |
| `lastRead` | `DateTime` | Fecha y hora de la última lectura recibida del dispositivo. |
| `pairedEquipmentId` | `UUID` | Equipo de refrigeración con el que está emparejado (referencia al contexto Assets Management). |

**Value Objects y enumeraciones**

| Clase | Descripción |
| :--- | :--- |
| `DeviceStatus` | Enum con los estados del ciclo de vida del dispositivo. |
| `ApiKey` | Credencial de acceso del dispositivo. Se entrega una sola vez, en texto plano, en el momento de emitirla o rotarla, y después solo se conserva su hash. |
| `EquipmentId` | Referencia tipada al equipo con el que se empareja el dispositivo. |

**Commands y Queries del dominio**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `PairDeviceCommand` | Command (record) | Empareja un dispositivo con un equipo de refrigeración. |
| `UnpairDeviceCommand` | Command (record) | Desvincula un dispositivo de su equipo. |
| `RotateApiKeyCommand` | Command (record) | Emite una nueva API key e invalida la anterior. |
| `ChangeDeviceStatusCommand` | Command (record) | Cambia el estado del dispositivo, incluida su baja. |
| `GetDeviceByIdQuery` | Query (record) | Obtiene un dispositivo por su identificador. |
| `GetDeviceByApiKeyQuery` | Query (record) | Obtiene el dispositivo que corresponde a una API key. |
| `GetDevicesByEquipmentQuery` | Query (record) | Lista los dispositivos emparejados con un equipo. |

**Domain Services (interfaces)**

| Interfaz | Descripción |
| :--- | :--- |
| `DeviceCommandService` | Contrato de las operaciones que cambian el estado: emparejar, desemparejar, rotar credencial y cambiar estado. |
| `DeviceQueryService` | Contrato de las consultas de dispositivos y de verificación de credenciales. |

**Repositories (interfaces)**

| Interfaz | Descripción |
| :--- | :--- |
| `DeviceRepository` | Abstracción de persistencia del aggregate `Device`. El dominio solo conoce esta interfaz. Su implementación pertenece a la Infrastructure Layer. |

**Domain Events**

| Evento | Descripción |
| :--- | :--- |
| `Dispositivo Registrado` | Se emite cuando un dispositivo se da de alta en la plataforma. |
| `Dispositivo Emparejado` | Se emite cuando un dispositivo queda vinculado a un equipo. |
| `Dispositivo Dado de Baja` | Se emite cuando un dispositivo se retira de la plataforma. |

**Reglas de negocio del dominio**

- Cada dispositivo se autentica con una API key, y de ella se guarda únicamente el hash.
- Un dispositivo se empareja con un equipo. Antes de emparejarlo, el equipo debe existir y pertenecer al dueño que lo solicita.
- Al rotar la API key, la credencial anterior deja de ser válida.
- Un dispositivo dado de baja no puede autenticarse ni enviar telemetría.

#### 4.2.5.2. Interface Layer.

La Interface Layer expone las capacidades del contexto. Recibe las solicitudes HTTP que el **API Gateway** enruta hacia el *Device Endpoint* (GET, POST, PUT) y publica una fachada para que otros contextos verifiquen credenciales de dispositivos. Se organiza en los subpaquetes `controllers`, `resources`, `assemblers` y `acl`.

**Controllers**

| Clase | Descripción |
| :--- | :--- |
| `DeviceController` | Controlador REST para el emparejamiento y desemparejamiento de dispositivos y la rotación de su API key. Cubre las historias US-03 (gestión de equipos con su identificador de dispositivo) y US-26 (programación del ESP32 para enviar telemetría). Depende de `DeviceCommandService` y `DeviceQueryService`. |

Método principal:

| Método | Descripción |
| :--- | :--- |
| `pair(req: PairDeviceRequest): ResponseEntity<DeviceResponse>` | Recibe la solicitud de emparejamiento, la convierte en un `PairDeviceCommand`, la delega al servicio de comandos y devuelve el dispositivo emparejado. |

**Resources (records)**

| Clase | Descripción |
| :--- | :--- |
| `PairDeviceRequest` | Datos de entrada para emparejar un dispositivo con un equipo. |
| `DeviceResponse` | Representación del dispositivo en las respuestas de la API. No expone el hash de la API key. |

**Assemblers**

| Clase | Método | Descripción |
| :--- | :--- | :--- |
| `DeviceAssembler` | `toResource(d: Device): DeviceResponse` | Convierte el aggregate `Device` en el recurso de respuesta. |
| `DeviceAssembler` | `toCommand(r: PairDeviceRequest): PairDeviceCommand` | Transforma el recurso de emparejamiento en el comando del dominio. |

**ACL / Facade (inbound services)**

| Clase | Descripción |
| :--- | :--- |
| `DeviceContextFacade` | Fachada que expone a otros contextos la verificación de la API key y la resolución del dispositivo hacia su equipo, sin revelar el aggregate `Device`. Depende de `DeviceQueryService`. |

Método de `DeviceContextFacade`:

| Método | Descripción |
| :--- | :--- |
| `verifyApiKey(key: String): Optional<UUID>` | Verifica la API key recibida y devuelve el identificador asociado. Si la clave no es válida, devuelve un resultado vacío. |

Consumidor de la fachada:

| Contexto consumidor | Uso |
| :--- | :--- |
| Monitoring and Alerting | Verifica la API key del dispositivo y resuelve el equipo emparejado antes de aceptar la telemetría. |

#### 4.2.5.3. Application Layer.

La Application Layer orquesta los flujos del contexto. Recibe los comandos y consultas de la Interface Layer, coordina el aggregate `Device`, el repositorio y los servicios externos, y delega las reglas de negocio en el dominio. Sus capabilities son **registrar y emparejar dispositivos, rotar credenciales, cambiar el estado o dar de baja un dispositivo, y verificar credenciales**.

**Command Services**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `DeviceCommandServiceImpl` | `DeviceCommandService` | Ejecuta los procesos que modifican el estado de los dispositivos. Depende de `DeviceRepository` y del servicio externo de activos. |

Manejadores de comandos:

| Método | Flujo |
| :--- | :--- |
| `handle(cmd: PairDeviceCommand): Optional<Device>` | 1) Consulta a Assets Management, mediante el ACL, que el equipo exista y pertenezca al dueño solicitante. 2) Emite la API key del dispositivo y guarda su hash. 3) Asocia el `pairedEquipmentId` al aggregate `Device`. 4) Persiste el dispositivo. 5) Registra el evento `Dispositivo Emparejado`. |
| `handle(cmd: UnpairDeviceCommand)` | Desvincula el dispositivo de su equipo y persiste el cambio. |
| `handle(cmd: RotateApiKeyCommand)` | Genera una nueva API key, reemplaza el hash almacenado e invalida la credencial anterior. |
| `handle(cmd: ChangeDeviceStatusCommand)` | Cambia el estado del dispositivo. Si se trata de una baja, registra `Dispositivo Dado de Baja`. |

**Query Services**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `DeviceQueryServiceImpl` | `DeviceQueryService` | Resuelve las consultas de lectura sobre dispositivos usando `DeviceRepository`. |

Manejadores de consultas:

| Método | Descripción |
| :--- | :--- |
| `handle(q: GetDeviceByIdQuery)` | Devuelve el dispositivo que corresponde al identificador. |
| `handle(q: GetDeviceByApiKeyQuery): Optional<Device>` | Devuelve el dispositivo cuya API key coincide con la recibida. Es la consulta que usa `DeviceContextFacade`. |
| `handle(q: GetDevicesByEquipmentQuery)` | Devuelve los dispositivos emparejados con un equipo. |

**Outbound Services (ACL)**

| Clase | Contexto destino | Descripción |
| :--- | :--- | :--- |
| `ExternalAssetServiceFromDevice` | Assets Management | Anti-Corruption Layer que verifica que el equipo exista y pertenezca al dueño solicitante antes del emparejamiento. |

**Método del ACL:**

| Método | Descripción |
| :--- | :--- |
| `checkEquipment(id: UUID): boolean` | Indica si el equipo existe y puede emparejarse con el dispositivo. |

**Flujo de integración**

| Flujo | Descripción |
| :--- | :--- |
| Emparejar dispositivo IoT a un equipo | El dueño solicita el emparejamiento. Device Management consulta a Assets Management si el equipo es válido, genera la credencial del dispositivo y registra el vínculo. Corresponde al Escenario 05 del Domain Message Flow. |
| Verificación de telemetría | Cuando el dispositivo envía lecturas, Monitoring and Alerting consulta la fachada de este contexto para validar la API key y resolver el equipo antes de procesar los datos. |

#### 4.2.5.4. Infrastructure Layer.

La Infrastructure Layer contiene las clases que acceden a la base de datos. Implementa la abstracción de repositorio definida en el dominio, de modo que el modelo no dependa de una tecnología concreta.

**Persistencia (Repositories)**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `SpringDataJpaDeviceRepository` | `DeviceRepository` | Implementación con Spring Data JPA del repositorio del aggregate `Device`. Opera sobre el esquema `devices` de la instancia **PostgreSQL v18** (*Platform Database*), que mantiene un esquema por bounded context. |

Responsabilidades del repositorio:

- Guardar, actualizar y consultar dispositivos.
- Buscar un dispositivo por identificador y por hash de API key.
- Listar los dispositivos emparejados con un equipo.

**Modelo de tabla del esquema `devices`**

| Tabla | Columna | Tipo | Descripción |
| :--- | :--- | :--- | :--- |
| `Device` | `device_id` | `VARCHAR` (PK) | Identificador del dispositivo. |
| `Device` | `device_uid` | `VARCHAR(10)` | Identificador físico grabado en la placa. |
| `Device` | `board_model` | `VARCHAR(30)` | Modelo de la placa. |
| `Device` | `firmware_version` | `VARCHAR(30)` | Versión del firmware. |
| `Device` | `api_hash` | `VARCHAR(30)` | Hash de la API key. |
| `Device` | `status` | `VARCHAR(35)` | Estado del dispositivo. |
| `Device` | `last_read` | `VARCHAR(25)` | Fecha de la última lectura recibida. |
| `Device` | `equipment_id` | `VARCHAR` (FK) | Equipo con el que está emparejado. |

**Adaptador hacia otro contexto**

| Clase | Descripción |
| :--- | :--- |
| Adaptador de `ExternalAssetServiceFromDevice` | Comunicación con Assets Management para verificar la existencia y la pertenencia del equipo antes de emparejar. |

**Resumen de dependencias externas**

| Recurso | Tipo | Uso en Device Management |
| :--- | :--- | :--- |
| PostgreSQL v18 (esquema `devices`) | Base de datos relacional | Persistencia de los dispositivos. |
| Assets Management | Bounded context interno | Verificación del equipo antes del emparejamiento. |
| Monitoring and Alerting | Bounded context interno (consumidor) | Verifica la API key y resuelve el equipo de cada dispositivo. |

#### 4.2.5.5. Bounded Context Software Architecture Component Level Diagrams.

En el siguiente diagrama de componentes mostramos cómo organizamos el contexto Device Management. Se observan el Device Controller que atiende el emparejamiento, el desemparejamiento y la rotación de la API key, los servicios de comandos y consultas, el aggregate `Device` con su repositorio y la fachada que usa Monitoring and Alerting para verificar credenciales. También se muestra la capa anticorrupción hacia Assets Management, que valida el equipo antes de emparejarlo, y el esquema `devices` de la base de datos.

![IceTrack Bounded Context Component Level Diagram - Device Management](assets/chapter04/c4/component/deviceComponent.png)

#### 4.2.5.6. Bounded Context Software Architecture Code Level Diagrams.

En esta sección presentamos los diagramas de nivel de código del bounded context Device Management: el diagrama de clases de la capa de dominio y el diseño de la base de datos del esquema `devices`.

##### 4.2.5.6.1. Bounded Context Domain Layer Class Diagrams.

El siguiente diagrama de clases representa la estructura del contexto organizada por capas. En el dominio se encuentra el aggregate `Device` junto con las interfaces de servicios, y en la capa de aplicación los servicios de comandos y consultas y el servicio externo hacia Assets Management. En la capa de interfaces se ubican el controlador, el assembler, los recursos y la fachada, y en infraestructura la implementación JPA del repositorio.

![IceTrack Bounded Context Domain Layer Class Diagram - Device Management](assets/chapter04/diagrams/class/deviceManagementDiagramClass.png)

##### 4.2.5.6.2. Bounded Context Database Design Diagram.

El siguiente diagrama presenta el diseño de la base de datos del esquema `devices`. La tabla `Device` almacena la identificación física de cada placa, su modelo, la versión de firmware, el hash de su API key, su estado, la fecha de la última lectura y el equipo con el que está emparejada.

![IceTrack Bounded Context Database Design Diagram - Device Management](assets/chapter04/diagrams/database/deviceManagementDiagramDatabase.png)

---

### 4.2.6. Bounded Context: Service Request Management

En el bounded context Service Request Management gestionamos el ciclo de vida completo de una solicitud de mantenimiento: su creación por el dueño, su aceptación o rechazo por el proveedor, la asignación de un técnico, el registro de las intervenciones en campo y su finalización. También incluye la evaluación que el dueño realiza del servicio recibido. Junto con Monitoring and Alerting, es uno de los dos núcleos operativos de IceTrack.

#### 4.2.6.1. Domain Layer.

La Domain Layer del bounded context **Service Request Management** contiene el modelo del segundo núcleo operativo de IceTrack: el ciclo de vida de una solicitud de mantenimiento y la calificación del servicio recibido. El dueño crea la solicitud, el proveedor la acepta o rechaza, se asigna un técnico, el técnico registra sus intervenciones en campo y la solicitud se completa. Luego el dueño evalúa el servicio. El modelo se organiza en tres subdominios, cada uno con su propio aggregate: **ServiceRequest**, **Intervention** y **Review**.

**Aggregate Roots**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `ServiceRequest` | Aggregate Root | Representa una solicitud de mantenimiento o reparación sobre un equipo. Controla su máquina de estados, el técnico asignado y el historial de estados. |
| `Intervention` | Aggregate Root | Representa una intervención técnica realizada en campo para atender una solicitud. Registra el técnico, el periodo de ejecución y el resumen de hallazgos. |
| `Review` | Aggregate Root | Representa la evaluación que el dueño hace de un servicio completado. Solo puede editarse durante una ventana de tiempo limitada. |

Atributos de `ServiceRequest`:

| Atributo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id` | `UUID` | Identificador único de la solicitud. |
| `equipmentId` | `UUID` | Equipo sobre el que se solicita el servicio (referencia a Assets Management). |
| `ownerId` | `UUID` | Perfil del dueño que crea la solicitud (referencia a Profiles). |
| `siteId` | `UUID` | Sede donde se encuentra el equipo. |
| `technicianId` | `UUID` | Técnico asignado. Es nulo hasta que el proveedor lo asigna. |
| `origin` | `String` | Origen de la solicitud. |
| `type` | `ServiceType` | Tipo de servicio (mantenimiento preventivo o reparación correctiva). |
| `priority` | `ServicePriority` | Prioridad de la solicitud. |
| `description` | `String` | Detalle del problema o del servicio requerido. |
| `status` | `ServiceRequestStatus` | Estado actual dentro de la máquina de estados. |
| `completedAt` | `DateTime` | Fecha de finalización. |
| `canceledAt` | `DateTime` | Fecha de cancelación. |

Atributos de `Intervention`:

| Atributo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id` | `UUID` | Identificador de la intervención. |
| `requestId` | `UUID` | Solicitud que atiende. |
| `technicianId` | `UUID` | Técnico que realiza la intervención. |
| `status` | `InterventionStatus` | Estado de la intervención. |
| `summary` | `String` | Resumen de hallazgos y acciones realizadas. |
| `startTime` | `DateTime` | Inicio de la intervención. |
| `endTime` | `DateTime` | Fin de la intervención. |

Atributos de `Review`:

| Atributo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id` | `UUID` | Identificador de la evaluación. |
| `requestId` | `UUID` | Solicitud evaluada. |
| `ownerId` | `UUID` | Dueño que evalúa. |
| `technicianId` | `UUID` | Técnico evaluado. |
| `rating` | `ReviewRating` | Calificación en comunicación, eficacia y desempeño. |
| `comment` | `String` | Comentario libre del dueño. |
| `editableUntil` | `DateTime` | Fecha límite para editar la evaluación (48 horas). |

**Value Objects y enumeraciones**

| Clase | Descripción |
| :--- | :--- |
| `ServiceRequestStatus` | Enum con la máquina de estados de la solicitud: `PENDING`, `ACCEPTED`, `REJECTED`, `IN_PROGRESS`, `CANCELED` y `COMPLETED`. |
| `ServiceType` | Tipo de servicio solicitado (preventivo o correctivo). |
| `ServicePriority` | Prioridad de atención de la solicitud. |
| `InterventionStatus` | Estado de una intervención técnica. |
| `ReviewRating` | Value Object que agrupa las calificaciones de comunicación, eficacia y desempeño. |

**Commands y Queries del dominio**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `CreateRequestCommand` | Command (record) | Crea una solicitud de servicio. |
| `AcceptRequestCommand` | Command (record) | El proveedor acepta la solicitud. |
| `RejectRequestCommand` | Command (record) | El proveedor rechaza la solicitud. |
| `CancelRequestCommand` | Command (record) | Cancela la solicitud. |
| `AssignTechnicianCommand` | Command (record) | Asigna un técnico a la solicitud. |
| `StartInterventionCommand` | Command (record) | Registra el inicio de una intervención. |
| `CompleteInterventionCommand` | Command (record) | Registra la finalización de una intervención y cierra la solicitud. |
| `SubmitReviewCommand` | Command (record) | Envía la evaluación de un servicio completado. |
| `UpdateReviewCommand` | Command (record) | Edita una evaluación dentro de su ventana de edición. |
| `GetRequestByIdQuery` | Query (record) | Obtiene una solicitud por su identificador. |
| `GetRequestsByOwnerQuery` | Query (record) | Lista las solicitudes de un dueño. |
| `GetRequestsByTechnicianQuery` | Query (record) | Lista las solicitudes asignadas a un técnico. |
| `GetRequestsByStatusQuery` | Query (record) | Lista las solicitudes según su estado. |
| `GetInterventionsByRequestQuery` | Query (record) | Lista las intervenciones de una solicitud. |
| `GetInterventionsByTechnicianQuery` | Query (record) | Lista las intervenciones de un técnico. |
| `GetReviewByRequestQuery` | Query (record) | Obtiene la evaluación de una solicitud. |
| `GetAverageRatingByTechnicianQuery` | Query (record) | Calcula el promedio de calificaciones de un técnico. |

**Domain Services (interfaces)**

| Interfaz | Descripción |
| :--- | :--- |
| `TechnicianAssignmentService` | Domain Service que resuelve los técnicos candidatos para una solicitud según su especialidad y disponibilidad. |
| `ServiceRequestCommandService` | Contrato de las operaciones que modifican el ciclo de vida de una solicitud. |
| `ServiceRequestQueryService` | Contrato de las consultas, el seguimiento y el filtrado de solicitudes. |
| `InterventionCommandService` | Contrato del registro de intervenciones y del cierre de la solicitud padre. |
| `InterventionQueryService` | Contrato de las consultas de intervenciones. |
| `ReviewCommandService` | Contrato del envío y la edición de evaluaciones. |
| `ReviewQueryService` | Contrato de las consultas de evaluaciones y promedios de calificación. |

**Repositories (interfaces)**

| Interfaz | Descripción |
| :--- | :--- |
| `ServiceRequestRepository` | Abstracción de persistencia del aggregate `ServiceRequest`. |
| `InterventionRepository` | Abstracción de persistencia del aggregate `Intervention`. |
| `ReviewRepository` | Abstracción de persistencia del aggregate `Review`. |

**Domain Events**

| Evento | Descripción |
| :--- | :--- |
| `Solicitud Creada` | Se emite cuando se registra una nueva solicitud de servicio. |
| `Solicitud Completada` | Se emite cuando la solicitud finaliza tras completarse la intervención. |
| `Reseña Creada` | Se emite cuando el dueño envía la evaluación del servicio. |

**Reglas de negocio del dominio**

- La solicitud sigue una máquina de estados: `PENDING`, `ACCEPTED`, `REJECTED`, `IN_PROGRESS`, `CANCELED` y `COMPLETED`. No se permiten transiciones fuera de ese flujo.
- El dueño crea la solicitud y el proveedor la acepta o la rechaza. Solo una solicitud aceptada puede tener un técnico asignado.
- El técnico se asigna según su especialidad y disponibilidad.
- Al completarse la intervención, la solicitud padre pasa a `COMPLETED`.
- El dueño solo puede evaluar un servicio ya completado, y solo puede editar su evaluación durante las 48 horas posteriores a enviarla.

#### 4.2.6.2. Interface Layer.

La Interface Layer expone las capacidades del contexto hacia el exterior. Recibe las solicitudes HTTP que el **API Gateway** enruta después de validar el JWT, y publica una fachada para que otros contextos lean solicitudes, intervenciones y evaluaciones. Cada subdominio tiene su propio controlador.

**Controllers**

| Clase | Descripción |
| :--- | :--- |
| `ServiceRequestController` | Controlador REST del *Service Request Endpoint* (GET, POST, PUT). Gestiona la creación, el seguimiento, la aceptación, el rechazo, la cancelación y la asignación de técnico. Cubre US-04, US-05, US-21, TS-01 y TS-05. Depende de `ServiceRequestCommandService` y `ServiceRequestQueryService`. |
| `InterventionController` | Controlador REST del *Intervention Endpoint* (GET, POST). Gestiona el inicio y la finalización de intervenciones técnicas. Cubre TS-02. |
| `ReviewController` | Controlador REST del *Review Endpoint* (GET, POST, PUT). Gestiona el envío y la edición de evaluaciones. Cubre US-12 y TS-03. |

**Método principal:**

| Clase | Método | Descripción |
| :--- | :--- | :--- |
| `ServiceRequestController` | `create(req: CreateRequestResource): ResponseEntity<ServiceResponse>` | Recibe los datos de la solicitud, los convierte en un `CreateRequestCommand`, invoca al servicio de comandos y devuelve la solicitud creada. |

**Resources (records)**

| Clase | Descripción |
| :--- | :--- |
| `CreateRequestResource` | Datos de entrada para crear una solicitud de servicio (equipo, tipo, prioridad y descripción). |
| `ServiceResponse` | Representación de una solicitud en las respuestas de la API. |

**ACL / Facade (inbound services)**

| Clase | Descripción |
| :--- | :--- |
| `ServiceRequestContextFacade` | Fachada que expone a otros contextos los datos de solicitudes, intervenciones y evaluaciones, sin revelar los aggregates internos. Depende de `ServiceRequestQueryService`. |

**Consumidor de la fachada:**

| Contexto consumidor | Uso |
| :--- | :--- |
| Reporting and Analytics | Lee solicitudes, intervenciones y evaluaciones para calcular el cumplimiento de mantenimiento y el desempeño de los técnicos. |

#### 4.2.6.3. Application Layer.
La Application Layer orquesta los flujos del contexto. Recibe los comandos y consultas de la Interface Layer, coordina los aggregates, los repositorios y los servicios externos, y delega las reglas de negocio en el dominio. Sus capabilities son **crear y gestionar solicitudes, asignar técnicos, registrar intervenciones en campo, completar el servicio, y recibir y consultar evaluaciones**.

**Command Services**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `ServiceRequestCommandServiceImpl` | `ServiceRequestCommandService` | Gestiona el ciclo de vida de la solicitud y sus transiciones de estado. Depende de `ServiceRequestRepository`, `TechnicianAssignmentService` y los servicios externos. |
| `InterventionCommandServiceImpl` | `InterventionCommandService` | Registra las intervenciones y cierra la solicitud padre al completarlas. Depende de `InterventionRepository`. |
| `ReviewCommandServiceImpl` | `ReviewCommandService` | Gestiona el envío de evaluaciones y su edición dentro de la ventana permitida. Depende de `ReviewRepository`. |

**Manejadores de comandos:**

| Clase | Método | Flujo |
| :--- | :--- | :--- |
| `ServiceRequestCommandServiceImpl` | `handle(cmd: CreateRequestCommand): Optional<ServiceRequest>` | 1) Crea el aggregate `ServiceRequest` en estado `PENDING`. 2) Lo persiste. 3) Registra `Solicitud Creada`. 4) Solicita la notificación mediante Notification Management. Si la solicitud es correctiva, puede precargarse con el contexto de la alerta desde Monitoring and Alerting (US-29). |
| `ServiceRequestCommandServiceImpl` | `handle(cmd: AcceptRequestCommand / RejectRequestCommand)` | El proveedor acepta o rechaza la solicitud y el aggregate cambia de estado. |
| `ServiceRequestCommandServiceImpl` | `handle(cmd: AssignTechnicianCommand)` | Resuelve los candidatos con `TechnicianAssignmentService`, asigna el técnico, persiste el cambio y notifica la asignación. |
| `ServiceRequestCommandServiceImpl` | `handle(cmd: CancelRequestCommand)` | Cancela la solicitud y registra la fecha de cancelación. |
| `InterventionCommandServiceImpl` | `handle(cmd: StartInterventionCommand)` | Crea la intervención, registra la hora de inicio y pasa la solicitud a `IN_PROGRESS`. |
| `InterventionCommandServiceImpl` | `handle(cmd: CompleteInterventionCommand): void` | Registra el fin, el resumen de hallazgos y el estado de la intervención, y cierra la solicitud padre como `COMPLETED`. Registra `Solicitud Completada` y solicita la notificación. |
| `ReviewCommandServiceImpl` | `handle(cmd: SubmitReviewCommand)` | Verifica que la solicitud esté completada, crea la evaluación con su fecha límite de edición y registra `Reseña Creada`. |
| `ReviewCommandServiceImpl` | `handle(cmd: UpdateReviewCommand)` | Permite editar la evaluación solo si sigue dentro de las 48 horas. |

**Query Services**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `ServiceRequestQueryServiceImpl` | `ServiceRequestQueryService` | Resuelve las consultas, el seguimiento y el filtrado de solicitudes. |
| `InterventionQueryServiceImpl` | `InterventionQueryService` | Resuelve las consultas de intervenciones por solicitud o por técnico. |
| `ReviewQueryServiceImpl` | `ReviewQueryService` | Resuelve las consultas de evaluaciones y el promedio de calificación de un técnico. |

**Manejadores de consultas:**

| Clase | Método | Descripción |
| :--- | :--- | :--- |
| `ServiceRequestQueryServiceImpl` | `handle(q: GetRequestByIdQuery)` | Devuelve la solicitud que corresponde al identificador. |
| `ServiceRequestQueryServiceImpl` | `handle(q: GetRequestsByOwnerQuery / GetRequestsByTechnicianQuery / GetRequestsByStatusQuery)` | Devuelve las solicitudes de un dueño, de un técnico o en un estado determinado. |
| `InterventionQueryServiceImpl` | `handle(q: GetInterventionsByRequestQuery / GetInterventionsByTechnicianQuery)` | Devuelve las intervenciones de una solicitud o de un técnico. |
| `ReviewQueryServiceImpl` | `handle(q: GetReviewByRequestQuery)` | Devuelve la evaluación de una solicitud. |
| `ReviewQueryServiceImpl` | `handle(q: GetAverageRatingByTechnicianQuery)` | Devuelve el promedio de calificaciones de un técnico. |

**Outbound Services (ACL)**

| Clase | Contexto destino | Descripción |
| :--- | :--- | :--- |
| `MonitoringExternalService` | Monitoring and Alerting | ACL que recupera el contexto de la alerta y del equipo para precargar una orden de trabajo correctiva (US-29). |
| `ProfilesExternalService` | Profiles and Preferences Management | ACL que consulta la especialidad y la disponibilidad de los técnicos para la asignación. |
| `NotificationExternalService` | Notification Management | ACL que solicita el envío de notificaciones cuando una solicitud se crea, se asigna o se completa. |

**Flujos de integración**

| Flujo | Descripción |
| :--- | :--- |
| Crear solicitud referenciando un equipo | El dueño crea la solicitud sobre un equipo. El contexto la registra en estado `PENDING` y notifica al proveedor. Corresponde al Escenario 03 del Domain Message Flow. |
| Asignación de técnico | Al asignar, el contexto consulta a Profiles por especialidad y disponibilidad, y notifica al técnico. |
| Cierre del servicio | Al completarse la intervención, la solicitud pasa a `COMPLETED`, se notifica al dueño y queda habilitada la evaluación. |
| Indicadores de desempeño | Reporting and Analytics consulta las solicitudes, intervenciones y evaluaciones mediante la fachada. |

#### 4.2.6.4. Infrastructure Layer.

La Infrastructure Layer contiene las clases que acceden a la base de datos. Implementa los repositorios definidos en el dominio, de modo que el modelo no dependa de una tecnología concreta.

**Persistencia (Repositories)**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `SpringDataJpaServiceRequestRepository` | `ServiceRequestRepository` | Implementación con Spring Data JPA del repositorio del aggregate `ServiceRequest`. |
| `SpringDataJpaInterventionRepository` | `InterventionRepository` | Implementación con Spring Data JPA del repositorio del aggregate `Intervention`. |
| `SpringDataJpaReviewRepository` | `ReviewRepository` | Implementación con Spring Data JPA del repositorio del aggregate `Review`. |

Los tres repositorios operan sobre el esquema `services` de la instancia **PostgreSQL v18** (*Platform Database*), que mantiene un esquema por bounded context.

Responsabilidades de los repositorios:

- Guardar, actualizar y consultar solicitudes por identificador, dueño, técnico y estado.
- Guardar intervenciones y consultarlas por solicitud o por técnico.
- Guardar evaluaciones y consultarlas por solicitud, además de calcular el promedio de calificación por técnico.

**Modelo de tablas del esquema `services`**

| Tabla | Columna | Tipo | Descripción |
| :--- | :--- | :--- | :--- |
| `ServiceRequest` | `request_id` | `VARCHAR` (PK) | Identificador de la solicitud. |
| `ServiceRequest` | `origin` | `VARCHAR(25)` | Origen de la solicitud. |
| `ServiceRequest` | `type` | `VARCHAR(35)` | Tipo de servicio. |
| `ServiceRequest` | `priority` | `VARCHAR(35)` | Prioridad. |
| `ServiceRequest` | `description` | `VARCHAR(50)` | Descripción del problema. |
| `ServiceRequest` | `status` | `VARCHAR(40)` | Estado de la solicitud. |
| `ServiceRequest` | `completed_at` | `DATETIME` | Fecha de finalización. |
| `ServiceRequest` | `canceled_at` | `DATETIME` | Fecha de cancelación. |
| `ServiceRequest` | `owner_profiles_id` | `VARCHAR` (FK) | Perfil del dueño. |
| `ServiceRequest` | `user_id` | `VARCHAR` (FK) | Usuario asociado. |
| `ServiceRequest` | `site_id` | `VARCHAR` (FK) | Sede del equipo. |
| `ServiceRequest` | `equipment_id` | `VARCHAR` (FK) | Equipo del servicio. |
| `ServiceRequest` | `user_profiles_id` | `VARCHAR` (FK) | Perfil asociado al servicio. |
| `Intervention` | `intervention_id` | `VARCHAR` (PK) | Identificador de la intervención. |
| `Intervention` | `status` | `VARCHAR(30)` | Estado de la intervención. |
| `Intervention` | `summary` | `VARCHAR(50)` | Resumen de hallazgos. |
| `Intervention` | `start_time` | `DATETIME` | Inicio. |
| `Intervention` | `end_time` | `DATETIME` | Fin. |
| `Intervention` | `request_id` | `VARCHAR` (FK) | Solicitud atendida. |
| `Intervention` | `technician_profiles_id` | `VARCHAR` (FK) | Técnico que interviene. |
| `Review` | `review_id` | `VARCHAR` (PK) | Identificador de la evaluación. |
| `Review` | `rating_comunication` | `INTEGER` | Calificación de comunicación. |
| `Review` | `rating_eficacy` | `INTEGER` | Calificación de eficacia. |
| `Review` | `performance` | `VARCHAR(40)` | Calificación de desempeño. |
| `Review` | `comment` | `VARCHAR(50)` | Comentario del dueño. |
| `Review` | `request_id` | `VARCHAR` (FK) | Solicitud evaluada. |
| `Review` | `owner_profiles_id` | `VARCHAR` (FK) | Dueño que evalúa. |
| `Review` | `technician_profiles_id` | `VARCHAR` (FK) | Técnico evaluado. |

**Adaptadores hacia otros contextos**

| Clase | Descripción |
| :--- | :--- |
| Adaptador de `MonitoringExternalService` | Comunicación con Monitoring and Alerting para obtener el contexto de la alerta. |
| Adaptador de `ProfilesExternalService` | Comunicación con Profiles para consultar la especialidad y la disponibilidad de los técnicos. |
| Adaptador de `NotificationExternalService` | Comunicación con Notification Management para solicitar el envío de notificaciones. |

**Resumen de dependencias externas**

| Recurso | Tipo | Uso en Service Request Management |
| :--- | :--- | :--- |
| PostgreSQL v18 (esquema `services`) | Base de datos relacional | Persistencia de solicitudes, intervenciones y evaluaciones. |
| Monitoring and Alerting | Bounded context interno | Contexto de la alerta para precargar solicitudes correctivas. |
| Profiles and Preferences Management | Bounded context interno | Especialidad y disponibilidad de los técnicos. |
| Notification Management | Bounded context interno | Notificaciones de creación, asignación y finalización. |
| Reporting and Analytics | Bounded context interno (consumidor) | Lectura de solicitudes, intervenciones y evaluaciones. |

#### 4.2.6.5. Bounded Context Software Architecture Component Level Diagrams.

En el siguiente diagrama de componentes mostramos cómo organizamos el contexto en tres subdominios: ServiceRequest, Intervention y Review. Cada uno cuenta con su controlador, sus servicios de comandos y consultas, su aggregate y su repositorio. Se incluye el servicio de dominio que resuelve los técnicos candidatos a una asignación, la fachada que consume Reporting and Analytics, las capas anticorrupción hacia Monitoring, Profiles y Notification, y el esquema `services` de la base de datos.

![IceTrack Bounded Context Component Level Diagram - Service Request Management](assets/chapter04/c4/component/serviceComponent.png)

#### 4.2.6.6. Bounded Context Software Architecture Code Level Diagrams.

En esta sección presentamos los diagramas de nivel de código del bounded context Service Request Management: el diagrama de clases de la capa de dominio y el diseño de la base de datos del esquema `services`.

##### 4.2.6.6.1. Bounded Context Domain Layer Class Diagrams.

El siguiente diagrama de clases representa la estructura del contexto organizada por capas. Incluye el aggregate de la solicitud de servicio, las interfaces de los servicios de solicitudes e intervenciones, el servicio de asignación de técnicos, los servicios de comandos de la capa de aplicación, el controlador, los recursos y la fachada de la capa de interfaces, y los repositorios JPA de la capa de infraestructura.

![IceTrack Bounded Context Domain Layer Class Diagram - Service Request Management](assets/chapter04/diagrams/class/serviceDiagramClass.png)

##### 4.2.6.6.2. Bounded Context Database Design Diagram.

El siguiente diagrama presenta el diseño de la base de datos del esquema `services`. La tabla `ServiceRequest` guarda las solicitudes con su tipo, prioridad, estado y fechas, la tabla `Intervention` registra las intervenciones realizadas por los técnicos, y la tabla `Review` almacena las evaluaciones de los dueños sobre cada servicio.

![IceTrack Bounded Context Database Design Diagram - Service Request Management](assets/chapter04/diagrams/database/serviceDiagramDatabase.png)

---

### 4.2.7. Bounded Context: Notification Management

En el bounded context Notification Management generamos y gestionamos las notificaciones dirigidas a cada usuario, ya sea por un mantenimiento vencido, una alerta de monitoreo o una actualización de una solicitud de servicio. Es un contexto genérico de soporte: no decide cuándo notificar, sino que actúa cuando otro contexto se lo solicita mediante su fachada, resolviendo quién debe recibir el mensaje y en qué idioma.

#### 4.2.7.1. Domain Layer.

La Domain Layer del bounded context **Notification Management** contiene el modelo de las notificaciones que la plataforma envía a sus usuarios. Es un contexto genérico de soporte: convierte los eventos que ocurren en otros contextos (alertas de monitoreo, cambios en solicitudes de servicio, mantenimientos vencidos) en mensajes dirigidos a un destinatario concreto, con un canal y un estado de entrega. Su modelo se centra en un único aggregate, **Notification**, y en un domain service que determina a quién debe notificarse cada evento.

**Aggregate Root**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `Notification` | Aggregate Root / Entity | Representa un mensaje dirigido a un usuario. Controla su estado de lectura, su descarte y su estado de entrega. |

Atributos de `Notification`:

| Atributo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id` | `UUID` | Identificador único de la notificación. |
| `userId` | `UUID` | Destinatario de la notificación (referencia al usuario de IAM). |
| `message` | `String` | Mensaje localizado que se muestra al destinatario. |
| `type` | `NotificationType` | Tipo de notificación (mantenimiento vencido, alerta de monitoreo o actualización de una solicitud). |
| `severity` | `NotificationSeverity` | Nivel de severidad de la notificación. |
| `channel` | `String` | Canal por el que se entrega la notificación. |
| `deliveryStatus` | `String` | Estado de entrega de la notificación. |
| `isRead` | `Boolean` | Indica si el destinatario ya la leyó. |
| `dismissedAt` | `DateTime` | Fecha y hora en que el destinatario la descartó. |
| `equipmentId` | `UUID` | Equipo relacionado con el evento que originó la notificación. |
| `deviceId` | `UUID` | Dispositivo relacionado, cuando el evento proviene de telemetría. |
| `alertId` | `UUID` | Alerta relacionada, cuando la notificación se origina en Monitoring and Alerting. |

**Value Objects y enumeraciones**

| Clase | Descripción |
| :--- | :--- |
| `NotificationType` | Enum con el tipo de notificación: mantenimiento vencido, alerta de monitoreo o actualización de solicitud de servicio. |
| `NotificationSeverity` | Enum con el nivel de severidad de la notificación. |
| `Recipient` | Value Object que identifica al destinatario, con sus datos de contacto y su idioma. |

**Commands y Queries del dominio**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `CreateNotificationCommand` | Command (record) | Solicita la creación de una notificación a partir de un evento de otro contexto. |
| `MarkAsReadCommand` | Command (record) | Marca una notificación como leída. |
| `DismissCommand` | Command (record) | Descarta una notificación. |
| `GetUserNotificationsQuery` | Query (record) | Lista las notificaciones de un usuario. |
| `GetUnreadCountQuery` | Query (record) | Obtiene la cantidad de notificaciones no leídas de un usuario. |

**Domain Services**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `RecipientResolver` | Domain Service | Determina quién debe ser notificado ante un evento dado: el dueño del equipo, el técnico asignado o ambos. |
| `NotificationCommandService` | Interfaz | Contrato de las operaciones que crean y modifican notificaciones. |
| `NotificationQueryService` | Interfaz | Contrato de las consultas de notificaciones y del contador de no leídas. |

**Repositories (interfaces)**

| Interfaz | Descripción |
| :--- | :--- |
| `NotificationRepository` | Abstracción de persistencia del aggregate `Notification`. El dominio solo conoce esta interfaz. Su implementación pertenece a la Infrastructure Layer. |

**Domain Events**

| Evento | Descripción |
| :--- | :--- |
| `Notificación Generada` | Se emite cuando se crea una notificación para un destinatario. |
| `Notificación Leída` | Se emite cuando el destinatario marca la notificación como leída. |
| `Notificación Descartada` | Se emite cuando el destinatario descarta la notificación. |

**Reglas de negocio del dominio**

- Una notificación pertenece a un único destinatario.
- Los destinatarios de un evento los determina `RecipientResolver`: el dueño del equipo, el técnico asignado o ambos, según el evento.
- El mensaje se construye en el idioma del destinatario, con base en las preferencias de su perfil.
- Una notificación puede leerse y descartarse por el destinatario, y guarda la fecha de descarte.
- Este contexto no decide cuándo se debe notificar. Solo actúa cuando otro contexto se lo solicita.

#### 4.2.7.2. Interface Layer.

La Interface Layer expone las capacidades del contexto hacia el exterior. Recibe las solicitudes HTTP que el **API Gateway** enruta hacia el *Notification Endpoint* (GET, PUT) y publica una fachada para que los demás contextos soliciten notificaciones sin conocer los detalles del canal ni de la entrega.

**Controllers**

| Clase | Descripción |
| :--- | :--- |
| `NotificationController` | Controlador REST que permite al usuario listar sus notificaciones, marcarlas como leídas y descartarlas. Depende de `NotificationCommandService` y `NotificationQueryService`. |

**Método principal:**

| Método | Descripción |
| :--- | :--- |
| `markAsRead(id: UUID): ResponseEntity<Void>` | Convierte la solicitud en un `MarkAsReadCommand` y lo delega al servicio de comandos. |

**Resources (records)**

| Clase | Descripción |
| :--- | :--- |
| `NotificationResponse` | Representación de una notificación en las respuestas de la API (mensaje, tipo, severidad, estado de lectura). |

**ACL / Facade (inbound services)**

| Clase | Descripción |
| :--- | :--- |
| `NotificationContextFacade` | Fachada que expone a los demás contextos la creación de notificaciones, ocultando el canal y los detalles de entrega. Depende de `NotificationCommandService`. |

Método de `NotificationContextFacade`:

| Método | Descripción |
| :--- | :--- |
| `dispatch(userId: UUID, msg: String): void` | Solicita el envío de una notificación al usuario indicado. |

**Consumidores de la fachada:**

| Contexto consumidor | Evento que origina la notificación |
| :--- | :--- |
| Monitoring and Alerting | Excursión térmica o dispositivo sin señal. |
| Service Request Management | Solicitud creada, técnico asignado o servicio completado. |
| Reporting and Analytics | Reporte listo para el usuario que lo solicitó. |

#### 4.2.7.3. Application Layer.

La Application Layer orquesta los flujos del contexto. Recibe los comandos y consultas de la Interface Layer y de la fachada, coordina el aggregate `Notification`, el repositorio y los servicios externos, y delega las reglas de negocio en el dominio. Sus capabilities son **crear notificaciones a partir de eventos de otros contextos, resolver a sus destinatarios, y permitir su consulta, lectura y descarte**.

**Command Services**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `NotificationCommandServiceImpl` | `NotificationCommandService` | Construye el mensaje localizado, resuelve los destinatarios y registra el resultado de la entrega. Depende de `NotificationRepository`. |

Manejadores de comandos:

| Método | Flujo |
| :--- | :--- |
| `handle(cmd: CreateNotificationCommand): void` | 1) Recibe el evento de otro contexto a través de la fachada. 2) Usa `RecipientResolver` para determinar los destinatarios. 3) Consulta a Profiles los datos de contacto y el idioma de cada destinatario. 4) Construye el mensaje localizado. 5) Crea y persiste una `Notification` por destinatario. 6) Registra `Notificación Generada` y el resultado de la entrega. |
| `handle(cmd: MarkAsReadCommand): void` | Busca la notificación, la marca como leída, persiste el cambio y registra `Notificación Leída`. |
| `handle(cmd: DismissCommand)` | Descarta la notificación, registra la fecha de descarte y emite `Notificación Descartada`. |

**Query Services**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `NotificationQueryServiceImpl` | `NotificationQueryService` | Resuelve las consultas de notificaciones usando `NotificationRepository`. |

Manejadores de consultas:

| Método | Descripción |
| :--- | :--- |
| `handle(q: GetUserNotificationsQuery): List<Notification>` | Devuelve las notificaciones de un usuario. |
| `handle(q: GetUnreadCountQuery)` | Devuelve la cantidad de notificaciones no leídas de un usuario, útil para el indicador del dashboard. |

**Outbound Services (ACL)**

| Clase | Contexto destino | Descripción |
| :--- | :--- | :--- |
| `ProfilesExternalService` | Profiles and Preferences Management | ACL que resuelve los datos de contacto y el idioma de cada destinatario. |

**Flujos de integración**

| Flujo | Descripción |
| :--- | :--- |
| Alerta de monitoreo | Cuando Monitoring and Alerting detecta una excursión térmica o un dispositivo sin señal, solicita la notificación mediante la fachada. Este contexto resuelve los destinatarios y la crea. |
| Actualización de solicitud de servicio | Cuando una solicitud se crea, se asigna a un técnico o se completa, Service Request Management solicita la notificación al dueño, al técnico o a ambos. |
| Reporte listo | Cuando Reporting and Analytics termina un reporte, solicita notificar al usuario que lo pidió. |
| Mantenimiento vencido | Cuando un equipo supera su intervalo de mantenimiento configurado, se genera una notificación que el dueño puede consultar y descartar. |

#### 4.2.7.4. Infrastructure Layer.

La Infrastructure Layer contiene las clases que acceden a la base de datos y a otros contextos. Implementa la abstracción de repositorio definida en el dominio, de modo que el modelo no dependa de una tecnología concreta.

**Persistencia (Repositories)**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `SpringDataJpaNotificationRepository` | `NotificationRepository` | Implementación con Spring Data JPA del repositorio del aggregate `Notification`. Opera sobre el esquema `notifications` de la instancia **PostgreSQL v18** (*Platform Database*), que mantiene un esquema por bounded context. |

Responsabilidades del repositorio:

- Guardar y actualizar notificaciones.
- Consultar las notificaciones de un usuario.
- Contar las notificaciones no leídas de un usuario.

**Modelo de tabla del esquema `notifications`**

| Tabla | Columna | Tipo | Descripción |
| :--- | :--- | :--- | :--- |
| `Notification` | `notification_id` | `VARCHAR` (PK) | Identificador de la notificación. |
| `Notification` | `message` | `VARCHAR(50)` | Mensaje mostrado al destinatario. |
| `Notification` | `type` | `VARCHAR(40)` | Tipo de notificación. |
| `Notification` | `severity` | `VARCHAR(40)` | Severidad. |
| `Notification` | `is_read` | `BOOLEAN` | Indica si fue leída. |
| `Notification` | `dismissed_at` | `DATETIME` | Fecha de descarte. |
| `Notification` | `user_id` | `VARCHAR` (FK) | Destinatario. |
| `Notification` | `equipment_id` | `VARCHAR` (FK) | Equipo relacionado. |
| `Notification` | `device_id` | `VARCHAR` (FK) | Dispositivo relacionado. |
| `Notification` | `alert_id` | `VARCHAR` (FK) | Alerta relacionada. |

**Adaptador hacia otro contexto**

| Clase | Descripción |
| :--- | :--- |
| Adaptador de `ProfilesExternalService` | Comunicación con Profiles para obtener los datos de contacto y el idioma del destinatario. |

**Resumen de dependencias externas**

| Recurso | Tipo | Uso en Notification Management |
| :--- | :--- | :--- |
| PostgreSQL v18 (esquema `notifications`) | Base de datos relacional | Persistencia de las notificaciones. |
| Profiles and Preferences Management | Bounded context interno | Datos de contacto e idioma de los destinatarios. |
| Monitoring and Alerting, Service Request Management y Reporting and Analytics | Bounded contexts internos (consumidores) | Solicitan la creación de notificaciones mediante la fachada. |

#### 4.2.7.5. Bounded Context Software Architecture Component Level Diagrams.

En el siguiente diagrama de componentes mostramos cómo organizamos el contexto Notification Management. Se observan el Notification Controller que permite consultar, leer y descartar notificaciones, la fachada que reciben Monitoring, Service Request y Reporting, los servicios de comandos y consultas, el aggregate `Notification` con su repositorio y el servicio de dominio que resuelve a los destinatarios. También se muestra la capa anticorrupción hacia Profiles and Preferences y el esquema `notifications` de la base de datos.

![IceTrack Bounded Context Component Level Diagram - Notification Management](assets/chapter04/c4/component/notificationComponent.png)

#### 4.2.7.6. Bounded Context Software Architecture Code Level Diagrams.

En esta sección presentamos los diagramas de nivel de código del bounded context Notification Management: el diagrama de clases de la capa de dominio y el diseño de la base de datos del esquema `notifications`.

##### 4.2.7.6.1. Bounded Context Domain Layer Class Diagrams.

El siguiente diagrama de clases representa la estructura del contexto organizada por capas. En el dominio se encuentra el aggregate `Notification` y las interfaces de los servicios de comandos y consultas. En la capa de aplicación se ubican sus implementaciones, en la capa de interfaces el controlador, el recurso de respuesta y la fachada del contexto, y en infraestructura la implementación JPA del repositorio.

![IceTrack Bounded Context Domain Layer Class Diagram - Notification Management](assets/chapter04/diagrams/class/notificationManagementDiagramClass.png)

##### 4.2.7.6.2. Bounded Context Database Design Diagram.

El siguiente diagrama presenta el diseño de la base de datos del esquema `notifications`. La tabla `Notification` almacena el mensaje, su tipo y severidad, su estado de lectura y de descarte, y las referencias al usuario destinatario y al equipo, dispositivo o alerta que originó la notificación.

![IceTrack Bounded Context Database Design Diagram - Notification Management](assets/chapter04/diagrams/database/notificationDiagramDatabase.png)

---

### 4.2.8. Bounded Context: Reporting and Analytics

En el bounded context Reporting and Analytics calculamos indicadores de negocio a partir de la información de otros contextos: el cumplimiento del mantenimiento, el tiempo de actividad de los equipos, las excursiones de temperatura y el desempeño de los técnicos. Es un contexto de consumo, ya que no es dueño de los datos operativos, sino que los lee de Monitoring and Alerting y de Service Request Management para generar reportes de forma asíncrona.

#### 4.2.8.1. Domain Layer.

La Domain Layer del bounded context **Reporting and Analytics** contiene el modelo de los reportes que la plataforma genera para sus usuarios. Es un contexto de soporte y consumo: no es dueño de los datos operativos, sino que calcula indicadores de negocio a partir de la información de otros contextos (cumplimiento de mantenimiento, tiempo de actividad de los equipos y desempeño de los técnicos). Su modelo gira en torno a un único aggregate, **Report**, y a dos domain services: uno que elige la estrategia de generación según el tipo de reporte y otro que calcula los indicadores cuantitativos de la cadena de frío.

**Aggregate Root**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `Report` | Aggregate Root | Representa una solicitud de reporte y su resultado. Controla su máquina de estados y la referencia al archivo generado. |

Atributos de `Report`:

| Atributo | Tipo | Descripción |
| :--- | :--- | :--- |
| `id` | `UUID` | Identificador único del reporte. |
| `type` | `ReportType` | Tipo de reporte solicitado. |
| `format` | `ReportFormat` | Formato de salida del reporte. |
| `filters` | `ReportFilters` | Filtros aplicados a la generación (equipo, sede, rango de fechas, entre otros). |
| `status` | `ReportStatus` | Estado actual dentro de la máquina de estados. |
| `url` | `String` | Referencia al archivo generado, disponible cuando el reporte se completa. |

**Value Objects y enumeraciones**

| Clase | Descripción |
| :--- | :--- |
| `ReportType` | Enum con los tipos de reporte: `MaintenanceCompliance`, `EquipmentUptime`, `TechnicianPerformance` y `TemperatureExcursion`. |
| `ReportFormat` | Formato de salida del reporte. |
| `ReportFilters` | Value Object que agrupa los criterios con los que se genera el reporte. |
| `ReportStatus` | Enum con los estados del reporte: `PENDING`, `GENERATING`, `COMPLETED` y `FAILED`. |

**Commands y Queries del dominio**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `RequestReportCommand` | Command (record) | Solicita la generación de un reporte. |
| `MarkAsGeneratingCommand` | Command (record) | Marca el reporte como en proceso de generación. |
| `MarkAsCompletedCommand` | Command (record) | Marca el reporte como completado y registra la referencia al archivo generado. |
| `MarkAsFailedCommand` | Command (record) | Marca el reporte como fallido. |
| `GetReportByIdQuery` | Query (record) | Obtiene un reporte por su identificador. |
| `SearchReportsByFiltersQuery` | Query (record) | Busca reportes por nombre, tipo o estado. |
| `GetRecentReportsQuery` | Query (record) | Lista los reportes generados más recientemente. |

**Domain Services**

| Clase | Categoría | Descripción |
| :--- | :--- | :--- |
| `ReportGenerationStrategy` | Domain Service (interfaz, patrón Strategy) | Define cómo se genera cada tipo de reporte. Hay una estrategia por cada `ReportType`: `MaintenanceCompliance`, `EquipmentUptime`, `TechnicianPerformance` y `TemperatureExcursion`. |
| `ReportGenerationStrategyRegistry` | Domain Service | Selecciona la estrategia correspondiente al tipo de reporte solicitado. |
| `ColdChainMetricsCalculator` | Domain Service | Calcula los indicadores cuantitativos de la cadena de frío: temperatura cinética media (ponderada con Arrhenius), grados-minuto de excursión, porcentaje de tiempo de actividad, desviación estándar de la temperatura, tiempo medio de reparación (MTTR) y calificación promedio. |
| `ReportCommandService` | Interfaz | Contrato de las operaciones que solicitan y actualizan el estado de un reporte. |
| `ReportQueryService` | Interfaz | Contrato de las consultas, la búsqueda y la descarga de reportes. |

**Repositories (interfaces)**

| Interfaz | Descripción |
| :--- | :--- |
| `ReportRepository` | Abstracción de persistencia del aggregate `Report`. El dominio solo conoce esta interfaz. Su implementación pertenece a la Infrastructure Layer. |

**Domain Events**

| Evento | Descripción |
| :--- | :--- |
| `Reporte Generado` | Se emite cuando un reporte termina su generación y queda disponible para el usuario que lo solicitó. |

**Reglas de negocio del dominio**

- La generación de un reporte es asíncrona. El reporte recorre los estados `PENDING`, `GENERATING` y `COMPLETED`, o `FAILED` si la generación no puede completarse.
- La estrategia de generación se elige según el tipo de reporte solicitado.
- Los indicadores se calculan con datos provenientes de otros contextos, y este contexto no modifica esa información.
- Un reporte solo puede descargarse cuando su estado es `COMPLETED`.

#### 4.2.8.2. Interface Layer.

La Interface Layer expone las capacidades del contexto hacia el exterior. Recibe las solicitudes HTTP que el **API Gateway** enruta hacia el *Report Endpoint* (GET, POST) después de validar el JWT. Este contexto solo consume información de otros contextos, por lo que no publica fachada de entrada.

**Controllers**

| Clase | Descripción |
| :--- | :--- |
| `ReportController` | Controlador REST para solicitar reportes, buscarlos por nombre, tipo y estado, y descargarlos. Cubre las historias US-22 (buscar reportes por filtros) y US-24 (ver reporte de servicio realizado). Depende de `ReportCommandService` y `ReportQueryService`. |

Método principal:

| Método | Descripción |
| :--- | :--- |
| `generate(req: RequestReportResource): ResponseEntity<ReportResponse>` | Recibe la solicitud de reporte, la convierte en un `RequestReportCommand`, la delega al servicio de comandos y devuelve el reporte creado. |

**Resources (records)**

| Clase | Descripción |
| :--- | :--- |
| `RequestReportResource` | Datos de entrada para solicitar un reporte (tipo, formato y filtros). |
| `ReportResponse` | Representación del reporte en las respuestas de la API (tipo, estado y enlace de descarga). |

#### 4.2.8.3. Application Layer.

La Application Layer orquesta los flujos del contexto. Recibe los comandos y consultas de la Interface Layer, coordina el aggregate `Report`, el repositorio, las estrategias de generación y los servicios externos, y delega las reglas de negocio en el dominio. Sus capabilities son **solicitar y generar reportes de forma asíncrona, calcular indicadores de la cadena de frío, buscar y descargar reportes, y avisar al usuario cuando su reporte está listo**.

**Command Services**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `ReportCommandServiceImpl` | `ReportCommandService` | Conduce la generación asíncrona del reporte a través de su máquina de estados. Depende de `ReportRepository` y de `ReportGenerationStrategyRegistry`. |

Manejadores de comandos:

| Método | Flujo |
| :--- | :--- |
| `handle(cmd: RequestReportCommand): Optional<Report>` | 1) Crea el aggregate `Report` en estado `PENDING` y lo persiste. 2) Selecciona la estrategia correspondiente al tipo mediante `ReportGenerationStrategyRegistry`. 3) Marca el reporte como `GENERATING`. 4) La estrategia solicita los datos a los contextos de origen y `ColdChainMetricsCalculator` calcula los indicadores. 5) Al terminar, marca el reporte como `COMPLETED` con la referencia al archivo generado, o como `FAILED` si ocurre un error. 6) Registra `Reporte Generado` y solicita la notificación al usuario. |
| `handle(cmd: MarkAsGeneratingCommand)` | Cambia el estado del reporte a `GENERATING`. |
| `handle(cmd: MarkAsCompletedCommand)` | Cambia el estado a `COMPLETED` y guarda la referencia al archivo generado. |
| `handle(cmd: MarkAsFailedCommand)` | Cambia el estado a `FAILED`. |

**Query Services**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `ReportQueryServiceImpl` | `ReportQueryService` | Resuelve las consultas de reportes usando `ReportRepository`. |

Manejadores de consultas:

| Método | Descripción |
| :--- | :--- |
| `handle(q: GetReportByIdQuery): Optional<Report>` | Devuelve el reporte que corresponde al identificador. |
| `handle(q: SearchReportsByFiltersQuery)` | Busca reportes por nombre, tipo o estado. |
| `handle(q: GetRecentReportsQuery)` | Devuelve los reportes generados más recientemente. |

**Estrategias de generación**

| Tipo de reporte | Contexto de origen de los datos | Indicadores que calcula |
| :--- | :--- | :--- |
| `MaintenanceCompliance` | Service Request Management | Cumplimiento del mantenimiento programado. |
| `EquipmentUptime` | Monitoring and Alerting | Porcentaje de tiempo de actividad de los equipos. |
| `TechnicianPerformance` | Service Request Management | Tiempo medio de reparación (MTTR) y calificación promedio de los técnicos. |
| `TemperatureExcursion` | Monitoring and Alerting | Temperatura cinética media, grados-minuto de excursión y desviación estándar de la temperatura. |

**Outbound Services (ACL)**

| Clase | Contexto destino | Descripción |
| :--- | :--- | :--- |
| `ServiceRequestExternalService` | Service Request Management | ACL que lee solicitudes, intervenciones y evaluaciones, que alimentan los reportes de cumplimiento y de desempeño de técnicos. |
| `MonitoringExternalService` | Monitoring and Alerting | ACL que lee el historial de telemetría y los registros de alertas, que alimentan los reportes de temperatura y de tiempo de actividad. |
| `NotificationExternalService` | Notification Management | ACL que anuncia que el reporte está listo para el usuario que lo solicitó. |

**Flujo de integración**

| Flujo | Descripción |
| :--- | :--- |
| Generar reporte de cumplimiento | El usuario solicita un reporte. El contexto lo registra, elige la estrategia según el tipo, lee los datos de los contextos de origen, calcula los indicadores y guarda el resultado. Al finalizar, notifica al usuario. Corresponde al Escenario 04 del Domain Message Flow. |

#### 4.2.8.4. Infrastructure Layer.

La Infrastructure Layer contiene las clases que acceden a la base de datos y a los demás contextos. Implementa la abstracción de repositorio definida en el dominio, de modo que el modelo no dependa de una tecnología concreta.

**Persistencia (Repositories)**

| Clase | Implementa | Descripción |
| :--- | :--- | :--- |
| `SpringDataJpaReportRepository` | `ReportRepository` | Implementación con Spring Data JPA del repositorio del aggregate `Report`. Opera sobre el esquema `reporting` de la instancia **PostgreSQL v18** (*Platform Database*), que mantiene un esquema por bounded context. |

Responsabilidades del repositorio:

- Guardar y actualizar reportes, incluido su estado y la referencia al archivo generado.
- Consultar reportes por identificador.
- Buscar reportes por nombre, tipo y estado.
- Listar los reportes más recientes.

**Adaptadores hacia otros contextos**

| Clase | Descripción |
| :--- | :--- |
| Adaptador de `ServiceRequestExternalService` | Comunicación con Service Request Management para leer solicitudes, intervenciones y evaluaciones. |
| Adaptador de `MonitoringExternalService` | Comunicación con Monitoring and Alerting para leer el historial de telemetría y las alertas. |
| Adaptador de `NotificationExternalService` | Comunicación con Notification Management para solicitar el aviso de reporte listo. |

**Resumen de dependencias externas**

| Recurso | Tipo | Uso en Reporting and Analytics |
| :--- | :--- | :--- |
| PostgreSQL v18 (esquema `reporting`) | Base de datos relacional | Persistencia de los reportes. |
| Service Request Management | Bounded context interno (Upstream) | Solicitudes, intervenciones y evaluaciones. |
| Monitoring and Alerting | Bounded context interno (Upstream) | Historial de telemetría y alertas. |
| Notification Management | Bounded context interno | Aviso de reporte listo. |

#### 4.2.8.5. Bounded Context Software Architecture Component Level Diagrams.

En el siguiente diagrama de componentes mostramos cómo organizamos el contexto Reporting and Analytics. Se observan el Report Controller que atiende la solicitud, búsqueda y descarga de reportes, los servicios de comandos y consultas, el aggregate `Report` con su repositorio, la estrategia de generación seleccionada según el tipo de reporte y el calculador de indicadores de la cadena de frío. También se muestran las capas anticorrupción hacia Service Request, Monitoring y Notification, y el esquema `reporting` de la base de datos.

![IceTrack Bounded Context Component Level Diagram - Reporting and Analytics](assets/chapter04/c4/component/reportingComponent.png)

#### 4.2.8.6. Bounded Context Software Architecture Code Level Diagrams.

En esta sección presentamos los diagramas de nivel de código del bounded context Reporting and Analytics: el diagrama de clases de la capa de dominio y el diseño de la base de datos del esquema `reporting`.

##### 4.2.8.6.1. Bounded Context Domain Layer Class Diagrams.

El siguiente diagrama de clases representa la estructura del contexto organizada por capas. En el dominio se encuentra el aggregate `Report` y las interfaces de los servicios de comandos y consultas. En la capa de aplicación se ubican sus implementaciones junto con el registro de estrategias de generación, en la capa de interfaces el controlador y los recursos de solicitud y respuesta, y en infraestructura la implementación JPA del repositorio.

![IceTrack Bounded Context Domain Layer Class Diagram - Reporting and Analytics](assets/chapter04/diagrams/class/reportingDiagramClass.png)

##### 4.2.8.6.2. Bounded Context Database Design Diagram.

El siguiente diagrama presenta el diseño de la base de datos del esquema `reporting`, donde persistimos los reportes solicitados por los usuarios junto con su tipo, su estado de generación y la referencia al archivo resultante.

![IceTrack Bounded Context Database Design Diagram - Reporting and Analytics](assets/chapter04/diagrams/database/reportingDiagramDatabase.png)

# Conclusiones

## Conclusiones y Recomendaciones

**Conclusiones**

-  En los capítulos I y II confirmamos que los negocios con cadena de frío en Lima operan con mantenimiento reactivo y datos aislados en controladores. Esto genera pérdidas de inventario, sobreconsumo eléctrico y fallas inesperadas. Las entrevistas a heladerías y a técnicos, junto con los User Personas, el User Task Matrix y los Journey Maps, nos mostraron que ambos segmentos comparten la necesidad de controlar la temperatura y prevenir fallas.

- En el capítulo III convertimos las necesidades en épicas, historias de usuario y historias técnicas con criterios de aceptación en Gherkin. También definimos requisitos no funcionales concretos, como una latencia menor a 3 segundos en el dashboard, almacenamiento en búfer en el ESP32 ante cortes de red y comunicaciones cifradas. 

- En el capítulo IV dividimos la solución en ocho bounded contexts, con Monitoring and Alerting como Core Domain y Service Request Management como segundo núcleo operativo. Definimos sus relaciones con Context Mapping y protegimos la integración entre contextos con capas anticorrupción. Documentamos la arquitectura con los diagramas C4 y detallamos cada contexto en sus capas de dominio, interfaz, aplicación e infraestructura, con sus diagramas de componentes, de clases y de base de datos. Esta separación permite que cada integrante del equipo trabaje un contexto de forma independiente y que el sistema evolucione sin afectar a los demás.

En cuanto al trabajo en equipo, como grupo consolidamos liderazgo conjunto, colaboración inclusiva y planificación por metas. Cada integrante asumió tareas según sus fortalezas, cumplió plazos y aportó a la coherencia del informe. Este modo de trabajo permitió integrar entrevistas, modelos de dominio y arquitectura en una propuesta sólida y lista para la siguiente fase.

**Recomendación**

- Recomendamos construir primero un flujo completo y mínimo del Core Domain, que va desde el envío de la telemetría por el ESP32 hasta la generación de una alerta y su visualización en el dashboard, e implementarlo con las historias de mayor prioridad del backlog. Una vez funcionando, conviene validarlo con una prueba piloto en una o dos heladerías de Lima antes de desarrollar los contextos de soporte, como Reporting and Analytics. Esto permitirá confirmar con usuarios reales las hipótesis sobre alertas y umbrales, y ajustar las reglas de evaluación con datos reales de operación. Así reducimos el riesgo de invertir esfuerzo en funciones que los usuarios no necesiten.

# Bibliografía

- Agraria.pe. (2 de julio de 2019). *Perú pierde más del 33% de los alimentos que produce por mal uso de la cadena de frío*. Agencia Agraria de Noticias. https://www.agraria.pe/noticias/peru-pierde-mas-del-33-de-los-alimentos-que-produce-por-mal--19324

- Agroperú Informa. (2 de julio de 2026). *Eficiencia en la cadena de frío reduce el desperdicio de alimentos y fortalece el abastecimiento*. Agroperú. https://www.agroperu.pe/eficiencia-en-la-cadena-de-frio-reduce-el-desperdicio-de-alimentos-y-fortalece-el-abastecimiento/

- Axios. (s.f.). *Axios: Promise based HTTP client for the browser and node.js*. https://axios-http.com/docs/intro

- Conventional Commits. (s.f.). *Conventional commits*. https://www.conventionalcommits.org/

- Dawsongroup TCS. (2024). *Eficiencia energética en refrigeración industrial: cómo reducir el consumo sin comprometer la calidad*. Dawsongroup Ibérica. https://dawsongrouptcs.com/iberica/proyectos/eficiencia-energetica-en-refrigeracion-industrial-como-reducir-el-consumo-sin-comprometer-la-calidad/

- Google. (s.f.). *Google HTML/CSS style guide*. https://google.github.io/styleguide/htmlcssguide.html

- PrimeVue. (s.f.). *PrimeVue: The most complete UI component library for Vue.js*. https://primevue.org

- REST API Tutorial. (s.f.). *What is REST?*. https://www.restapitutorial.com/introduction/whatisrest

- RESTfulAPI.net. (s.f.). *REST API tutorial*. https://restfulapi.net

- Seguas. (2024). *La importancia del frío industrial en la industria alimentaria*. Seguas - Refrigeración Industrial. https://www.seguas.com/importancia-frio-industria-alimentaria/

- W3Schools. (s.f.). *HTML style guide and coding conventions*. https://www.w3schools.com/html/html5_syntax.asp

- Zabarburu. (4 de marzo de 2026). *Guía básica sobre cadena de frío y su continuidad térmica*. Zabarburu Soluciones. https://zabarburu.com.pe/recursos/guias/sobre-cadena-de-frio/

- La Noticia Perú. (29 de septiembre de 2023). *Se malograron 345 mil vacunas y las pérdidas ascienden a S/14 millones.* La Noticia. https://lanoticia.com.pe/se-malograron-345-mil-vacunas-y-las-perdidas-ascienden-a-s-14-millones/

# Anexos

## Recursos y enlaces del proyecto
  
- **URL de la organización del proyecto:** 
  https://github.com/1ASI0730-2520-7452-G1-FrostShield
  <br>
- **URL del repositorio del reporte:** 
  https://github.com/1ASI0730-2520-7452-G1-FrostShield/Report
  <br>
- **URL del repositorio de la Landing Page:** 
  https://github.com/1ASI0730-2520-7452-G1-FrostShield/IceTrack---Landing-Page
  <br>
- **URL del repositorio del Frontend:** 
  https://github.com/1ASI0730-2520-7452-G1-FrostShield/IceTrack-Frontend
  <br>
- **URL del repositorio del Backend:** 
  https://github.com/1ASI0730-2520-7452-G1-FrostShield/IceTrack-Platform
  <br>

- **Enlace del Lucidchart:**
https://lucid.app/lucidchart/817cb83d-3d5c-4aca-9dd8-25223ee29a7f/edit?viewport_loc=-1747%2C-10860%2C36858%2C19690%2C0_0&invitationId=inv_b7e0210c-55d8-452c-a5f7-617ffe06cfaa
