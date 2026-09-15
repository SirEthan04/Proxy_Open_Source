# Carátula

<p align="center">
  <img src="http://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" width="100" alt="Descripción">
</p>

<p align="center"><b>Universidad Peruana de Ciencias Aplicadas S.A.C.</b></p>
<p align="center"><b>Ingeniería de Software</b></p>
<p align="center"><b>Ciclo: 5</b></p>
<p align="center"><b>1ASI0729-2620</b></p>
<p align="center"><b>Desarrollo de Aplicaciones Open Source</b></p>
<p align="center"><b>NRC: 7760</b></p>
<p align="center"><b>Docente: Juan Antonio Flores Moroco</b></p>

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
| U202421082 | Saravia Hiso, Johan Álvaro |
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
  * [5.3. Validation Interviews](#53-validation-interviews)

    * [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    * [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    * [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  * [5.4. Video About-the-Product](#54-video-about-the-product)

* [Conclusiones](#conclusiones)

  * [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

* [Video About-the-Team](#video-about-the-team)

* [Bibliografía](#bibliografía)

* [Anexos](#anexos)


---

# Student Outcome

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
| Soy un estudiante de 19 años cursando el quito ciclo de la carrera de Ingeniería de Software. Considero que mi capacidad de tener un enfoque analítico y la eficiencia de desarrollar una solución eficiente. Mis habilidades blandas me permiten empatizar con los usuarios y acompañado de mi resiliencia, compromiso y productividad me permiten realizar propuestas mas estructuradas y optimas. |
| Foto |

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
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores

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
| <br><br><br><br><br><br><br><br><br><br><br><br> |
| **Nombres y apellidos:**  <br>**Edad:** 28  <br>**Distrito:** San Martin de Porrez  <br>**Resumen de la entrevista:** Lucía, de 28 años, trabaja como administradora de un minimarket en San Martín de Porres. Ella comenta que el control del inventario se realiza mediante un sistema POS, reportes en Excel y conteos físicos en las góndolas y el almacén. Sin embargo, existen diferencias frecuentes entre el stock registrado en el sistema y la cantidad real de productos, principalmente porque algunos productos dañados o retirados no siempre son registrados correctamente. <br><br>El control de los productos próximos a vencer se realiza de forma manual, revisando las fechas y aplicando el método FEFO, que consiste en colocar adelante los productos que vencen primero. A pesar de esto, suelen tener pequeñas pérdidas semanales por productos vencidos, especialmente yogures, embutidos y pan de molde. Para reducir estas pérdidas, Lucía coloca los productos próximos a vencer en zonas más visibles y aplica descuentos cuando faltan pocos días para su vencimiento. <br><br>Además, la comunicación sobre incidencias del inventario se realiza mediante el sistema, guías de remisión y un grupo de WhatsApp. Lucía considera que sería muy útil contar con una aplicación móvil que permita escanear códigos de barras, revisar el stock, las fechas de vencimiento y los pedidos en camino, además de recibir alertas cuando un producto esté por agotarse o próximo a vencer. <br><br>**URL:** |

| |
|---|
| ![Imagen de la entrevista](RUTA-DE-LA-IMAGEN) |
| **Nombres y apellidos:**  <br>**Edad:**  <br>**Distrito:**  <br><br>**Resumen de la entrevista:**  <br>Jimmy, administrador de un pequeño minimarket, comenta que actualmente controla el inventario de forma mixta: registra diariamente los movimientos en un cuaderno y, al finalizar la semana, pasa la información a una plantilla de Excel. Sin embargo, uno de los principales problemas es que durante las horas de mayor venta no siempre se registran correctamente todos los productos, lo que genera diferencias entre el stock registrado y el stock real. <br><br>El control de los productos próximos a vencer se realiza de manera manual. Los trabajadores revisan los estantes y el almacén mientras reponen o limpian los productos. A pesar de estas revisiones, se presentan pérdidas una o dos veces al mes, principalmente en productos como lácteos y panes que pueden quedar poco visibles al fondo de los estantes. <br><br>Cuando un producto está próximo a vencer o tiene poca rotación, lo colocan cerca de la caja o en zonas más visibles para facilitar su venta. También aplican descuentos o promociones para intentar recuperar la inversión antes de que el producto venza. <br><br>Jimmy menciona que las diferencias de stock ocurren casi todas las semanas, especialmente en golosinas, galletas, cereales y gaseosas, debido a errores de registro o consumo del personal. <br><br>Finalmente, considera importante contar con un sistema digital, principalmente desde el celular, que permita recibir alertas automáticas de bajo stock y vencimientos, generar reportes de los productos más vendidos y conectarse con un lector de códigos de barras para registrar fácilmente productos, pérdidas o roturas. <br><br>**URL:** |

| |
|---|
| ![Imagen de la entrevista](RUTA-DE-LA-IMAGEN) |
| **Nombres y apellidos:**  <br>**Edad:** 49  <br>**Distrito:**  <br><br>**Resumen de la entrevista:**  <br>Silvia Bravo, de 49 años, participa en la administración de un minimarket y explica que el control del stock se realiza revisando y contando los productos disponibles. Una de las principales dificultades es que, en ocasiones, la cantidad real no coincide con la cantidad que deberían tener registrada, por lo que deben estar pendientes constantemente del inventario. <br><br>La identificación de productos próximos a vencer se realiza revisando manualmente las fechas de vencimiento. Las pérdidas por vencimiento ocurren con frecuencia, especialmente en productos como yogur, leche y panes, ya que tienen una duración más corta. Para mantenerse comunicados sobre los cambios en el inventario, utilizan principalmente WhatsApp y un registro donde anotan información importante, como las fechas de vencimiento y los productos que ingresan. <br><br>Cuando un producto está próximo a vencer o tiene poca rotación, realizan ofertas, por ejemplo, combinándolo con otro producto que sí tiene mayor salida y reduciendo el precio para facilitar su venta. Los descuentos se aplican principalmente cuando los productos están cerca de vencer. Finalmente, Silvia considera que sería útil contar con un sistema digital que envíe alertas sobre los productos próximos a vencer y que también brinde orientación sobre qué acciones tomar para evitar pérdidas. <br><br>**URL:** |

### Segmento Empleados

| |
|---|
| ![Imagen de la entrevista](RUTA-DE-LA-IMAGEN) |
| **Nombres y apellidos:**  <br>**Edad:**  <br>**Distrito:**  <br><br>**Resumen:**  <br>Joseph trabaja en un minimarket realizando tareas de atención al cliente, registro de ventas, reposición de productos y control de almacén. Actualmente, las entradas y salidas de productos se registran manualmente en un cuaderno, lo que puede generar errores o confusiones, especialmente en las horas de mayor movimiento o cuando llega mercadería mientras se atiende a los clientes. <br><br>Para conocer el stock disponible, deben revisar y contar físicamente los productos en los estantes, lo cual puede resultar lento y complicado. La revisión de fechas de vencimiento también se realiza manualmente, generalmente cuando llega nueva mercadería. Si encuentran un producto vencido, lo retiran del estante y se lo comunican al administrador para evitar que llegue al cliente. <br><br>Joseph menciona que los errores en el inventario suelen ocurrir principalmente durante las horas de mayor venta, cuando hay más presión de trabajo. Los cambios de stock o problemas con los productos se comunican de forma verbal y mediante el cuaderno de registro. Además, considera que las tareas más tediosas son contar los productos y revisar uno por uno las fechas de vencimiento. <br><br>Finalmente, señala que sería útil contar con una herramienta digital sencilla que permita registrar entradas y salidas, consultar el stock disponible y facilitar el control del inventario, reduciendo así el tiempo y los errores del proceso manual. <br><br>**URL:** |

| |
|---|
| ![Imagen de la entrevista](RUTA-DE-LA-IMAGEN) |
| **Nombres y apellidos:**  <br>**Edad:** 20  <br>**Distrito:**  <br><br>**Resumen:**  <br>Andrés Marzano, de 20 años, tiene experiencia trabajando en atención al cliente y almacén. Explica que las entradas de productos se registraban después de verificar que la mercadería recibida coincidiera con la información del documento de entrega, para luego ingresarla en el sistema. Las salidas, por su parte, se registraban mediante boletas electrónicas. <br><br>Uno de los principales problemas era conocer con precisión la cantidad disponible de productos, especialmente cuando se trataba de artículos pequeños, ya que podían cometerse errores al contarlos. Esta tarea se volvía más complicada cuando, al mismo tiempo, tenían que atender a los clientes. <br><br>Para controlar los productos próximos a vencer, colocaban adelante los que tenían menor tiempo de vida útil y dejaban al fondo los productos recién llegados. Además, revisaban las fechas de vencimiento en los turnos de día y noche. Cuando un producto estaba cerca de vencer, trataban de darle prioridad a su venta; si ya quedaban pocos días y no se lograba vender, se registraba como merma para calcular las pérdidas. <br><br>Finalmente, Andrés señala que los mayores errores en el control del inventario se presentaban principalmente durante las mañanas, cuando había mayor cantidad de clientes y debían dividir su atención entre las ventas y las tareas de inventario. <br><br>**URL:** |

| |
|---|
| ![Imagen de la entrevista](RUTA-DE-LA-IMAGEN) |
| **Nombres y apellidos:**  <br>**Edad:** 20  <br>**Distrito:**  <br><br>**Resumen:**  <br>Pablo Moreno, empleado de un minimarket, explica que las entradas y salidas de productos se registran principalmente de forma manual y, en algunos casos, mediante Excel. Este proceso no siempre se actualiza de inmediato, por lo que a veces existen diferencias entre el stock registrado y la cantidad real disponible, especialmente en productos de alta rotación o durante las horas de mayor atención. La revisión de productos próximos a vencer también se realiza manualmente, verificando las fechas directamente en los productos. Cuando un producto está vencido se retira de la venta, mientras que los productos próximos a vencer pueden colocarse en zonas más visibles o venderse con descuento. Pablo también menciona que los errores suelen ocurrir cuando hay muchos clientes o cuando llega bastante mercadería al mismo tiempo. Los problemas de stock se comunican personalmente o por WhatsApp, aunque la información puede perderse entre tantos mensajes. Finalmente, considera que sería útil contar con un sistema digital accesible desde el celular o computadora que permita registrar entradas y salidas, actualizar el stock rápidamente y recibir alertas sobre productos próximos a vencer. <br><br>**URL:** |


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
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping

## 2.4. Big Picture EventStorming

## 2.5. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. User Stories

Épicas

| Epic ID | Nombre | Descripción |
|---|---|---|
| **EP01** | **Acceso, Roles y Configuración del Negocio** | **Como** responsable de una minimarket, **quiero** gestionar el acceso de administradores y empleados, así como los parámetros operativos del negocio, **para** asegurar que cada usuario utilice únicamente las funciones que le corresponden y que el sistema se adapte a la operación real del establecimiento. |
| **EP02** | **Catálogo, Inventario y Gestión de Lotes** | **Como** administrador o empleado, **quiero** registrar productos, controlar existencias y gestionar lotes con fechas de vencimiento, **para** mantener un inventario confiable, actualizado y trazable. |
| **EP03** | **Vencimientos, Mermas y Ofertas Estratégicas** | **Como** administrador, **quiero** detectar productos próximos a vencer, registrar mermas y generar ofertas estratégicas, **para** reducir pérdidas económicas y mejorar la rotación de productos perecibles. |
| **EP04** | **Operación Diaria y Movimientos de Stock** | **Como** empleado, **quiero** registrar de forma rápida las operaciones diarias que afectan el inventario, **para** que el stock del sistema refleje lo que realmente ocurre en el punto de venta y almacén. |
| **EP05** | **Reportes, Analítica y Alertas Operativas** | **Como** administrador, **quiero** visualizar indicadores, reportes y alertas sobre stock, ventas, rotación, vencimientos y mermas, **para** tomar decisiones operativas basadas en información actualizada. |
| **EP06** | **Auditoría, Seguridad y Continuidad Operativa** | **Como** administrador, **quiero** contar con trazabilidad, controles de seguridad y herramientas de soporte, **para** proteger la información del negocio y supervisar las acciones realizadas dentro de BodeGo. |

---

User Stories

# EP01 — Acceso, Roles y Configuración del Negocio

## US01 — Inicio de sesión

**User Story ID:** US01  
**Epic ID:** EP01  
**Título:** Inicio de sesión

### Descripción

**Como** usuario registrado, **quiero** iniciar sesión con mis credenciales, **para** acceder de forma segura a BodeGo.

### Acceptance Criteria

**Scenario: Inicio de sesión exitoso**

**Dado que** el usuario se encuentra registrado y su cuenta está activa,  
**Cuando** ingresa credenciales válidas,  
**Entonces** el sistema autentica al usuario y muestra la interfaz correspondiente a su rol.

---

## US02 — Acceso según rol

**User Story ID:** US02  
**Epic ID:** EP01  
**Título:** Acceso según rol

### Descripción

**Como** usuario, **quiero** visualizar una interfaz adaptada a mi rol de Administrador o Empleado, **para** acceder únicamente a las funciones que me corresponden.

### Acceptance Criteria

**Scenario: Redirección según rol**

**Dado que** el usuario inició sesión correctamente,  
**Cuando** el sistema identifica su rol,  
**Entonces** muestra el panel administrativo o el panel operativo de empleado según corresponda.

---

## US03 — Registro de empleados

**User Story ID:** US03  
**Epic ID:** EP01  
**Título:** Registro de empleados

### Descripción

**Como** administrador, **quiero** crear cuentas para los empleados del negocio, **para** permitirles operar en el sistema con credenciales individuales.

### Acceptance Criteria

**Scenario: Crear cuenta de empleado**

**Dado que** el administrador se encuentra en la gestión de usuarios,  
**Cuando** registra los datos obligatorios de un nuevo empleado,  
**Entonces** el sistema crea la cuenta con rol Empleado y deja registro de la creación.

---

## US04 — Activación y desactivación de usuarios

**User Story ID:** US04  
**Epic ID:** EP01  
**Título:** Activación y desactivación de usuarios

### Descripción

**Como** administrador, **quiero** activar o desactivar cuentas de empleados, **para** controlar quién puede acceder a la información del negocio.

### Acceptance Criteria

**Scenario: Desactivar empleado**

**Dado que** existe una cuenta de empleado activa,  
**Cuando** el administrador selecciona la opción de desactivar,  
**Entonces** el sistema bloquea nuevos accesos de esa cuenta sin eliminar su historial.

---

## US05 — Edición de perfil

**User Story ID:** US05  
**Epic ID:** EP01  
**Título:** Edición de perfil

### Descripción

**Como** usuario, **quiero** actualizar mis datos personales y de contacto, **para** mantener correcta la información asociada a mi cuenta.

### Acceptance Criteria

**Scenario: Actualizar perfil**

**Dado que** el usuario se encuentra autenticado,  
**Cuando** modifica datos válidos y guarda los cambios,  
**Entonces** el sistema actualiza la información y confirma la operación.

---

## US06 — Configuración de datos del negocio

**User Story ID:** US06  
**Epic ID:** EP01  
**Título:** Configuración de datos del negocio

### Descripción

**Como** administrador, **quiero** configurar nombre comercial, dirección, contacto y horarios, **para** mantener centralizada la información operativa del establecimiento.

### Acceptance Criteria

**Scenario: Actualizar datos del negocio**

**Dado que** el administrador accede a la configuración general,  
**Cuando** modifica los datos y confirma los cambios,  
**Entonces** el sistema guarda la nueva configuración y la utiliza en los módulos correspondientes.

---

## US07 — Configuración de umbrales de stock

**User Story ID:** US07  
**Epic ID:** EP01  
**Título:** Configuración de umbrales de stock

### Descripción

**Como** administrador, **quiero** definir niveles de stock bajo y crítico, **para** recibir alertas de reposición adaptadas a mi operación.

### Acceptance Criteria

**Scenario: Definir umbral de stock**

**Dado que** existe un producto registrado,  
**Cuando** el administrador asigna valores de stock bajo y crítico válidos,  
**Entonces** el sistema guarda los umbrales y los utiliza para clasificar el inventario.

---

## US08 — Configuración de días de alerta de vencimiento

**User Story ID:** US08  
**Epic ID:** EP01  
**Título:** Configuración de días de alerta de vencimiento

### Descripción

**Como** administrador, **quiero** definir cuántos días antes del vencimiento debe alertarme el sistema, **para** adaptar el control de perecibles a las políticas del negocio.

### Acceptance Criteria

**Scenario: Definir ventana de vencimiento**

**Dado que** el administrador se encuentra en parámetros operativos,  
**Cuando** registra una cantidad válida de días de anticipación,  
**Entonces** el sistema guarda el parámetro y lo aplica a los lotes con fecha de vencimiento.

---

# EP02 — Catálogo, Inventario y Gestión de Lotes

## US09 — Registro de productos

**User Story ID:** US09  
**Epic ID:** EP02  
**Título:** Registro de productos

### Descripción

**Como** administrador, **quiero** crear productos con su información comercial y operativa, **para** incorporarlos al catálogo interno y controlar sus existencias.

### Acceptance Criteria

**Scenario: Crear producto**

**Dado que** el administrador accede al módulo de productos,  
**Cuando** completa los campos obligatorios y confirma el registro,  
**Entonces** el sistema crea el producto y lo deja disponible para movimientos de inventario.

---

## US10 — Edición de productos

**User Story ID:** US10  
**Epic ID:** EP02  
**Título:** Edición de productos

### Descripción

**Como** administrador, **quiero** modificar nombre, categoría, unidad, costo o precio de un producto, **para** mantener actualizada la información utilizada en la operación.

### Acceptance Criteria

**Scenario: Editar producto**

**Dado que** existe un producto registrado,  
**Cuando** el administrador modifica información válida,  
**Entonces** el sistema guarda los cambios sin alterar el historial de movimientos previos.

---

## US11 — Desactivación de productos

**User Story ID:** US11  
**Epic ID:** EP02  
**Título:** Desactivación de productos

### Descripción

**Como** administrador, **quiero** desactivar productos que ya no comercializo, **para** evitar nuevos movimientos sin perder su historial.

### Acceptance Criteria

**Scenario: Desactivar producto**

**Dado que** existe un producto activo,  
**Cuando** el administrador confirma su desactivación,  
**Entonces** el sistema impide nuevos registros operativos para el producto y conserva su historial.

---

## US12 — Organización por categorías

**User Story ID:** US12  
**Epic ID:** EP02  
**Título:** Organización por categorías

### Descripción

**Como** administrador, **quiero** clasificar los productos por categorías, **para** facilitar su búsqueda y análisis dentro del inventario.

### Acceptance Criteria

**Scenario: Asignar categoría**

**Dado que** existen categorías disponibles,  
**Cuando** el administrador selecciona una categoría para un producto,  
**Entonces** el sistema guarda la clasificación y permite filtrar el producto por ella.

---

## US13 — Búsqueda y filtros de inventario

**User Story ID:** US13  
**Epic ID:** EP02  
**Título:** Búsqueda y filtros de inventario

### Descripción

**Como** administrador o empleado, **quiero** buscar productos por nombre, código, categoría o estado de stock, **para** encontrar rápidamente el artículo que necesito gestionar.

### Acceptance Criteria

**Scenario: Buscar producto**

**Dado que** existen productos registrados,  
**Cuando** el usuario ingresa un criterio de búsqueda o aplica un filtro,  
**Entonces** el sistema muestra únicamente los productos que cumplen el criterio.

---

## US14 — Ingreso de stock por lote

**User Story ID:** US14  
**Epic ID:** EP02  
**Título:** Ingreso de stock por lote

### Descripción

**Como** empleado, **quiero** registrar el ingreso de mercadería indicando cantidad y lote, **para** actualizar el inventario cuando se recibe nueva mercadería.

### Acceptance Criteria

**Scenario: Registrar ingreso**

**Dado que** existe un producto activo,  
**Cuando** el empleado registra cantidad, lote y datos requeridos del ingreso,  
**Entonces** el sistema incrementa el stock y registra el movimiento con fecha y usuario.

---

## US15 — Registro de fecha de vencimiento por lote

**User Story ID:** US15  
**Epic ID:** EP02  
**Título:** Registro de fecha de vencimiento por lote

### Descripción

**Como** empleado, **quiero** asociar una fecha de vencimiento a cada lote perecible, **para** permitir el control preventivo de productos próximos a caducar.

### Acceptance Criteria

**Scenario: Registrar vencimiento**

**Dado que** el empleado está registrando un lote de un producto perecible,  
**Cuando** ingresa una fecha de vencimiento válida,  
**Entonces** el sistema asocia la fecha al lote y la considera en las alertas de caducidad.

---

## US16 — Consulta de stock por lote

**User Story ID:** US16  
**Epic ID:** EP02  
**Título:** Consulta de stock por lote

### Descripción

**Como** administrador o empleado, **quiero** visualizar las existencias separadas por lote, **para** conocer qué unidades deben utilizarse primero y mantener trazabilidad.

### Acceptance Criteria

**Scenario: Consultar lotes**

**Dado que** un producto posee más de un lote con stock,  
**Cuando** el usuario abre el detalle de inventario,  
**Entonces** el sistema muestra cantidad disponible, fecha de ingreso y vencimiento de cada lote.

---

## US17 — Ajuste manual de inventario

**User Story ID:** US17  
**Epic ID:** EP02  
**Título:** Ajuste manual de inventario

### Descripción

**Como** administrador, **quiero** corregir diferencias de stock indicando cantidad y motivo, **para** alinear el inventario digital con el conteo físico cuando exista una discrepancia.

### Acceptance Criteria

**Scenario: Ajustar stock**

**Dado que** existe una diferencia identificada en un producto,  
**Cuando** el administrador registra el ajuste y un motivo obligatorio,  
**Entonces** el sistema actualiza la existencia y guarda el ajuste en el historial de auditoría.

---

## US18 — Conteo físico de inventario

**User Story ID:** US18  
**Epic ID:** EP02  
**Título:** Conteo físico de inventario

### Descripción

**Como** administrador o empleado, **quiero** registrar un conteo físico de productos, **para** comparar las existencias reales con las registradas en BodeGo.

### Acceptance Criteria

**Scenario: Registrar conteo**

**Dado que** el usuario inicia una revisión física,  
**Cuando** ingresa las cantidades contadas para los productos seleccionados,  
**Entonces** el sistema calcula diferencias y permite que un administrador revise los ajustes necesarios.

---

# EP03 — Vencimientos, Mermas y Ofertas Estratégicas

## US19 — Detección de productos próximos a vencer

**User Story ID:** US19  
**Epic ID:** EP03  
**Título:** Detección de productos próximos a vencer

### Descripción

**Como** administrador, **quiero** visualizar automáticamente los lotes que se aproximan a su vencimiento, **para** actuar antes de que se conviertan en merma.

### Acceptance Criteria

**Scenario: Detectar lote próximo a vencer**

**Dado que** existen lotes con fecha de vencimiento y una ventana de alerta configurada,  
**Cuando** un lote ingresa dentro del período de alerta,  
**Entonces** el sistema lo clasifica como próximo a vencer y lo muestra en el panel correspondiente.

---

## US20 — Priorización por fecha de vencimiento

**User Story ID:** US20  
**Epic ID:** EP03  
**Título:** Priorización por fecha de vencimiento

### Descripción

**Como** administrador o empleado, **quiero** ordenar los lotes perecibles por fecha de vencimiento, **para** dar salida primero a los productos con menor vida útil.

### Acceptance Criteria

**Scenario: Ordenar por vencimiento**

**Dado que** existen varios lotes perecibles,  
**Cuando** el usuario selecciona ordenar por vencimiento,  
**Entonces** el sistema muestra primero los lotes con fecha más próxima.

---

## US21 — Registro de merma

**User Story ID:** US21  
**Epic ID:** EP03  
**Título:** Registro de merma

### Descripción

**Como** empleado, **quiero** registrar unidades perdidas, dañadas o vencidas indicando su motivo, **para** mantener el stock real y documentar las pérdidas operativas.

### Acceptance Criteria

**Scenario: Registrar merma**

**Dado que** existe stock disponible del producto o lote,  
**Cuando** el empleado indica cantidad y motivo de merma,  
**Entonces** el sistema descuenta las unidades y registra la operación con fecha, usuario y causa.

---

## US22 — Clasificación de motivos de merma

**User Story ID:** US22  
**Epic ID:** EP03  
**Título:** Clasificación de motivos de merma

### Descripción

**Como** administrador, **quiero** definir y consultar categorías de merma, **para** identificar las principales causas de pérdida del negocio.

### Acceptance Criteria

**Scenario: Clasificar merma**

**Dado que** existen movimientos de merma,  
**Cuando** el administrador consulta el reporte por motivo,  
**Entonces** el sistema agrupa las pérdidas por categorías como vencimiento, daño, rotura u otras configuradas.

---

## US23 — Sugerencia automática de oferta

**User Story ID:** US23  
**Epic ID:** EP03  
**Título:** Sugerencia automática de oferta

### Descripción

**Como** administrador, **quiero** recibir propuestas de oferta para lotes próximos a vencer, **para** reducir mermas mediante acciones comerciales oportunas.

### Acceptance Criteria

**Scenario: Generar sugerencia**

**Dado que** un lote cumple las reglas configuradas de proximidad al vencimiento y tiene stock disponible,  
**Cuando** el sistema evalúa el lote,  
**Entonces** genera una sugerencia de oferta con producto, lote, cantidad y descuento propuesto.

---

## US24 — Creación manual de oferta

**User Story ID:** US24  
**Epic ID:** EP03  
**Título:** Creación manual de oferta

### Descripción

**Como** administrador, **quiero** crear una oferta para un producto o lote específico, **para** impulsar su rotación cuando lo considere necesario.

### Acceptance Criteria

**Scenario: Crear oferta**

**Dado que** existe stock disponible para el producto o lote,  
**Cuando** el administrador define precio o descuento y vigencia,  
**Entonces** el sistema registra la oferta y la deja activa durante el período definido.

---

## US25 — Aprobación de oferta sugerida

**User Story ID:** US25  
**Epic ID:** EP03  
**Título:** Aprobación de oferta sugerida

### Descripción

**Como** administrador, **quiero** aprobar o editar una oferta sugerida por BodeGo, **para** mantener control sobre las promociones antes de aplicarlas.

### Acceptance Criteria

**Scenario: Aprobar sugerencia**

**Dado que** existe una sugerencia automática pendiente,  
**Cuando** el administrador revisa sus condiciones y selecciona aprobar,  
**Entonces** el sistema activa la oferta con los valores confirmados.

---

## US26 — Finalización automática de oferta

**User Story ID:** US26  
**Epic ID:** EP03  
**Título:** Finalización automática de oferta

### Descripción

**Como** administrador, **quiero** hacer que las ofertas terminen cuando vence su vigencia o se agota el stock asociado, **para** evitar promociones inválidas en la operación diaria.

### Acceptance Criteria

**Scenario: Finalizar oferta**

**Dado que** existe una oferta activa,  
**Cuando** se alcanza su fecha de fin o el stock asignado llega a cero,  
**Entonces** el sistema cambia la oferta a finalizada y evita nuevas aplicaciones.

---

# EP04 — Operación Diaria y Movimientos de Stock

## US27 — Registro rápido de venta

**User Story ID:** US27  
**Epic ID:** EP04  
**Título:** Registro rápido de venta

### Descripción

**Como** empleado, **quiero** registrar los productos vendidos durante la atención, **para** descontar automáticamente las unidades del inventario.

### Acceptance Criteria

**Scenario: Registrar venta**

**Dado que** los productos seleccionados tienen stock disponible,  
**Cuando** el empleado registra cantidades y confirma la operación,  
**Entonces** el sistema descuenta el stock y genera un movimiento de salida.

---

## US28 — Aplicación de oferta en venta

**User Story ID:** US28  
**Epic ID:** EP04  
**Título:** Aplicación de oferta en venta

### Descripción

**Como** empleado, **quiero** visualizar y aplicar ofertas vigentes al registrar una venta, **para** utilizar correctamente las promociones definidas por el administrador.

### Acceptance Criteria

**Scenario: Aplicar oferta vigente**

**Dado que** un producto tiene una oferta activa y válida,  
**Cuando** el empleado lo agrega a una operación de venta,  
**Entonces** el sistema aplica las condiciones vigentes y muestra el precio resultante.

---

## US29 — Validación de stock antes de venta

**User Story ID:** US29  
**Epic ID:** EP04  
**Título:** Validación de stock antes de venta

### Descripción

**Como** empleado, **quiero** recibir una validación de disponibilidad antes de confirmar una salida, **para** evitar que el inventario quede con cantidades negativas.

### Acceptance Criteria

**Scenario: Evitar venta sin stock**

**Dado que** la cantidad solicitada supera la existencia disponible,  
**Cuando** el empleado intenta confirmar la operación,  
**Entonces** el sistema bloquea la confirmación e informa el stock disponible.

---

## US30 — Salida FEFO sugerida

**User Story ID:** US30  
**Epic ID:** EP04  
**Título:** Salida FEFO sugerida

### Descripción

**Como** empleado, **quiero** recibir una sugerencia del lote que debe salir primero, **para** priorizar la venta de unidades con vencimiento más cercano.

### Acceptance Criteria

**Scenario: Sugerir lote de salida**

**Dado que** un producto posee varios lotes disponibles con distintas fechas de vencimiento,  
**Cuando** el empleado registra una salida,  
**Entonces** el sistema propone primero el lote con vencimiento más próximo.

---

## US31 — Registro de devolución de cliente

**User Story ID:** US31  
**Epic ID:** EP04  
**Título:** Registro de devolución de cliente

### Descripción

**Como** empleado, **quiero** registrar una devolución e indicar si el producto retorna al stock, **para** mantener correctamente las existencias y el historial de operaciones.

### Acceptance Criteria

**Scenario: Registrar devolución**

**Dado que** existe una venta previamente registrada,  
**Cuando** el empleado selecciona el producto devuelto y su condición,  
**Entonces** el sistema registra la devolución y repone stock únicamente cuando el producto es apto.

---

## US32 — Registro de devolución a proveedor

**User Story ID:** US32  
**Epic ID:** EP04  
**Título:** Registro de devolución a proveedor

### Descripción

**Como** administrador o empleado autorizado, **quiero** registrar unidades que salen del inventario para ser devueltas al proveedor, **para** controlar las salidas no asociadas a ventas.

### Acceptance Criteria

**Scenario: Registrar devolución a proveedor**

**Dado que** existe stock del lote seleccionado,  
**Cuando** el usuario autorizado registra cantidad y motivo,  
**Entonces** el sistema descuenta las unidades y guarda el movimiento como devolución a proveedor.

---

## US33 — Registro de recepción de mercadería

**User Story ID:** US33  
**Epic ID:** EP04  
**Título:** Registro de recepción de mercadería

### Descripción

**Como** empleado, **quiero** registrar una recepción de productos de forma ágil, **para** actualizar existencias durante el abastecimiento diario.

### Acceptance Criteria

**Scenario: Recibir mercadería**

**Dado que** el empleado tiene acceso al módulo de recepción,  
**Cuando** registra productos, cantidades y lotes recibidos,  
**Entonces** el sistema incrementa el stock y genera los movimientos de entrada correspondientes.

---

## US34 — Historial diario de operaciones

**User Story ID:** US34  
**Epic ID:** EP04  
**Título:** Historial diario de operaciones

### Descripción

**Como** empleado, **quiero** consultar las operaciones que registré durante mi turno, **para** verificar ventas, ingresos, devoluciones y mermas realizadas.

### Acceptance Criteria

**Scenario: Consultar operaciones del turno**

**Dado que** el empleado ha registrado movimientos durante el día,  
**Cuando** accede a su historial operativo,  
**Entonces** el sistema muestra sus operaciones ordenadas por fecha y hora.

---

## US35 — Corrección de operación reciente

**User Story ID:** US35  
**Epic ID:** EP04  
**Título:** Corrección de operación reciente

### Descripción

**Como** empleado, **quiero** solicitar la corrección de una operación registrada por error, **para** evitar alterar el inventario sin trazabilidad.

### Acceptance Criteria

**Scenario: Solicitar corrección**

**Dado que** existe una operación reciente registrada por el empleado,  
**Cuando** selecciona corregir e indica el motivo,  
**Entonces** el sistema registra la solicitud y exige autorización administrativa cuando la corrección afecta stock consolidado.

---

## US36 — Cierre operativo del turno

**User Story ID:** US36  
**Epic ID:** EP04  
**Título:** Cierre operativo del turno

### Descripción

**Como** empleado, **quiero** visualizar un resumen de los movimientos realizados antes de terminar mi turno, **para** comprobar que las operaciones del día quedaron registradas.

### Acceptance Criteria

**Scenario: Cerrar turno**

**Dado que** el empleado tiene operaciones registradas en la jornada,  
**Cuando** selecciona la opción de cierre,  
**Entonces** el sistema muestra un resumen de ventas, entradas, devoluciones, ajustes autorizados y mermas del turno.

---

# EP05 — Reportes, Analítica y Alertas Operativas

## US37 — Dashboard administrativo

**User Story ID:** US37  
**Epic ID:** EP05  
**Título:** Dashboard administrativo

### Descripción

**Como** administrador, **quiero** visualizar los principales indicadores del negocio en un solo panel, **para** conocer rápidamente el estado del inventario y la operación.

### Acceptance Criteria

**Scenario: Consultar dashboard**

**Dado que** existen datos operativos registrados,  
**Cuando** el administrador ingresa al panel principal,  
**Entonces** el sistema muestra indicadores actualizados de stock, ventas, mermas, vencimientos y productos críticos.

---

## US38 — Reporte de stock bajo y crítico

**User Story ID:** US38  
**Epic ID:** EP05  
**Título:** Reporte de stock bajo y crítico

### Descripción

**Como** administrador, **quiero** consultar los productos que requieren reposición, **para** priorizar las compras y evitar quiebres de stock.

### Acceptance Criteria

**Scenario: Consultar stock crítico**

**Dado que** existen productos por debajo de sus umbrales,  
**Cuando** el administrador abre el reporte de reposición,  
**Entonces** el sistema clasifica los productos por nivel bajo o crítico.

---

## US39 — Reporte de productos próximos a vencer

**User Story ID:** US39  
**Epic ID:** EP05  
**Título:** Reporte de productos próximos a vencer

### Descripción

**Como** administrador, **quiero** consultar los lotes en riesgo de vencimiento, **para** planificar ofertas, rotación o retiro oportuno.

### Acceptance Criteria

**Scenario: Consultar vencimientos**

**Dado que** existen lotes dentro de la ventana de alerta,  
**Cuando** el administrador abre el reporte de vencimientos,  
**Entonces** el sistema muestra producto, lote, cantidad y días restantes ordenados por urgencia.

---

## US40 — Reporte de mermas

**User Story ID:** US40  
**Epic ID:** EP05  
**Título:** Reporte de mermas

### Descripción

**Como** administrador, **quiero** analizar las pérdidas por producto, motivo y período, **para** identificar patrones y reducir costos operativos.

### Acceptance Criteria

**Scenario: Analizar mermas**

**Dado que** existen mermas registradas,  
**Cuando** el administrador selecciona un período,  
**Entonces** el sistema muestra cantidades y valor estimado de pérdida agrupados por producto y motivo.

---

## US41 — Reporte de productos de alta rotación

**User Story ID:** US41  
**Epic ID:** EP05  
**Título:** Reporte de productos de alta rotación

### Descripción

**Como** administrador, **quiero** identificar los productos con mayor frecuencia de salida, **para** priorizar reposición y ubicación física en el negocio.

### Acceptance Criteria

**Scenario: Consultar alta rotación**

**Dado que** existen suficientes movimientos de salida,  
**Cuando** el administrador consulta el análisis de rotación,  
**Entonces** el sistema ordena los productos según su frecuencia o volumen de salida.

---

## US42 — Clasificación Pareto 80/20

**User Story ID:** US42  
**Epic ID:** EP05  
**Título:** Clasificación Pareto 80/20

### Descripción

**Como** administrador, **quiero** identificar los productos que concentran la mayor parte de las salidas o ventas, **para** enfocar la gestión en los artículos más relevantes.

### Acceptance Criteria

**Scenario: Calcular Pareto**

**Dado que** existe historial suficiente de operaciones,  
**Cuando** el administrador solicita el análisis Pareto,  
**Entonces** el sistema clasifica los productos según su contribución acumulada y destaca el grupo de mayor impacto.

---

## US43 — Alertas operativas

**User Story ID:** US43  
**Epic ID:** EP05  
**Título:** Alertas operativas

### Descripción

**Como** administrador, **quiero** recibir alertas sobre stock crítico, vencimientos y eventos relevantes, **para** reaccionar oportunamente ante riesgos operativos.

### Acceptance Criteria

**Scenario: Generar alerta**

**Dado que** se cumple una regla configurada de stock o vencimiento,  
**Cuando** el sistema detecta la condición,  
**Entonces** genera una alerta visible para el administrador con acceso al elemento afectado.

---

## US44 — Filtrado de reportes por período

**User Story ID:** US44  
**Epic ID:** EP05  
**Título:** Filtrado de reportes por período

### Descripción

**Como** administrador, **quiero** filtrar los reportes por fechas y categorías, **para** analizar la evolución del negocio en intervalos específicos.

### Acceptance Criteria

**Scenario: Filtrar reporte**

**Dado que** el administrador se encuentra en un reporte,  
**Cuando** selecciona un rango de fechas y filtros válidos,  
**Entonces** el sistema recalcula y muestra únicamente la información del período seleccionado.

---

# EP06 — Auditoría, Seguridad y Continuidad Operativa

## US45 — Historial de movimientos de inventario

**User Story ID:** US45  
**Epic ID:** EP06  
**Título:** Historial de movimientos de inventario

### Descripción

**Como** administrador, **quiero** consultar todas las entradas y salidas que afectaron un producto, **para** auditar cómo se originó su stock actual.

### Acceptance Criteria

**Scenario: Consultar movimientos**

**Dado que** un producto posee movimientos registrados,  
**Cuando** el administrador abre su historial,  
**Entonces** el sistema muestra fecha, tipo, cantidad, lote y usuario responsable de cada movimiento.

---

## US46 — Bitácora de acciones de usuarios

**User Story ID:** US46  
**Epic ID:** EP06  
**Título:** Bitácora de acciones de usuarios

### Descripción

**Como** administrador, **quiero** consultar acciones relevantes realizadas por los usuarios, **para** supervisar cambios sensibles dentro del sistema.

### Acceptance Criteria

**Scenario: Consultar bitácora**

**Dado que** existen acciones auditables registradas,  
**Cuando** el administrador accede a la bitácora,  
**Entonces** el sistema muestra usuario, acción, fecha, hora y entidad afectada.

---

## US47 — Cambio seguro de contraseña

**User Story ID:** US47  
**Epic ID:** EP06  
**Título:** Cambio seguro de contraseña

### Descripción

**Como** usuario, **quiero** cambiar mi contraseña desde la configuración de seguridad, **para** proteger mi cuenta frente a accesos no autorizados.

### Acceptance Criteria

**Scenario: Cambiar contraseña**

**Dado que** el usuario se encuentra autenticado,  
**Cuando** ingresa su contraseña actual y una nueva que cumple las reglas definidas,  
**Entonces** el sistema actualiza la credencial y confirma el cambio.

---

## US48 — Recuperación de acceso

**User Story ID:** US48  
**Epic ID:** EP06  
**Título:** Recuperación de acceso

### Descripción

**Como** usuario, **quiero** recuperar el acceso cuando olvido mi contraseña, **para** volver a utilizar mi cuenta sin intervención manual innecesaria.

### Acceptance Criteria

**Scenario: Solicitar recuperación**

**Dado que** existe una cuenta asociada al identificador ingresado,  
**Cuando** el usuario inicia el proceso de recuperación,  
**Entonces** el sistema habilita un mecanismo seguro para restablecer la contraseña.

---

## US49 — Cierre de sesión

**User Story ID:** US49  
**Epic ID:** EP06  
**Título:** Cierre de sesión

### Descripción

**Como** usuario, **quiero** cerrar mi sesión cuando termino de utilizar BodeGo, **para** evitar que terceros accedan a mi cuenta desde el mismo dispositivo.

### Acceptance Criteria

**Scenario: Cerrar sesión**

**Dado que** el usuario se encuentra autenticado,  
**Cuando** selecciona cerrar sesión,  
**Entonces** el sistema invalida la sesión actual y retorna a la pantalla de acceso.

---

## US50 — Centro de ayuda operativo

**User Story ID:** US50  
**Epic ID:** EP06  
**Título:** Centro de ayuda operativo

### Descripción

**Como** administrador o empleado, **quiero** consultar ayuda sobre las funciones principales del sistema, **para** resolver dudas frecuentes durante la operación diaria.

### Acceptance Criteria

**Scenario: Consultar ayuda**

**Dado que** el usuario se encuentra autenticado,  
**Cuando** accede al centro de ayuda y selecciona un tema,  
**Entonces** el sistema muestra instrucciones relacionadas con la funcionalidad seleccionada.

## 3.2. Impact Mapping

Impact Mapping

| **Business Goals** | **Actors** | **Impact** | **Deliverables** | **User Stories** |
|---|---|---|---|---|
| **Goal N°1:**<br>**Mantener un inventario preciso, actualizado y trazable para reducir diferencias entre el stock físico y el registrado en el sistema.** | Administrador | Mantener un catálogo de productos correctamente estructurado. | Gestión de productos y categorías. | **US09: Registro de productos.** Como administrador, quiero crear productos con su información comercial y operativa, para incorporarlos al catálogo interno y controlar sus existencias.<br><br>**US10: Edición de productos.** Como administrador, quiero modificar nombre, categoría, unidad, costo o precio de un producto, para mantener actualizada la información utilizada en la operación.<br><br>**US11: Desactivación de productos.** Como administrador, quiero desactivar productos que ya no comercializo, para evitar nuevos movimientos sin perder su historial.<br><br>**US12: Organización por categorías.** Como administrador, quiero clasificar los productos por categorías, para facilitar su búsqueda y análisis dentro del inventario. |
|  | Administrador / Empleado | Localizar rápidamente productos y conocer su situación actual. | Buscador y filtros de inventario. | **US13: Búsqueda y filtros de inventario.** Como administrador o empleado, quiero buscar productos por nombre, código, categoría o estado de stock, para encontrar rápidamente el artículo que necesito gestionar. |
|  | Empleado | Registrar correctamente la mercadería que ingresa al establecimiento. | Gestión de ingresos y lotes. | **US14: Ingreso de stock por lote.** Como empleado, quiero registrar el ingreso de mercadería indicando cantidad y lote, para actualizar el inventario cuando se recibe nueva mercadería.<br><br>**US15: Registro de fecha de vencimiento por lote.** Como empleado, quiero asociar una fecha de vencimiento a cada lote perecible, para permitir el control preventivo de productos próximos a caducar. |
|  | Administrador / Empleado | Conocer la composición real del stock de cada producto. | Consulta de inventario por lotes. | **US16: Consulta de stock por lote.** Como administrador o empleado, quiero visualizar las existencias separadas por lote, para conocer qué unidades deben utilizarse primero y mantener trazabilidad. |
|  | Administrador | Corregir diferencias detectadas entre el inventario físico y el digital. | Ajustes manuales de inventario. | **US17: Ajuste manual de inventario.** Como administrador, quiero corregir diferencias de stock indicando cantidad y motivo, para alinear el inventario digital con el conteo físico cuando exista una discrepancia. |
|  | Administrador / Empleado | Detectar diferencias mediante verificaciones físicas periódicas. | Conteo físico de inventario. | **US18: Conteo físico de inventario.** Como administrador o empleado, quiero registrar un conteo físico de productos, para comparar las existencias reales con las registradas en BodeGo. |
| **Goal N°2:**<br>**Reducir las pérdidas económicas producidas por productos vencidos, dañados o deteriorados.** | Administrador | Detectar productos que se encuentran en riesgo de vencimiento antes de convertirse en merma. | Sistema automático de control de vencimientos. | **US19: Detección de productos próximos a vencer.** Como administrador, quiero visualizar automáticamente los lotes que se aproximan a su vencimiento, para actuar antes de que se conviertan en merma. |
|  | Administrador / Empleado | Priorizar la salida de los productos con menor vida útil. | Priorización de lotes por vencimiento. | **US20: Priorización por fecha de vencimiento.** Como administrador o empleado, quiero ordenar los lotes perecibles por fecha de vencimiento, para dar salida primero a los productos con menor vida útil. |
|  | Empleado | Registrar inmediatamente las pérdidas detectadas durante la operación. | Módulo de registro de mermas. | **US21: Registro de merma.** Como empleado, quiero registrar unidades perdidas, dañadas o vencidas indicando su motivo, para mantener el stock real y documentar las pérdidas operativas. |
|  | Administrador | Identificar por qué se producen las pérdidas de inventario. | Clasificación de causas de merma. | **US22: Clasificación de motivos de merma.** Como administrador, quiero definir y consultar categorías de merma, para identificar las principales causas de pérdida del negocio. |
|  | Administrador | Convertir productos próximos a vencer en oportunidades de venta antes de perderlos. | Motor de sugerencias de ofertas. | **US23: Sugerencia automática de oferta.** Como administrador, quiero recibir propuestas de oferta para lotes próximos a vencer, para reducir mermas mediante acciones comerciales oportunas. |
|  | Administrador | Poder decidir manualmente qué productos requieren una promoción. | Gestión manual de ofertas. | **US24: Creación manual de oferta.** Como administrador, quiero crear una oferta para un producto o lote específico, para impulsar su rotación cuando lo considere necesario. |
|  | Administrador | Mantener control sobre las promociones sugeridas automáticamente. | Flujo de aprobación de ofertas. | **US25: Aprobación de oferta sugerida.** Como administrador, quiero aprobar o editar una oferta sugerida por BodeGo, para mantener control sobre las promociones antes de aplicarlas. |
|  | Administrador | Evitar que se utilicen ofertas vencidas o asociadas a productos agotados. | Control automático de vigencia. | **US26: Finalización automática de oferta.** Como administrador, quiero hacer que las ofertas terminen cuando vence su vigencia o se agota el stock asociado, para evitar promociones inválidas en la operación diaria. |
|  | Administrador | Identificar con anticipación los lotes con mayor riesgo de convertirse en pérdida. | Reporte de vencimientos. | **US39: Reporte de productos próximos a vencer.** Como administrador, quiero consultar los lotes en riesgo de vencimiento, para planificar ofertas, rotación o retiro oportuno. |
|  | Administrador | Medir económicamente las pérdidas del establecimiento. | Reporte analítico de mermas. | **US40: Reporte de mermas.** Como administrador, quiero analizar las pérdidas por producto, motivo y período, para identificar patrones y reducir costos operativos. |
| **Goal N°3:**<br>**Agilizar el registro de las operaciones diarias realizadas por los empleados y mantener el stock actualizado en tiempo real.** | Empleado | Registrar rápidamente los productos vendidos. | Registro operativo de ventas. | **US27: Registro rápido de venta.** Como empleado, quiero registrar los productos vendidos durante la atención, para descontar automáticamente las unidades del inventario. |
|  | Empleado | Aplicar correctamente las promociones configuradas por el administrador. | Aplicación automática de ofertas. | **US28: Aplicación de oferta en venta.** Como empleado, quiero visualizar y aplicar ofertas vigentes al registrar una venta, para utilizar correctamente las promociones definidas por el administrador. |
|  | Empleado | Evitar vender cantidades superiores al inventario real. | Validación de disponibilidad. | **US29: Validación de stock antes de venta.** Como empleado, quiero recibir una validación de disponibilidad antes de confirmar una salida, para evitar que el inventario quede con cantidades negativas. |
|  | Empleado | Dar salida primero a los lotes con vencimiento más cercano. | Gestión FEFO de lotes. | **US30: Salida FEFO sugerida.** Como empleado, quiero recibir una sugerencia del lote que debe salir primero, para priorizar la venta de unidades con vencimiento más cercano. |
|  | Empleado | Registrar correctamente productos devueltos por los clientes. | Gestión de devoluciones de clientes. | **US31: Registro de devolución de cliente.** Como empleado, quiero registrar una devolución e indicar si el producto retorna al stock, para mantener correctamente las existencias y el historial de operaciones. |
|  | Administrador / Empleado autorizado | Controlar mercadería retirada para ser devuelta al proveedor. | Gestión de devoluciones a proveedores. | **US32: Registro de devolución a proveedor.** Como administrador o empleado autorizado, quiero registrar unidades que salen del inventario para ser devueltas al proveedor, para controlar las salidas no asociadas a ventas. |
|  | Empleado | Registrar rápidamente la mercadería recibida durante el abastecimiento. | Módulo de recepción de mercadería. | **US33: Registro de recepción de mercadería.** Como empleado, quiero registrar una recepción de productos de forma ágil, para actualizar existencias durante el abastecimiento diario. |
|  | Empleado | Revisar las operaciones realizadas durante su jornada. | Historial operativo personal. | **US34: Historial diario de operaciones.** Como empleado, quiero consultar las operaciones que registré durante mi turno, para verificar ventas, ingresos, devoluciones y mermas realizadas. |
|  | Empleado / Administrador | Corregir errores operativos sin perder trazabilidad. | Flujo controlado de correcciones. | **US35: Corrección de operación reciente.** Como empleado, quiero solicitar la corrección de una operación registrada por error, para evitar alterar el inventario sin trazabilidad. |
|  | Empleado | Verificar las operaciones realizadas antes de finalizar su jornada. | Cierre operativo de turno. | **US36: Cierre operativo del turno.** Como empleado, quiero visualizar un resumen de los movimientos realizados antes de terminar mi turno, para comprobar que las operaciones del día quedaron registradas. |
| **Goal N°4:**<br>**Facilitar al administrador la toma de decisiones mediante información operativa clara, centralizada y actualizada.** | Administrador | Conocer rápidamente la situación general de la bodega o minimarket. | Dashboard administrativo. | **US37: Dashboard administrativo.** Como administrador, quiero visualizar los principales indicadores del negocio en un solo panel, para conocer rápidamente el estado del inventario y la operación. |
|  | Administrador | Detectar productos que necesitan reposición antes de quedarse sin stock. | Reporte de stock bajo y crítico. | **US38: Reporte de stock bajo y crítico.** Como administrador, quiero consultar los productos que requieren reposición, para priorizar las compras y evitar quiebres de stock. |
|  | Administrador | Identificar los productos con mayor movimiento. | Reporte de rotación de productos. | **US41: Reporte de productos de alta rotación.** Como administrador, quiero identificar los productos con mayor frecuencia de salida, para priorizar reposición y ubicación física en el negocio. |
|  | Administrador | Identificar los productos que generan la mayor parte de la operación del negocio. | Analítica Pareto 80/20. | **US42: Clasificación Pareto 80/20.** Como administrador, quiero identificar los productos que concentran la mayor parte de las salidas o ventas, para enfocar la gestión en los artículos más relevantes. |
|  | Administrador | Reaccionar rápidamente ante riesgos de stock o vencimiento. | Centro de alertas operativas. | **US43: Alertas operativas.** Como administrador, quiero recibir alertas sobre stock crítico, vencimientos y eventos relevantes, para reaccionar oportunamente ante riesgos operativos. |
|  | Administrador | Analizar la información histórica bajo diferentes períodos y criterios. | Filtros analíticos. | **US44: Filtrado de reportes por período.** Como administrador, quiero filtrar los reportes por fechas y categorías, para analizar la evolución del negocio en intervalos específicos. |
| **Goal N°5:**<br>**Garantizar que cada usuario acceda únicamente a las funciones correspondientes a su responsabilidad dentro del negocio.** | Administrador / Empleado | Acceder de forma segura a BodeGo. | Sistema de autenticación. | **US01: Inicio de sesión.** Como usuario registrado, quiero iniciar sesión con mis credenciales, para acceder de forma segura a BodeGo. |
|  | Administrador / Empleado | Visualizar únicamente las funciones correspondientes a su rol. | Control de acceso basado en roles. | **US02: Acceso según rol.** Como usuario, quiero visualizar una interfaz adaptada a mi rol de Administrador o Empleado, para acceder únicamente a las funciones que me corresponden. |
|  | Administrador | Otorgar accesos individuales al personal. | Gestión de usuarios. | **US03: Registro de empleados.** Como administrador, quiero crear cuentas para los empleados del negocio, para permitirles operar en el sistema con credenciales individuales. |
|  | Administrador | Retirar permisos a personal que ya no debe acceder al sistema. | Activación y desactivación de cuentas. | **US04: Activación y desactivación de usuarios.** Como administrador, quiero activar o desactivar cuentas de empleados, para controlar quién puede acceder a la información del negocio. |
|  | Administrador / Empleado | Mantener actualizados sus datos personales. | Gestión de perfil. | **US05: Edición de perfil.** Como usuario, quiero actualizar mis datos personales y de contacto, para mantener correcta la información asociada a mi cuenta. |
|  | Administrador | Adaptar BodeGo a las características del establecimiento. | Configuración general del negocio. | **US06: Configuración de datos del negocio.** Como administrador, quiero configurar nombre comercial, dirección, contacto y horarios, para mantener centralizada la información operativa del establecimiento. |
|  | Administrador | Definir cuándo un producto debe considerarse bajo o crítico. | Configuración de umbrales. | **US07: Configuración de umbrales de stock.** Como administrador, quiero definir niveles de stock bajo y crítico, para recibir alertas de reposición adaptadas a mi operación. |
|  | Administrador | Adaptar el sistema de vencimientos a la política del establecimiento. | Parámetros de vencimiento. | **US08: Configuración de días de alerta de vencimiento.** Como administrador, quiero definir cuántos días antes del vencimiento debe alertarme el sistema, para adaptar el control de perecibles a las políticas del negocio. |
|  | Administrador / Empleado | Mantener protegidas sus credenciales. | Gestión de contraseña. | **US47: Cambio seguro de contraseña.** Como usuario, quiero cambiar mi contraseña desde la configuración de seguridad, para proteger mi cuenta frente a accesos no autorizados. |
|  | Administrador / Empleado | Recuperar el acceso cuando se olvidan las credenciales. | Recuperación de acceso. | **US48: Recuperación de acceso.** Como usuario, quiero recuperar el acceso cuando olvido mi contraseña, para volver a utilizar mi cuenta sin intervención manual innecesaria. |
|  | Administrador / Empleado | Finalizar de manera segura el uso de la plataforma. | Cierre de sesión. | **US49: Cierre de sesión.** Como usuario, quiero cerrar mi sesión cuando termino de utilizar BodeGo, para evitar que terceros accedan a mi cuenta desde el mismo dispositivo. |
| **Goal N°6:**<br>**Aumentar el control y la trazabilidad de las operaciones realizadas dentro de BodeGo.** | Administrador | Identificar el origen de cualquier variación de inventario. | Historial detallado de movimientos. | **US45: Historial de movimientos de inventario.** Como administrador, quiero consultar todas las entradas y salidas que afectaron un producto, para auditar cómo se originó su stock actual. |
|  | Administrador | Conocer quién realizó cambios relevantes dentro de la plataforma. | Bitácora de auditoría. | **US46: Bitácora de acciones de usuarios.** Como administrador, quiero consultar acciones relevantes realizadas por los usuarios, para supervisar cambios sensibles dentro del sistema. |
|  | Administrador / Empleado | Resolver dudas relacionadas con las funciones del sistema sin interrumpir la operación. | Centro de ayuda operativo. | **US50: Centro de ayuda operativo.** Como administrador o empleado, quiero consultar ayuda sobre las funciones principales del sistema, para resolver dudas frecuentes durante la operación diaria. |
## 3.3. Product Backlog

# Product Backlog — BodeGo

| **# Orden** | **User Story ID** | **Descripción** | **Story Point**<br>**(0 - 8)** |
|---:|:---:|---|---:|
| **1** | **US01** | Como usuario registrado, quiero iniciar sesión con mis credenciales, para acceder de forma segura a BodeGo. | **2** |
| **2** | **US02** | Como usuario, quiero visualizar una interfaz adaptada a mi rol de Administrador o Empleado, para acceder únicamente a las funciones que me corresponden. | **3** |
| **3** | **US03** | Como administrador, quiero crear cuentas para los empleados del negocio, para permitirles operar en el sistema con credenciales individuales. | **3** |
| **4** | **US06** | Como administrador, quiero configurar nombre comercial, dirección, contacto y horarios, para mantener centralizada la información operativa del establecimiento. | **2** |
| **5** | **US09** | Como administrador, quiero crear productos con su información comercial y operativa, para incorporarlos al catálogo interno y controlar sus existencias. | **3** |
| **6** | **US12** | Como administrador, quiero clasificar los productos por categorías, para facilitar su búsqueda y análisis dentro del inventario. | **2** |
| **7** | **US14** | Como empleado, quiero registrar el ingreso de mercadería indicando cantidad y lote, para actualizar el inventario cuando se recibe nueva mercadería. | **5** |
| **8** | **US15** | Como empleado, quiero asociar una fecha de vencimiento a cada lote perecible, para permitir el control preventivo de productos próximos a caducar. | **3** |
| **9** | **US16** | Como administrador o empleado, quiero visualizar las existencias separadas por lote, para conocer qué unidades deben utilizarse primero y mantener trazabilidad. | **3** |
| **10** | **US13** | Como administrador o empleado, quiero buscar productos por nombre, código, categoría o estado de stock, para encontrar rápidamente el artículo que necesito gestionar. | **3** |
| **11** | **US27** | Como empleado, quiero registrar los productos vendidos durante la atención, para descontar automáticamente las unidades del inventario. | **5** |
| **12** | **US29** | Como empleado, quiero recibir una validación de disponibilidad antes de confirmar una salida, para evitar que el inventario quede con cantidades negativas. | **3** |
| **13** | **US21** | Como empleado, quiero registrar unidades perdidas, dañadas o vencidas indicando su motivo, para mantener el stock real y documentar las pérdidas operativas. | **3** |
| **14** | **US19** | Como administrador, quiero visualizar automáticamente los lotes que se aproximan a su vencimiento, para actuar antes de que se conviertan en merma. | **5** |
| **15** | **US20** | Como administrador o empleado, quiero ordenar los lotes perecibles por fecha de vencimiento, para dar salida primero a los productos con menor vida útil. | **3** |
| **16** | **US30** | Como empleado, quiero recibir una sugerencia del lote que debe salir primero, para priorizar la venta de unidades con vencimiento más cercano. | **5** |
| **17** | **US07** | Como administrador, quiero definir niveles de stock bajo y crítico, para recibir alertas de reposición adaptadas a mi operación. | **2** |
| **18** | **US08** | Como administrador, quiero definir cuántos días antes del vencimiento debe alertarme el sistema, para adaptar el control de perecibles a las políticas del negocio. | **2** |
| **19** | **US43** | Como administrador, quiero recibir alertas sobre stock crítico, vencimientos y eventos relevantes, para reaccionar oportunamente ante riesgos operativos. | **5** |
| **20** | **US17** | Como administrador, quiero corregir diferencias de stock indicando cantidad y motivo, para alinear el inventario digital con el conteo físico cuando exista una discrepancia. | **3** |
| **21** | **US18** | Como administrador o empleado, quiero registrar un conteo físico de productos, para comparar las existencias reales con las registradas en BodeGo. | **5** |
| **22** | **US33** | Como empleado, quiero registrar una recepción de productos de forma ágil, para actualizar existencias durante el abastecimiento diario. | **3** |
| **23** | **US34** | Como empleado, quiero consultar las operaciones que registré durante mi turno, para verificar ventas, ingresos, devoluciones y mermas realizadas. | **3** |
| **24** | **US36** | Como empleado, quiero visualizar un resumen de los movimientos realizados antes de terminar mi turno, para comprobar que las operaciones del día quedaron registradas. | **5** |
| **25** | **US22** | Como administrador, quiero definir y consultar categorías de merma, para identificar las principales causas de pérdida del negocio. | **3** |
| **26** | **US37** | Como administrador, quiero visualizar los principales indicadores del negocio en un solo panel, para conocer rápidamente el estado del inventario y la operación. | **5** |
| **27** | **US38** | Como administrador, quiero consultar los productos que requieren reposición, para priorizar las compras y evitar quiebres de stock. | **3** |
| **28** | **US39** | Como administrador, quiero consultar los lotes en riesgo de vencimiento, para planificar ofertas, rotación o retiro oportuno. | **3** |
| **29** | **US40** | Como administrador, quiero analizar las pérdidas por producto, motivo y período, para identificar patrones y reducir costos operativos. | **5** |
| **30** | **US41** | Como administrador, quiero identificar los productos con mayor frecuencia de salida, para priorizar reposición y ubicación física en el negocio. | **5** |
| **31** | **US42** | Como administrador, quiero identificar los productos que concentran la mayor parte de las salidas o ventas, para enfocar la gestión en los artículos más relevantes. | **5** |
| **32** | **US23** | Como administrador, quiero recibir propuestas de oferta para lotes próximos a vencer, para reducir mermas mediante acciones comerciales oportunas. | **8** |
| **33** | **US24** | Como administrador, quiero crear una oferta para un producto o lote específico, para impulsar su rotación cuando lo considere necesario. | **3** |
| **34** | **US25** | Como administrador, quiero aprobar o editar una oferta sugerida por BodeGo, para mantener control sobre las promociones antes de aplicarlas. | **3** |
| **35** | **US28** | Como empleado, quiero visualizar y aplicar ofertas vigentes al registrar una venta, para utilizar correctamente las promociones definidas por el administrador. | **3** |
| **36** | **US26** | Como administrador, quiero hacer que las ofertas terminen cuando vence su vigencia o se agota el stock asociado, para evitar promociones inválidas en la operación diaria. | **3** |
| **37** | **US31** | Como empleado, quiero registrar una devolución e indicar si el producto retorna al stock, para mantener correctamente las existencias y el historial de operaciones. | **3** |
| **38** | **US32** | Como administrador o empleado autorizado, quiero registrar unidades que salen del inventario para ser devueltas al proveedor, para controlar las salidas no asociadas a ventas. | **3** |
| **39** | **US35** | Como empleado, quiero solicitar la corrección de una operación registrada por error, para evitar alterar el inventario sin trazabilidad. | **5** |
| **40** | **US45** | Como administrador, quiero consultar todas las entradas y salidas que afectaron un producto, para auditar cómo se originó su stock actual. | **3** |
| **41** | **US46** | Como administrador, quiero consultar acciones relevantes realizadas por los usuarios, para supervisar cambios sensibles dentro del sistema. | **5** |
| **42** | **US44** | Como administrador, quiero filtrar los reportes por fechas y categorías, para analizar la evolución del negocio en intervalos específicos. | **2** |
| **43** | **US10** | Como administrador, quiero modificar nombre, categoría, unidad, costo o precio de un producto, para mantener actualizada la información utilizada en la operación. | **2** |
| **44** | **US11** | Como administrador, quiero desactivar productos que ya no comercializo, para evitar nuevos movimientos sin perder su historial. | **2** |
| **45** | **US04** | Como administrador, quiero activar o desactivar cuentas de empleados, para controlar quién puede acceder a la información del negocio. | **2** |
| **46** | **US05** | Como usuario, quiero actualizar mis datos personales y de contacto, para mantener correcta la información asociada a mi cuenta. | **1** |
| **47** | **US47** | Como usuario, quiero cambiar mi contraseña desde la configuración de seguridad, para proteger mi cuenta frente a accesos no autorizados. | **2** |
| **48** | **US48** | Como usuario, quiero recuperar el acceso cuando olvido mi contraseña, para volver a utilizar mi cuenta sin intervención manual innecesaria. | **3** |
| **49** | **US49** | Como usuario, quiero cerrar mi sesión cuando termino de utilizar BodeGo, para evitar que terceros accedan a mi cuenta desde el mismo dispositivo. | **1** |
| **50** | **US50** | Como administrador o empleado, quiero consultar ayuda sobre las funciones principales del sistema, para resolver dudas frecuentes durante la operación diaria. | **1** |

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
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
### 4.4.4. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture
### 4.6.1. Design-Level EventStorming
### 4.6.2. Software Architecture Context Diagram
### 4.6.3. Software Architecture Container Diagrams
### 4.6.4. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams

## 4.8. Database Design
### 4.8.1. Database Diagrams

---

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint n
#### 5.2.1.1. Sprint Planning n
#### 5.2.1.2. Aspect Leaders and Collaborators
#### 5.2.1.3. Sprint Backlog n
#### 5.2.1.4. Development Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint

## 5.3. Validation Interviews
### 5.3.1. Diseño de Entrevistas
### 5.3.2. Registro de Entrevistas
### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product

---

# Conclusiones

## Conclusiones y recomendaciones

---

# Video About-the-Team

---

# Bibliografía

---

# Anexos
