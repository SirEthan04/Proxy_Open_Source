# Carátula

![UPC](Recursos/images/upc.png)

**Universidad Peruana de Ciencias Aplicadas S.A.C.**

**Ingeniería de Software**

**Ciclo: 5**

**1ASI0729-2620**

**Desarrollo de Aplicaciones Open Source**

**NRC: 7760**

**Docente: Juan Antonio Flores Moroco**

---

### **Informe de Trabajo Final**

* **Nombre del Startup:** Proxy
* **Nombre del Producto:** BodeGo

---

### **Relación de Integrantes**

| Código | Apellidos y Nombres |
| :--- | :--- |
| U20241F385 | Blanco Medina, Jhorch Jhoseff |
| U20241G404 | Caldas Bravo, Mateo |
| U20241G610 | Chavez Sandoval, Dany Yohel |
| U202421082 | Saravia Hiso, Johan Alvaro |
| U202316162 | Trejo Espejo, Giordano Sebastian del Ángel |

---

* **Fecha:** 12/09/2026

---

# Registro de Versiones del Informe

* **Project Report Collaboration Insights**

---

# Contenido

## Tabla de Contenidos

* [Capítulo I: Introducción](#capítulo-i-introducción)

  * [1.1. Startup Profile](#11-startup-profile)

    * [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    * [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  * [1.2. Solution Profile](#12-solution-profile)

    * [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    * [1.2.2. Lean UX Process](#122-lean-ux-process)

      * [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      * [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      * [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      * [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  * [1.3. Segmentos objetivo](#13-segmentos-objetivo)

* [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

  * [2.1. Competidores](#21-competidores)

    * [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    * [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  * [2.2. Entrevistas](#22-entrevistas)

    * [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    * [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    * [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  * [2.3. Needfinding](#23-needfinding)

    * [2.3.1. User Personas](#231-user-personas)
    * [2.3.2. User Task Matrix](#232-user-task-matrix)
    * [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    * [2.3.4. Empathy Mapping](#234-empathy-mapping)
  * [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
  * [2.5. Ubiquitous Language](#25-ubiquitous-language)

* [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)

  * [3.1. User Stories](#31-user-stories)
  * [3.2. Impact Mapping](#32-impact-mapping)
  * [3.3. Product Backlog](#33-product-backlog)

* [Capítulo IV: Product Design](#capítulo-iv-product-design)

  * [4.1. Style Guidelines](#41-style-guidelines)

    * [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    * [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  * [4.2. Information Architecture](#42-information-architecture)

    * [4.2.1. Organization Systems](#421-organization-systems)
    * [4.2.2. Labeling Systems](#422-labeling-systems)
    * [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    * [4.2.4. Searching Systems](#424-searching-systems)
    * [4.2.5. Navigation Systems](#425-navigation-systems)
  * [4.3. Landing Page UI Design](#43-landing-page-ui-design)

    * [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    * [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  * [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)

    * [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    * [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    * [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    * [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  * [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  * [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)

    * [4.6.1. Design-Level EventStorming](#461-design-level-eventstorming)
    * [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    * [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    * [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  * [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)

    * [4.7.1. Class Diagrams](#471-class-diagrams)
  * [4.8. Database Design](#48-database-design)

    * [4.8.1. Database Diagrams](#481-database-diagrams)

* [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)

  * [5.1. Software Configuration Management](#51-software-configuration-management)

    * [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    * [5.1.2. Source Code Management](#512-source-code-management)
    * [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    * [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  * [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)

    * [5.2.1. Sprint n](#521-sprint-n)

      * [5.2.1.1. Sprint Planning n](#5211-sprint-planning-n)
      * [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      * [5.2.1.3. Sprint Backlog n](#5213-sprint-backlog-n)
      * [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      * [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      * [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      * [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      * [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

* [Conclusiones](#conclusiones)

  * [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

* [Video About-the-Team](#video-about-the-team)

* [Bibliografía](#bibliografía)

* [Anexos](#anexos)


---

# Student Outcome

| **Criterio específico** | **Acciones realizadas** | **Conclusiones** |
| --- | --- | --- |
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | **Mateo Caldas Bravo** <br><br> AV1: Lideré la organización inicial del equipo mediante la coordinación de reuniones y distribución de actividades. Realicé aportes en la definición de la propuesta de valor de BodeGo, identificación del problema y revisión de los avances realizados durante esta primera etapa. <br><br> TB1: Asumí un rol activo en la coordinación del desarrollo de las funcionalidades relacionadas con productos y lotes, manteniendo comunicación con mis compañeros para identificar dependencias y resolver dificultades durante la implementación. También apoyé la integración de mi trabajo con los demás módulos del Frontend. <br><br> **Johan Alvaro Saravia Hiso** <br><br> AV1: Realicé el análisis inicial del usuario objetivo y colaboré en la recopilación de información sobre las necesidades de los minimarkets. Aporté ideas que permitieron orientar la solución hacia una problemática real identificada. <br><br> TB1: Participé en las decisiones relacionadas con la implementación de los movimientos de inventario, compartiendo avances y observaciones con el equipo. Mantuve una comunicación constante con mis compañeros para facilitar la integración de esta funcionalidad con el resto de la aplicación. <br><br> **Dany Yohel Chavez Sandoval** <br><br> AV1: Aporté conocimientos relacionados con la propuesta tecnológica del proyecto, analizando la estructura inicial de la plataforma y brindando ideas sobre los componentes necesarios para el desarrollo futuro de BodeGo. <br><br> TB1: Contribuí activamente al trabajo en equipo mediante el desarrollo del dashboard de BodeGo y el apoyo en la documentación del proyecto. Además, mantuve una comunicación constante con mis compañeros para coordinar avances y aportar al cumplimiento conjunto de los objetivos. <br><br> **Jhorch Jhoseff Blanco Medina** <br><br> AV1: Colaboré en la revisión de la propuesta inicial del proyecto, brindando observaciones y sugerencias para mejorar la definición de funcionalidades y características principales de la solución. <br><br> TB1: Participé en la coordinación del equipo durante la implementación de las funcionalidades de identidad y acceso, compartiendo avances y apoyando a mis compañeros cuando fue necesario. Mi trabajo permitió avanzar de manera conjunta en la construcción de los módulos del Frontend. <br><br> **Giordano Sebastian del Ángel Trejo Espejo** <br><br> AV1: Realicé la organización y revisión de la documentación inicial del proyecto, ayudando a mantener la información ordenada y alineada con los objetivos definidos por el equipo. <br><br> TB1: Participé en el trabajo colaborativo mediante el desarrollo de las funcionalidades relacionadas con los conteos físicos. Compartí los avances realizados con el equipo y atendí las observaciones recibidas para facilitar la integración de esta funcionalidad con los demás componentes. | **AV1:** Durante la primera entrega, logramos establecer una dinámica de trabajo colaborativa en la que cada integrante asumió responsabilidades de acuerdo con sus habilidades. La comunicación y participación conjunta permitieron definir las bases del proyecto y avanzar hacia una propuesta común. <br><br> **TB1:** Durante el Sprint 2, fortalecimos el liderazgo compartido mediante la coordinación de avances, comunicación constante y apoyo entre los integrantes. La colaboración permitió integrar funcionalidades como productos y lotes, identidad y acceso, movimientos y conteos físicos dentro del Frontend de BodeGo. |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | **Mateo Caldas Bravo** <br><br> AV1: Organicé reuniones de coordinación y participé en la planificación de actividades necesarias para cumplir con los objetivos de la primera entrega. Ayudé a establecer prioridades relacionadas con la definición del problema, propuesta de valor y estructura inicial del proyecto. <br><br> TB1: Organicé las actividades necesarias para completar las funcionalidades de productos y lotes, priorizando las tareas de acuerdo con los objetivos establecidos para el Sprint 2. Realicé seguimiento de mis actividades para cumplir con los avances previstos. <br><br> **Johan Alvaro Saravia Hiso** <br><br> AV1: Colaboré durante las reuniones del equipo aportando ideas obtenidas del análisis del usuario objetivo. Ayudé a organizar la información recopilada y definir los aspectos importantes que debían considerarse en la solución. <br><br> TB1: Planifiqué las actividades relacionadas con los movimientos de inventario y distribuí el trabajo de acuerdo con las tareas definidas para el Sprint 2. Gestioné mis avances de manera ordenada para completar la funcionalidad asignada dentro del periodo establecido. <br><br> **Dany Yohel Chavez Sandoval** <br><br> AV1: Participé en la planificación de las actividades relacionadas con la propuesta tecnológica, aportando ideas sobre la estructura de la plataforma y los elementos necesarios para el desarrollo posterior del producto. <br><br> TB1: Participé en un entorno de trabajo colaborativo apoyando tanto en la implementación del dashboard como en la mejora de la documentación. Organicé mis actividades de acuerdo con las metas del equipo y cumplí con las tareas asignadas dentro del tiempo establecido. <br><br> **Jhorch Jhoseff Blanco Medina** <br><br> AV1: Apoyé en la coordinación del trabajo grupal mediante la revisión de avances y planteamiento de mejoras. Colaboré con mis compañeros para mantener una organización adecuada de las tareas asignadas. <br><br> TB1: Organicé las tareas relacionadas con la implementación de identidad y acceso considerando las prioridades definidas para el Sprint 2. Realicé las actividades asignadas y participé en la revisión de los avances para contribuir al cumplimiento de las metas establecidas. <br><br> **Giordano Sebastian del Ángel Trejo Espejo** <br><br> AV1: Realicé seguimiento de los avances del equipo y colaboré en la revisión de documentos para asegurar que los entregables mantuvieran coherencia con los objetivos establecidos para esta etapa. <br><br> TB1: Planifiqué las actividades necesarias para implementar los conteos físicos de inventario y realicé seguimiento de su avance durante el Sprint 2. Cumplí con las tareas asignadas y coordiné los ajustes necesarios para completar la funcionalidad. | **AV1:** Durante la primera entrega, establecimos una organización de trabajo que permitió distribuir responsabilidades y mantener una comunicación constante. Esto facilitó la planificación de las actividades y el cumplimiento de los objetivos establecidos para la etapa inicial de BodeGo. <br><br> **TB1:** Durante el Sprint 2, logramos organizar las tareas de acuerdo con las funcionalidades asignadas y realizar seguimiento de los avances. La planificación y coordinación del equipo permitieron cumplir con las actividades previstas para la implementación del Frontend Web de BodeGo. |

---

# Capítulo I: Introducción
## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

**Nombre del Startup:** Proxy  

**Nombre del Producto:** BodeGo  

**Enfoque de Negocios:** Aplicación web para la gestión integral de inventario, mermas y control operativo interno en minimarkets.  

**Propuesta de Valor:** BodeGo es una solución web de gestión interna que optimiza el control de stock y reduce las mermas por productos perecibles mediante un sistema de doble rol operativo. La plataforma permite al Administrador visualizar reportes, configurar el sistema y lanzar ofertas estratégicas, mientras que facilita al Empleado la actualización rápida de stock y el registro de las operaciones diarias en el punto de venta.  

**Mercado Objetivo:** El producto está dirigido al personal operativo y directivo de minimarkets, dividiendo a sus usuarios en dos segmentos clave: Administradores (dueños o gestores del negocio) y Empleados (personal de atención y almacén).


### 1.1.2. Perfiles de integrantes del equipo
| **Mateo Caldas Bravo (U20241G404)** |
| :--- |
| Soy un estudiante de 19 años cursando el quinto ciclo de la carrera de Ingeniería de Software. Considero que mi capacidad de tener un enfoque analítico y la eficiencia de desarrollar una solución eficiente. Mis habilidades blandas me permiten empatizar con los usuarios y acompañado de mi resiliencia, compromiso y productividad me permiten realizar propuestas mas estructuradas y optimas. |
| ![Foto Mateo](https://github.com/SirEthan04/Proxy_Open_Source/blob/main/Recursos/images/mateofoto.jpg) |

| **Johan Alvaro Saravia Hiso (U202421082)** |
| :--- |
| Soy un estudiante de 20 años actualmente en el quinto ciclo de la carrera de Ingeniería de Software. Me considero una persona responsable y comprometida con los demás, especialmente al trabajar en equipo. Tengo facilidad para analizar problemas y buscar soluciones prácticas. Además, procuro escuchar y comprender las ideas de mis compañeros para lograr un buen trabajo en conjunto. |
| ![Foto Johan](https://github.com/SirEthan04/Proxy_Open_Source/blob/main/Recursos/images/johanfoto.jpg) |

| **Chavez Sandoval, Dany Yohel (U20241G610)** |
| :--- |
| Soy un estudiante de 20 años actualmente en el quinto ciclo de la carrera de Ingeniería de Software. Me considero una persona responsable y comprometida con los demás, especialmente al trabajar en equipo. Tengo facilidad para analizar problemas y buscar soluciones prácticas. Además, procuro escuchar y comprender las ideas de mis compañeros para lograr un buen trabajo en conjunto. |
| ![Flujo Dany](https://github.com/SirEthan04/Proxy_Open_Source/blob/main/Recursos/images/danyfoto.jpg) |

| **Blanco Medina, Jhorch Jhoseff (U20241F385)** |
| :--- |
| Soy un estudiante de 20 años actualmente en el quinto ciclo de la carrera de Ingeniería de Software. Me considero una persona responsable y comprometida con los demás, especialmente al trabajar en equipo. Tengo facilidad para analizar problemas y buscar soluciones prácticas. Además, procuro escuchar y comprender las ideas de mis compañeros para lograr un buen trabajo en conjunto. |
| ![Foto Jhorch](https://github.com/SirEthan04/Proxy_Open_Source/blob/main/Recursos/images/jhorch%20foto.jpg) |

| **Trejo Espejo, Giordano Sebastian del Ángel (U202316162)** |
| :--- |
| Soy un estudiante de 20 años actualmente en el quinto ciclo de la carrera de Ingeniería de Software. Me considero una persona responsable y comprometida con los demás, especialmente al trabajar en equipo. Tengo facilidad para analizar problemas y buscar soluciones prácticas. Además, procuro escuchar y comprender las ideas de mis compañeros para lograr un buen trabajo en conjunto. |
| ![Foto Gio](https://github.com/SirEthan04/Proxy_Open_Source/blob/main/Recursos/images/giofoto.jpg) |

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática

En el sector del comercio minorista, específicamente en los minimarkets, la gestión operativa se realiza de manera empírica y manual. Esta falta de digitalización genera una baja visibilidad sobre el estado real de los inventarios, impactando directamente en la rentabilidad del negocio debido a la acumulación de mermas y a una deficiente comunicación interna entre el personal.

**Técnica de las 5 'W's y 2 'H's:**

**Who (¿Quién?):** Personal operativo y directivo de los minimarkets, dividido en dos roles clave: Administradores (dueños o gestores) y Empleados (personal de atención y almacén).  

**What (¿Qué?):** Deficiente gestión del inventario perecible que ocasiona mermas por productos vencidos, sumado a la falta de un sistema centralizado de control operativo y actualización de stock en tiempo real.  

**Where (¿Dónde?):** En las instalaciones, almacenes y puntos de venta de los minimarkets de Lima Metropolitana.  

**When (¿Cuándo?):** Ocurre de forma continua durante la operación diaria, intensificándose al momento de la recepción de mercadería, el despacho en caja y la rotación de productos en anaqueles.  

**Why (¿Por qué?):** Debido a la ausencia de herramientas digitales accesibles para el control de stock, la falta de asignación de permisos según el rol operativo y la dependencia de métodos manuales para identificar fechas de vencimiento y registrar operaciones.  

**How (¿Cómo?):** El Administrador gestiona el negocio sin visibilidad centralizada de reportes ni capacidad para lanzar ofertas estratégicas de liquidación. A su vez, el Empleado realiza el control de inventario mediante anotaciones físicas o de memoria, lo que dificulta detectar a tiempo los productos próximos a caducar e impide mantener el stock actualizado durante la jornada.  

**How Much (¿Cuánto?):** Pérdidas económicas constantes para el minimarket por mermas no detectadas a tiempo, descuadres de stock en el punto de venta y una reducción en el margen de ganancia al no poder liquidar estratégicamente la mercadería de baja rotación.

### 1.2.2 Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
Actualmente, los minimarkets presentan dificultades para mantener un control adecuado de su inventario debido al uso de registros manuales o herramientas poco especializadas. Esto ocasiona diferencias en el stock, poca visibilidad sobre los productos disponibles y dificultades para identificar productos próximos a vencer.

Los Administradores necesitan contar con información centralizada que les permita supervisar el inventario, consultar reportes y tomar decisiones frente a posibles mermas. Por otro lado, los Empleados necesitan una forma rápida y sencilla de actualizar el stock y registrar las operaciones realizadas durante la jornada.

BodeGo busca solucionar esta problemática mediante una plataforma web que centralice la gestión del inventario, permita controlar productos perecibles y diferencie las funcionalidades disponibles para Administradores y Empleados.

#### 1.2.2.2. Lean UX Assumptions

##### Business Assumptions

1. Existe una necesidad de mejorar la gestión de inventario en minimarkets que actualmente utilizan procesos manuales.
2. La reducción de mermas por productos vencidos puede generar un beneficio económico para el negocio.
3. Una plataforma web puede facilitar la gestión interna sin requerir herramientas especializadas.
4. La separación de funcionalidades entre Administradores y Empleados puede mejorar el control operativo.

##### User Assumptions

1. Los Administradores necesitan conocer rápidamente el estado general del inventario.
2. Los Administradores necesitan identificar productos próximos a vencer para tomar decisiones oportunas.
3. Los Empleados necesitan actualizar el stock de manera rápida y sencilla.
4. Los Empleados prefieren una interfaz simple para realizar sus tareas operativas.
5. Ambos usuarios necesitan acceder únicamente a las funcionalidades relacionadas con su rol.

##### Business Outcome Assumptions

1. Reducción de productos que vencen sin ser detectados previamente.
2. Mayor frecuencia de actualización del stock.
3. Disminución del uso de registros manuales para controlar el inventario.
4. Mayor visibilidad del estado del inventario para los Administradores.

##### User Outcome and Benefit Assumptions

1. Los Administradores podrán tener mayor control sobre el inventario y las mermas.
2. Los Administradores podrán tomar decisiones utilizando información organizada y actualizada.
3. Los Empleados podrán registrar cambios en el inventario con mayor facilidad.
4. Los Empleados podrán identificar rápidamente productos que requieren atención.
5. Ambos usuarios reducirán su dependencia de registros manuales.

##### Feature Assumptions

1. Un sistema de gestión de inventario permitirá mantener actualizado el stock de productos.
2. Las alertas de vencimiento permitirán identificar productos perecibles antes de que se conviertan en mermas.
3. Un dashboard con reportes permitirá al Administrador conocer rápidamente el estado del inventario.
4. La gestión de ofertas permitirá al Administrador impulsar la salida de productos próximos a vencer.
5. Un sistema de roles permitirá diferenciar las acciones disponibles para Administradores y Empleados.

#### 1.2.2.3. Lean UX Hypothesis Statements

##### Hypothesis Statement 1

Creemos que si implementamos un sistema de gestión de inventario, entonces los Administradores y Empleados podrán mantener el stock actualizado con mayor facilidad, reduciendo las diferencias entre el inventario registrado y el inventario disponible.

##### Hypothesis Statement 2

Creemos que si implementamos alertas para productos próximos a vencer, entonces los Administradores y Empleados podrán identificarlos con anticipación y reducir la cantidad de productos que se convierten en mermas.

##### Hypothesis Statement 3

Creemos que si proporcionamos un dashboard con reportes del inventario, entonces los Administradores podrán conocer rápidamente el estado del negocio y tomar decisiones utilizando información organizada.

##### Hypothesis Statement 4

Creemos que si implementamos una funcionalidad para crear ofertas sobre productos próximos a vencer, entonces los Administradores podrán promover su salida antes de que estos productos se conviertan en pérdidas.

##### Hypothesis Statement 5

Creemos que si implementamos un sistema de roles para Administradores y Empleados, entonces cada usuario podrá acceder únicamente a las funcionalidades correspondientes a sus responsabilidades, mejorando el control de las operaciones.

#### 1.2.2.4. Lean UX Canvas

<table>
<tr>
<td width="33%" valign="top">

### Business Problem

Actualmente, los minimarkets presentan dificultades para mantener un control adecuado de su inventario debido al uso de registros manuales o herramientas poco especializadas.

Esto genera diferencias entre el stock registrado y el stock real, poca visibilidad sobre los productos disponibles y dificultades para identificar productos próximos a vencer.

Como consecuencia, los Administradores tienen dificultades para supervisar el negocio y tomar decisiones oportunas, mientras que los Empleados presentan complicaciones para mantener actualizado el inventario durante las operaciones diarias.

---

### Users

- **Administradores:** dueños o gestores del minimarket encargados de supervisar el inventario, revisar reportes, configurar el sistema y tomar decisiones sobre productos y ofertas.

- **Empleados:** personal de atención y almacén encargado de actualizar el stock, registrar operaciones y controlar los productos durante la jornada.

</td>

<td width="34%" valign="top">

### Solutions

- **Gestión centralizada de inventario**, permitiendo registrar, consultar y actualizar la información de los productos.

- **Control de productos perecibles**, facilitando la identificación de productos próximos a vencer.

- **Alertas de vencimiento** que permitan actuar antes de que los productos se conviertan en mermas.

- **Dashboard y reportes** para que el Administrador pueda visualizar información relevante sobre el inventario.

- **Gestión de ofertas** para productos próximos a vencer o con poca rotación.

- **Sistema de roles y permisos**, diferenciando las funcionalidades disponibles para Administradores y Empleados.

</td>

<td width="33%" valign="top">

### Business Outcomes

- Reducir la cantidad de productos que vencen sin ser identificados previamente.

- Incrementar la frecuencia de actualización del inventario.

- Disminuir la dependencia de registros manuales.

- Mejorar la visibilidad del estado del inventario.

- Facilitar la toma de decisiones relacionadas con stock, mermas y productos próximos a vencer.

---

### User Outcomes & Benefits

- **Administradores:** mayor control y visibilidad del inventario, acceso a información organizada y mejor capacidad para tomar decisiones.

- **Empleados:** mayor facilidad para actualizar el stock, identificar productos que requieren atención y registrar operaciones.

- Reducción del esfuerzo requerido para realizar tareas relacionadas con el control del inventario.

- Mayor claridad sobre las funciones correspondientes a cada usuario.

</td>
</tr>
</table>

<br>

<table>
<tr>
<td width="34%" valign="top">

### Hypothesis

Creemos que si BodeGo proporciona una plataforma web que centralice el control del inventario, permita identificar productos próximos a vencer y diferencie las funciones de Administradores y Empleados, entonces será posible mejorar la gestión operativa del minimarket y reducir las pérdidas relacionadas con productos perecibles.

Consideraremos que esta propuesta genera resultados positivos cuando los usuarios logren mantener el stock actualizado con mayor frecuencia, identificar productos próximos a vencer antes de que se conviertan en mermas y reducir su dependencia de registros manuales.

</td>

<td width="33%" valign="top">

### What's the most important thing we need to learn first?

- ¿Los problemas relacionados con el control del stock ocurren con suficiente frecuencia en los minimarkets?

- ¿La pérdida de productos por vencimiento representa una preocupación importante para los Administradores?

- ¿Los Empleados estarían dispuestos a utilizar una plataforma web para registrar y actualizar el inventario?

- ¿Las alertas de vencimiento aportarían valor durante las operaciones diarias del minimarket?

</td>

<td width="33%" valign="top">

### What's the least amount of work we need to do to learn the next most important thing?

- Realizar entrevistas a Administradores y Empleados de minimarkets para conocer sus procesos actuales.

- Desarrollar un prototipo de baja fidelidad con las principales funciones de BodeGo.

- Realizar pruebas de usuario enfocadas en tareas como actualizar stock, buscar productos e identificar productos próximos a vencer.

- Recopilar comentarios de los usuarios para validar o modificar los supuestos planteados.

</td>
</tr>
</table>

## 1.3. Segmentos objetivo

BodeGo está dirigido al personal involucrado en la gestión y operación de minimarkets de Lima Metropolitana. Para el desarrollo de la solución se consideran dos segmentos principales: los **Administradores**, responsables de supervisar y gestionar el negocio, y los **Empleados**, encargados de las actividades operativas relacionadas con el inventario, almacén y atención.

### Segmento: Administradores de minimarkets

Este segmento está conformado por dueños, administradores o encargados de minimarkets que necesitan mantener control sobre el inventario, las mermas y las operaciones realizadas dentro del establecimiento.

- **Aspectos Demográficos:**
  - Edad: 31 a 60 años.
  - Nivel educativo: Secundaria completa, formación técnica o universitaria.
  - Ocupación: Dueños, administradores o gestores de minimarkets.
  - Nivel tecnológico: Medio, con uso frecuente de smartphones, computadoras y aplicaciones de gestión o comunicación.

- **Aspectos Geográficos:**
  - Ubicación: Lima Metropolitana.
  - Zona geográfica: Distritos urbanos con presencia de minimarkets y comercios minoristas.
  - Acceso: Usuarios con conexión a internet y acceso a dispositivos móviles o computadoras.

- **Aspectos Psicográficos:**
  - Interés por mejorar la organización y rentabilidad de su negocio.
  - Buscan reducir pérdidas ocasionadas por productos vencidos o de baja rotación.
  - Valoran tener mayor control sobre el inventario y las actividades de sus empleados.
  - Interés en herramientas que faciliten la toma de decisiones.
  - Preferencia por soluciones sencillas que no compliquen las operaciones del negocio.

### Segmento: Empleados de minimarkets

Este segmento está compuesto por trabajadores encargados de realizar actividades operativas dentro del minimarket, como la recepción de mercadería, reposición de productos, atención al cliente y actualización del inventario.

- **Aspectos Demográficos:**
  - Edad: 18 a 45 años.
  - Nivel educativo: Secundaria completa, formación técnica o universitaria.
  - Ocupación: Personal de atención, caja, almacén o reposición.
  - Nivel tecnológico: Medio, familiarizados principalmente con smartphones y aplicaciones de uso cotidiano.

- **Aspectos Geográficos:**
  - Ubicación: Lima Metropolitana.
  - Zona geográfica: Minimarkets ubicados principalmente en zonas urbanas y comerciales.
  - Acceso: Personal con acceso a internet y dispositivos disponibles dentro del establecimiento.

- **Aspectos Psicográficos:**
  - Buscan realizar sus actividades de manera rápida y sencilla.
  - Valoran herramientas que reduzcan el trabajo manual y repetitivo.
  - Prefieren interfaces intuitivas y fáciles de aprender.
  - Necesitan acceder rápidamente a información sobre stock y productos.
  - Valoran tener claridad sobre las tareas y responsabilidades asignadas.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

| Competidor | Descripción |
|---|---|
| **Bsale** | Es una plataforma de gestión comercial orientada a pequeñas y medianas empresas. Integra punto de venta, facturación electrónica, control de inventario en tiempo real y reportes. Cada venta o ingreso de mercadería puede actualizar automáticamente el stock, por lo que compite con BodeGo en el control y seguimiento del inventario. |
| **FácilVenta** | Es un software peruano dirigido a negocios como bodegas, minimarkets y tiendas. Integra punto de venta, facturación electrónica SUNAT y gestión de inventario. Para minimarkets incluye funciones como lector de códigos de barras, control de stock mínimo y alertas de productos próximos a vencer, por lo que es uno de los competidores más cercanos a la propuesta de BodeGo. |
| **Adiasoft** | Es un sistema ERP que cuenta con una solución específica para minimarkets, bodegas y retail. Ofrece punto de venta, inventario en tiempo real, códigos de barras, promociones, facturación electrónica, reportes y gestión de múltiples áreas del negocio. Se diferencia por tener un enfoque más amplio y empresarial que BodeGo. |
### 2.1.1. Análisis competitivo
| Competidor | Descripción |
|---|---|
| **Bsale** | Es una plataforma de gestión comercial orientada a pequeñas y medianas empresas. Integra punto de venta, facturación electrónica, control de inventario en tiempo real y reportes. Cada venta o ingreso puede actualizar automáticamente el stock. |
| **FácilVenta** | Es un software peruano dirigido a negocios como bodegas, minimarkets y tiendas. Integra punto de venta, facturación electrónica SUNAT y gestión de inventario. Para minimarkets incluye funciones como lector de códigos de barras, control de stock mínimo y alertas de productos próximos a vencer. |
| **Adiasoft** | Es un sistema ERP que cuenta con una solución específica para minimarkets, bodegas y retail. Ofrece punto de venta, inventario en tiempo real, códigos de barras, promociones, facturación electrónica, reportes y gestión de múltiples áreas del negocio. |
### 2.1.1. Análisis competitivo

| Categoría | Aspecto | **BodeGo** | **Bsale** | **FácilVenta** | **Adiasoft** |
|---|---|---|---|---|---|
| **Perfil** | **Overview** | BodeGo es una aplicación web pensada para ayudar a minimarkets a llevar un mejor control de su inventario. Busca facilitar tareas como registrar productos, controlar lotes, revisar vencimientos, registrar mermas. Además, diferencia las funciones que puede realizar un Administrador y un Empleado. | Bsale es una plataforma que reúne diferentes herramientas para manejar un negocio, como ventas, inventario, facturación electrónica y reportes. Permite que los movimientos realizados en el sistema actualicen el stock del negocio. | FácilVenta es un sistema peruano orientado a pequeños negocios como bodegas y minimarkets. Permite manejar ventas, inventario, facturación electrónica y productos próximos a vencer. | Adiasoft es un sistema de gestión empresarial que cuenta con soluciones para minimarkets y comercios. Permite manejar ventas, inventario, facturación, promociones y otras áreas del negocio. |
| **Perfil** | **Ventaja competitiva ¿Qué valor ofrece a los clientes?** | La principal propuesta de BodeGo es enfocarse en problemas comunes de los minimarkets, como diferencias de stock y productos que vencen sin ser detectados. Busca que el usuario pueda controlar lotes, recibir alertas y tomar acciones antes de que los productos se conviertan en pérdidas. | Su principal ventaja es que reúne varias funciones del negocio en una sola plataforma, permitiendo controlar ventas, inventario y facturación desde un mismo lugar. | Su ventaja es que está bastante orientado a bodegas y minimarkets peruanos. Incluye funciones útiles como control de vencimientos, códigos de barras, stock mínimo y facturación electrónica. | Su ventaja es la cantidad de funciones que ofrece. Puede ser utilizado por negocios que necesitan controlar no solo inventario y ventas, sino también otras áreas de la empresa. |
| **Perfil de Marketing** | **Mercado objetivo** | Dueños, administradores y empleados de minimarkets, especialmente pequeños y medianos negocios que necesitan mejorar el control de sus productos. Inicialmente se busca trabajar con minimarkets de Lima Metropolitana. | Pequeñas y medianas empresas que necesitan controlar ventas, inventario y facturación. | Bodegas, minimarkets, tiendas y pequeños o medianos comercios del Perú. | Minimarkets, tiendas, comercios retail y empresas que necesitan una herramienta de gestión más completa. |
| **Perfil de Marketing** | **Estrategias de marketing** | BodeGo podría promocionarse mediante redes sociales, una landing page, demostraciones del sistema y pruebas con minimarkets. La comunicación estaría enfocada principalmente en mostrar cómo el sistema puede ayudar a reducir pérdidas y facilitar el trabajo diario. | Promociona sus diferentes soluciones mediante su página web, demostraciones, contenido informativo y períodos de prueba para que los negocios conozcan la plataforma. | Utiliza su página web, demostraciones del sistema y contacto directo con los clientes. También destaca que su producto está pensado para negocios peruanos y cumple con requerimientos de SUNAT. | Promociona diferentes versiones de su sistema según el tamaño y tipo de negocio. También ofrece demostraciones y contacto con asesores para explicar las funcionalidades de la plataforma. |
| **Perfil de Producto** | **Productos & Servicios** | Control de productos, categorías, stock, lotes, fechas de vencimiento, mermas, alertas, ofertas, reportes, movimientos de inventario y gestión de usuarios según su rol. | Punto de venta, inventario, facturación electrónica, reportes, códigos de barras, clientes, caja y herramientas para ventas online. | Punto de venta, inventario, facturación electrónica SUNAT, códigos de barras, control de vencimientos, stock mínimo, compras, proveedores y reportes. | Punto de venta, inventario, códigos de barras, lotes, vencimientos, promociones, facturación electrónica, reportes y otros módulos empresariales. |
| **Perfil de Producto** | **Precios & Costos** | Se propone comenzar con un precio aproximado de **S/80 al mes** para un minimarket. La idea sería mantener un precio accesible mientras BodeGo se encuentra en crecimiento. | Sus planes se encuentran aproximadamente desde **S/189 mensuales**, aumentando según las herramientas y características que necesite el negocio. | Cuenta con planes aproximadamente desde **S/140 mensuales**, con opciones de mayor precio que incluyen más características y capacidad. | Cuenta con diferentes planes según las necesidades del negocio, desde opciones básicas hasta planes más completos que pueden superar los **S/300 mensuales**. |
| **Perfil de Producto** | **Canales de distribución (Web y/o Móvil)** | BodeGo funcionará principalmente como una aplicación web responsiva, por lo que podrá utilizarse desde una computadora, tablet o celular mediante un navegador. | Se puede utilizar desde la web y también cuenta con opciones para dispositivos móviles. | Puede ser utilizado desde computadoras y diferentes dispositivos para realizar operaciones del negocio. | Su plataforma puede utilizarse mediante internet desde diferentes dispositivos dependiendo del servicio contratado. |
| **Análisis SWOT** | **Fortalezas** | Está pensado específicamente para los problemas de inventario de los minimarkets. Se enfoca en productos perecibles, vencimientos y mermas. También busca tener una interfaz sencilla y separar claramente las funciones del Administrador y del Empleado. | Es una plataforma conocida y con varias herramientas integradas. Cuenta con inventario, ventas, facturación electrónica y funciones móviles. | Está enfocado directamente en bodegas y minimarkets. Cuenta con control de vencimientos, códigos de barras, stock mínimo y facturación electrónica. | Cuenta con una gran variedad de funciones y puede cubrir diferentes áreas de un negocio desde una sola plataforma. |
| **Análisis SWOT** | **Debilidades** | BodeGo todavía está en desarrollo y no tiene reconocimiento en el mercado. Además, actualmente no busca cubrir funciones como facturación electrónica o un sistema completo de punto de venta. | Al contar con muchas funciones, puede ser más de lo necesario para un minimarket pequeño que solamente busca mejorar su inventario. Además, el costo puede ser elevado para algunos negocios pequeños. | Algunas funciones y capacidades dependen del plan contratado, por lo que un negocio puede necesitar pagar un plan mayor conforme crece. | Al ser un sistema más completo, puede resultar más complejo para un pequeño minimarket que solamente necesita controlar su inventario y operaciones básicas. |
| **Análisis SWOT** | **Oportunidades** | Muchos minimarkets todavía trabajan con cuadernos, Excel o registros poco organizados. Existe la oportunidad de ofrecer una herramienta sencilla y económica que ayude a reducir productos vencidos y errores de stock. | Puede continuar creciendo mediante nuevas integraciones, comercio electrónico y herramientas para empresas que venden por diferentes canales. | Puede seguir captando pequeños negocios que desean pasar de procesos manuales a una solución digital con facturación electrónica. | Puede crecer entre negocios que necesitan manejar varias sucursales o centralizar diferentes áreas dentro de un mismo sistema. |
| **Análisis SWOT** | **Amenazas** | Existen competidores que ya cuentan con experiencia, clientes y funciones similares. Además, algunos minimarkets podrían preferir soluciones que también incluyan facturación electrónica y punto de venta. | Existen soluciones más económicas y especializadas que pueden resultar más atractivas para pequeños negocios. | Tiene que competir con plataformas más conocidas y con otras soluciones locales que pueden ofrecer precios similares. | Los minimarkets pequeños pueden preferir soluciones más sencillas y económicas en lugar de utilizar un ERP con una gran cantidad de módulos. |

### 2.1.2. Estrategias y tácticas frente a competidores
BodeGo busca diferenciarse de Bsale, FácilVenta y Adiasoft siendo una opción más simple y pensada especialmente para minimarkets. La idea es que ayude a llevar un mejor control del stock, detectar productos que están por vencer y evitar pérdidas por mermas.
También se plantea que tenga un precio accesible, alrededor de **S/80 al mes**, y que pueda usarse desde computadora o celular. Además, cada usuario tendría funciones según su rol, para que el sistema sea más fácil de entender y usar.
Como parte de la estrategia, se realizarían pruebas con minimarkets para mostrar de forma clara cómo BodeGo puede ayudar a ahorrar tiempo, reducir errores y tener un mejor control de los productos.

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

### Preguntas para el Segmento 1: Administrador (Dueño / Gestor del Minimarket)

1. ¿Cómo realiza actualmente el control del stock de productos en su minimarket?
2. ¿Qué dificultades tiene para conocer la cantidad real de productos disponibles?
3. ¿Cómo identifica actualmente los productos que están próximos a vencer?
4. ¿Con qué frecuencia tiene pérdidas por productos vencidos o que no se venden a tiempo?
5. ¿Cómo se informa sobre los cambios de stock realizados por sus empleados?
6. ¿Qué información considera importante para controlar mejor el inventario de su negocio?
7. ¿Qué acciones realiza cuando detecta productos próximos a vencer o con poca rotación?
8. ¿Cómo decide cuándo aplicar descuentos o promociones a determinados productos?
9. ¿Con qué frecuencia encuentra diferencias entre el stock registrado y el stock real?
10. ¿Qué funciones le gustaría encontrar en un sistema digital para gestionar su inventario?

### Preguntas para el Segmento 2: Empleado (Personal Operativo / Atención y Almacén)

1. ¿Cómo registra actualmente las entradas y salidas de productos durante su jornada?
2. ¿Qué tan fácil le resulta conocer la cantidad disponible de un producto? 
3. ¿Cómo revisa o identifica los productos que están próximos a vencer?
4. ¿Qué hace cuando encuentra un producto vencido o cercano a su fecha de vencimiento? 
5. ¿En qué momentos del día suelen presentarse más errores en el control del inventario?
6. ¿Cómo comunica al administrador los cambios de stock o problemas con los productos?
7. ¿Qué dificultades tiene al momento de registrar la llegada de nueva mercadería?
8. ¿Con qué frecuencia encuentra diferencias entre el stock registrado y el stock disponible?
9. ¿Qué herramienta o función facilitaría el registro de productos durante su trabajo?
10. ¿Qué actividad relacionada con el inventario le parece más lenta o complicada de realizar?

### 2.2.2. Registro de entrevistas
### Segmento Administradores

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Admin3-Entrevista.png) |
| **Nombres y apellidos:** Lucia <br>**Edad:** 28  <br>**Distrito:** San Martin de Porrez  <br>**Resumen de la entrevista:** Lucía, de 28 años, trabaja como administradora de un minimarket en San Martín de Porres. Ella comenta que el control del inventario se realiza mediante un sistema POS, reportes en Excel y conteos físicos en las góndolas y el almacén. Sin embargo, existen diferencias frecuentes entre el stock registrado en el sistema y la cantidad real de productos, principalmente porque algunos productos dañados o retirados no siempre son registrados correctamente. <br><br>El control de los productos próximos a vencer se realiza de forma manual, revisando las fechas y aplicando el método FEFO, que consiste en colocar adelante los productos que vencen primero. A pesar de esto, suelen tener pequeñas pérdidas semanales por productos vencidos, especialmente yogures, embutidos y pan de molde. Para reducir estas pérdidas, Lucía coloca los productos próximos a vencer en zonas más visibles y aplica descuentos cuando faltan pocos días para su vencimiento. <br><br>Además, la comunicación sobre incidencias del inventario se realiza mediante el sistema, guías de remisión y un grupo de WhatsApp. Lucía considera que sería muy útil contar con una aplicación móvil que permita escanear códigos de barras, revisar el stock, las fechas de vencimiento y los pedidos en camino, además de recibir alertas cuando un producto esté por agotarse o próximo a vencer. <br><br>**URL:** https://drive.google.com/file/d/1-8vfUZq2TVlsaK8B5TCyhvH-dXwfndUl/view?usp=drive_link |

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Admin1-Entrevista.png) |
| **Nombres y apellidos:** Jimmy Ruiz <br>**Edad:** 31 <br>**Distrito:** San Juan de Lurigancho <br><br>**Resumen de la entrevista:**  <br>Jimmy, administrador de un pequeño minimarket, comenta que actualmente controla el inventario de forma mixta: registra diariamente los movimientos en un cuaderno y, al finalizar la semana, pasa la información a una plantilla de Excel. Sin embargo, uno de los principales problemas es que durante las horas de mayor venta no siempre se registran correctamente todos los productos, lo que genera diferencias entre el stock registrado y el stock real. <br><br>El control de los productos próximos a vencer se realiza de manera manual. Los trabajadores revisan los estantes y el almacén mientras reponen o limpian los productos. A pesar de estas revisiones, se presentan pérdidas una o dos veces al mes, principalmente en productos como lácteos y panes que pueden quedar poco visibles al fondo de los estantes. <br><br>Cuando un producto está próximo a vencer o tiene poca rotación, lo colocan cerca de la caja o en zonas más visibles para facilitar su venta. También aplican descuentos o promociones para intentar recuperar la inversión antes de que el producto venza. <br><br>Jimmy menciona que las diferencias de stock ocurren casi todas las semanas, especialmente en golosinas, galletas, cereales y gaseosas, debido a errores de registro o consumo del personal. <br><br>Finalmente, considera importante contar con un sistema digital, principalmente desde el celular, que permita recibir alertas automáticas de bajo stock y vencimientos, generar reportes de los productos más vendidos y conectarse con un lector de códigos de barras para registrar fácilmente productos, pérdidas o roturas. <br><br>**URL:** https://drive.google.com/file/d/1eAsgHwrdiH4P3uMjAwPBXgNagRQ5b_eY/view?usp=drive_link |

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Admin2-Entrevista.png) |
| **Nombres y apellidos:** Silvia Bravo <br>**Edad:** 49  <br>**Distrito:** Independencia <br><br>**Resumen de la entrevista:**  <br>Silvia Bravo, de 49 años, participa en la administración de un minimarket y explica que el control del stock se realiza revisando y contando los productos disponibles. Una de las principales dificultades es que, en ocasiones, la cantidad real no coincide con la cantidad que deberían tener registrada, por lo que deben estar pendientes constantemente del inventario. <br><br>La identificación de productos próximos a vencer se realiza revisando manualmente las fechas de vencimiento. Las pérdidas por vencimiento ocurren con frecuencia, especialmente en productos como yogur, leche y panes, ya que tienen una duración más corta. Para mantenerse comunicados sobre los cambios en el inventario, utilizan principalmente WhatsApp y un registro donde anotan información importante, como las fechas de vencimiento y los productos que ingresan. <br><br>Cuando un producto está próximo a vencer o tiene poca rotación, realizan ofertas, por ejemplo, combinándolo con otro producto que sí tiene mayor salida y reduciendo el precio para facilitar su venta. Los descuentos se aplican principalmente cuando los productos están cerca de vencer. Finalmente, Silvia considera que sería útil contar con un sistema digital que envíe alertas sobre los productos próximos a vencer y que también brinde orientación sobre qué acciones tomar para evitar pérdidas. <br><br>**URL:** https://drive.google.com/file/d/1pg_DvKHgaqZ3YP34jLtGyl6jV7oni1yI/view?usp=drive_link |

### Segmento Empleados

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Empleado3-Entrevista.png) |
| **Nombres y apellidos:** Joseph <br>**Edad:** 23 <br>**Distrito:** Puente Piedra <br><br>**Resumen:**  <br>Joseph trabaja en un minimarket realizando tareas de atención al cliente, registro de ventas, reposición de productos y control de almacén. Actualmente, las entradas y salidas de productos se registran manualmente en un cuaderno, lo que puede generar errores o confusiones, especialmente en las horas de mayor movimiento o cuando llega mercadería mientras se atiende a los clientes. <br><br>Para conocer el stock disponible, deben revisar y contar físicamente los productos en los estantes, lo cual puede resultar lento y complicado. La revisión de fechas de vencimiento también se realiza manualmente, generalmente cuando llega nueva mercadería. Si encuentran un producto vencido, lo retiran del estante y se lo comunican al administrador para evitar que llegue al cliente. <br><br>Joseph menciona que los errores en el inventario suelen ocurrir principalmente durante las horas de mayor venta, cuando hay más presión de trabajo. Los cambios de stock o problemas con los productos se comunican de forma verbal y mediante el cuaderno de registro. Además, considera que las tareas más tediosas son contar los productos y revisar uno por uno las fechas de vencimiento. <br><br>Finalmente, señala que sería útil contar con una herramienta digital sencilla que permita registrar entradas y salidas, consultar el stock disponible y facilitar el control del inventario, reduciendo así el tiempo y los errores del proceso manual. <br><br>**URL:** https://drive.google.com/file/d/1TD5vcQrjeOiQnoPlT7bziEpWkTBYGCBs/view?usp=drive_link |

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Empleado2-Entrevista.png) |
| **Nombres y apellidos:** Andres Marzano <br>**Edad:** 20  <br>**Distrito:** San Juan de Lurigancho <br><br>**Resumen:**  <br>Andrés Marzano, de 20 años, tiene experiencia trabajando en atención al cliente y almacén. Explica que las entradas de productos se registraban después de verificar que la mercadería recibida coincidiera con la información del documento de entrega, para luego ingresarla en el sistema. Las salidas, por su parte, se registraban mediante boletas electrónicas. <br><br>Uno de los principales problemas era conocer con precisión la cantidad disponible de productos, especialmente cuando se trataba de artículos pequeños, ya que podían cometerse errores al contarlos. Esta tarea se volvía más complicada cuando, al mismo tiempo, tenían que atender a los clientes. <br><br>Para controlar los productos próximos a vencer, colocaban adelante los que tenían menor tiempo de vida útil y dejaban al fondo los productos recién llegados. Además, revisaban las fechas de vencimiento en los turnos de día y noche. Cuando un producto estaba cerca de vencer, trataban de darle prioridad a su venta; si ya quedaban pocos días y no se lograba vender, se registraba como merma para calcular las pérdidas. <br><br>Finalmente, Andrés señala que los mayores errores en el control del inventario se presentaban principalmente durante las mañanas, cuando había mayor cantidad de clientes y debían dividir su atención entre las ventas y las tareas de inventario. <br><br>**URL:** https://drive.google.com/file/d/1BCO2lHzXeeZyN7DED3hQVZv_ULh0Zdx2/view?usp=drive_link |

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Empleado1-Entrevista.png) |
| **Nombres y apellidos:** Pablo Moreno <br>**Edad:** 20  <br>**Distrito:** Callao <br><br>**Resumen:**  <br>Pablo Moreno, empleado de un minimarket, explica que las entradas y salidas de productos se registran principalmente de forma manual y, en algunos casos, mediante Excel. Este proceso no siempre se actualiza de inmediato, por lo que a veces existen diferencias entre el stock registrado y la cantidad real disponible, especialmente en productos de alta rotación o durante las horas de mayor atención. La revisión de productos próximos a vencer también se realiza manualmente, verificando las fechas directamente en los productos. Cuando un producto está vencido se retira de la venta, mientras que los productos próximos a vencer pueden colocarse en zonas más visibles o venderse con descuento. Pablo también menciona que los errores suelen ocurrir cuando hay muchos clientes o cuando llega bastante mercadería al mismo tiempo. Los problemas de stock se comunican personalmente o por WhatsApp, aunque la información puede perderse entre tantos mensajes. Finalmente, considera que sería útil contar con un sistema digital accesible desde el celular o computadora que permita registrar entradas y salidas, actualizar el stock rápidamente y recibir alertas sobre productos próximos a vencer. <br><br>**URL:** https://drive.google.com/file/d/1_V2W7VMWYRneIBc2ZAb0kEKlw-TLDnwO/view?usp=drive_link |



### 2.2.3. Análisis de entrevistas

## Análisis para el segmento de Administradores
A partir de las entrevistas realizadas a Lucía, Jimmy y Silvia, se pudo ver que los tres tienen problemas parecidos al momento de manejar el inventario de sus minimarkets.
Uno de los problemas que más se repite es la **diferencia entre el stock registrado y el stock real**, ya que el **100 % de los entrevistados** mencionó que en algún momento las cantidades no coinciden. Esto puede pasar por errores al registrar productos, pérdidas, productos dañados o movimientos que no se anotan correctamente.
También se encontró que el **100 % controla las fechas de vencimiento de forma manual**, revisando los productos directamente en los estantes o en el almacén. Esto hace que algunos productos puedan pasar desapercibidos y terminar venciendo, sobre todo los lácteos, yogures, leche y panes.
Por otro lado, los tres entrevistados comentaron que tienen pérdidas por productos vencidos. Para tratar de evitarlo, suelen hacer descuentos, promociones u ofertas. Además, el **66,7 % mencionó que coloca estos productos en lugares más visibles**, como cerca de la caja, para que se vendan más rápido.
En cuanto a las herramientas que utilizan, se puede ver que combinan métodos como Excel, sistemas POS, registros manuales y WhatsApp. Sin embargo, todavía sienten que la información no siempre está actualizada o reunida en un solo lugar.
Respecto a una posible solución, el **100 % considera útil recibir alertas de productos próximos a vencer**. Además, el **66,7 % mostró interés en funciones como alertas de bajo stock, uso desde el celular y registro de productos mediante códigos de barras**.

## Análisis para el segmento de Empleados
A partir de las entrevistas realizadas a Joseph, Andrés y Pablo, se pudo identificar que los tres tienen dificultades con tareas relacionadas con el inventario y el almacén del minimarket.
Uno de los principales problemas es el **registro y control del stock**. El **66,7 % de los entrevistados** mencionó que las entradas y salidas se registran principalmente de forma manual, utilizando cuadernos o Excel. Aunque Andrés trabajaba con un sistema digital, también señaló que podían existir errores al momento de contar los productos.
Otro aspecto que se repite es que los errores suelen aparecer cuando existe mayor carga de trabajo. El **100 % mencionó que los problemas de inventario aumentan durante las horas con mayor cantidad de clientes o cuando llega mercadería**.
La revisión de las **fechas de vencimiento también se realiza manualmente en el 100 % de los casos**. Los trabajadores revisan directamente cada producto y, cuando detectan uno próximo a vencer, tratan de darle mayor prioridad en la venta.
En cuanto a la comunicación, los problemas relacionados con el stock suelen informarse de forma verbal, mediante registros escritos o por WhatsApp. Sin embargo, este proceso puede generar confusiones.
Respecto a una posible solución, el **66,7 % mencionó directamente que sería útil contar con una herramienta digital de gestión**. Entre las funciones más importantes se encuentran el **registro de entradas y salidas, consulta rápida del stock y alertas de productos próximos a vencer**.

## 2.3. Needfinding
### 2.3.1. User Personas

---
Administrador

![User Persona Administrador](Recursos/images/UserPersona-Administrador.jpg)

---
Empleado

![User Persona Empleado](Recursos/images/UserPersona-Empleado.jpg)

### 2.3.2. User Task Matrix
---
 Administradores

| Tareas identificadas | Frecuencia | Importancia | Evidencia / Justificación |
|---|---|---|---|
| Revisar el estado general del inventario | Alta | Alta | El administrador necesita conocer el stock disponible y detectar diferencias entre el inventario registrado y el real. |
| Supervisar productos próximos a vencer | Alta | Alta | Los productos perecibles pueden generar pérdidas si no se identifican y gestionan antes de su vencimiento. |
| Revisar alertas de stock y vencimientos | Alta | Alta | Permite detectar rápidamente productos con stock crítico, bajo nivel de existencias o próximos a caducar. |
| Consultar reportes e indicadores | Media | Alta | Los reportes ayudan a conocer mermas, movimientos y comportamiento del inventario para tomar mejores decisiones. |
| Aplicar promociones u ofertas | Media | Alta | Las ofertas permiten liquidar productos próximos a vencer o con baja rotación antes de que se conviertan en merma. |
| Revisar las operaciones realizadas por empleados | Alta | Media | El administrador necesita mantener control sobre ingresos, salidas y mermas registradas durante la jornada. |
| Gestionar productos y datos del inventario | Media | Alta | Es necesario registrar, editar y mantener actualizada la información de los productos disponibles. |
| Gestionar empleados y permisos | Baja | Media | El administrador debe controlar qué empleados tienen acceso al sistema y las acciones que pueden realizar según su rol. |
| Configurar parámetros de stock y vencimiento | Baja | Media | Permite adaptar las alertas y reglas de inventario a las necesidades particulares del minimarket. |
| Identificar productos con mayor cantidad de mermas | Media | Alta | Conocer qué productos generan más pérdidas facilita tomar decisiones sobre compras, rotación y promociones. |
---
 Empleados

| Tareas identificadas | Frecuencia | Importancia | Evidencia / Justificación |
|---|---|---|---|
| Registrar el ingreso de mercadería | Alta | Alta | La recepción de productos ocurre regularmente y debe registrarse para mantener actualizado el inventario. |
| Registrar salidas de productos | Alta | Alta | Las salidas modifican constantemente las cantidades disponibles y deben reflejarse correctamente en el stock. |
| Consultar el stock disponible | Alta | Alta | El empleado necesita conocer rápidamente cuántas unidades quedan sin realizar revisiones manuales del almacén. |
| Registrar productos dañados, vencidos o perdidos como merma | Media | Alta | Registrar las mermas permite mantener el stock real y conocer las pérdidas generadas durante la operación. |
| Revisar productos próximos a vencer | Alta | Alta | Permite detectar productos perecibles antes de que caduquen y comunicar la situación al administrador. |
| Consultar información de un producto | Alta | Media | Durante la jornada puede necesitar verificar cantidades, categoría, estado o información relacionada con un producto. |
| Actualizar el stock después de una operación | Alta | Alta | Mantener las cantidades actualizadas evita diferencias entre el inventario físico y el registrado en el sistema. |
| Revisar sus operaciones realizadas durante el día | Media | Media | El historial permite verificar que los ingresos, salidas y mermas hayan sido registrados correctamente. |
| Comunicar incidencias de inventario | Media | Alta | El empleado debe informar situaciones como stock crítico, productos dañados o inconsistencias encontradas durante su jornada. |
| Buscar productos dentro del inventario | Alta | Media | Una búsqueda rápida reduce el tiempo necesario para localizar información entre una gran cantidad de productos. |

### 2.3.3. User Journey Mapping

## Administrador

|  | Etapa 1 | Etapa 2 | Etapa 3 | Etapa 4 | Etapa 5 |
|---|---|---|---|---|---|
| **Title** | Supervisión inicial del negocio | Revisión del inventario | Detección de problemas | Toma de decisiones | Seguimiento de resultados |
| **User Goals** | Conocer el estado general del minimarket | Verificar stock y productos disponibles | Detectar stock crítico, mermas o vencimientos | Reducir pérdidas y mejorar la rotación | Comprobar si las acciones tomadas funcionaron |
| **Process** | Revisa ventas, stock y operaciones del día | Consulta cantidades y revisa productos | Identifica productos próximos a vencer o con poco stock | Aplica promociones, repone productos o toma acciones | Revisa reportes, movimientos y resultados |
| **Problems** | Información dispersa o poco actualizada | Diferencias entre stock registrado y real | Detección tardía de productos próximos a vencer | Falta de información para tomar decisiones rápidas | Dificultad para medir mermas y resultados |
| **Experience** | Expectativa | Atención | Preocupación | Decisión | Tranquilidad / Incertidumbre |
| **Ideas / Opportunities** | Dashboard con información resumida | Inventario actualizado y filtros | Alertas automáticas de stock y vencimiento | Recomendaciones y lanzamiento de ofertas | Reportes claros sobre inventario y mermas |

---

## Empleado

|  | Etapa 1 | Etapa 2 | Etapa 3 | Etapa 4 | Etapa 5 |
|---|---|---|---|---|---|
| **Title** | Inicio de la jornada | Recepción de mercadería | Actualización del inventario | Gestión de incidencias | Revisión de operaciones |
| **User Goals** | Conocer las tareas y estado del inventario | Registrar correctamente los productos recibidos | Mantener actualizado el stock durante el día | Registrar mermas y detectar productos próximos a vencer | Confirmar que sus operaciones fueron registradas correctamente |
| **Process** | Revisa productos, stock y pendientes | Recibe productos y verifica cantidades | Registra ingresos, salidas y consulta existencias | Informa o registra productos dañados, vencidos o faltantes | Consulta el historial de operaciones realizadas |
| **Problems** | Falta de información actualizada | Errores al registrar cantidades o lotes | Olvidar actualizar movimientos durante momentos de alta demanda | Dificultad para identificar vencimientos o comunicar incidencias | No saber si una operación fue registrada correctamente |
| **Experience** | Atención | Concentración | Presión | Preocupación | Alivio |
| **Ideas / Opportunities** | Dashboard simple con acciones rápidas | Registro sencillo de ingresos y lotes | Actualización rápida y automática del stock | Alertas y registro simplificado de mermas | Historial de operaciones fácil de consultar |

---

### 2.3.4. Empathy Mapping

## Administrador

![Empathy Map Administrador](Recursos/images/EmphathyMapping-Administrador.jpg)

## Empleado

![Empathy Map Empleado](Recursos/images/EmphathyMapping-Empleado.jpg)

## 2.4. Big Picture EventStorming

Nuestro equipo se enfocó en el dominio del negocio de los minimarkets, identificando los Domain Events más significativos a lo largo de la línea de tiempo operativo, desde que la mercadería ingresa al local hasta que es vendida o registrada como merma.
A continuación se identificaron los siguientes flujos principales a través de Domain Events.

![Big Picture EventStorming](Recursos/images/Bigpicture-eventstorming.png)

## 2.5. Ubiquitous Language

Para asegurar que entre los miembros del equipo y los stakeholders se comuniquen sin ambigüedades, se definieron los términos específicos correspondientes al Business Domain de BodeGo. Todos los términos tienen su nomenclatura en inglés.

- **Product:** Artículo físico que se comercializa en el minimarket. Contiene información general como nombre, código de barras y categoría.
- **Batch:** Conjunto de unidades de un mismo producto que ingresan al inventario en la misma fecha, también comparten la misma fecha de vencimiento.
- **Stock / Inventory:** Cantidad física actual disponible de un producto o lote específico dentro del minimarket.
- **Wastage:** Unidades de un producto que son retiradas del inventario, pudiendo ser por daño físico, vencimiento o robo.
- **Expiration Date:** Día límite establecido por el fabricante para el consumo seguro de un lote.
- **Threshold:** Límite preestablecido por el administrador que al ser sobrepasado, activa una alerta, como por ejemplo Stock mínimo o Días previos al vencimiento.
- **Inventory Movement:** Registro de auditoría que registra cualquier actualización en el Stock (Entrada, Salida, Ajuste o Merma).
- **Offer:** Descuento de precio aplicado a un lote específico que se encuentre próximo a su fecha de vencimiento para acelerar su rotación.
- **Role:** Conjunto de permisos asignados a un usuario, que puede ser Admin o Employee, que define a qué módulos y acciones tiene acceso dentro de BodeGo.

# Capítulo III: Requirements Specification

## 3.1. User Stories

## Épicas

| **EPIC-01** | **Presencia Digital y Landing Page** |
|-------------|---------------------------------------|
| **Descripción:** | **Como** visitante interesado en mejorar la gestión de un minimarket, **quiero** conocer la propuesta de valor, beneficios y funcionalidades de BodeGo mediante una Landing Page informativa **para** comprender cómo la plataforma puede ayudar a organizar el inventario y reducir pérdidas operativas. |

<br>

| **EPIC-02** | **Experiencia Frontend Web** |
|-------------|-------------------------------|
| **Descripción:** | **Como** administrador o empleado, **quiero** utilizar una aplicación web organizada con acceso a las principales funcionalidades de BodeGo **para** consultar información, navegar entre módulos y realizar mis actividades de manera sencilla y eficiente. |

<br>

| **EPIC-03** | **Catálogo e Inventario** |
|-------------|----------------------------|
| **Descripción:** | **Como** administrador o empleado autorizado, **quiero** gestionar categorías, productos, cantidades, lotes y fechas de vencimiento **para** mantener organizada y actualizada la información del inventario del minimarket. |

<br>

| **EPIC-04** | **Movimientos de Inventario** |
|-------------|--------------------------------|
| **Descripción:** | **Como** administrador o empleado, **quiero** registrar y consultar entradas, salidas, ajustes y mermas del inventario **para** mantener la trazabilidad de las operaciones y controlar los cambios realizados sobre las existencias. |

<br>

| **EPIC-05** | **Conteos Físicos de Inventario** |
|-------------|------------------------------------|
| **Descripción:** | **Como** administrador o empleado autorizado, **quiero** registrar conteos físicos y comparar las cantidades encontradas con las registradas en el sistema **para** identificar diferencias y mejorar la precisión del inventario. |

<br>

| **EPIC-06** | **Monitoreo y Alertas** |
|-------------|--------------------------|
| **Descripción:** | **Como** administrador, **quiero** consultar y gestionar alertas relacionadas con situaciones importantes del inventario, como stock bajo o productos vencidos, **para** detectar oportunamente condiciones que requieren atención. |

<br>

| **EPIC-07** | **Reportes y Dashboard** |
|-------------|---------------------------|
| **Descripción:** | **Como** administrador, **quiero** consultar indicadores y reportes relacionados con productos, inventario, movimientos y mermas **para** analizar el estado operativo del negocio y apoyar la toma de decisiones. |

<br>

| **EPIC-08** | **Gestión de Usuarios, Autenticación y Seguridad** |
|-------------|----------------------------------------------------|
| **Descripción:** | **Como** administrador o usuario registrado, **quiero** contar con mecanismos de gestión de usuarios, roles, autenticación, contraseñas y sesiones **para** proteger el acceso a la información y garantizar que cada usuario utilice únicamente las funcionalidades autorizadas. |

---

## User Stories

| **Epic / Story ID** | **Título** | **Descripción** | **Criterios de Aceptación** | **Relacionado con (Epic ID)** |
|---|---|---|---|---|
| US01 | Visualización de la Propuesta de Valor | **Como** visitante, **quiero** conocer la propuesta principal de BodeGo, **para** comprender cómo puede ayudar a mejorar la gestión de un minimarket. | **Scenario:** Consultar propuesta de valor<br><br>**Given** el visitante accede a la Landing Page.<br>**When** consulta la información principal de BodeGo.<br>**Then** obtiene información sobre el propósito y valor de la solución.<br><br>**Scenario:** Consultar información del producto<br><br>**Given** la información de BodeGo se encuentra disponible.<br>**When** el visitante consulta el contenido principal.<br>**Then** puede identificar el problema que busca solucionar la plataforma. | EPIC-01 |
| US02 | Consulta de Beneficios de BodeGo | **Como** visitante, **quiero** conocer los beneficios principales de BodeGo, **para** evaluar el valor que puede aportar a la gestión de mi negocio. | **Scenario:** Consultar beneficios<br><br>**Given** el visitante desea conocer las ventajas de BodeGo.<br>**When** consulta los beneficios del producto.<br>**Then** obtiene información relacionada con control de inventario, reducción de pérdidas y organización operativa.<br><br>**Scenario:** Comprender beneficios<br><br>**Given** existen beneficios publicados.<br>**When** el visitante los consulta.<br>**Then** puede identificar el valor proporcionado por la solución. | EPIC-01 |
| US03 | Presentación de Funcionalidades Principales | **Como** visitante, **quiero** conocer las funcionalidades principales de BodeGo, **para** comprender el alcance de la solución antes de utilizarla. | **Scenario:** Consultar funcionalidades<br><br>**Given** el visitante desea conocer las capacidades de BodeGo.<br>**When** consulta las funcionalidades disponibles.<br>**Then** obtiene información relacionada con inventario, operaciones, alertas y reportes.<br><br>**Scenario:** Comprender alcance funcional<br><br>**Given** las funcionalidades están disponibles para consulta.<br>**When** el visitante las revisa.<br>**Then** puede identificar las principales tareas soportadas por BodeGo. | EPIC-01 |
| US04 | Explicación del Funcionamiento de BodeGo | **Como** visitante, **quiero** conocer cómo funciona BodeGo, **para** entender cómo se utiliza durante la operación de un minimarket. | **Scenario:** Consultar funcionamiento<br><br>**Given** el visitante desea entender el uso de BodeGo.<br>**When** consulta la explicación de funcionamiento.<br>**Then** obtiene los pasos generales de utilización de la plataforma.<br><br>**Scenario:** Diferenciar responsabilidades<br><br>**Given** existen diferentes tipos de usuario.<br>**When** el visitante consulta el funcionamiento.<br>**Then** puede distinguir las responsabilidades generales del Administrador y del Empleado. | EPIC-01 |
| US05 | Formulario de Contacto Comercial | **Como** visitante interesado, **quiero** enviar mis datos de contacto, **para** solicitar información adicional sobre BodeGo. | **Scenario:** Registrar solicitud válida<br><br>**Given** el visitante proporciona la información obligatoria válida.<br>**When** envía una solicitud de contacto.<br>**Then** la solicitud queda registrada correctamente.<br><br>**Scenario:** Rechazar información incompleta<br><br>**Given** faltan datos obligatorios.<br>**When** se intenta registrar la solicitud.<br>**Then** el sistema rechaza el registro incompleto. | EPIC-01 |
| US06 | Visualización del Dashboard Administrativo | **Como** Administrador, **quiero** consultar indicadores generales y movimientos recientes del negocio, **para** identificar rápidamente el estado operativo y las situaciones que requieren atención. | **Scenario:** Consultar indicadores del negocio<br><br>**Given** existen productos, lotes y registros operativos disponibles.<br>**When** el Administrador consulta el resumen del negocio.<br>**Then** obtiene indicadores de productos activos, lotes, stock bajo, vencimientos próximos y alertas pendientes.<br><br>**Scenario:** Consultar movimientos recientes<br><br>**Given** existen movimientos de inventario registrados.<br>**When** el Administrador consulta el resumen operativo.<br>**Then** obtiene los movimientos recientes asociados al negocio. | EPIC-02 |
| US07 | Navegación entre Módulos del Sistema | **Como** usuario de BodeGo, **quiero** acceder a los diferentes módulos disponibles, **para** realizar mis actividades de manera organizada. | **Scenario:** Acceder a módulo autorizado<br><br>**Given** el usuario posee acceso a la aplicación.<br>**When** solicita acceder a una funcionalidad disponible.<br>**Then** el sistema permite el acceso al módulo correspondiente.<br><br>**Scenario:** Mantener sesión durante navegación<br><br>**Given** el usuario mantiene una sesión válida.<br>**When** accede a diferentes módulos.<br>**Then** puede continuar utilizando las funcionalidades autorizadas. | EPIC-02 |
| US08 | Visualización del Inventario | **Como** Administrador o Empleado, **quiero** consultar los productos registrados, **para** conocer el estado general del inventario. | **Scenario:** Consultar inventario existente<br><br>**Given** existen productos registrados.<br>**When** el usuario consulta el inventario.<br>**Then** obtiene la información disponible de los productos.<br><br>**Scenario:** Consultar inventario vacío<br><br>**Given** no existen productos registrados.<br>**When** el usuario consulta el inventario.<br>**Then** el sistema devuelve una colección vacía. | EPIC-02 |
| US09 | Consulta de Información de Productos y Lotes | **Como** Administrador o Empleado, **quiero** consultar la información asociada a productos y lotes, **para** conocer sus datos operativos. | **Scenario:** Consultar información existente<br><br>**Given** existe información asociada a un producto o lote.<br>**When** el usuario realiza la consulta.<br>**Then** obtiene los datos registrados correspondientes.<br><br>**Scenario:** Consultar recurso inexistente<br><br>**Given** el producto o lote solicitado no existe.<br>**When** se realiza la consulta.<br>**Then** el sistema informa que el recurso no está disponible. | EPIC-02 |
| US10 | Visualización de Operaciones | **Como** Empleado, **quiero** consultar las operaciones registradas, **para** revisar la actividad realizada sobre el inventario. | **Scenario:** Consultar operaciones existentes<br><br>**Given** existen operaciones registradas.<br>**When** el Empleado consulta las operaciones.<br>**Then** obtiene información sobre tipo, producto, cantidad y fecha.<br><br>**Scenario:** Consultar operaciones inexistentes<br><br>**Given** no existen operaciones registradas.<br>**When** se realiza la consulta.<br>**Then** el sistema devuelve una colección vacía. | EPIC-02 |
| US11 | Búsqueda y Filtrado de Productos | **Como** Administrador o Empleado, **quiero** buscar productos mediante criterios disponibles, **para** encontrar rápidamente la información que necesito. | **Scenario:** Buscar productos coincidentes<br><br>**Given** existen productos que cumplen el criterio indicado.<br>**When** el usuario realiza una búsqueda.<br>**Then** obtiene únicamente los productos coincidentes.<br><br>**Scenario:** Buscar sin coincidencias<br><br>**Given** ningún producto cumple el criterio indicado.<br>**When** el usuario realiza la búsqueda.<br>**Then** el sistema devuelve una colección vacía. | EPIC-02 |
| US12 | Visualización de Alertas | **Como** Administrador, **quiero** consultar alertas relacionadas con el inventario, **para** conocer situaciones que requieren atención. | **Scenario:** Consultar alertas existentes<br><br>**Given** existen alertas registradas.<br>**When** el Administrador consulta las alertas.<br>**Then** obtiene su información y estado correspondiente.<br><br>**Scenario:** Consultar sin alertas<br><br>**Given** no existen alertas registradas.<br>**When** el Administrador realiza la consulta.<br>**Then** el sistema devuelve una colección vacía. | EPIC-02 |
| US13 | Visualización de Reportes | **Como** Administrador, **quiero** consultar diferentes reportes, **para** analizar información relacionada con el inventario y las operaciones. | **Scenario:** Consultar tipo de reporte<br><br>**Given** existen datos operativos disponibles.<br>**When** el Administrador solicita un tipo de reporte.<br>**Then** obtiene la información correspondiente al reporte solicitado.<br><br>**Scenario:** Cambiar tipo de reporte<br><br>**Given** existen diferentes reportes disponibles.<br>**When** el Administrador solicita otro tipo de reporte.<br>**Then** obtiene la información correspondiente al nuevo criterio. | EPIC-02 |
| US14 | Gestión Visual de Productos | **Como** Administrador, **quiero** disponer de las acciones necesarias para gestionar productos, **para** mantener organizado el catálogo. | **Scenario:** Consultar acciones autorizadas<br><br>**Given** existe un producto registrado.<br>**When** el Administrador solicita gestionar su información.<br>**Then** dispone de las operaciones autorizadas sobre el producto.<br><br>**Scenario:** Restringir acción no autorizada<br><br>**Given** un usuario no posee autorización administrativa.<br>**When** intenta realizar una operación restringida.<br>**Then** el sistema rechaza la operación. | EPIC-02 |
| US15 | Gestión Visual de Negocios | **Como** Administrador, **quiero** registrar y consultar los negocios administrados en BodeGo, **para** mantener organizada la información de los establecimientos. | **Scenario:** Registrar negocio válido<br><br>**Given** el Administrador proporciona los datos obligatorios de un negocio.<br>**When** solicita registrar el establecimiento.<br>**Then** el negocio queda disponible en el listado correspondiente.<br><br>**Scenario:** Consultar negocios registrados<br><br>**Given** existen negocios registrados en la plataforma.<br>**When** el Administrador consulta la información de negocios.<br>**Then** obtiene los establecimientos y sus datos disponibles. | EPIC-02 |
| US16 | Registro de Productos | **Como** Administrador, **quiero** registrar nuevos productos, **para** mantener actualizado el catálogo del negocio. | **Scenario:** Registrar producto válido<br><br>**Given** se proporcionan los datos obligatorios válidos.<br>**When** el Administrador registra el producto.<br>**Then** el producto queda disponible en el catálogo.<br><br>**Scenario:** Rechazar datos inválidos<br><br>**Given** existen datos obligatorios inválidos o incompletos.<br>**When** se intenta registrar el producto.<br>**Then** el sistema rechaza el registro. | EPIC-03 |
| US17 | Actualización de Productos | **Como** Administrador, **quiero** modificar la información de un producto, **para** mantener sus datos actualizados. | **Scenario:** Actualizar producto existente<br><br>**Given** existe el producto solicitado.<br>**When** el Administrador registra cambios válidos.<br>**Then** la información del producto queda actualizada.<br><br>**Scenario:** Actualizar producto inexistente<br><br>**Given** el producto solicitado no existe.<br>**When** se intenta modificarlo.<br>**Then** el sistema rechaza la operación. | EPIC-03 |
| US18 | Desactivación de Productos | **Como** Administrador, **quiero** desactivar productos que ya no se comercializan, **para** mantener vigente el catálogo sin perder su historial. | **Scenario:** Desactivar producto activo<br><br>**Given** existe un producto activo.<br>**When** el Administrador solicita desactivarlo.<br>**Then** el producto cambia a estado inactivo.<br><br>**Scenario:** Conservar historial del producto<br><br>**Given** el producto posee operaciones registradas.<br>**When** se desactiva.<br>**Then** sus registros históricos permanecen disponibles. | EPIC-03 |
| US19 | Clasificación de Productos por Categoría | **Como** Administrador, **quiero** asociar categorías a los productos, **para** organizar el catálogo y facilitar su clasificación. | **Scenario:** Asociar categoría existente<br><br>**Given** existen el producto y la categoría seleccionada.<br>**When** el Administrador realiza la asociación.<br>**Then** el producto queda relacionado con la categoría.<br><br>**Scenario:** Asociar categoría inexistente<br><br>**Given** la categoría seleccionada no existe.<br>**When** se intenta realizar la asociación.<br>**Then** el sistema rechaza la operación. | EPIC-03 |
| US20 | Registro de Lotes | **Como** Administrador o Empleado autorizado, **quiero** registrar lotes de productos, **para** controlar cantidades y fechas de vencimiento. | **Scenario:** Registrar lote válido<br><br>**Given** existe el producto asociado y los datos del lote son válidos.<br>**When** se registra el lote.<br>**Then** queda asociado correctamente al producto.<br><br>**Scenario:** Registrar lote con producto inexistente<br><br>**Given** el producto asociado no existe.<br>**When** se intenta registrar el lote.<br>**Then** el sistema rechaza la operación. | EPIC-03 |
| US21 | Consulta de Lotes y Vencimientos | **Como** usuario autorizado, **quiero** consultar los lotes de un producto, **para** conocer sus cantidades y fechas de vencimiento. | **Scenario:** Consultar lotes existentes<br><br>**Given** el producto posee lotes registrados.<br>**When** el usuario consulta sus lotes.<br>**Then** obtiene las cantidades y fechas correspondientes.<br><br>**Scenario:** Producto sin lotes<br><br>**Given** el producto no posee lotes registrados.<br>**When** se realiza la consulta.<br>**Then** el sistema devuelve una colección vacía. | EPIC-03 |
| US22 | Consulta de Disponibilidad de Inventario | **Como** Administrador o Empleado, **quiero** conocer la cantidad disponible de los productos, **para** tomar decisiones antes de realizar operaciones. | **Scenario:** Consultar disponibilidad<br><br>**Given** existe información del producto en inventario.<br>**When** el usuario consulta su disponibilidad.<br>**Then** obtiene la cantidad registrada correspondiente.<br><br>**Scenario:** Producto sin disponibilidad<br><br>**Given** la cantidad disponible del producto es cero.<br>**When** se realiza la consulta.<br>**Then** el sistema identifica que no existe disponibilidad. | EPIC-03 |
| US23 | Registro de Entradas de Inventario | **Como** Empleado, **quiero** registrar entradas de productos, **para** reflejar el ingreso de mercadería al inventario. | **Scenario:** Registrar entrada válida<br><br>**Given** existe un lote válido y la cantidad ingresada es mayor que cero.<br>**When** el Empleado registra la entrada.<br>**Then** se crea el movimiento correspondiente.<br><br>**Scenario:** Registrar cantidad inválida<br><br>**Given** la cantidad ingresada no es válida.<br>**When** se intenta registrar la entrada.<br>**Then** el sistema rechaza la operación. | EPIC-04 |
| US24 | Registro de Salidas de Inventario | **Como** Empleado, **quiero** registrar salidas de productos, **para** mantener actualizado el inventario después de una operación. | **Scenario:** Registrar salida válida<br><br>**Given** existe disponibilidad suficiente.<br>**When** el Empleado registra la salida.<br>**Then** se crea el movimiento correspondiente.<br><br>**Scenario:** Registrar salida sin disponibilidad<br><br>**Given** la cantidad solicitada supera la disponible.<br>**When** se intenta registrar la salida.<br>**Then** el sistema rechaza la operación. | EPIC-04 |
| US25 | Validación de Disponibilidad | **Como** Empleado, **quiero** que se valide la disponibilidad antes de registrar una salida, **para** evitar inconsistencias en el inventario. | **Scenario:** Validar disponibilidad suficiente<br><br>**Given** existe cantidad suficiente para la operación.<br>**When** se solicita una salida válida.<br>**Then** el sistema permite continuar con el registro.<br><br>**Scenario:** Validar disponibilidad insuficiente<br><br>**Given** la cantidad solicitada supera la disponible.<br>**When** se valida la operación.<br>**Then** el sistema impide continuar con el registro. | EPIC-04 |
| US26 | Registro de Ajustes de Stock | **Como** Administrador, **quiero** registrar ajustes de stock a partir de diferencias identificadas en el inventario, **para** documentar y corregir discrepancias sin perder la trazabilidad. | **Scenario:** Registrar ajuste válido<br><br>**Given** existe un producto o lote y se identifica una diferencia que requiere ajuste.<br>**When** el Administrador registra el cambio con su cantidad y motivo.<br>**Then** el ajuste queda registrado con los datos necesarios para su seguimiento.<br><br>**Scenario:** Rechazar ajuste inválido<br><br>**Given** la cantidad proporcionada no cumple las reglas de inventario.<br>**When** se intenta registrar el ajuste.<br>**Then** el sistema rechaza la operación sin aplicar cambios inválidos. | EPIC-04 |
| US27 | Historial de Movimientos de Inventario | **Como** Administrador, **quiero** consultar los movimientos registrados, **para** conocer la trazabilidad del inventario. | **Scenario:** Consultar historial existente<br><br>**Given** existen movimientos registrados.<br>**When** el Administrador solicita el historial.<br>**Then** obtiene entradas, salidas y ajustes registrados.<br><br>**Scenario:** Consultar historial vacío<br><br>**Given** no existen movimientos registrados.<br>**When** se realiza la consulta.<br>**Then** el sistema devuelve una colección vacía. | EPIC-04 |
| US28 | Registro de Mermas | **Como** Empleado, **quiero** registrar productos dañados, vencidos o perdidos, **para** documentar las pérdidas del negocio. | **Scenario:** Registrar merma válida<br><br>**Given** existe el producto y la cantidad indicada es válida.<br>**When** el Empleado registra la merma.<br>**Then** la pérdida queda registrada correctamente.<br><br>**Scenario:** Registrar merma superior a disponibilidad<br><br>**Given** la cantidad de merma supera la disponible.<br>**When** se intenta registrar.<br>**Then** el sistema rechaza la operación. | EPIC-04 |
| US29 | Clasificación de Motivos de Merma | **Como** Administrador, **quiero** identificar el motivo de cada merma, **para** analizar las principales causas de pérdida. | **Scenario:** Registrar motivo de merma<br><br>**Given** existe una merma registrada.<br>**When** el Administrador asigna un motivo válido.<br>**Then** la merma conserva dicha clasificación.<br><br>**Scenario:** Consultar motivo registrado<br><br>**Given** existen mermas clasificadas.<br>**When** se realiza la consulta.<br>**Then** se obtiene el motivo asociado a cada registro. | EPIC-04 |
| US30 | Registro de Conteo Físico | **Como** usuario autorizado, **quiero** registrar un conteo físico, **para** comparar las existencias reales con las registradas en el sistema. | **Scenario:** Registrar conteo válido<br><br>**Given** existe un lote válido.<br>**When** el usuario registra la cantidad encontrada físicamente.<br>**Then** el conteo queda almacenado correctamente.<br><br>**Scenario:** Registrar cantidad inválida<br><br>**Given** la cantidad física proporcionada no es válida.<br>**When** se intenta registrar el conteo.<br>**Then** el sistema rechaza la operación. | EPIC-05 |
| US31 | Cálculo de Diferencia de Inventario | **Como** Administrador, **quiero** conocer la diferencia entre la cantidad registrada y la cantidad física, **para** identificar descuadres de inventario. | **Scenario:** Calcular diferencia<br><br>**Given** existe un conteo físico registrado.<br>**When** se compara la cantidad física con la cantidad registrada.<br>**Then** se obtiene la diferencia correspondiente.<br><br>**Scenario:** Cantidades coincidentes<br><br>**Given** ambas cantidades son iguales.<br>**When** se realiza la comparación.<br>**Then** la diferencia obtenida es cero. | EPIC-05 |
| US32 | Consulta del Historial de Conteos | **Como** Administrador, **quiero** consultar conteos físicos anteriores, **para** realizar seguimiento de las verificaciones del inventario. | **Scenario:** Consultar conteos existentes<br><br>**Given** existen conteos físicos registrados.<br>**When** el Administrador consulta el historial.<br>**Then** obtiene los registros correspondientes.<br><br>**Scenario:** Consultar sin conteos<br><br>**Given** no existen conteos físicos registrados.<br>**When** se realiza la consulta.<br>**Then** el sistema devuelve una colección vacía. | EPIC-05 |
| US33 | Registro de Solicitudes de Corrección | **Como** Empleado, **quiero** solicitar la revisión de una diferencia detectada en el inventario, **para** documentar posibles errores antes de que se realice una corrección. | **Scenario:** Registrar solicitud de corrección<br><br>**Given** existe una operación o conteo asociado a una discrepancia.<br>**When** el Empleado registra una solicitud con el motivo correspondiente.<br>**Then** la solicitud queda registrada con estado pendiente de revisión.<br><br>**Scenario:** Rechazar solicitud incompleta<br><br>**Given** la solicitud no contiene la información obligatoria.<br>**When** se intenta registrarla.<br>**Then** el sistema rechaza la solicitud y no crea un registro incompleto. | EPIC-05 |
| US34 | Revisión de Solicitudes de Corrección | **Como** Administrador, **quiero** aprobar o rechazar las solicitudes de corrección recibidas, **para** controlar las modificaciones solicitadas sobre el inventario. | **Scenario:** Aprobar solicitud pendiente<br><br>**Given** existe una solicitud de corrección pendiente.<br>**When** el Administrador aprueba la solicitud.<br>**Then** el estado de la solicitud queda registrado como aprobado.<br><br>**Scenario:** Rechazar solicitud pendiente<br><br>**Given** existe una solicitud de corrección pendiente.<br>**When** el Administrador rechaza la solicitud.<br>**Then** el estado de la solicitud queda registrado como rechazado. | EPIC-05 |
| US35 | Generación de Alertas de Stock Bajo | **Como** Administrador, **quiero** recibir alertas cuando un producto tenga stock bajo, **para** identificar necesidades de reposición. | **Scenario:** Detectar stock bajo<br><br>**Given** un producto cumple la condición definida de stock bajo.<br>**When** se evalúa su estado de inventario.<br>**Then** se genera una alerta asociada al producto.<br><br>**Scenario:** Producto sin condición de alerta<br><br>**Given** el producto no cumple la condición de stock bajo.<br>**When** se evalúa su estado.<br>**Then** no se genera una alerta de stock bajo. | EPIC-06 |
| US36 | Generación de Alertas por Vencimiento | **Como** Administrador, **quiero** identificar lotes vencidos, **para** evitar que continúen siendo considerados disponibles para la operación. | **Scenario:** Detectar lote vencido<br><br>**Given** la fecha de vencimiento del lote es anterior a la fecha actual.<br>**When** se evalúa el lote.<br>**Then** se genera una alerta de vencimiento.<br><br>**Scenario:** Evaluar lote vigente<br><br>**Given** la fecha de vencimiento todavía es válida.<br>**When** se evalúa el lote.<br>**Then** no se genera una alerta de vencimiento. | EPIC-06 |
| US37 | Consulta y Filtrado de Alertas | **Como** Administrador, **quiero** consultar las alertas y filtrarlas por sus características, **para** identificar con mayor facilidad las situaciones que requieren revisión. | **Scenario:** Consultar alertas registradas<br><br>**Given** existen alertas relacionadas con el inventario.<br>**When** el Administrador consulta las alertas.<br>**Then** obtiene sus tipos, niveles, mensajes y estados de atención.<br><br>**Scenario:** Filtrar alertas por estado<br><br>**Given** existen alertas pendientes y atendidas.<br>**When** el Administrador aplica un filtro de estado.<br>**Then** obtiene únicamente las alertas que cumplen el criterio seleccionado. | EPIC-06 |
| US38 | Atención de Alertas | **Como** Administrador, **quiero** marcar una alerta como atendida, **para** diferenciar las situaciones que ya fueron revisadas. | **Scenario:** Atender alerta pendiente<br><br>**Given** existe una alerta pendiente.<br>**When** el Administrador la marca como atendida.<br>**Then** su estado cambia a atendida.<br><br>**Scenario:** Conservar historial de alerta<br><br>**Given** una alerta ha sido atendida.<br>**When** se consulta posteriormente.<br>**Then** continúa disponible como registro histórico. | EPIC-06 |
| US39 | Consulta de Registros de Auditoría | **Como** Administrador, **quiero** consultar los registros de auditoría de las operaciones realizadas, **para** dar seguimiento a las acciones registradas en el sistema. | **Scenario:** Consultar auditoría existente<br><br>**Given** existen registros de auditoría disponibles.<br>**When** el Administrador solicita el historial de acciones.<br>**Then** obtiene los registros y la información de seguimiento disponible.<br><br>**Scenario:** Consultar auditoría sin registros<br><br>**Given** no existen registros para los criterios consultados.<br>**When** el Administrador solicita el historial.<br>**Then** el sistema devuelve una colección vacía. | EPIC-06 |
| US40 | Dashboard de Indicadores del Negocio | **Como** Administrador, **quiero** consultar indicadores consolidados de inventario y operaciones, **para** apoyar la toma de decisiones a partir de información resumida. | **Scenario:** Consultar indicadores operativos<br><br>**Given** existen registros de productos, lotes, movimientos y alertas.<br>**When** se calculan los indicadores del negocio.<br>**Then** se obtienen totales de productos, lotes, vencimientos, stock bajo, alertas y movimientos disponibles.<br><br>**Scenario:** Consultar indicadores sin registros<br><br>**Given** no existen registros suficientes para un indicador.<br>**When** se solicita el resumen del negocio.<br>**Then** el sistema devuelve un valor válido para ausencia de datos. | EPIC-07 |
| US41 | Reporte de Inventario | **Como** Administrador, **quiero** consultar un reporte del inventario, **para** conocer los productos, su stock, precio, categoría y estado. | **Scenario:** Generar reporte de inventario<br><br>**Given** existen productos registrados.<br>**When** el Administrador solicita el reporte de inventario.<br>**Then** obtiene la información consolidada de los productos.<br><br>**Scenario:** Reporte de inventario vacío<br><br>**Given** no existen productos registrados.<br>**When** se solicita el reporte.<br>**Then** el sistema devuelve una colección vacía. | EPIC-07 |
| US42 | Reporte de Movimientos de Inventario | **Como** Administrador, **quiero** consultar reportes de entradas y salidas de inventario, **para** analizar los ingresos y egresos registrados en el negocio. | **Scenario:** Consultar reporte de entradas<br><br>**Given** existen movimientos de tipo entrada.<br>**When** el Administrador solicita el reporte de entradas.<br>**Then** obtiene únicamente los movimientos de entrada registrados.<br><br>**Scenario:** Consultar reporte de salidas<br><br>**Given** existen movimientos de tipo salida.<br>**When** el Administrador solicita el reporte de salidas.<br>**Then** obtiene únicamente los movimientos de salida registrados. | EPIC-07 |
| US43 | Consulta de Recomendaciones Estratégicas | **Como** Administrador, **quiero** consultar y solicitar recomendaciones relacionadas con productos críticos, **para** evaluar posibles acciones para reducir pérdidas operativas. | **Scenario:** Consultar recomendaciones disponibles<br><br>**Given** existen recomendaciones relacionadas con el inventario.<br>**When** el Administrador solicita consultarlas.<br>**Then** obtiene las recomendaciones y la información que permite evaluarlas.<br><br>**Scenario:** Solicitar generación sin condiciones suficientes<br><br>**Given** no existen condiciones o datos suficientes para producir una recomendación.<br>**When** el Administrador solicita generar recomendaciones.<br>**Then** el sistema informa que no hay recomendaciones disponibles y no registra propuestas inexistentes. | EPIC-06 |
| US44 | Reporte de Mermas del Negocio | **Como** Administrador, **quiero** consultar las mermas registradas, **para** analizar las pérdidas generadas en el negocio. | **Scenario:** Consultar reporte de mermas<br><br>**Given** existen registros de merma.<br>**When** el Administrador solicita el reporte.<br>**Then** obtiene producto, cantidad, motivo y fecha asociados.<br><br>**Scenario:** Reporte sin mermas<br><br>**Given** no existen registros de merma.<br>**When** se realiza la consulta.<br>**Then** el sistema devuelve una colección vacía. | EPIC-07 |
| US45 | Gestión de Ofertas Estratégicas | **Como** Administrador, **quiero** registrar y consultar ofertas asociadas a productos, **para** apoyar acciones comerciales sobre productos seleccionados. | **Scenario:** Registrar oferta válida<br><br>**Given** existe un producto registrado y se proporcionan condiciones de oferta válidas.<br>**When** el Administrador registra precio o descuento y período de vigencia.<br>**Then** la oferta queda asociada al producto con sus condiciones comerciales.<br><br>**Scenario:** Rechazar oferta con vigencia inválida<br><br>**Given** el período de vigencia de la oferta no es válido.<br>**When** se intenta registrar la oferta.<br>**Then** el sistema rechaza el registro y conserva la información anterior. | EPIC-06 |
| US46 | Gestión de Usuarios | **Como** Administrador, **quiero** registrar y administrar usuarios, **para** controlar quién puede utilizar BodeGo. | **Scenario:** Registrar usuario válido<br><br>**Given** se proporcionan los datos obligatorios de una nueva cuenta.<br>**When** el Administrador registra al usuario.<br>**Then** la cuenta queda creada correctamente.<br><br>**Scenario:** Registrar usuario duplicado<br><br>**Given** ya existe una cuenta con el identificador proporcionado.<br>**When** se intenta registrar nuevamente.<br>**Then** el sistema rechaza la operación. | EPIC-08 |
| US47 | Gestión de Roles y Permisos | **Como** Administrador, **quiero** asignar roles a los usuarios, **para** controlar las acciones que pueden realizar dentro de BodeGo. | **Scenario:** Asignar rol válido<br><br>**Given** existe un usuario y un rol válido.<br>**When** el Administrador realiza la asignación.<br>**Then** los permisos del usuario corresponden al rol asignado.<br><br>**Scenario:** Restringir acción no autorizada<br><br>**Given** el usuario no posee la autorización requerida.<br>**When** intenta realizar una operación restringida.<br>**Then** el sistema rechaza el acceso. | EPIC-08 |
| US48 | Inicio de Sesión Seguro | **Como** usuario registrado, **quiero** autenticarme mediante mis credenciales, **para** acceder a las funcionalidades autorizadas. | **Scenario:** Autenticar credenciales válidas<br><br>**Given** existe una cuenta activa y las credenciales son correctas.<br>**When** el usuario intenta autenticarse.<br>**Then** obtiene acceso a una sesión autorizada.<br><br>**Scenario:** Rechazar credenciales inválidas<br><br>**Given** las credenciales no son válidas.<br>**When** el usuario intenta autenticarse.<br>**Then** el sistema rechaza el acceso. | EPIC-08 |
| US49 | Recuperación y Cambio de Contraseña | **Como** usuario, **quiero** cambiar o recuperar mi contraseña, **para** mantener protegido el acceso a mi cuenta. | **Scenario:** Cambiar contraseña válida<br><br>**Given** el usuario cumple las condiciones de validación.<br>**When** proporciona una nueva contraseña válida.<br>**Then** la credencial queda actualizada.<br><br>**Scenario:** Rechazar contraseña inválida<br><br>**Given** la nueva contraseña no cumple las reglas de seguridad.<br>**When** se intenta actualizarla.<br>**Then** el sistema rechaza el cambio. | EPIC-08 |
| US50 | Cierre de Sesión y Protección de Cuenta | **Como** usuario autenticado, **quiero** cerrar mi sesión de forma segura, **para** evitar accesos posteriores desde el dispositivo utilizado. | **Scenario:** Cerrar sesión activa<br><br>**Given** existe una sesión activa.<br>**When** el usuario solicita cerrarla.<br>**Then** la sesión queda invalidada.<br><br>**Scenario:** Acceder con sesión cerrada<br><br>**Given** la sesión ha sido invalidada.<br>**When** se intenta acceder a un recurso protegido utilizando dicha sesión.<br>**Then** el sistema rechaza el acceso. | EPIC-08 |

---

## Technical Stories

| **Technical Stories ID** | **Título** | **Descripción** | **Criterios de Aceptación** | **Relacionado con (Epic ID)** |
|---|---|---|---|---|
| TS01 | Consulta REST Inicial del Catálogo | **Como** Developer, **quiero** disponer de un endpoint REST inicial para consultar productos, **para** permitir que la primera versión del Frontend de BodeGo obtenga información estructurada del catálogo. | **Scenario:** Consultar productos registrados<br><br>**Given** existen productos registrados en el catálogo.<br>**When** el API recibe una solicitud `GET` para consultar los productos.<br>**Then** responde con la colección de productos disponibles y código `200`.<br><br>**Scenario:** Consultar catálogo vacío<br><br>**Given** no existen productos registrados.<br>**When** el API recibe una solicitud `GET` para consultar el catálogo.<br>**Then** responde con una colección vacía y código `200`.<br><br>**Scenario:** Consultar producto inexistente<br><br>**Given** no existe un producto con el identificador solicitado.<br>**When** el API recibe una solicitud `GET` para consultar dicho producto.<br>**Then** responde con código `404` y un mensaje que identifica el recurso inexistente. | EPIC-03 |
| TS02 | Gestión REST de Productos | **Como** Developer, **quiero** disponer de operaciones REST para registrar, consultar y actualizar productos, **para** permitir que la aplicación administre correctamente el catálogo de inventario de BodeGo. | **Scenario:** Registrar un producto<br><br>**Given** el API recibe los datos obligatorios y válidos de un producto.<br>**When** procesa una solicitud `POST` de registro.<br>**Then** crea el producto y responde con el recurso registrado y código `201`.<br><br>**Scenario:** Actualizar un producto<br><br>**Given** existe un producto registrado en el sistema.<br>**When** el API recibe una solicitud `PUT` con información válida.<br>**Then** actualiza los datos del producto y responde con código `200`.<br><br>**Scenario:** Rechazar producto inexistente<br><br>**Given** no existe el producto solicitado.<br>**When** el API recibe una solicitud para actualizarlo.<br>**Then** responde con código `404` y conserva los registros existentes. | EPIC-03 |
| TS03 | Gestión REST de Categorías | **Como** Developer, **quiero** disponer de operaciones REST para consultar categorías y asociarlas a productos, **para** organizar el catálogo y facilitar la clasificación del inventario. | **Scenario:** Consultar categorías<br><br>**Given** existen categorías registradas.<br>**When** el API recibe una solicitud `GET` para consultar las categorías.<br>**Then** responde con la colección correspondiente y código `200`.<br><br>**Scenario:** Asociar categoría a un producto<br><br>**Given** existen un producto y una categoría válidos.<br>**When** el API recibe una solicitud para asociar la categoría al producto.<br>**Then** registra la asociación y responde con código `200`.<br><br>**Scenario:** Categoría inexistente<br><br>**Given** la categoría solicitada no existe.<br>**When** el API procesa una solicitud de asociación.<br>**Then** responde con código `404` y no modifica la clasificación del producto. | EPIC-03 |
| TS04 | Gestión REST de Lotes | **Como** Developer, **quiero** disponer de operaciones REST para registrar y consultar lotes asociados a productos, **para** mantener información sobre cantidades, fechas de ingreso y vencimientos del inventario. | **Scenario:** Registrar un lote<br><br>**Given** existe un producto válido y la solicitud contiene los datos obligatorios del lote.<br>**When** el API recibe una solicitud `POST` para registrarlo.<br>**Then** crea el lote asociado al producto y responde con código `201`.<br><br>**Scenario:** Consultar lotes de un producto<br><br>**Given** existen lotes asociados a un producto.<br>**When** el API recibe una solicitud `GET` para consultarlos.<br>**Then** responde con los lotes, sus cantidades y fechas correspondientes con código `200`.<br><br>**Scenario:** Registrar lote con datos inválidos<br><br>**Given** la solicitud contiene una cantidad o fecha que no cumple las reglas de validación.<br>**When** el API procesa el registro.<br>**Then** rechaza la solicitud con código `400` y no crea el lote. | EPIC-03 |
| TS05 | Consulta REST de Disponibilidad de Inventario | **Como** Developer, **quiero** disponer de operaciones REST para consultar la cantidad disponible de los productos, **para** proporcionar información de inventario actualizada a los diferentes módulos de BodeGo. | **Scenario:** Consultar disponibilidad de producto<br><br>**Given** existe un producto registrado con información de inventario.<br>**When** el API recibe una solicitud `GET` para consultar su disponibilidad.<br>**Then** responde con la cantidad disponible y código `200`.<br><br>**Scenario:** Consultar producto sin stock<br><br>**Given** existe un producto cuya disponibilidad es cero.<br>**When** el API procesa la consulta.<br>**Then** responde con cantidad cero y código `200`.<br><br>**Scenario:** Consultar producto inexistente<br><br>**Given** el producto solicitado no existe.<br>**When** el API recibe la solicitud de consulta.<br>**Then** responde con código `404` y un mensaje de recurso no encontrado. | EPIC-03 |
| TS06 | Registro REST de Movimientos de Inventario | **Como** Developer, **quiero** disponer de operaciones REST para registrar y consultar entradas, salidas y ajustes de inventario, **para** mantener la trazabilidad de las operaciones realizadas sobre los productos y lotes. | **Scenario:** Registrar movimiento de inventario<br><br>**Given** existe un lote válido y la solicitud contiene un tipo de movimiento y una cantidad permitidos.<br>**When** el API recibe una solicitud `POST` para registrar el movimiento.<br>**Then** crea el registro asociado al lote y responde con código `201`.<br><br>**Scenario:** Consultar historial de movimientos<br><br>**Given** existen movimientos registrados.<br>**When** el API recibe una solicitud `GET` para consultar el historial.<br>**Then** responde con los movimientos disponibles y código `200`.<br><br>**Scenario:** Rechazar movimiento inválido<br><br>**Given** la solicitud contiene un tipo de movimiento no permitido o una cantidad inválida.<br>**When** el API procesa la solicitud.<br>**Then** responde con código `400` y no registra el movimiento. | EPIC-04 |
| TS07 | Validación REST de Salidas y Ajustes | **Como** Developer, **quiero** implementar validaciones para las operaciones que modifican las cantidades del inventario, **para** evitar registros que generen existencias negativas o inconsistentes. | **Scenario:** Validar salida con disponibilidad suficiente<br><br>**Given** la cantidad solicitada es menor o igual a la cantidad disponible.<br>**When** el servicio procesa la validación de salida.<br>**Then** permite continuar con la operación.<br><br>**Scenario:** Rechazar salida por disponibilidad insuficiente<br><br>**Given** la cantidad solicitada supera la disponibilidad del lote.<br>**When** el API procesa la solicitud de salida.<br>**Then** responde con código `409` y conserva la cantidad anterior.<br><br>**Scenario:** Rechazar ajuste inválido<br><br>**Given** un ajuste produciría una cantidad de inventario no permitida.<br>**When** el servicio valida la operación.<br>**Then** rechaza el ajuste con código `409` y no modifica el inventario. | EPIC-04 |
| TS08 | Gestión REST de Mermas | **Como** Developer, **quiero** disponer de operaciones REST para registrar y consultar mermas de productos, **para** documentar las pérdidas ocasionadas por daños, vencimientos u otros motivos operativos. | **Scenario:** Registrar una merma<br><br>**Given** existe un producto válido y la solicitud contiene una cantidad y un motivo permitidos.<br>**When** el API recibe una solicitud `POST` para registrar la merma.<br>**Then** registra la pérdida y responde con código `201`.<br><br>**Scenario:** Consultar mermas registradas<br><br>**Given** existen registros de mermas.<br>**When** el API recibe una solicitud `GET` para consultarlos.<br>**Then** responde con los productos, cantidades, motivos y fechas con código `200`.<br><br>**Scenario:** Rechazar merma por cantidad insuficiente<br><br>**Given** la cantidad de merma supera la cantidad disponible.<br>**When** el API procesa la solicitud.<br>**Then** rechaza la operación con código `409` y conserva las cantidades anteriores. | EPIC-04 |
| TS09 | Gestión REST de Conteos Físicos y Solicitudes de Corrección | **Como** Developer, **quiero** disponer de operaciones REST para registrar conteos físicos y administrar solicitudes de corrección, **para** documentar diferencias de inventario y permitir su revisión por un Administrador. | **Scenario:** Registrar conteo físico<br><br>**Given** existe un lote válido y la cantidad física proporcionada es permitida.<br>**When** el API recibe una solicitud `POST` para registrar el conteo.<br>**Then** crea el conteo asociado al lote y responde con código `201`.<br><br>**Scenario:** Consultar conteos registrados<br><br>**Given** existen conteos físicos registrados.<br>**When** el API recibe una solicitud `GET` para consultarlos.<br>**Then** devuelve el historial de conteos y responde con código `200`.<br><br>**Scenario:** Registrar solicitud de corrección<br><br>**Given** existe un conteo registrado y la solicitud contiene un motivo válido.<br>**When** el API recibe una solicitud `POST` de corrección.<br>**Then** crea la solicitud vinculada al conteo y responde con código `201`.<br><br>**Scenario:** Revisar solicitud de corrección<br><br>**Given** existe una solicitud pendiente y el usuario tiene autorización de revisión.<br>**When** el API recibe una solicitud `PATCH` para aprobarla o rechazarla.<br>**Then** actualiza el estado de la solicitud y responde con código `200` sin alterar automáticamente el stock.<br><br>**Scenario:** Rechazar cantidad física inválida<br><br>**Given** la solicitud contiene una cantidad física negativa o inválida.<br>**When** el API procesa el registro del conteo.<br>**Then** responde con código `400` y no registra el conteo. | EPIC-05 |
| TS10 | Gestión REST de Alertas Operativas | **Como** Developer, **quiero** disponer de operaciones REST para registrar y consultar alertas relacionadas con el inventario, **para** permitir que la aplicación informe situaciones que requieren atención. | **Scenario:** Registrar alerta de inventario<br><br>**Given** existe una condición válida de inventario que requiere atención.<br>**When** el API recibe una solicitud válida de registro de alerta.<br>**Then** crea la alerta con su tipo, nivel y mensaje y responde con código `201`.<br><br>**Scenario:** Consultar alertas registradas<br><br>**Given** existen alertas disponibles.<br>**When** el API recibe una solicitud `GET` para consultarlas.<br>**Then** responde con la colección correspondiente y código `200`.<br><br>**Scenario:** Consultar sin alertas<br><br>**Given** no existen alertas registradas.<br>**When** el API recibe la solicitud de consulta.<br>**Then** responde con una colección vacía y código `200`. | EPIC-06 |
| TS11 | Atención de Alertas y Consulta REST de Auditoría | **Como** Developer, **quiero** disponer de operaciones REST para atender y filtrar alertas y consultar registros de auditoría, **para** permitir el seguimiento de las condiciones detectadas y las acciones registradas en BodeGo. | **Scenario:** Marcar alerta como atendida<br><br>**Given** existe una alerta pendiente.<br>**When** el API recibe una solicitud `PATCH` válida para marcarla como atendida.<br>**Then** actualiza el estado de atención y responde con código `200` sin modificar el inventario.<br><br>**Scenario:** Filtrar alertas<br><br>**Given** existen alertas con diferentes tipos, niveles o estados.<br>**When** el API recibe una solicitud `GET` con filtros válidos.<br>**Then** devuelve únicamente las alertas coincidentes y código `200`.<br><br>**Scenario:** Consultar auditoría<br><br>**Given** existen registros de auditoría y la solicitud está autorizada.<br>**When** el API recibe una solicitud `GET` para consultar el historial de auditoría.<br>**Then** devuelve los registros disponibles y responde con código `200`.<br><br>**Scenario:** Consultar auditoría sin registros<br><br>**Given** no existen registros de auditoría para los criterios solicitados.<br>**When** el API recibe una solicitud `GET` válida.<br>**Then** responde con una colección vacía y código `200`.<br><br>**Scenario:** Actualizar alerta inexistente<br><br>**Given** la alerta solicitada no existe.<br>**When** el API recibe una solicitud para actualizarla.<br>**Then** responde con código `404` sin modificar otros registros. | EPIC-06 |
| TS12 | Gestión REST de Recomendaciones y Ofertas Estratégicas | **Como** Developer, **quiero** disponer de operaciones REST para consultar y solicitar recomendaciones y para registrar y consultar ofertas, **para** respaldar acciones comerciales sobre productos que requieren atención. | **Scenario:** Consultar recomendaciones<br><br>**Given** existen recomendaciones registradas.<br>**When** el API recibe una solicitud `GET` para consultarlas.<br>**Then** responde con las recomendaciones disponibles y código `200`.<br><br>**Scenario:** Solicitar generación de recomendaciones<br><br>**Given** existe información suficiente del inventario para evaluar los criterios definidos.<br>**When** el API recibe una solicitud `POST` de generación de recomendaciones.<br>**Then** devuelve el resultado de la evaluación y código `200`.<br><br>**Scenario:** Registrar oferta estratégica<br><br>**Given** existe un producto válido y los datos de la oferta cumplen las reglas definidas.<br>**When** el API recibe una solicitud `POST` para registrar una oferta.<br>**Then** crea la oferta asociada al producto y responde con código `201`.<br><br>**Scenario:** Consultar ofertas<br><br>**Given** existen ofertas registradas.<br>**When** el API recibe una solicitud `GET` para consultarlas.<br>**Then** devuelve las ofertas disponibles y código `200`.<br><br>**Scenario:** Rechazar oferta inválida<br><br>**Given** la oferta contiene un descuento o un período de vigencia no válido.<br>**When** el API procesa el registro solicitado.<br>**Then** responde con código `400` y no registra la oferta. | EPIC-06 |
| TS13 | Consulta REST de Indicadores y Reportes Operativos | **Como** Developer, **quiero** disponer de recursos REST para obtener indicadores del Dashboard y reportes de inventario, movimientos y mermas, **para** presentar información resumida y detallada de las operaciones de BodeGo. | **Scenario:** Consultar indicadores del Dashboard<br><br>**Given** existen datos de productos, lotes y operaciones.<br>**When** el API recibe una solicitud `GET` para consultar los indicadores.<br>**Then** responde con los indicadores calculados y código `200`.<br><br>**Scenario:** Consultar reporte de inventario<br><br>**Given** existen productos registrados.<br>**When** el API recibe una solicitud `GET` para el reporte de inventario.<br>**Then** devuelve los productos y su información disponible con código `200`.<br><br>**Scenario:** Consultar entradas y salidas<br><br>**Given** existen movimientos con distintos tipos.<br>**When** el API recibe una solicitud `GET` con un filtro de tipo válido.<br>**Then** responde con los movimientos coincidentes y código `200`.<br><br>**Scenario:** Consultar reporte de mermas<br><br>**Given** existen mermas registradas.<br>**When** el API recibe una solicitud `GET` para el reporte de mermas.<br>**Then** devuelve productos, cantidades, motivos y fechas con código `200`.<br><br>**Scenario:** Consultar reporte sin datos<br><br>**Given** no existen registros que cumplan los criterios de consulta.<br>**When** el API recibe una solicitud `GET` válida.<br>**Then** responde con una colección vacía o indicadores en cero, según el recurso, y código `200`. | EPIC-07 |
| TS14 | Gestión REST de Negocios y Usuarios | **Como** Developer, **quiero** disponer de operaciones REST para registrar y consultar negocios y administrar usuarios, **para** respaldar la gestión de establecimientos y cuentas autorizadas de BodeGo. | **Scenario:** Registrar negocio<br><br>**Given** los datos obligatorios del negocio son válidos y la solicitud está autorizada.<br>**When** el API recibe una solicitud `POST` de registro.<br>**Then** crea el negocio y responde con código `201`.<br><br>**Scenario:** Consultar negocios<br><br>**Given** existen negocios registrados y la solicitud está autorizada.<br>**When** el API recibe una solicitud `GET` para consultarlos.<br>**Then** devuelve los negocios disponibles y código `200`.<br><br>**Scenario:** Registrar usuario<br><br>**Given** los datos obligatorios del nuevo usuario son válidos y la solicitud está autorizada.<br>**When** el API recibe una solicitud `POST` para registrar la cuenta.<br>**Then** crea el usuario y responde con código `201` sin exponer credenciales sensibles.<br><br>**Scenario:** Consultar usuarios<br><br>**Given** existen usuarios registrados y la solicitud está autorizada.<br>**When** el API recibe una solicitud `GET` para consultarlos.<br>**Then** devuelve la información permitida y código `200`.<br><br>**Scenario:** Rechazar usuario duplicado<br><br>**Given** ya existe una cuenta con el identificador proporcionado.<br>**When** el API recibe una solicitud de registro duplicada.<br>**Then** responde con código `409` y no crea otra cuenta. | EPIC-08 |
| TS15 | Autenticación y Gestión de Sesiones | **Como** Developer, **quiero** disponer de servicios REST para autenticar usuarios y gestionar sesiones, **para** proteger el acceso a las funcionalidades de BodeGo. | **Scenario:** Autenticar usuario válido<br><br>**Given** existe una cuenta activa y las credenciales proporcionadas son correctas.<br>**When** el API recibe una solicitud de autenticación.<br>**Then** valida las credenciales y responde con la información de sesión autorizada.<br><br>**Scenario:** Rechazar credenciales inválidas<br><br>**Given** las credenciales proporcionadas no son válidas.<br>**When** el API procesa la autenticación.<br>**Then** responde con código `401` sin revelar información sensible.<br><br>**Scenario:** Cerrar sesión<br><br>**Given** existe una sesión activa.<br>**When** el API procesa una solicitud válida de cierre de sesión.<br>**Then** invalida la sesión correspondiente e impide su reutilización. | EPIC-08 |
| TS16 | Roles, Contraseñas y Protección de Acceso | **Como** Developer, **quiero** disponer de servicios REST para gestionar roles, actualizar contraseñas y validar autorizaciones, **para** garantizar que cada usuario acceda únicamente a las operaciones permitidas. | **Scenario:** Autorizar operación según rol<br><br>**Given** existe un usuario autenticado con un rol autorizado.<br>**When** el API recibe una solicitud a un recurso protegido.<br>**Then** permite la operación correspondiente.<br><br>**Scenario:** Rechazar operación sin permisos<br><br>**Given** el usuario autenticado no posee el permiso requerido.<br>**When** intenta acceder a un recurso protegido.<br>**Then** el API rechaza la operación con código `403`.<br><br>**Scenario:** Actualizar contraseña<br><br>**Given** el usuario cumple las condiciones de validación y proporciona una nueva contraseña válida.<br>**When** el API procesa la solicitud de actualización.<br>**Then** actualiza la credencial y responde con código `200` sin exponer información sensible.<br><br>**Scenario:** Rechazar contraseña inválida<br><br>**Given** la contraseña proporcionada no cumple las reglas de seguridad.<br>**When** el API procesa la solicitud.<br>**Then** responde con código `400` y conserva la credencial anterior. | EPIC-08 |

---

## 3.2. Impact Mapping

---

| **Business Goals** | **Actors** | **Impact** | **Deliverables** | **User Stories** |
|---|---|---|---|---|
| **Goal N°1:**<br>**Captar el interés de negocios minoristas mediante una presencia digital clara que comunique la propuesta de valor de BodeGo durante los primeros 12 meses.** | Visitante / Cliente potencial | Conocer la solución BodeGo, comprender sus beneficios y solicitar información sobre la plataforma. | Landing Page comercial.<br><br>Secciones informativas del producto.<br><br>Formulario de contacto. | **US01: Visualización del Hero Principal.** Como visitante, quiero visualizar una sección principal con la propuesta de valor de BodeGo, para comprender cómo la plataforma ayuda a gestionar inventarios y reducir mermas.<br><br>**US02: Visualización de Beneficios del Producto.** Como visitante, quiero conocer los beneficios principales de BodeGo, para identificar las ventajas de utilizar una plataforma de gestión operativa.<br><br>**US03: Presentación de Funcionalidades Principales.** Como visitante, quiero visualizar las funcionalidades principales de BodeGo, para conocer las herramientas disponibles antes de utilizar la aplicación.<br><br>**US05: Formulario de Contacto Comercial.** Como visitante, quiero enviar una solicitud de contacto, para recibir información adicional sobre BodeGo. |
| | Visitante / Cliente potencial | Entender el funcionamiento general del producto antes de incorporarlo al negocio. | Sección explicativa del funcionamiento de la plataforma. | **US04: Visualización del Funcionamiento de BodeGo.** Como visitante, quiero conocer cómo funciona BodeGo, para entender el flujo general de uso dentro de una bodega o minimarket. |
| **Goal N°2:**<br>**Mejorar el control operativo del inventario reduciendo errores de registro manual en un 40% durante los primeros 12 meses.** | Administrador | Mantener productos correctamente registrados y organizados dentro del sistema. | Gestión de productos.<br><br>Categorías.<br><br>Detalle de productos. | **US16: Registro de Productos.** Como Administrador, quiero registrar nuevos productos, para mantener actualizado el catálogo de inventario.<br><br>**US17: Edición de Información del Producto.** Como Administrador, quiero modificar la información de un producto registrado, para mantener datos actualizados.<br><br>**US18: Clasificación de Productos por Categoría.** Como Administrador, quiero asignar categorías a los productos, para organizar el inventario y facilitar su búsqueda.<br><br>**US09: Consulta del Detalle de Producto.** Como Administrador o Empleado, quiero visualizar el detalle de un producto, para revisar información específica del artículo. |
| | Administrador / Empleado | Encontrar rápidamente productos y conocer su disponibilidad actual. | Buscador y filtros de inventario.<br><br>Visualización de inventario. | **US08: Visualización del Módulo de Inventario.** Como Administrador o Empleado, quiero visualizar el inventario registrado, para conocer la disponibilidad actual de productos.<br><br>**US11: Filtrado y Búsqueda de Productos.** Como Administrador o Empleado, quiero buscar productos mediante filtros, para encontrar rápidamente los artículos que necesito gestionar.<br><br>**US21: Consulta de Stock Actual.** Como Administrador o Empleado, quiero consultar la cantidad disponible de cada producto, para conocer el estado actual del inventario. |
| **Goal N°3:**<br>**Reducir en un 30% las pérdidas generadas por productos vencidos, dañados o deteriorados durante los primeros 10 meses.** | Administrador / Empleado | Controlar productos perecibles y actuar antes de generar pérdidas económicas. | Gestión de lotes.<br><br>Control de vencimientos.<br><br>Registro de mermas.<br><br>Alertas preventivas. | **US20: Gestión de Lotes y Fechas de Vencimiento.** Como Empleado, quiero registrar lotes con fechas de vencimiento, para controlar productos perecibles.<br><br>**US27: Control de Productos Próximos a Vencer.** Como Administrador, quiero identificar productos próximos a vencer, para tomar acciones preventivas.<br><br>**US31: Registro de Productos Dañados o Vencidos.** Como Empleado, quiero registrar productos dañados o vencidos, para mantener actualizado el inventario.<br><br>**US34: Generación de Alertas de Stock Bajo.** Como Administrador, quiero recibir alertas cuando un producto tenga stock bajo, para anticipar necesidades de reposición. |
| **Goal N°4:**<br>**Digitalizar el 80% de las operaciones diarias realizadas por empleados durante los primeros 6 meses de implementación.** | Empleado Operativo | Registrar correctamente ingresos, salidas y movimientos del inventario. | Registro de operaciones.<br><br>Actualización automática de stock.<br><br>Historial operativo. | **US19: Registro de Ingreso de Inventario.** Como Empleado, quiero registrar ingresos de productos al inventario, para mantener actualizado el stock disponible.<br><br>**US23: Registro de Salida de Productos.** Como Empleado, quiero registrar salidas de productos, para mantener actualizado el inventario.<br><br>**US26: Historial de Movimientos de Inventario.** Como Administrador, quiero consultar el historial de movimientos, para conocer la trazabilidad.<br><br>**US34: Visualización de Operaciones del Empleado.** Como Empleado, quiero consultar mis operaciones realizadas, para verificar movimientos registrados durante mi jornada. |
| **Goal N°5:**<br>**Mejorar la toma de decisiones del administrador mediante indicadores y reportes operativos durante los primeros 12 meses.** | Administrador | Analizar información del negocio para tomar decisiones estratégicas. | Dashboard administrativo.<br><br>Reportes analíticos.<br><br>Indicadores operativos. | **US37: Dashboard de Indicadores del Negocio.** Como Administrador, quiero visualizar indicadores generales del negocio, para conocer rápidamente el estado operativo.<br><br>**US38: Reporte de Rotación de Productos.** Como Administrador, quiero conocer la rotación de productos, para identificar comportamiento del inventario.<br><br>**US39: Reporte de Productos Próximos a Vencer.** Como Administrador, quiero consultar productos próximos a vencer, para planificar acciones preventivas.<br><br>**US40: Reporte de Mermas del Negocio.** Como Administrador, quiero visualizar reportes de mermas, para analizar pérdidas generadas. |
| **Goal N°6:**<br>**Garantizar que todos los accesos al sistema sean seguros mediante autenticación y permisos definidos durante la primera versión productiva.** | Administrador / Empleado | Acceder únicamente a las funcionalidades correspondientes según su responsabilidad. | Gestión de usuarios.<br><br>Roles y permisos.<br><br>Autenticación.<br><br>Gestión de contraseña. | **US46: Registro de Usuarios del Sistema.** Como Administrador, quiero registrar usuarios dentro de BodeGo, para permitir accesos autorizados.<br><br>**US47: Gestión de Roles y Permisos.** Como Administrador, quiero asignar roles y permisos, para controlar el acceso a funcionalidades.<br><br>**US48: Inicio de Sesión Seguro.** Como usuario registrado, quiero iniciar sesión mediante mis credenciales, para acceder de manera segura.<br><br>**US49: Recuperación y Cambio de Contraseña.** Como usuario, quiero recuperar o cambiar mi contraseña, para mantener protegido mi acceso.<br><br>**US50: Cierre de Sesión y Protección de Cuenta.** Como usuario, quiero cerrar mi sesión correctamente, para evitar accesos no autorizados. |

## 3.3. Product Backlog

# Product Backlog — BodeGo

| **# Orden** | **Story ID (US / TS)** | **Título** | **Descripción** | **Story Points** (1 / 2 / 3 / 5) |
|---:|:---:|---|---|---:|
| **1** | **US01** | Visualización de la Propuesta de Valor | **Como** visitante, **quiero** conocer la propuesta principal de BodeGo, **para** comprender cómo puede ayudar a mejorar la gestión de un minimarket. | **2** |
| **2** | **US02** | Consulta de Beneficios de BodeGo | **Como** visitante, **quiero** conocer los beneficios principales de BodeGo, **para** evaluar el valor que puede aportar a la gestión de mi negocio. | **2** |
| **3** | **US03** | Presentación de Funcionalidades Principales | **Como** visitante, **quiero** conocer las funcionalidades principales de BodeGo, **para** comprender el alcance de la solución antes de utilizarla. | **3** |
| **4** | **US04** | Explicación del Funcionamiento de BodeGo | **Como** visitante, **quiero** conocer cómo funciona BodeGo, **para** entender cómo se utiliza durante la operación de un minimarket. | **2** |
| **5** | **US05** | Formulario de Contacto Comercial | **Como** visitante interesado, **quiero** enviar mis datos de contacto, **para** solicitar información adicional sobre BodeGo. | **3** |
| **6** | **US06** | Visualización del Dashboard Administrativo | **Como** Administrador, **quiero** consultar indicadores generales y movimientos recientes del negocio, **para** identificar rápidamente el estado operativo y las situaciones que requieren atención. | **5** |
| **7** | **US08** | Visualización del Inventario | **Como** Administrador o Empleado, **quiero** consultar los productos registrados, **para** conocer el estado general del inventario. | **3** |
| **8** | **US11** | Búsqueda y Filtrado de Productos | **Como** Administrador o Empleado, **quiero** buscar productos mediante criterios disponibles, **para** encontrar rápidamente la información que necesito. | **3** |
| **9** | **US09** | Consulta de Información de Productos y Lotes | **Como** Administrador o Empleado, **quiero** consultar la información asociada a productos y lotes, **para** conocer sus datos operativos. | **2** |
| **10** | **US07** | Navegación entre Módulos del Sistema | **Como** usuario de BodeGo, **quiero** acceder a los diferentes módulos disponibles, **para** realizar mis actividades de manera organizada. | **3** |
| **11** | **US10** | Visualización de Operaciones | **Como** Empleado, **quiero** consultar las operaciones registradas, **para** revisar la actividad realizada sobre el inventario. | **3** |
| **12** | **US12** | Visualización de Alertas | **Como** Administrador, **quiero** consultar alertas relacionadas con el inventario, **para** conocer situaciones que requieren atención. | **5** |
| **13** | **US13** | Visualización de Reportes | **Como** Administrador, **quiero** consultar diferentes reportes, **para** analizar información relacionada con el inventario y las operaciones. | **5** |
| **14** | **US14** | Gestión Visual de Productos | **Como** Administrador, **quiero** disponer de las acciones necesarias para gestionar productos, **para** mantener organizado el catálogo. | **3** |
| **15** | **US15** | Gestión Visual de Negocios | **Como** Administrador, **quiero** registrar y consultar los negocios administrados en BodeGo, **para** mantener organizada la información de los establecimientos. | **2** |
| **16** | **TS01** | Consulta REST Inicial del Catálogo | **Como** Developer, **quiero** disponer de un endpoint REST inicial para consultar productos, **para** permitir que la primera versión del Frontend de BodeGo obtenga información estructurada del catálogo. | **2** |
| **17** | **US16** | Registro de Productos | **Como** Administrador, **quiero** registrar nuevos productos, **para** mantener actualizado el catálogo del negocio. | **3** |
| **18** | **US18** | Desactivación de Productos | **Como** Administrador, **quiero** desactivar productos que ya no se comercializan, **para** mantener vigente el catálogo sin perder su historial. | **2** |
| **19** | **US17** | Actualización de Productos | **Como** Administrador, **quiero** modificar la información de un producto, **para** mantener sus datos actualizados. | **2** |
| **20** | **TS02** | Gestión REST de Productos | **Como** Developer, **quiero** disponer de operaciones REST para registrar, consultar y actualizar productos, **para** permitir que la aplicación administre correctamente el catálogo de inventario de BodeGo. | **5** |
| **21** | **US19** | Clasificación de Productos por Categoría | **Como** Administrador, **quiero** asociar categorías a los productos, **para** organizar el catálogo y facilitar su clasificación. | **5** |
| **22** | **TS03** | Gestión REST de Categorías | **Como** Developer, **quiero** disponer de operaciones REST para consultar categorías y asociarlas a productos, **para** organizar el catálogo y facilitar la clasificación del inventario. | **3** |
| **23** | **US20** | Registro de Lotes | **Como** Administrador o Empleado autorizado, **quiero** registrar lotes de productos, **para** controlar cantidades y fechas de vencimiento. | **3** |
| **24** | **US21** | Consulta de Lotes y Vencimientos | **Como** usuario autorizado, **quiero** consultar los lotes de un producto, **para** conocer sus cantidades y fechas de vencimiento. | **3** |
| **25** | **TS04** | Gestión REST de Lotes | **Como** Developer, **quiero** disponer de operaciones REST para registrar y consultar lotes asociados a productos, **para** mantener información sobre cantidades, fechas de ingreso y vencimientos del inventario. | **5** |
| **26** | **US23** | Registro de Entradas de Inventario | **Como** Empleado, **quiero** registrar entradas de productos, **para** reflejar el ingreso de mercadería al inventario. | **5** |
| **27** | **US22** | Consulta de Disponibilidad de Inventario | **Como** Administrador o Empleado, **quiero** conocer la cantidad disponible de los productos, **para** tomar decisiones antes de realizar operaciones. | **5** |
| **28** | **TS05** | Consulta REST de Disponibilidad de Inventario | **Como** Developer, **quiero** disponer de operaciones REST para consultar la cantidad disponible de los productos, **para** proporcionar información de inventario actualizada a los diferentes módulos de BodeGo. | **3** |
| **29** | **US24** | Registro de Salidas de Inventario | **Como** Empleado, **quiero** registrar salidas de productos, **para** mantener actualizado el inventario después de una operación. | **3** |
| **30** | **TS06** | Registro REST de Movimientos de Inventario | **Como** Developer, **quiero** disponer de operaciones REST para registrar y consultar entradas, salidas y ajustes de inventario, **para** mantener la trazabilidad de las operaciones realizadas sobre los productos y lotes. | **5** |
| **31** | **US25** | Validación de Disponibilidad | **Como** Empleado, **quiero** que se valide la disponibilidad antes de registrar una salida, **para** evitar inconsistencias en el inventario. | **3** |
| **32** | **US26** | Registro de Ajustes de Stock | **Como** Administrador, **quiero** registrar ajustes de stock a partir de diferencias identificadas en el inventario, **para** documentar y corregir discrepancias sin perder la trazabilidad. | **3** |
| **33** | **TS07** | Validación REST de Salidas y Ajustes | **Como** Developer, **quiero** implementar validaciones para las operaciones que modifican las cantidades del inventario, **para** evitar registros que generen existencias negativas o inconsistentes. | **3** |
| **34** | **US29** | Clasificación de Motivos de Merma | **Como** Administrador, **quiero** identificar el motivo de cada merma, **para** analizar las principales causas de pérdida. | **5** |
| **35** | **TS08** | Gestión REST de Mermas | **Como** Developer, **quiero** disponer de operaciones REST para registrar y consultar mermas de productos, **para** documentar las pérdidas ocasionadas por daños, vencimientos u otros motivos operativos. | **3** |
| **36** | **US30** | Registro de Conteo Físico | **Como** usuario autorizado, **quiero** registrar un conteo físico, **para** comparar las existencias reales con las registradas en el sistema. | **5** |
| **37** | **US27** | Historial de Movimientos de Inventario | **Como** Administrador, **quiero** consultar los movimientos registrados, **para** conocer la trazabilidad del inventario. | **5** |
| **38** | **US28** | Registro de Mermas | **Como** Empleado, **quiero** registrar productos dañados, vencidos o perdidos, **para** documentar las pérdidas del negocio. | **5** |
| **39** | **US31** | Cálculo de Diferencia de Inventario | **Como** Administrador, **quiero** conocer la diferencia entre la cantidad registrada y la cantidad física, **para** identificar descuadres de inventario. | **3** |
| **40** | **US32** | Consulta del Historial de Conteos | **Como** Administrador, **quiero** consultar conteos físicos anteriores, **para** realizar seguimiento de las verificaciones del inventario. | **3** |
| **41** | **US33** | Registro de Solicitudes de Corrección | **Como** Empleado, **quiero** solicitar la revisión de una diferencia detectada en el inventario, **para** documentar posibles errores antes de que se realice una corrección. | **5** |
| **42** | **US34** | Revisión de Solicitudes de Corrección | **Como** Administrador, **quiero** aprobar o rechazar las solicitudes de corrección recibidas, **para** controlar las modificaciones solicitadas sobre el inventario. | **3** |
| **43** | **TS09** | Gestión REST de Conteos Físicos y Solicitudes de Corrección | **Como** Developer, **quiero** disponer de operaciones REST para registrar conteos físicos y administrar solicitudes de corrección, **para** documentar diferencias de inventario y permitir su revisión por un Administrador. | **5** |
| **44** | **US35** | Generación de Alertas de Stock Bajo | **Como** Administrador, **quiero** recibir alertas cuando un producto tenga stock bajo, **para** identificar necesidades de reposición. | **3** |
| **45** | **US36** | Generación de Alertas por Vencimiento | **Como** Administrador, **quiero** identificar lotes vencidos, **para** evitar que continúen siendo considerados disponibles para la operación. | **5** |
| **46** | **US37** | Consulta y Filtrado de Alertas | **Como** Administrador, **quiero** consultar las alertas y filtrarlas por sus características, **para** identificar con mayor facilidad las situaciones que requieren revisión. | **5** |
| **47** | **TS10** | Gestión REST de Alertas Operativas | **Como** Developer, **quiero** disponer de operaciones REST para registrar y consultar alertas relacionadas con el inventario, **para** permitir que la aplicación informe situaciones que requieren atención. | **3** |
| **48** | **US38** | Atención de Alertas | **Como** Administrador, **quiero** marcar una alerta como atendida, **para** diferenciar las situaciones que ya fueron revisadas. | **5** |
| **49** | **US39** | Consulta de Registros de Auditoría | **Como** Administrador, **quiero** consultar los registros de auditoría de las operaciones realizadas, **para** dar seguimiento a las acciones registradas en el sistema. | **5** |
| **50** | **TS11** | Atención de Alertas y Consulta REST de Auditoría | **Como** Developer, **quiero** disponer de operaciones REST para atender y filtrar alertas y consultar registros de auditoría, **para** permitir el seguimiento de las condiciones detectadas y las acciones registradas en BodeGo. | **3** |
| **51** | **US40** | Dashboard de Indicadores del Negocio | **Como** Administrador, **quiero** consultar indicadores consolidados de inventario y operaciones, **para** apoyar la toma de decisiones a partir de información resumida. | **5** |
| **52** | **US41** | Reporte de Inventario | **Como** Administrador, **quiero** consultar un reporte del inventario, **para** conocer los productos, su stock, precio, categoría y estado. | **5** |
| **53** | **US42** | Reporte de Movimientos de Inventario | **Como** Administrador, **quiero** consultar reportes de entradas y salidas de inventario, **para** analizar los ingresos y egresos registrados en el negocio. | **3** |
| **54** | **US43** | Consulta de Recomendaciones Estratégicas | **Como** Administrador, **quiero** consultar y solicitar recomendaciones relacionadas con productos críticos, **para** evaluar posibles acciones para reducir pérdidas operativas. | **5** |
| **55** | **US44** | Reporte de Mermas del Negocio | **Como** Administrador, **quiero** consultar las mermas registradas, **para** analizar las pérdidas generadas en el negocio. | **5** |
| **56** | **TS13** | Consulta REST de Indicadores y Reportes Operativos | **Como** Developer, **quiero** disponer de recursos REST para obtener indicadores del Dashboard y reportes de inventario, movimientos y mermas, **para** presentar información resumida y detallada de las operaciones de BodeGo. | **5** |
| **57** | **US45** | Gestión de Ofertas Estratégicas | **Como** Administrador, **quiero** registrar y consultar ofertas asociadas a productos, **para** apoyar acciones comerciales sobre productos seleccionados. | **5** |
| **58** | **TS12** | Gestión REST de Recomendaciones y Ofertas Estratégicas | **Como** Developer, **quiero** disponer de operaciones REST para consultar y solicitar recomendaciones y para registrar y consultar ofertas, **para** respaldar acciones comerciales sobre productos que requieren atención. | **5** |
| **59** | **US46** | Gestión de Usuarios | **Como** Administrador, **quiero** registrar y administrar usuarios, **para** controlar quién puede utilizar BodeGo. | **3** |
| **60** | **TS14** | Gestión REST de Negocios y Usuarios | **Como** Developer, **quiero** disponer de operaciones REST para registrar y consultar negocios y administrar usuarios, **para** respaldar la gestión de establecimientos y cuentas autorizadas de BodeGo. | **3** |
| **61** | **US47** | Gestión de Roles y Permisos | **Como** Administrador, **quiero** asignar roles a los usuarios, **para** controlar las acciones que pueden realizar dentro de BodeGo. | **5** |
| **62** | **US48** | Inicio de Sesión Seguro | **Como** usuario registrado, **quiero** autenticarme mediante mis credenciales, **para** acceder a las funcionalidades autorizadas. | **3** |
| **63** | **TS15** | Autenticación y Gestión de Sesiones | **Como** Developer, **quiero** disponer de servicios REST para autenticar usuarios y gestionar sesiones, **para** proteger el acceso a las funcionalidades de BodeGo. | **5** |
| **64** | **US49** | Recuperación y Cambio de Contraseña | **Como** usuario, **quiero** cambiar o recuperar mi contraseña, **para** mantener protegido el acceso a mi cuenta. | **3** |
| **65** | **US50** | Cierre de Sesión y Protección de Cuenta | **Como** usuario autenticado, **quiero** cerrar mi sesión de forma segura, **para** evitar accesos posteriores desde el dispositivo utilizado. | **1** |
| **66** | **TS16** | Roles, Contraseñas y Protección de Acceso | **Como** Developer, **quiero** disponer de servicios REST para gestionar roles, actualizar contraseñas y validar autorizaciones, **para** garantizar que cada usuario acceda únicamente a las operaciones permitidas. | **5** |

---

# Capítulo IV: Product Design

## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines

El sistema de diseño de **BodeGo** se basa en una estética moderna, limpia y funcional, orientada a facilitar la gestión diaria de inventarios en minimarkets. La interfaz busca mostrar la información de manera clara y ordenada, permitiendo que Administradores y Empleados puedan identificar rápidamente el estado del stock, los productos próximos a vencer y las operaciones realizadas.

- **Branding & Tono:**
  - **Tono:** Profesional, confiable y práctico.
  - **Lenguaje:** Claro, directo y orientado a las operaciones del minimarket.
  - **Personalidad:** BodeGo se presenta como una herramienta de apoyo para mantener el inventario organizado y reducir pérdidas por productos perecibles.
  - **Identidad:** Se prioriza la sensación de control, rapidez y seguridad en las operaciones.

- **Typography:**
  - **Fuente principal:** Hanken Grotesk.
  - **Títulos:** Uso de pesos Bold o SemiBold para destacar nombres de módulos, indicadores y datos importantes.
  - **Contenido:** Peso Regular para tablas, descripciones y textos informativos.
  - **Etiquetas:** Tamaño reducido para estados, categorías, fechas y datos secundarios.
  - Se mantiene una jerarquía visual clara entre títulos, subtítulos, indicadores y contenido.

- **Colors:**
  - **Principal:** Azul `#2563EB`, utilizado para botones, acciones principales, elementos seleccionados y enlaces.
  - **Secundario:** Azul oscuro `#0F172A`, empleado principalmente en textos importantes y elementos de alto contraste.
  - **Terciario:** Verde `#10B981`, utilizado para indicar estados correctos, productos activos, ingresos o acciones exitosas.
  - **Neutral:** Gris `#64748B`, empleado en información secundaria, iconos y etiquetas.
  - **Rojo:** Utilizado para alertas críticas, productos vencidos, stock crítico y errores.
  - **Amarillo/Naranja:** Utilizado para advertencias y productos próximos a vencer.

- **Spacing:**
  - Los módulos mantienen márgenes y separaciones constantes entre tarjetas, tablas y formularios.
  - Las tarjetas utilizan bordes suavemente redondeados.
  - La información se distribuye mediante bloques y columnas para evitar la saturación visual.
  - Los indicadores principales cuentan con mayor espacio para facilitar su identificación.

- **Iconografía:**
  - Se utilizan iconos simples acompañados de texto para facilitar la comprensión.
  - Los iconos permiten diferenciar rápidamente acciones como registrar ingreso, registrar salida, registrar merma, consultar inventario o acceder a reportes.
  - Los colores de los iconos también ayudan a comunicar el estado de cada operación.

---

### 4.1.2. Web Style Guidelines

BodeGo está diseñado principalmente como una **aplicación web de gestión interna**, por lo que la interfaz busca aprovechar el espacio disponible en computadoras utilizadas en caja, oficina o almacén.

Los diseños presentan una navegación lateral permanente y un área principal destinada a dashboards, tablas, gráficos y operaciones.

- **Diseño Responsivo:**
  - **En Computadora (Desktop):** Se mantiene un menú lateral fijo y el contenido se distribuye utilizando tarjetas, tablas y columnas.
  - **En Tablet:** El contenido puede reducir el número de columnas y reorganizar tarjetas de forma vertical.
  - **En Celular:** Las tarjetas y controles se presentan en una sola columna y el menú lateral puede transformarse en un menú desplegable.

- **Componentes Web:**
  - **Botón Primario:** Fondo azul para acciones principales como “Nuevo producto”, “Registrar operación” o “Lanzar oferta”.
  - **Botón Secundario:** Fondo claro o borde azul para acciones complementarias como editar, ver detalle o cancelar.
  - **Botón de Peligro:** Rojo para acciones relacionadas con eliminación, errores o estados críticos.

- **Tarjetas de Indicadores:**
  - Presentan información resumida como productos totales, stock crítico, productos por vencer y mermas.
  - Incluyen iconos y colores que ayudan a diferenciar cada indicador.
  - Se ubican principalmente en la parte superior de los dashboards.

- **Tablas:**
  - Se utilizan para mostrar productos, lotes, empleados y operaciones.
  - Presentan columnas claramente separadas.
  - Incorporan estados mediante etiquetas de colores como **Activo**, **Crítico**, **Próximo a vencer** o **Vencido**.
  - Pueden incluir buscadores, filtros y paginación.

- **Formularios:**
  - Campos de entrada con bordes simples y etiquetas visibles.
  - Los formularios deben mostrar mensajes claros cuando un dato sea incorrecto.
  - Las acciones de guardar o registrar deben destacar sobre las opciones secundarias.

- **Navegación:**
  - Barra lateral ubicada en el lado izquierdo.
  - Logo de BodeGo ubicado en la parte superior.
  - El módulo seleccionado se diferencia mediante color de fondo o texto destacado.
  - En la parte inferior se muestra información del usuario y la opción para cerrar sesión.

- **Interacción:**
  - Los cambios de estado deben mostrarse inmediatamente después de registrar una operación.
  - Las acciones importantes deben generar mensajes de confirmación.
  - Los elementos interactivos deben cambiar visualmente al pasar el cursor.
  - Los gráficos y tablas deben mantener una lectura sencilla sin sobrecargar la pantalla.

- **Accesibilidad:**
  - Alto contraste entre fondo y texto.
  - Los estados no deben identificarse únicamente mediante colores, sino también mediante texto o iconos.
  - Los botones principales deben tener un tamaño suficiente para ser identificados fácilmente.

---

## 4.2. Information Architecture
### 4.2.1. Organization Systems

La arquitectura de información de BodeGo se organiza mediante sistemas **jerárquicos, secuenciales y matriciales**, permitiendo que cada usuario pueda acceder rápidamente a las funciones correspondientes a su rol.

Los mockups muestran una clara separación entre el Dashboard del Administrador y el Dashboard del Empleado, además de módulos especializados para inventario, vencimientos, alertas, reportes, empleados y configuración.

- **Sistema Jerárquico:**
  - **Dashboard Administrador:** Primero se muestran indicadores generales como productos totales, stock crítico, productos por vencer y mermas. Después se muestran alertas, movimientos, productos vendidos y lotes próximos a vencer.
  - **Dashboard Empleado:** Primero se muestran ingresos, salidas y mermas del día; posteriormente aparecen las operaciones rápidas y el historial diario.
  - **Inventario:** Se muestra primero el catálogo general y posteriormente el detalle de cada producto.
  - **Vencimientos:** Se priorizan primero los productos vencidos o próximos a vencer.

- **Sistema Secuencial:**
  - **Registro de Producto:** Datos generales → categoría → stock → precio → información del lote → guardar.
  - **Registro de Ingreso:** Seleccionar producto → ingresar cantidad → registrar lote → confirmar.
  - **Registro de Salida:** Seleccionar producto → indicar cantidad → confirmar operación.
  - **Registro de Merma:** Seleccionar producto → cantidad → motivo → confirmar registro.
  - **Gestión de Vencimiento:** Identificar producto → revisar días restantes → seleccionar acción → actualizar inventario.

- **Sistema Matricial:**
  - **Inventario:** Producto + categoría + estado.
  - **Vencimientos:** Producto + lote + fecha de vencimiento + estado.
  - **Operaciones:** Tipo de operación + empleado + fecha + producto.
  - **Empleados:** Nombre + rol + turno + estado.
  - **Reportes:** Fecha + categoría + producto + tipo de movimiento.

- **Esquemas de Categorización:**
  - **Por Rol:** Administrador y Empleado.
  - **Por Función:** Dashboard, Inventario, Vencimientos, Alertas, Reportes, Empleados y Configuración.
  - **Por Estado:** Activo, stock bajo, stock crítico, próximo a vencer y vencido.
  - **Cronológico:** Las operaciones y alertas se presentan comenzando por las más recientes.
  - **Por Prioridad:** Los productos con mayor riesgo de vencimiento o falta de stock aparecen primero.

---

### 4.2.2. Labeling Systems

El sistema de etiquetado de BodeGo utiliza palabras breves y relacionadas directamente con las actividades realizadas en un minimarket. El objetivo es que Administradores y Empleados puedan reconocer cada función sin conocimientos técnicos.

## Etiquetas Principales de Navegación

- **Dashboard:** Resumen del estado actual del minimarket.
- **Inventario:** Gestión y consulta de productos y stock.
- **Vencimientos:** Control de productos y lotes próximos a caducar.
- **Alertas:** Notificaciones sobre situaciones que requieren atención.
- **Reportes:** Visualización de métricas e indicadores del negocio.
- **Empleados:** Gestión del personal y permisos.
- **Configuración:** Ajustes generales del sistema.

## Etiquetas de Acciones

- **“Nuevo producto”**: Registra un producto en el inventario.
- **“Registrar ingreso”**: Añade unidades al stock.
- **“Registrar salida”**: Registra productos que salen del inventario.
- **“Registrar merma”**: Registra productos perdidos, dañados o vencidos.
- **“Consultar inventario”**: Permite revisar productos disponibles.
- **“Lanzar oferta”**: Permite aplicar una estrategia de liquidación.
- **“Ver producto”**: Abre información detallada del producto.
- **“Editar”**: Permite modificar información registrada.

## Etiquetas Contextuales

- **Éxito:** “Operación registrada correctamente”.
- **Stock bajo:** “Quedan pocas unidades disponibles”.
- **Stock crítico:** “Producto con stock crítico”.
- **Próximo a vencer:** “Producto próximo a vencer”.
- **Vencido:** “Producto vencido”.
- **Error:** “No se pudo completar la operación. Inténtalo nuevamente”.

---

### 4.2.3. SEO Tags and Meta Tags

En esta sección se definen los principales **SEO Tags y Meta Tags** utilizados en BodeGo, tanto para la **Landing Page** como para las páginas principales de la **Web Application**.

El objetivo es mejorar la identificación del sitio en los motores de búsqueda y mantener una estructura clara en los títulos y descripciones de cada página. En el caso de las secciones internas de la aplicación, se evita su indexación debido a que contienen información privada del minimarket.

### Landing Page

La Landing Page es la página pública principal de BodeGo y está orientada a presentar la solución, sus beneficios y funcionalidades.

| Tag | Valor |
|---|---|
| **Title** | BodeGo \| Gestión de Inventario para Minimarkets |
| **Description** | BodeGo es una plataforma web que ayuda a los minimarkets a controlar su stock, gestionar productos perecibles, reducir mermas y supervisar sus operaciones diarias. |
| **Keywords** | BodeGo, gestión de inventario, minimarket, control de stock, productos perecibles, control de vencimientos, mermas, inventario digital |
| **Author** | Equipo BodeGo |
| **Robots** | index, follow |
| **Language** | es |
| **Viewport** | width=device-width, initial-scale=1.0 |

**Implementación:**

```html
<title>BodeGo | Gestión de Inventario para Minimarkets</title>

<meta
  name="description"
  content="BodeGo es una plataforma web que ayuda a los minimarkets a controlar su stock, gestionar productos perecibles, reducir mermas y supervisar sus operaciones diarias."
/>

<meta
  name="keywords"
  content="BodeGo, gestión de inventario, minimarket, control de stock, productos perecibles, control de vencimientos, mermas, inventario digital"
/>

<meta name="author" content="Equipo BodeGo" />
<meta name="robots" content="index, follow" />
<meta name="language" content="Spanish" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

---

### Web Application

Las páginas internas de BodeGo están orientadas al uso de Administradores y Empleados. Debido a que contienen información operativa y requieren autenticación, no deben ser indexadas por los motores de búsqueda.

| Página | Title | Description | Keywords | Author | Robots |
|---|---|---|---|---|---|
| **Inicio de Sesión** | Iniciar Sesión \| BodeGo | Accede a BodeGo para gestionar el inventario, productos, vencimientos y operaciones de tu minimarket. | BodeGo, iniciar sesión, inventario minimarket, gestión de stock | Equipo BodeGo | noindex, nofollow |
| **Dashboard Administrador** | Dashboard Administrador \| BodeGo | Visualiza el estado general del inventario, alertas, productos por vencer y operaciones del minimarket. | dashboard, BodeGo, inventario, stock, alertas, vencimientos | Equipo BodeGo | noindex, nofollow |
| **Inventario** | Inventario \| BodeGo | Consulta y administra los productos, categorías, stock y estado del inventario del minimarket. | inventario, productos, stock, BodeGo, minimarket | Equipo BodeGo | noindex, nofollow |
| **Vencimientos** | Control de Vencimientos \| BodeGo | Supervisa lotes y productos próximos a vencer para reducir pérdidas y mejorar la rotación del inventario. | vencimientos, productos perecibles, lotes, mermas, BodeGo | Equipo BodeGo | noindex, nofollow |
| **Alertas** | Centro de Alertas \| BodeGo | Revisa alertas relacionadas con stock crítico, productos próximos a vencer y operaciones del minimarket. | alertas, stock crítico, vencimientos, BodeGo | Equipo BodeGo | noindex, nofollow |
| **Reportes** | Reportes y Analítica \| BodeGo | Consulta reportes e indicadores sobre inventario, movimientos, productos y mermas del minimarket. | reportes, analítica, inventario, mermas, stock, BodeGo | Equipo BodeGo | noindex, nofollow |
| **Empleados** | Gestión de Empleados \| BodeGo | Administra empleados, roles, permisos y actividad operativa dentro del minimarket. | empleados, roles, permisos, personal, BodeGo | Equipo BodeGo | noindex, nofollow |
| **Dashboard Empleado** | Dashboard Empleado \| BodeGo | Consulta operaciones diarias y accede al registro de ingresos, salidas y mermas del inventario. | empleado, operaciones, inventario, ingresos, salidas, mermas | Equipo BodeGo | noindex, nofollow |
| **Operaciones** | Operaciones de Inventario \| BodeGo | Registra ingresos, salidas y mermas de productos para mantener actualizado el stock del minimarket. | operaciones, ingresos, salidas, mermas, stock, BodeGo | Equipo BodeGo | noindex, nofollow |

---

### Consideraciones de Indexación

La **Landing Page** utiliza:

```html
<meta name="robots" content="index, follow" />
```

Esto permite que los motores de búsqueda puedan encontrar y mostrar BodeGo en los resultados de búsqueda.

Por otro lado, las páginas internas de la **Web Application** utilizan:

```html
<meta name="robots" content="noindex, nofollow" />
```

Esto evita que páginas como Dashboard, Inventario, Empleados, Reportes u Operaciones sean indexadas, ya que contienen información interna y requieren autenticación para acceder.

---

### 4.2.4. Searching Systems

El sistema de búsqueda de BodeGo permite localizar rápidamente productos, lotes, empleados y operaciones, reduciendo el tiempo necesario para revisar grandes cantidades de información.

- **Herramientas de Búsqueda:**
  - **Barra de búsqueda:** Disponible principalmente en Inventario y otras pantallas con grandes cantidades de registros.
  - **Filtro por categoría:** Permite visualizar productos pertenecientes a una categoría determinada.
  - **Filtro por estado:** Permite mostrar productos activos, con stock bajo, críticos o vencidos.
  - **Filtro por fechas:** Utilizado en reportes, operaciones y vencimientos.
  - **Filtro por lote:** Facilita la identificación de productos perecibles.

- **Búsqueda en Inventario:**
  - Código del producto.
  - Nombre.
  - Categoría.
  - Estado.
  - Cantidad disponible.

- **Búsqueda en Vencimientos:**
  - Producto.
  - Número de lote.
  - Fecha de vencimiento.
  - Días restantes.
  - Nivel de prioridad.

- **Visualización de Resultados:**
  - Los resultados se presentan principalmente mediante tablas.
  - Los estados importantes se identifican mediante colores y etiquetas.
  - Los resultados pueden organizarse por prioridad o fecha de vencimiento.
  - Cuando no existan coincidencias se puede mostrar: **“No se encontraron resultados con los filtros seleccionados.”**

---

### 4.2.5. Navigation Systems

El sistema de navegación de BodeGo busca reducir la cantidad de pasos necesarios para acceder a las principales funciones del minimarket. La navegación se adapta de acuerdo con los permisos del Administrador y del Empleado.

## Estructura de Navegación del Administrador

La barra lateral puede incluir:

**Dashboard | Inventario | Vencimientos | Alertas | Reportes | Empleados | Configuración**

El Administrador tiene acceso a funciones de supervisión, análisis y configuración.

## Estructura de Navegación del Empleado

La navegación del Empleado debe concentrarse principalmente en las operaciones necesarias durante su jornada:

**Dashboard | Inventario | Operaciones**

Desde el Dashboard también dispone de accesos rápidos para:

- Registrar ingreso.
- Registrar salida.
- Registrar merma.
- Consultar inventario.

## Técnicas de Navegación

- **Menú lateral:** Permite desplazarse entre módulos sin regresar al inicio.
- **Acciones rápidas:** Permiten realizar las operaciones más frecuentes desde el Dashboard.
- **Breadcrumbs o rutas:** Facilitan regresar desde el detalle de un producto hacia el inventario.
- **Paginación:** Utilizada en tablas con gran cantidad de productos, empleados u operaciones.
- **Filtros:** Permiten reducir el contenido sin cambiar de pantalla.

## Estados de Navegación

- **Cargando:** Se muestran indicadores visuales mientras se obtiene la información.
- **Sin resultados:** Se informa cuando una búsqueda o filtro no tiene coincidencias.
- **Error:** Se muestra un mensaje indicando que no fue posible cargar la información.
- **Operación exitosa:** Se confirma inmediatamente después de registrar un ingreso, salida o merma.
- **Alerta crítica:** Los elementos que necesitan atención inmediata se destacan mediante rojo.
- **Advertencia:** Los productos próximos a vencer o con stock bajo se identifican con amarillo o naranja.

---

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe

![WireframeL1](Recursos/images/Landing1.png)
---
![WireframeL2](Recursos/images/Landing2.png)
---
![WireframeL3](Recursos/images/Landing3.png)
---
![WireframeL4](Recursos/images/Landing4.png)
---
![WireframeL5](Recursos/images/Landing5.png)
---

### 4.3.2. Landing Page Mock-ups

![LPMock-Up1](Recursos/images/LandingPage-mockup1.jpg)
---

![LPMock-Up2](Recursos/images/LandingPage-mockup2.jpg)
---

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes

![Wireframe 1](Recursos/images/WF1.png)

---

![Wireframe 2](Recursos/images/WF2.png)

---

![Wireframe 3](Recursos/images/WF3.png)

---

![Wireframe 4](Recursos/images/WF4.png)

---

![Wireframe 5](Recursos/images/WF5.png)

---

![Wireframe 6](Recursos/images/WF6.png)

---

![Wireframe 7](Recursos/images/WF7.png)

---

![Wireframe 8](Recursos/images/WF8.png)

---

![Wireframe 9](Recursos/images/WF9.png)

---

![Wireframe 10](Recursos/images/WF10.png)

---

![Wireframe 11](Recursos/images/WF11.png)

---

![Wireframe 12](Recursos/images/WF12.png)

---

![Wireframe 13](Recursos/images/WF13.png)

---

![Wireframe 14](Recursos/images/WF14.png)

---
enlace: https://www.figma.com/design/lkkyQ42TCu70ZypY4hiuMi/Figma-Proxy?node-id=4-2&t=ZKhGhyVBP4tT2C8g-1

### 4.4.2. Web Applications Wireflow Diagrams
![Wireflow 0](Recursos/images/Wireflow_App.png)

---

enlace: https://www.figma.com/design/lkkyQ42TCu70ZypY4hiuMi/Figma-Proxy?node-id=9-8766&t=ZKhGhyVBP4tT2C8g-1

---

### 4.4.3. Web Applications Mock-ups
![Mockup App 1](Recursos/images/Mockup-App1.png)

---

![Mockup App 2](Recursos/images/Mockup-App2.png)

---

![Mockup App 3](Recursos/images/Mockup-App3.png)

---

![Mockup App 4](Recursos/images/Mockup-App4.png)

---

![Mockup App 5](Recursos/images/Mockup-App5.png)

---

![Mockup App 6](Recursos/images/Mockup-App6.png)

---

![Mockup App 7](Recursos/images/Mockup-App7.png)

---

![Mockup App 8](Recursos/images/Mockup-App8.png)

---

![Mockup App 9](Recursos/images/Mockup-App9.png)

---

![Mockup App 10](Recursos/images/Mockup-App10.png)

---

![Mockup App 11](Recursos/images/Mockup-App11.png)

---

![Mockup App 12](Recursos/images/Mockup-App12.png)

---

![Mockup App 13](Recursos/images/Mockup-App13.png)

---

![Mockup App 14](Recursos/images/Mockup-App14.png)

---
Enlace de Figma: https://www.figma.com/design/lkkyQ42TCu70ZypY4hiuMi/Figma-Proxy?node-id=4-2&t=ZKhGhyVBP4tT2C8g-1
---

### 4.4.4. Web Applications User Flow Diagrams

## LEYENDA

![Leyenda Flow Diagram](Recursos/images/LEYENDA.jpg)

## FLUJO DE USUARIO

![Flujo de Usuario Flow Diagram](Recursos/images/FLUJO%20DE%20USUARIO.jpg)

## FLUJO DE ADMINISTRADOR

![Flujo de Administrador Flow Diagram](Recursos/images/FLUJO%20DE%20ADMINISTRADOR.jpg)

## FLUJO DE EMPLEADO

![Flujo de Empleado Flow Diagram](Recursos/images/FLUJO%20DE%20EMPLEADO.jpg)

---

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture
### 4.6.1. Design-Level EventStorming
![Estructura / Captura 1](Recursos/images/es1.png)

---

![Estructura / Captura 2](Recursos/images/es2.png)

---

![Estructura / Captura 3](Recursos/images/es3.png)

---

![Estructura / Captura 4](Recursos/images/es4.png)

---

![Estructura / Captura 5](Recursos/images/es5.png)

---

![Estructura / Captura 6](Recursos/images/es6.png)

---

![Estructura / Captura 7](Recursos/images/es7.png)

---

![Estructura / Captura 8](Recursos/images/es8.png)

---

![Estructura / Captura 9](Recursos/images/es9.png)

---

![Estructura / Captura 9](Recursos/images/es91.png)

---

![Estructura / Captura 9](Recursos/images/es92.png)

---

![Estructura / Captura 9](Recursos/images/es93.png)

---
[Nuestro link del miro](https://miro.com/app/board/uXjVHm55KfI=/)
---

### 4.6.2. Software Architecture Context Diagram
![Context](Recursos/images/SystemContext.png)
### 4.6.3. Software Architecture Container Diagrams
![Container](Recursos/images/Containers.png)

### 4.6.4. Software Architecture Components Diagrams
![Components-Worker](Recursos/images/Components-Worker.png)

---

![Components-API](Recursos/images/Components-API.png)
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
Los diagramas de clases de BodeGo representan las principales entidades, atributos, comportamientos y relaciones del sistema.
Siguiendo los principios de Diseño Orientado al Dominio (DDD), la solución se divide en distintos Contextos Acotados (Bounded Contexts), manteniendo separadas sus responsabilidades y reduciendo el acoplamiento entre módulos.

- **Diagrama de clases**
  ![Diagrama de clases](Recursos/images/DiagramaClases.jpg)


- **Configuración Empresarial y Acceso BC:**

  ![DiagramaCL / BC1](Recursos/images/dcl1_confacceso.png)

---

- **Catálogo e Inventario BC:**

  ![DiagramaCL / BC2](Recursos/images/dcl2_catinv.png)

---

- **Operaciones diarias y Mermas BC:**

  ![DiagramaCL / BC3](Recursos/images/dcl3_opemerma.png)

---

- **Ofertas estratégicas BC:**

  ![DiagramaCL / BC4](Recursos/images/dcl4_recoferta.png)

---

- **Auditoría y Seguimiento BC:**

  ![DiagramaCL / BC5](Recursos/images/dcl5_audseg.png)

## 4.8. Database Design
Se presenta el diseño de la base de datos relacional que permitirá graficar la información para los objetos de cada Bounded Context identificados en la aplicación BodeGo.

 ![DiagramaDB / BC1](Recursos/images/bd-complete.jpeg)
 
### 4.8.1. Database Diagrams
El siguiente diagrama de base de datos Entity-Relationship contiene las tablas, columnas y tipos de datos que establecen las relaciones entre las entidades del sistema separados por Bounded Context.

- **Configuración Empresarial y Acceso BC:**

  ![DiagramaDB / BC1](Recursos/images/d1_confaccesoBC.jpg)

---

- **Catálogo e Inventario BC:**

  ![DiagramaDB / BC2](Recursos/images/d2_catinv.jpg)

---

- **Operaciones diarias y Mermas BC:**

  ![DiagramaDB / BC3](Recursos/images/d3_opmermaBC.jpg)

---

- **Ofertas estratégicas BC:**

  ![DiagramaDB / BC4](Recursos/images/d4_recofertaBC.jpg)

---

- **Auditoría y Seguimiento BC:**

  ![DiagramaDB / BC5](Recursos/images/d5_audsegBC.jpg)

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
Para el desarrollo de BodeGo se establecerán un conjunto de herramientas que permitan mantener la consistencia del proyecto durante su ciclo de vida. Estas configuraciones permitirán que los integrantes del equipo trabajen bajo una misma estructura para el control de versiones, configuración del entorno de desarrollo y posterior despliegue de la aplicación.

### 5.1.1. Software Development Environment Configuration
## . Project Management

- **Discord:** Una herramienta de comunicación y coordinación del equipo. Permite organizar conversaciones por canales, realizar reuniones de voz, compartir avances, resolver dudas y coordinar las actividades relacionadas con el desarrollo de BodeGo.
---
![Logo Discord](Recursos/images/dc1.jpg)
---
Link de inicio de sesión Discord: https://discord.com/

---

Evidencia de uso:

![Reunion Discord](Recursos/images/dc2.jpg)

## . Requirement Management

- **Miro:** Se utilizará como herramienta colaborativa para la gestión y análisis de requisitos de BodeGo. Permitirá organizar visualmente información obtenida durante la investigación, como User Personas, Empathy Maps, User Journey Maps e Impact Mapping.
---

  ![Logo Miro](Recursos/images/miro.png)

  Link de inicio de sesión Miro: https://miro.com/es/

---

- **UXPressia:** Se utilizará para elaborar y documentar artefactos relacionados con la experiencia de usuario, como User Personas y User Journey Maps, permitiendo representar las características, necesidades, objetivos y experiencias de los segmentos de usuarios de BodeGo.
---

  ![Logo UXPressia](Recursos/images/ux.png)

  Link de inicio de sesión UXPressia: https://uxpressia.com/

---

- **Structurizr:** Se utilizará para modelar y documentar la arquitectura de software de BodeGo mediante diagramas basados en el modelo C4. Permitirá representar la estructura general del sistema, sus principales contenedores, componentes y relaciones.
---
![Logo structurizr](Recursos/images/struc.png)
---

## . Product UX/UI Design

- **Figma:** Una herramienta de colaboración que facilita el desarrollo conjunto de wireframes y mockups.
---

  ![Imagen de la entrevista](Recursos/images/figma.png)

  Link de inicio de sesión Figma: https://www.figma.com/es-la/

---

- **LucidChart:** Una herramienta colaborativa que posibilita la creación conjunta de wireframes flow y mockups flow.
---

  ![Imagen de la entrevista](Recursos/images/lucid.png)

  Link de inicio de sesión LucidChart: https://lucid.co/es/lucidchart

---

## . Software Development

- **HTML5:** Es un lenguaje de etiquetado utilizado para crear la estructura de una página web. Se empleará para incluir componentes como texto, imágenes, enlaces, botones y videos.
---

  ![Logo HTML5](Recursos/images/html.png)

  Informacion relacionada: https://www.esic.edu/rethink/tecnologia/html5-que-es-caracteristicas-y-como-funciona-c#:~:text=El%20HTML5%20es%20un%20est%C3%A1ndar,%2C%20estilo%20de%20letra%2C%20etc.

---

- **CSS:** Es un lenguaje de diseño gráfico utilizado para dar formato y estilo a la presentación de los documentos HTML.
---
  ![Logo CSS](Recursos/images/css.png)

  Informacion relacionada: https://developer.mozilla.org/es/docs/Web/CSS

---

- **JavaScript:** Es un lenguaje de programación dinámico orientado a objetos que se utilizará para implementar funcionalidades e interactividad en la aplicación web.
---
  ![Logo Javascript](Recursos/images/js.png)

  Informacion relacionada: https://developer.mozilla.org/es/docs/Web/JavaScript

---

- **intellJ IDEA** Es un entorno de desarrollo integrado (IDE) diseñado para programar en Java.
---
  ![Logo intellJIdea](Recursos/images/intell.jpg)

  Link de descarga: https://www.jetbrains.com/es-es/idea/download/?section=windows

## . Software Testing

- **Lenguaje Gherkin:** Es un Lenguaje Específico de Dominio (DSL) diseñado para describir el comportamiento esperado del sistema mediante escenarios comprensibles tanto para desarrolladores como para otros integrantes del equipo.

## . Software Documentation

- **GitHub:** Es una plataforma utilizada para el alojamiento y control de versiones del código fuente de un proyecto. Facilita el trabajo colaborativo entre los integrantes del equipo y permite mantener un historial de los cambios realizados.
---
  ![Logo GitHub](Recursos/images/gh6.jpg)

---

## . Software Deployment

- **GitHub Pages:** Es una plataforma que permite realizar despliegues de aplicaciones web directamente desde un repositorio de GitHub.

  ![Logo GitHub Pages](Recursos/images/gh7.png)

---

  Link de inicio: https://github.com/?locale=es-419

---

  Link de descarga: https://github.com/apps/desktop?locale=es-419

---

  **Nuestros repositorios:**

| Nombre del repositorio | Link |
| :--- | :--- |
| Documentación | https://github.com/SirEthan04/Proxy_Open_Source |
| LandingPage | https://github.com/SirEthan04/Proxy_Open_Source_LandingPage |
| FrontEnd | https://github.com/SirEthan04/Proxy_Open_Source_Front-end |
| WebApplication | https://github.com/SirEthan04/Proxy_Open_Source_Web-Application |

---
### 5.1.2. Source Code Management
---

![Estructura / Captura 9](Recursos/images/gh9.jpg)

---
## GitFlow Implementation
Para organizar el trabajo colaborativo del equipo se utilizará **GitFlow** como modelo de ramificación, empleando Git para el control de versiones.
Este modelo permitirá separar el código estable de BodeGo de las funcionalidades que se encuentren en desarrollo, facilitando que diferentes integrantes del equipo puedan trabajar simultáneamente en módulos como inventario, productos, lotes, mermas, ofertas, usuarios y reportes.

### Main Branch

La rama main será la rama principal y contendrá las versiones estables de BodeGo que se encuentren preparadas para producción.
No se desarrollarán funcionalidades directamente sobre esta rama. Los cambios llegarán a main mediante la integración de ramas release y hotfix.

## Develop Branch

La rama develop contendrá los cambios más recientes del proyecto que serán incluidos en próximas versiones de BodeGo.
Funcionará como punto de integración de las diferentes funcionalidades desarrolladas por el equipo. Antes de que una versión sea incorporada a main, las nuevas características serán integradas y verificadas previamente en develop.

## Feature Branch

Las ramas feature serán utilizadas para desarrollar nuevas funcionalidades de **BodeGo** de forma independiente.
Cada característica deberá contar con su propia rama, permitiendo que los integrantes del equipo trabajen en diferentes módulos sin modificar directamente la rama develop.

## Release Branch

Las ramas release serán utilizadas cuando las funcionalidades previstas para una nueva versión de BodeGo ya hayan sido integradas en develop.
Su objetivo será preparar una versión antes de pasarla a producción. Durante esta etapa podrán realizarse pruebas, ajustes menores y correcciones de errores sin impedir que el equipo continúe desarrollando nuevas características en develop.

## Hotfix Branch

Las ramas hotfix serán utilizadas para corregir errores importantes encontrados en una versión de BodeGo que ya se encuentre en producción.
Estas ramas permitirán solucionar rápidamente un problema sin interrumpir el desarrollo de nuevas funcionalidades que continúe realizándose en develop.

## Support Branch

Para la primera etapa del desarrollo de BodeGo no se utilizarán ramas supoort, debido a que el proyecto no contempla inicialmente el mantenimiento simultáneo de múltiples versiones antiguas del producto.
En caso de que en el futuro BodeGo deba mantener diferentes versiones en producción, podrán incorporarse ramas de soporte específicas.

## Conventional Commits

Para mantener un historial de cambios claro y comprensible, los mensajes de los commits del proyecto BodeGo seguirán la especificación Conventional Commits.

Esta convención permitirá identificar rápidamente el propósito de cada modificación realizada por los integrantes del equipo.¿

La estructura general será: git commit -m <type>[optional scope]: <title>“ -m “<description” 

### Tipos de Conventional Commits
- feat: Incorporación de una nueva funcionalidad.
- fix: Corrección de un error. 
- docs: Cambios en documentación. 
- style: Cambios de formato que no modifican el funcionamiento. 
- refactor: Reestructuración del código sin agregar funcionalidades ni corregir errores. 
- test: Adición o modificación de pruebas. 
- chore: Tareas de mantenimiento o configuración. 
- perf: Mejoras relacionadas con el rendimiento. 

### 5.1.3. Source Code Style Guide & Conventions
Como norma general, todo el código desarrollado para BodeGo deberá utilizar nombres en inglés. Esto incluye variables, funciones, métodos, clases, archivos, atributos y demás elementos utilizados durante el desarrollo.

La finalidad de estas reglas es mantener un código ordenado y fácil de entender para todos los integrantes del equipo.

---

HTML

Use Lowercase Element Names

Los elementos HTML se escribirán en minúsculas.

```html
<section>
    <h2>Inventory</h2>
    <p>Available products</p>
</section>
```

Close All HTML Elements

Todos los elementos HTML que necesiten una etiqueta de cierre deberán cerrarse correctamente.

```html
<section>
    <h2>Inventory</h2>
    <p>Available products</p>
</section>
```

Use Lowercase Attribute Names

Los atributos HTML también se escribirán en minúsculas.

```html
<a href="/inventory">View inventory</a>
```

Use Alternative Text for Images

Las imágenes utilizadas en BodeGo deberán incluir el atributo alt para indicar brevemente su contenido.

```html
<img
    src="assets/bodego-logo.png"
    alt="BodeGo logo">
```

Use Semantic HTML Elements

Cuando sea posible, se utilizarán etiquetas semánticas para organizar mejor las páginas.
Algunas de las etiquetas que se utilizarán son:

```text
header
nav
main
section
article
footer
```

Spaces and Equal Signs

No se utilizarán espacios innecesarios alrededor del signo igual en los atributos.

Correcto:

```html
<link rel="stylesheet" href="styles.css">
```

Incorrecto:

```html
<link rel = "stylesheet" href = "styles.css">
```


CSS

ID and Class Naming

Las clases e identificadores CSS deberán utilizar nombres claros y relacionados con el elemento que representan.

```css
#inventory {
}

#dashboard {
}

.product-card {
}

.stock-alert {
}
```
Se evitarán nombres poco descriptivos como:

```css
.box1 {
}

.element2 {
}
```

ID and Class Name Style

Para los nombres de clases e identificadores CSS se utilizará kebab-case.

```css
.product-card {
}

.inventory-table {
}

.stock-alert {
}
```

Shorthand Properties

Cuando sea posible, se utilizarán propiedades abreviadas para evitar código innecesario.

En lugar de:

```css
.product-card {
    margin-top: 16px;
    margin-right: 16px;
    margin-bottom: 16px;
    margin-left: 16px;
}
```

Se utilizará:

```css
.product-card {
    margin: 16px;
}
```

Declaration Order

Las propiedades CSS deberán mantenerse ordenadas para facilitar la lectura del código.

```css
.product-card {
    background: white;
    border: 1px solid #e5e7eb;
    border-radius: 8px;
    display: flex;
    margin: 16px;
    padding: 16px;
    text-align: left;
}
```

JavaScript

Use Expanded Syntax

El código JavaScript deberá escribirse de manera clara y ordenada, colocando cada instrucción en una línea diferente cuando sea necesario.

```javascript
function calculateAvailableStock() {
    console.log("Calculating available stock");
}
```
Variable Naming

Las variables utilizarán camelCase y deberán tener nombres descriptivos en inglés.

```javascript
let availableStock = 20;
let productName = "Milk";
let expirationDate = "2026-10-20";
let criticalStockThreshold = 5;
```

Se evitarán nombres poco claros como:

```javascript
let x;
let data1;
let thing;
```

Declaring Variables

Se utilizará const cuando el valor no necesite cambiar.

```javascript
const productId = 10;
const productName = "Milk";
```

Se utilizará let cuando el valor pueda modificarse.

```javascript
let availableStock = 20;

availableStock = availableStock - 1;
```

Function Naming

Las funciones utilizarán camelCase y sus nombres deberán indicar claramente la acción que realizan.

Ejemplos:

```javascript
function registerProduct() {
}
```

```javascript
function calculateStock() {
}
```

```javascript
function showExpirationAlert() {
}
```

Constants

Las constantes globales podrán utilizar UPPER_SNAKE_CASE.

Ejemplos:

```javascript
const MAX_LOGIN_ATTEMPTS = 5;
const DEFAULT_STOCK_THRESHOLD = 10;
```
Java

PascalCase

Las clases utilizarán PascalCase.

```java
public class ProductService {
}
```

```java
public class InventoryService {
}
```

```java
public class BatchService {
}
```

---

camelCase

Los métodos, variables locales, parámetros y atributos utilizarán camelCase.

```java
private int productId;
private String productName;
```
---
Clear Comments

Los comentarios se utilizarán cuando ayuden a entender partes del código que los demas integrantes del grupo no comprendan.

```java
// Checks whether the batch is close to its expiration date.
public boolean isNearExpiration(LocalDate expirationDate) {
    return expirationDate.isBefore(LocalDate.now().plusDays(7));
}
```

---

Single Responsibility

Cada clase deberá encargarse principalmente de una responsabilidad.

- ProductService se encargará de las operaciones relacionadas con productos.
- InventoryService se encargará de las operaciones relacionadas con inventario.
- BatchService se encargará de la gestión de lotes.
- WastageService se encargará del registro y gestión de mermas.

Gherkin

Los escenarios y criterios de aceptación de BodeGo deberán seguir una estructura uniforme y utilizar nombres en inglés.

escriptive and Concise Titles for Scenarios

Los escenarios deberán tener títulos claros que permitan entender rápidamente qué comportamiento se está evaluando.

```gherkin
Feature: User authentication

Scenario: Successful login
    Given the user has an active account
    When the user enters valid credentials
    Then the system should grant access according to the user role
```

Follow the Given-When-Then Structure Consistently

Los escenarios deberán utilizar la estructura Given, When y Then.

- Given: representa la condición inicial.
- When: representa la acción realizada.
- Then: representa el resultado esperado.


Focus on Business-Readable Language

Los escenarios deberán utilizar un lenguaje relacionado con las actividades del minimarket y evitar detalles técnicos de programación.

```gherkin
Scenario: Register damaged product as wastage

    Given the employee finds a damaged product
    When the employee registers the product as wastage
    Then the stock should be updated
    And the wastage should be recorded
```
Add Comments When Necessary

Se podrán agregar comentarios cuando sea necesario explicar el propósito de un escenario.

```gherkin
# This scenario checks the registration of expired products as wastage.

Scenario: Register expired product as wastage

    Given a product batch has expired
    When the employee registers the expired units
    Then the units should be recorded as wastage
    And the stock should be updated
```

### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
## Sprint 1 - Desarrollo de la Landing Page de BodeGo
Durante el Sprint 1, el equipo se enfocó en desarrollar la primera versión funcional de la Landing Page de BodeGo.
El objetivo fue transformar los wireframes y diseños realizados previamente en una página web funcional que permitiera presentar de manera clara la solución propuesta para los minimarkets.

#### 5.2.1.1. Sprint Planning 1

El Sprint Planning permitió organizar y definir las actividades que serían desarrolladas durante el Sprint 1 de BodeGo.

Durante esta reunión, el equipo estableció como objetivo principal desarrollar la primera versión funcional de la Landing Page de BodeGo, con el propósito de presentar la propuesta de valor del producto, sus beneficios, sus principales funcionalidades y un medio de contacto para los visitantes.

| **Sprint #** | **Sprint 1** |
|---|---|
| **Sprint Planning Background** | El Sprint tiene como objetivo desarrollar la primera versión funcional de la Landing Page de BodeGo, enfocándose en la presentación del producto y sus principales características. |
| **Date** | 2026-09-17 |
| **Time** | 5:00 pm |
| **Location** | Discord |
| **Prepared By** | Equipo de desarrollo BodeGo |
| **Attendees (to planning meeting)** | Day / Mateo / Yorch / Johan / Gior |
| **Sprint 0 Review Summary** | No existe un sprint previo, debido a que este es el primer sprint del proyecto. |
| **Sprint 0 Retrospective Summary** | No existe un sprint previo del cual obtener conclusiones o acciones de mejora. |
| **Sprint Goal & User Stories** | US01 – Visualización de la Propuesta de Valor (2 SP); US02 – Consulta de Beneficios de BodeGo (2 SP); US03 – Presentación de Funcionalidades Principales (3 SP); US04 – Explicación del Funcionamiento de BodeGo (2 SP); US05 – Formulario de Contacto Comercial (3 SP). |
| **Sprint 1 Goal** | Desarrollar una Landing Page funcional y responsive para BodeGo que permita a los visitantes conocer la propuesta de valor de la plataforma, sus beneficios, sus principales funcionalidades y su funcionamiento general, además de proporcionar un formulario de contacto para solicitar información adicional. |
| **Sprint 1 Velocity** | 12 Story Points (estimación inicial del trabajo comprometido). |
| **Sum of Story Points** | 12 Story Points. |

#### 5.2.1.2. Aspect Leaders and Collaborators

Durante el Sprint 1 se identificaron los principales aspectos de trabajo necesarios para implementar la Landing Page de BodeGo.

| Team Member (Last Name, First Name) | GitHub Username | Landing Page Structure & Navigation | Product Benefits & Impact | Product Features & Explanation | Contact & Footer Section | Responsive Design |
|---|---|---|---|---|---|---|
| Dany Chavez | Danysss-cmd | L | C | C | - | C |
| Mateo Caldas | Ethan.Matt | C | L | C | - | C |
| Yorch Blanco | Bleim-154 | C | C | L | - | C |
| Johan Saravia | yowuan | - | C | C | L | C |
| Giordano Trejo | igogriogriorgiori | C | C | C | C | L |

#### 5.2.1.3. Sprint Backlog 1

Durante el Sprint 1, las actividades estuvieron orientadas al desarrollo de la primera versión funcional de la Landing Page de BodeGo.

El objetivo principal fue transformar los wireframes y mockups previamente diseñados en una interfaz web funcional que permita comunicar la propuesta de valor del producto, presentar sus principales funcionalidades y captar potenciales usuarios interesados en la solución.

![Evidencia Sprint Backlog n1](https://github.com/SirEthan04/Proxy_Open_Source/blob/main/Recursos/images/EvidenciaSprintBacklog%20N1.jpg)
Enlace: https://trello.com/invite/b/6aac64ebaf51e9bfb4c107de/ATTI7980c4d39c19509f8439a763ed2f3081F674FEDD/bodego

---

| **User Story ID** | **Story Title** | **Task ID** | **Task Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
|---|---|---|---|---|---:|---|---|
| US01 | Visualización de la Propuesta de Valor | TSK001 | Create Landing Page Structure | Crear la estructura inicial de la Landing Page tomando como referencia los wireframes definidos, incluyendo componentes, archivos y estilos generales. | 2 | Dany | Hecho |
| US01 | Visualización de la Propuesta de Valor | TSK002 | Implement Navigation Bar | Implementar la barra de navegación principal con el logo de BodeGo, enlaces de navegación y acceso a las secciones informativas. | 2 | Dany | Hecho |
| US01 | Visualización de la Propuesta de Valor | TSK003 | Implement Hero Section | Desarrollar la sección principal de la Landing Page para comunicar la propuesta de valor de BodeGo mediante un título, descripción e información destacada del producto. | 3 | Dany | Hecho |
| US02 | Consulta de Beneficios de BodeGo | TSK004 | Implement Benefits Section | Implementar la sección de beneficios para presentar las ventajas de BodeGo relacionadas con el control de inventario, reducción de mermas y organización del negocio. | 4 | Mateo | Hecho |
| US03 | Presentación de Funcionalidades Principales | TSK005 | Implement Solutions Section | Desarrollar la sección que presenta las funcionalidades principales de BodeGo, incluyendo inventario, movimientos, alertas y reportes. | 3 | Yorch | Hecho |
| US04 | Explicación del Funcionamiento de BodeGo | TSK006 | Implement How It Works Section | Implementar la sección que explica el funcionamiento general de BodeGo y las actividades que pueden realizar el Administrador y el Empleado. | 3 | Yorch | Hecho |
| US02 | Consulta de Beneficios de BodeGo | TSK007 | Implement Impact Section | Desarrollar la sección de impacto para explicar cómo BodeGo contribuye a mejorar el control de productos y reducir pérdidas operativas. | 2 | Mateo | Hecho |
| US05 | Formulario de Contacto Comercial | TSK008 | Implement Contact Section | Implementar el formulario de contacto para permitir que los visitantes interesados proporcionen sus datos y soliciten información adicional sobre BodeGo. | 3 | Johan | Hecho |
| US05 | Formulario de Contacto Comercial | TSK009 | Implement Footer Section | Implementar el pie de página con información general de BodeGo, enlaces relevantes y datos de contacto. | 2 | Johan | Hecho |
| US01–US05 | Landing Page de BodeGo | TSK010 | Implement Responsive Design | Adaptar las secciones de la Landing Page para su correcta visualización en dispositivos móviles, tablets y computadoras de escritorio. | 5 | Diego | Hecho |

---

#### 5.2.1.4. Development Evidence for Sprint Review
---

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|
| Danysss-cmd/Landing Page Repository | feature/hero-section | 371ee21 | feat: implement BodeGo value proposition section | Desarrollo de la sección principal de la Landing Page para presentar la propuesta de valor de BodeGo y comunicar su propósito a los visitantes. | 17/09/2026 |
| SirEthan04/Landing Page Repository | feature/value-proposition | fa49632 | feat: implement product benefits section | Implementación de la sección de beneficios de BodeGo, destacando el control de inventario, la reducción de pérdidas y la organización operativa del negocio. | 17/09/2026 |
| Bleim-154/Landing Page Repository | feature/solutions-section | 003f372 | feat: implement main product features section | Desarrollo de la sección de funcionalidades principales de BodeGo, presentando las capacidades de inventario, movimientos, alertas y reportes. | 17/09/2026 |
| SirEthan04//Landing Page Repository | feature/impact-section | 7182b63 | feat: implement BodeGo business impact section | Implementación de la sección de impacto para explicar cómo BodeGo contribuye a mejorar la gestión del minimarket y reducir las pérdidas operativas. | 17/09/2026 |
| yowuan/Landing Page Repository | feature/contact-form | e281064 | feat: implement commercial contact form | Desarrollo del formulario de contacto comercial para permitir que los visitantes interesados proporcionen sus datos y soliciten información adicional sobre BodeGo. | 17/09/2026 |
| Diego27-16/Landing Page Repository | feature/footer | dfb92c0 | feat: implement landing page footer section | Implementación del pie de página de BodeGo con información general del producto, enlaces relevantes y datos de contacto. | 17/09/2026 |

---
#### 5.2.1.5. Execution Evidence for Sprint Review
---

![Estructura / Captura 9](Recursos/images/nl1.jpg)

---
![Estructura / Captura 9](Recursos/images/nl2.jpeg)

---
![Estructura / Captura 9](Recursos/images/nl3.jpeg)

---
![Estructura / Captura 9](Recursos/images/nl4.jpeg)

---
![Estructura / Captura 9](Recursos/images/nl5.jpeg)

---
![Estructura / Captura 9](Recursos/images/nl6.jpeg)

---
![Estructura / Captura 9](Recursos/images/nl7.jpeg)

---
![Estructura / Captura 9](Recursos/images/nl8.jpeg)

---
![Estructura / Captura 9](Recursos/images/nl9.jpeg)

---
![Estructura / Captura 9](Recursos/images/nl10.jpeg)

---
![Estructura / Captura 9](Recursos/images/nl11.jpeg)

---

Landing Page Desplegada: https://sirethan04.github.io/Proxy_Open_Source_LandingPage/

---

#### 5.2.1.6. Services Documentation Evidence for Sprint Review
Se ha omitido la sección de la aplicación web debido a que solo se ha desarrollado la Landing Page. Se ofrecerá más información sobre la aplicación en
una etapa posterior del desarrollo.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review
Se ha omitido la sección de la aplicación web debido a que solo se ha desarrollado la Landing Page. Se ofrecerá más información sobre la aplicación en
una etapa posterior del desarrollo.

#### 5.2.1.8. Team Collaboration Insights during Sprint
---

![Estructura / Captura 9](Recursos/images/gh8.png)

---
![Estructura / Captura 9](Recursos/images/ghe.png)

---

### 5.2.2. Sprint 2

## Sprint 2 - Desarrollo del Frontend Web de BodeGo

Durante el Sprint 2, el equipo se enfocó en desarrollar la primera versión funcional del Frontend Web de BodeGo.

El objetivo fue implementar las principales vistas de la aplicación, permitiendo la navegación entre módulos, consulta del inventario, visualización de productos, alertas, reportes y demás funcionalidades definidas para esta etapa.

#### 5.2.2.1. Sprint Planning 2

El Sprint Planning permitió organizar las actividades que serían desarrolladas durante el Sprint 2. En esta reunión se definió como objetivo principal implementar la primera versión funcional del Frontend Web de BodeGo.

| **Sprint #** | **Sprint 2** |
|---|---|
| **Sprint Planning Background** | El Sprint tiene como objetivo desarrollar la primera versión funcional del Frontend Web de BodeGo. |
| **Date** | 2026-10-4 |
| **Time** | 2:00 pm |
| **Location** | Discord |
| **Prepared By** | Equipo de desarrollo BodeGo |
| **Attendees (to planning meeting)** | Dany / Mateo / Jhorch / Johan / Gior |
| **Sprint 1 Review Summary** | Se desarrolló la primera versión funcional de la Landing Page de BodeGo. |
| **Sprint 1 Retrospective Summary** | Se identificó la necesidad de continuar con el desarrollo de la aplicación web manteniendo la estructura visual y responsive. |
| **Sprint Goal & User Stories** | |
| **Sprint 2 Goal** | Desarrollar la primera versión funcional del Frontend Web de BodeGo, implementando las principales vistas y funcionalidades de la aplicación. |
| **Sprint 2 Velocity** | 34 Story Points |
| **Sum of Story Points** | 34 Story Points |

#### 5.2.2.2. Aspect Leaders and Collaborators

Durante el Sprint 2 se identificaron los principales aspectos de trabajo necesarios para implementar el Frontend Web de BodeGo.

| **Team Member (Last Name, First Name)** | **GitHub Username** | **Frontend Structure & Navigation** | **Dashboard & Modules** | **Inventory & Products** | **Alerts & Reports** | **Responsive Design** |
| --------------------------------------- | ------------------- | ----------------------------------- | ----------------------- | ----------------------- | -------------------- | --------------------- |
| Dany Chavez                             | Danysss-cmd         | L                                   | C                       | C                       | C                    | C                     |
| Mateo Caldas                            | Ethan.Matt          | C                                   | L                       | C                       | C                    | C                     |
| Yorch Blanco                            | Bleim-154           | C                                   | C                       | L                       | C                    | C                     |
| Johan Saravia                           | yowuan              | C                                   | C                       | C                       | L                    | C                     |
| Giordano Trejo                          | igogriogriorgiori   | C                                   | C                       | C                       | C                    | L                     |

#### 5.2.2.3. Sprint Backlog 2

Durante el Sprint 2, las actividades estuvieron orientadas al desarrollo de la primera versión funcional del Frontend Web de BodeGo.

El objetivo principal fue implementar las principales vistas de la aplicación y permitir la navegación entre sus diferentes módulos.

![Evidencia Sprint Backlog N2](Recursos/images/Evidencia%20Sprint%20Backlog%20n2.jpg)

Enlace: https://trello.com/invite/b/6aac64ebaf51e9bfb4c107de/ATTI7980c4d39c19509f8439a763ed2f3081F674FEDD/bodego

---

| **User Story ID** | **Story Title** | **Task ID** | **Task Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
|---|---|---|---|---|---:|---|---|
| US06 | Visualización del Dashboard Administrativo | TSK011 | Implement dashboard | Desarrollar el dashboard administrativo mostrando los principales indicadores y datos del negocio. | 4 | Mateo | Hecho |
| US07 | Navegación entre Módulos del Sistema | TSK012 | Implement application navigation | Implementar la navegación entre los principales módulos de la aplicación web. | 3 | Dany | Hecho |
| US08 | Visualización del Módulo de Inventario | TSK013 | Implement inventory view | Desarrollar la vista principal del inventario mostrando los productos y su información disponible. | 4 | Yorch | Hecho |
| US09 | Consulta del Detalle de Producto | TSK014 | Implement product detail | Desarrollar la vista con la información detallada de cada producto seleccionado. | 3 | Johan | Hecho |
| US10 | Visualización de Operaciones del Empleado | TSK015 | Implement employee operations | Desarrollar la vista para consultar las operaciones realizadas por el empleado. | 3 | Johan | Hecho |
| US11 | Búsqueda y Filtrado de Productos | TSK016 | Implement search and filters | Implementar la búsqueda y los filtros necesarios para localizar productos dentro del inventario. | 3 | Yorch | Hecho |
| US12 | Visualización de Alertas Operativas | TSK017 | Implement alerts view | Desarrollar la vista para mostrar las alertas relacionadas con el inventario y la operación del negocio. | 4 | Mateo | Hecho |
| US13 | Visualización de Reportes del Negocio | TSK018 | Implement reports view | Desarrollar la vista para consultar los principales reportes disponibles en la aplicación. | 3 | Gior | Hecho |
| US14 | Gestión Visual de Productos | TSK019 | Implement product management | Desarrollar la interfaz para gestionar visualmente los productos registrados en BodeGo. | 3 | Dany | Hecho |
| US15 | Visualización de Información del Negocio | TSK020 | Implement business information | Desarrollar la vista para mostrar la información general del negocio. | 2 | Gior | Hecho |

#### 5.2.2.4. Development Evidence for Sprint Review.
---

| Repository              | Branch                    | Commit ID | Commit Message                          | Commit Message Body                                                            | Committed on |
| ----------------------- | ------------------------- | --------- | --------------------------------------- | ------------------------------------------------------------------------------ | ------------ |
| Danysss-cmd/Proxy_Open_Source_Front-end | develop      | a4069a8   | feat: add dashboard       | Implementación de la vista principal del dashboard de BodeGo. | 05/10/2026   |
| SirEthan04/Proxy_Open_Source_Front-end | develop | 9e1b553   | feat: add lots products | Implementación de la funcionalidad para gestionar lotes de productos.      | 05/10/2026   |
| Bleim-154/Proxy_Open_Source_Front-end | develop | 5c41ea5   | feat: add iam | Implementación de la gestión de accesos y permisos de los usuarios.      | 05/10/2026   |
| igogriogriorgiori/Proxy_Open_Source_Front-end | develop    | 808803e   | feat: add physical count  | Implementación de la funcionalidad para realizar y gestionar conteos físicos de inventario.         | 06/10/2026   |
| yowuan/Proxy_Open_Source_Front-end | develop     | 4b74f3d   | feature: add movementsV2              | Implementación de la funcionalidad para registrar y consultar movimientos de inventario.                      | 06/10/2026   |

---
#### 5.2.2.5. Execution Evidence for Sprint Review
---

![Estructura / login](Recursos/images/ExecusionReview_login.jpg)

---
![Estructura / panel](Recursos/images/ExecusionReview_panel.jpg)

---
![Estructura / productos](Recursos/images/ExecusionReview_productos.jpg)

---
![Estructura / lotes](Recursos/images/ExecusionReview_lotes.jpg)

---
![Estructura / movimientos](Recursos/images/ExecusionReview_movimientos.jpg)

---
![Estructura / alertas](Recursos/images/ExecusionReview_alertas.jpg)

---
#### 5.2.2.6. Services Documentation Evidence for Sprint Review

Durante el Sprint 2 no se desarrollaron ni documentaron servicios web, debido a que el objetivo principal del sprint fue la implementación del Frontend Web de BodeGo.

La documentación de los servicios y endpoints correspondientes a la lógica del negocio será desarrollada durante el Sprint 3, cuando se inicie la implementación del Backend.

#### 5.2.2.7. Software Deployment Evidence for Sprint Review

Durante el Sprint 2 se realizó el despliegue de la primera versión del Frontend Web de BodeGo utilizando GitHub Pages.

El despliegue permitió publicar la aplicación web y verificar el correcto funcionamiento de las principales vistas desarrolladas durante el sprint.

Actividades realizadas:

1. Integración de los cambios desarrollados en el repositorio del Frontend.
2. Configuración del despliegue mediante GitHub Pages.
3. Publicación de la primera versión del Frontend Web.
4. Verificación de las principales vistas y rutas de la aplicación.
5. Validación del acceso a la aplicación desde el entorno publicado.

**Evidencias del despliegue:**

1. Configuración dentro del Github:
---
![Imagen de la entrevista](Recursos/images/efe3.jpeg)
---
3. Despliegue exitoso del Frontend (Firebase):
---
![Imagen de la entrevista](Recursos/images/efe1.jpeg)
---
5. Verificación y autorizacion en el IntellIdea:
 ---
![Imagen de la entrevista](Recursos/images/efe2.jpeg)
---
7. Aplicación Web publicada.
---
![Imagen de la entrevista](Recursos/images/efe4.jpeg)
---

**Enlace de la aplicación:**  
Enlace: https://proxy-open-source.web.app/dashboard

Únicamente funciona por ahora el enlace para iniciar sesión y muestra los datos de los productos  pero no permite cambiar por el momento porque requiere datos de categoría que no se pueden implementar categorías en mockapi.

#### 5.2.2.8. Team Collaboration Insights during Sprint
---

![Estructura / TeamColaborations](Recursos/images/TeamColaborationsSprint2.jpg)

---

# Conclusiones

## Conclusiones y recomendaciones
El proyecto BodeGo busca solucionar el problema de la falta de control y organización del inventario en los minimarkets, especialmente en la gestión de productos perecibles, diferencias de stock y pérdidas ocasionadas por vencimientos. A través de una plataforma web de gestión, se permite que los Administradores y Empleados puedan realizar sus actividades de manera más ordenada, rápida y eficiente.

Las validaciones realizadas permitieron confirmar que los usuarios presentan dificultades al utilizar métodos manuales como cuadernos, archivos de Excel o revisiones físicas constantes. Por ello, funcionalidades como el control de inventario, alertas de vencimiento, reportes y gestión de roles representan una solución alineada con las necesidades identificadas durante el proceso de investigación.

La aplicación busca ofrecer una experiencia sencilla e intuitiva, enfocándose en reducir el tiempo empleado en tareas operativas y mejorar la toma de decisiones dentro del minimarket. Entre sus principales características destacan:

- Control actualizado del inventario.
- Alertas sobre productos próximos a vencer.
- Reportes para conocer el estado del negocio.
- Gestión de usuarios según sus responsabilidades.

Estas funcionalidades están diseñadas para disminuir los errores en el registro de productos, evitar pérdidas innecesarias y brindar mayor visibilidad sobre el estado real del inventario. De esta manera, BodeGo permite que los Administradores puedan tomar decisiones más oportunas y que los Empleados puedan realizar sus tareas de forma rápida y organizada.

---

# Video About-the-Team

---

# Bibliografía

---

# Anexos
---
Enlace de Figma: https://www.figma.com/design/lkkyQ42TCu70ZypY4hiuMi/Figma-Proxy?node-id=4-2&t=ZKhGhyVBP4tT2C8g-1
---
Nuestro link del miro: https://miro.com/app/board/uXjVHm55KfI=/
---
Nuestro repositorio de documentación: https://github.com/SirEthan04/Proxy_Open_Source
---
Nuestro repositorio de landingpage: https://github.com/SirEthan04/Proxy_Open_Source_LandingPage
---
Nuestro repositorio de frontend: https://github.com/SirEthan04/Proxy_Open_Source_Front-end
---
Nuestro repositorio de web aplication: https://github.com/SirEthan04/Proxy_Open_Source_Web-Application
---
