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
| Soy un estudiante de 19 años cursando el quinto ciclo de la carrera de Ingeniería de Software. Considero que mi capacidad de tener un enfoque analítico y la eficiencia de desarrollar una solución eficiente. Mis habilidades blandas me permiten empatizar con los usuarios y acompañado de mi resiliencia, compromiso y productividad me permiten realizar propuestas mas estructuradas y optimas. |
| Foto |

| **Johan Alvaro Saravia Hiso (U202421082)** |
| :--- |
| Soy un estudiante de 20 años actualmente en el quinto ciclo de la carrera de Ingeniería de Software. Me considero una persona responsable y comprometida con los demás, especialmente al trabajar en equipo. Tengo facilidad para analizar problemas y buscar soluciones prácticas. Además, procuro escuchar y comprender las ideas de mis compañeros para lograr un buen trabajo en conjunto. |
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
| **Nombres y apellidos:** Lucia <br>**Edad:** 28  <br>**Distrito:** San Martin de Porrez  <br>**Resumen de la entrevista:** Lucía, de 28 años, trabaja como administradora de un minimarket en San Martín de Porres. Ella comenta que el control del inventario se realiza mediante un sistema POS, reportes en Excel y conteos físicos en las góndolas y el almacén. Sin embargo, existen diferencias frecuentes entre el stock registrado en el sistema y la cantidad real de productos, principalmente porque algunos productos dañados o retirados no siempre son registrados correctamente. <br><br>El control de los productos próximos a vencer se realiza de forma manual, revisando las fechas y aplicando el método FEFO, que consiste en colocar adelante los productos que vencen primero. A pesar de esto, suelen tener pequeñas pérdidas semanales por productos vencidos, especialmente yogures, embutidos y pan de molde. Para reducir estas pérdidas, Lucía coloca los productos próximos a vencer en zonas más visibles y aplica descuentos cuando faltan pocos días para su vencimiento. <br><br>Además, la comunicación sobre incidencias del inventario se realiza mediante el sistema, guías de remisión y un grupo de WhatsApp. Lucía considera que sería muy útil contar con una aplicación móvil que permita escanear códigos de barras, revisar el stock, las fechas de vencimiento y los pedidos en camino, además de recibir alertas cuando un producto esté por agotarse o próximo a vencer. <br><br>**URL:** |

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Admin1-Entrevista.png) |
| **Nombres y apellidos:** Jimmy Ruiz <br>**Edad:** 31 <br>**Distrito:** San Juan de Lurigancho <br><br>**Resumen de la entrevista:**  <br>Jimmy, administrador de un pequeño minimarket, comenta que actualmente controla el inventario de forma mixta: registra diariamente los movimientos en un cuaderno y, al finalizar la semana, pasa la información a una plantilla de Excel. Sin embargo, uno de los principales problemas es que durante las horas de mayor venta no siempre se registran correctamente todos los productos, lo que genera diferencias entre el stock registrado y el stock real. <br><br>El control de los productos próximos a vencer se realiza de manera manual. Los trabajadores revisan los estantes y el almacén mientras reponen o limpian los productos. A pesar de estas revisiones, se presentan pérdidas una o dos veces al mes, principalmente en productos como lácteos y panes que pueden quedar poco visibles al fondo de los estantes. <br><br>Cuando un producto está próximo a vencer o tiene poca rotación, lo colocan cerca de la caja o en zonas más visibles para facilitar su venta. También aplican descuentos o promociones para intentar recuperar la inversión antes de que el producto venza. <br><br>Jimmy menciona que las diferencias de stock ocurren casi todas las semanas, especialmente en golosinas, galletas, cereales y gaseosas, debido a errores de registro o consumo del personal. <br><br>Finalmente, considera importante contar con un sistema digital, principalmente desde el celular, que permita recibir alertas automáticas de bajo stock y vencimientos, generar reportes de los productos más vendidos y conectarse con un lector de códigos de barras para registrar fácilmente productos, pérdidas o roturas. <br><br>**URL:** |

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Admin2-Entrevista.png) |
| **Nombres y apellidos:** Silvia Bravo <br>**Edad:** 49  <br>**Distrito:** Independencia <br><br>**Resumen de la entrevista:**  <br>Silvia Bravo, de 49 años, participa en la administración de un minimarket y explica que el control del stock se realiza revisando y contando los productos disponibles. Una de las principales dificultades es que, en ocasiones, la cantidad real no coincide con la cantidad que deberían tener registrada, por lo que deben estar pendientes constantemente del inventario. <br><br>La identificación de productos próximos a vencer se realiza revisando manualmente las fechas de vencimiento. Las pérdidas por vencimiento ocurren con frecuencia, especialmente en productos como yogur, leche y panes, ya que tienen una duración más corta. Para mantenerse comunicados sobre los cambios en el inventario, utilizan principalmente WhatsApp y un registro donde anotan información importante, como las fechas de vencimiento y los productos que ingresan. <br><br>Cuando un producto está próximo a vencer o tiene poca rotación, realizan ofertas, por ejemplo, combinándolo con otro producto que sí tiene mayor salida y reduciendo el precio para facilitar su venta. Los descuentos se aplican principalmente cuando los productos están cerca de vencer. Finalmente, Silvia considera que sería útil contar con un sistema digital que envíe alertas sobre los productos próximos a vencer y que también brinde orientación sobre qué acciones tomar para evitar pérdidas. <br><br>**URL:** |

### Segmento Empleados

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Empleado3-Entrevista.png) |
| **Nombres y apellidos:** Joseph <br>**Edad:** 23 <br>**Distrito:** Puente Piedra <br><br>**Resumen:**  <br>Joseph trabaja en un minimarket realizando tareas de atención al cliente, registro de ventas, reposición de productos y control de almacén. Actualmente, las entradas y salidas de productos se registran manualmente en un cuaderno, lo que puede generar errores o confusiones, especialmente en las horas de mayor movimiento o cuando llega mercadería mientras se atiende a los clientes. <br><br>Para conocer el stock disponible, deben revisar y contar físicamente los productos en los estantes, lo cual puede resultar lento y complicado. La revisión de fechas de vencimiento también se realiza manualmente, generalmente cuando llega nueva mercadería. Si encuentran un producto vencido, lo retiran del estante y se lo comunican al administrador para evitar que llegue al cliente. <br><br>Joseph menciona que los errores en el inventario suelen ocurrir principalmente durante las horas de mayor venta, cuando hay más presión de trabajo. Los cambios de stock o problemas con los productos se comunican de forma verbal y mediante el cuaderno de registro. Además, considera que las tareas más tediosas son contar los productos y revisar uno por uno las fechas de vencimiento. <br><br>Finalmente, señala que sería útil contar con una herramienta digital sencilla que permita registrar entradas y salidas, consultar el stock disponible y facilitar el control del inventario, reduciendo así el tiempo y los errores del proceso manual. <br><br>**URL:** |

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Empleado2-Entrevista.png) |
| **Nombres y apellidos:*Andres Marzano*  <br>**Edad:** 20  <br>**Distrito:** San Juan de Lurigancho <br><br>**Resumen:**  <br>Andrés Marzano, de 20 años, tiene experiencia trabajando en atención al cliente y almacén. Explica que las entradas de productos se registraban después de verificar que la mercadería recibida coincidiera con la información del documento de entrega, para luego ingresarla en el sistema. Las salidas, por su parte, se registraban mediante boletas electrónicas. <br><br>Uno de los principales problemas era conocer con precisión la cantidad disponible de productos, especialmente cuando se trataba de artículos pequeños, ya que podían cometerse errores al contarlos. Esta tarea se volvía más complicada cuando, al mismo tiempo, tenían que atender a los clientes. <br><br>Para controlar los productos próximos a vencer, colocaban adelante los que tenían menor tiempo de vida útil y dejaban al fondo los productos recién llegados. Además, revisaban las fechas de vencimiento en los turnos de día y noche. Cuando un producto estaba cerca de vencer, trataban de darle prioridad a su venta; si ya quedaban pocos días y no se lograba vender, se registraba como merma para calcular las pérdidas. <br><br>Finalmente, Andrés señala que los mayores errores en el control del inventario se presentaban principalmente durante las mañanas, cuando había mayor cantidad de clientes y debían dividir su atención entre las ventas y las tareas de inventario. <br><br>**URL:** |

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Empleado1-Entrevista.png) |
| **Nombres y apellidos:** Pablo Moreno <br>**Edad:** 20  <br>**Distrito:** Callao <br><br>**Resumen:**  <br>Pablo Moreno, empleado de un minimarket, explica que las entradas y salidas de productos se registran principalmente de forma manual y, en algunos casos, mediante Excel. Este proceso no siempre se actualiza de inmediato, por lo que a veces existen diferencias entre el stock registrado y la cantidad real disponible, especialmente en productos de alta rotación o durante las horas de mayor atención. La revisión de productos próximos a vencer también se realiza manualmente, verificando las fechas directamente en los productos. Cuando un producto está vencido se retira de la venta, mientras que los productos próximos a vencer pueden colocarse en zonas más visibles o venderse con descuento. Pablo también menciona que los errores suelen ocurrir cuando hay muchos clientes o cuando llega bastante mercadería al mismo tiempo. Los problemas de stock se comunican personalmente o por WhatsApp, aunque la información puede perderse entre tantos mensajes. Finalmente, considera que sería útil contar con un sistema digital accesible desde el celular o computadora que permita registrar entradas y salidas, actualizar el stock rápidamente y recibir alertas sobre productos próximos a vencer. <br><br>**URL:** |



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

## Administrador

![User Persona Administrador](Recursos/images/UserPersona-Administrador.jpg)

## Empleado

![User Persona Empleado](Recursos/images/UserPersona-Empleado.jpg)

### 2.3.2. User Task Matrix

## Administradores

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

## Empleados

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

Épicas

| **EPIC-01** | **Gestión de Presencia Digital y Landing Page** |
|-------------|--------------------------------------------------|
| **Descripción:** | **Como** negocio interesado en optimizar su operación, **quiero** conocer la propuesta de valor, funcionalidades y beneficios de BodeGo mediante una landing page clara y profesional **para** comprender cómo la plataforma ayuda a gestionar inventarios, reducir mermas y mejorar los procesos internos del minimarket. |

<br>

| **EPIC-02** | **Aplicación Web y Gestión Operativa** |
|-------------|-----------------------------------------|
| **Descripción:** | **Como** administrador o empleado, **quiero** contar con una aplicación web intuitiva con módulos organizados según mis necesidades operativas **para** gestionar inventario, productos y actividades diarias de manera rápida, sencilla y eficiente. |

<br>

| **EPIC-03** | **Control de Inventario y Productos** |
|-------------|----------------------------------------|
| **Descripción:** | **Como** administrador o empleado, **quiero** registrar, consultar y actualizar productos, cantidades, lotes y movimientos de inventario **para** mantener un control preciso del stock disponible y reducir diferencias entre el inventario físico y digital. |

<br>

| **EPIC-04** | **Gestión de Mermas, Alertas y Reportes Inteligentes** |
|-------------|---------------------------------------------------------|
| **Descripción:** | **Como** administrador, **quiero** visualizar alertas, indicadores y reportes sobre productos próximos a vencer, mermas y rotación de inventario **para** tomar decisiones oportunas que permitan reducir pérdidas y mejorar la rentabilidad del negocio. |

<br>

| **EPIC-05** | **Automatización de Procesos Operativos** |
|-------------|--------------------------------------------|
| **Descripción:** | **Como** administrador o empleado, **quiero** disponer de funcionalidades automatizadas para registrar operaciones, controlar vencimientos y gestionar acciones sobre productos críticos **para** agilizar las tareas diarias y mejorar la eficiencia del establecimiento. |

<br>

| **EPIC-06** | **Gestión de Usuarios y Seguridad del Sistema** |
|-------------|-------------------------------------------------|
| **Descripción:** | **Como** administrador o empleado, **quiero** contar con un sistema seguro de acceso, roles y permisos **para** proteger la información del negocio y garantizar que cada usuario pueda utilizar únicamente las funcionalidades correspondientes a su responsabilidad. |

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

### 4.4.2. Web Applications Wireflow Diagrams
![Wireflow 0](Recursos/images/Wireflow_App.png)

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
![Components-API](Recursos/images/BodeGo-diagramaClases.png)
## 4.8. Database Design
Se presenta el diseño de la base de datos relacional que permitirá graficar la información para los objetos de cada Bounded Context identificados en la aplicación BodeGo.

### 4.8.1. Database Diagrams
El siguiente diagrama de base de datos Entity-Relationship contiene las tablas, columnas y tipos de datos que establecen las relaciones entre las entidades del sistema.
![Diagrama / Diseño 1](Recursos/images/d1.png)

---

![Diagrama / Diseño 2](Recursos/images/d2.png)

---

![Diagrama / Diseño 3](Recursos/images/d3.png)

---

![Diagrama / Diseño 4](Recursos/images/d4.png)

---

![Diagrama / Diseño 5](Recursos/images/d5.png)

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
Para el desarrollo de BodeGo se establecerán un conjunto de herramientas que permitan mantener la consistencia del proyecto durante su ciclo de vida. Estas configuraciones permitirán que los integrantes del equipo trabajen bajo una misma estructura para el control de versiones, configuración del entorno de desarrollo y posterior despliegue de la aplicación.

### 5.1.1. Software Development Environment Configuration
## . Project Management

- **Discord:** Una herramienta de comunicación y coordinación del equipo. Permite organizar conversaciones por canales, realizar reuniones de voz, compartir avances, resolver dudas y coordinar las actividades relacionadas con el desarrollo de BodeGo.

![Imagen de reunión](Recursos/images/imagenReunion.png)

## . Requirement Management

- **Miro:** Se utilizará como herramienta colaborativa para la gestión y análisis de requisitos de BodeGo. Permitirá organizar visualmente información obtenida durante la investigación, como User Personas, Empathy Maps, User Journey Maps e Impact Mapping.

- **UXPressia:** Se utilizará para elaborar y documentar artefactos relacionados con la experiencia de usuario, como User Personas y User Journey Maps, permitiendo representar las características, necesidades, objetivos y experiencias de los segmentos de usuarios de BodeGo.

- **Structurizr:** Se utilizará para modelar y documentar la arquitectura de software de BodeGo mediante diagramas basados en el modelo C4. Permitirá representar la estructura general del sistema, sus principales contenedores, componentes y relaciones.

## . Product UX/UI Design

- **Figma:** Una herramienta de colaboración que facilita el desarrollo conjunto de wireframes y mockups.

- **LucidChart:** Una herramienta colaborativa que posibilita la creación conjunta de wireframes flow y mockups flow.

## . Software Development

- **HTML5:** Es un lenguaje de etiquetado utilizado para crear la estructura de una página web. Se empleará para incluir componentes como texto, imágenes, enlaces, botones y videos.

- **CSS:** Es un lenguaje de diseño gráfico utilizado para dar formato y estilo a la presentación de los documentos HTML.

- **JavaScript:** Es un lenguaje de programación dinámico orientado a objetos que se utilizará para implementar funcionalidades e interactividad en la aplicación web.

- **WebStorm:** Es un entorno de desarrollo integrado (IDE) que se empleará para trabajar con JavaScript y desarrollar la aplicación.

## . Software Testing

- **Lenguaje Gherkin:** Es un Lenguaje Específico de Dominio (DSL) diseñado para describir el comportamiento esperado del sistema mediante escenarios comprensibles tanto para desarrolladores como para otros integrantes del equipo.

## . Software Documentation

- **GitHub:** Es una plataforma utilizada para el alojamiento y control de versiones del código fuente de un proyecto. Facilita el trabajo colaborativo entre los integrantes del equipo y permite mantener un historial de los cambios realizados.

## . Software Deployment

- **GitHub Pages:** Es una plataforma que permite realizar despliegues de aplicaciones web directamente desde un repositorio de GitHub.


### 5.1.2. Source Code Management

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

Para mantener un historial de cambios claro y comprensible, los mensajes de los commits del proyecto BodeGo seguirán la especificación **Conventional Commits**.

Esta convención permitirá identificar rápidamente el propósito de cada modificación realizada por los integrantes del equipo.

La estructura general será: git commit -m <type>[optional scope]: <title>“ -m “<description” 

### Tipos de Conventional Commits

| Tipo | Uso |
|---|---|
| `feat` | Incorporación de una nueva funcionalidad. |
| `fix` | Corrección de un error. |
| `docs` | Cambios en documentación. |
| `style` | Cambios de formato que no modifican el funcionamiento. |
| `refactor` | Reestructuración del código sin agregar funcionalidades ni corregir errores. |
| `test` | Adición o modificación de pruebas. |
| `chore` | Tareas de mantenimiento o configuración. |
| `perf` | Mejoras relacionadas con el rendimiento. |

### 5.1.3. Source Code Style Guide & Conventions
Como norma general, todo el código desarrollado para **BodeGo** deberá utilizar nombres en inglés. Esto incluye variables, funciones, métodos, clases, archivos, atributos y demás elementos utilizados durante el desarrollo.

La finalidad de estas reglas es mantener un código ordenado y fácil de entender para todos los integrantes del equipo.

---

## HTML

### Use Lowercase Element Names

Los elementos HTML se escribirán en minúsculas.

```html
<section>
    <h2>Inventory</h2>
    <p>Available products</p>
</section>
```

### Close All HTML Elements

Todos los elementos HTML que necesiten una etiqueta de cierre deberán cerrarse correctamente.

```html
<section>
    <h2>Inventory</h2>
    <p>Available products</p>
</section>
```

### Use Lowercase Attribute Names

Los atributos HTML también se escribirán en minúsculas.

```html
<a href="/inventory">View inventory</a>
```

### Use Alternative Text for Images

Las imágenes utilizadas en BodeGo deberán incluir el atributo alt para indicar brevemente su contenido.

```html
<img
    src="assets/bodego-logo.png"
    alt="BodeGo logo">
```

### Use Semantic HTML Elements

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

### Spaces and Equal Signs

No se utilizarán espacios innecesarios alrededor del signo igual en los atributos.

Correcto:

```html
<link rel="stylesheet" href="styles.css">
```

Incorrecto:

```html
<link rel = "stylesheet" href = "styles.css">
```


## CSS

### ID and Class Naming

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

### ID and Class Name Style

Para los nombres de clases e identificadores CSS se utilizará kebab-case.

```css
.product-card {
}

.inventory-table {
}

.stock-alert {
}
```

### Shorthand Properties

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

### Declaration Order

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

## JavaScript

### Use Expanded Syntax

El código JavaScript deberá escribirse de manera clara y ordenada, colocando cada instrucción en una línea diferente cuando sea necesario.

```javascript
function calculateAvailableStock() {
    console.log("Calculating available stock");
}
```
### Variable Naming

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

### Declaring Variables

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

### Function Naming

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

### Constants

Las constantes globales podrán utilizar UPPER_SNAKE_CASE.

Ejemplos:

```javascript
const MAX_LOGIN_ATTEMPTS = 5;
const DEFAULT_STOCK_THRESHOLD = 10;
```

## C#

### PascalCase

Las clases, métodos y propiedades utilizarán PascalCase.

```csharp
public class ProductService
{
}
```

```csharp
public class InventoryService
{
}
```

```csharp
public class BatchService
{
}
```

### camelCase

Las variables locales y parámetros utilizarán camelCase.

```csharp
int productId;
string productName;
int availableStock;
DateTime expirationDate;
```

### Interface Naming

Las interfaces utilizarán PascalCase y comenzarán con la letra I.

```csharp
public interface IProductService
{
}
```

```csharp
public interface IInventoryService
{
}
```

```csharp
public interface IWastageService
{
}
```

### Clear Comments

Los comentarios se utilizarán cuando ayuden a entender alguna regla de negocio o una parte del código que no sea evidente.
Los comentarios deberán escribirse en inglés.

```csharp
// Checks whether the batch is close to its expiration date.
public bool IsNearExpiration(DateTime expirationDate)
{
    return expirationDate <= DateTime.Today.AddDays(7);
}
```

### Single Responsibility

Cada clase deberá encargarse principalmente de una responsabilidad.

- ProductService se encargará de las operaciones relacionadas con productos.
- InventoryService se encargará de las operaciones relacionadas con inventario.
- BatchService se encargará de la gestión de lotes.
- WastageService se encargará del registro y gestión de mermas.

## Gherkin

Los escenarios y criterios de aceptación de BodeGo deberán seguir una estructura uniforme y utilizar nombres en inglés.

### Descriptive and Concise Titles for Scenarios

Los escenarios deberán tener títulos claros que permitan entender rápidamente qué comportamiento se está evaluando.

```gherkin
Feature: User authentication

Scenario: Successful login
    Given the user has an active account
    When the user enters valid credentials
    Then the system should grant access according to the user role
```

### Follow the Given-When-Then Structure Consistently

Los escenarios deberán utilizar la estructura Given, When y Then.

- Given: representa la condición inicial.
- When: representa la acción realizada.
- Then: representa el resultado esperado.


### Focus on Business-Readable Language

Los escenarios deberán utilizar un lenguaje relacionado con las actividades del minimarket y evitar detalles técnicos de programación.

```gherkin
Scenario: Register damaged product as wastage

    Given the employee finds a damaged product
    When the employee registers the product as wastage
    Then the stock should be updated
    And the wastage should be recorded
```
### Add Comments When Necessary

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

El print Planning permitió organizar las actividades que serían desarrolladas durante el Sprint 1.
En esta reunión se definió como objetivo principal implementar la Landing Page de BodeGo a partir de los diseños y wireframes
| Sprint # | Sprint 1 |
| --- | --- |
| **Sprint Planning Background** | |
| **Date** | 2026-09-13 |
| **Time** | 8:00 pm |
| **Location** | Discord - Reunión virtual |
| **Prepared By** | Mateo Caldas Bravo |
| **Attendees (to planning meeting)** | Dany Yohel, Mateo, Yorch, Johan, Guior |
| **Sprint 1 Goal** | Implementar una primera versión funcional y responsive de la Landing Page de BodeGo que permita comunicar la propuesta de valor, las principales funcionalidades y los beneficios de la plataforma para los minimarkets. |
| **Sprint 1 Velocity** | 23 Story Points |
| **Sum of Story Points** | 23 Story Points |

#### 5.2.1.2. Aspect Leaders and Collaborators

Durante el Sprint 1 se identificaron los principales aspectos de trabajo necesarios para implementar la Landing Page de BodeGo.

| Team Member | GitHub Username | Landing Page Structure | UI & Styling | Content | Documentation | GitHub / SCM |
| --- | --- | --- | --- | --- | --- | --- |
| Dany Chavez | Danysss-cmd | L | C | C | C | C |
| Mateo Caldas| `[username]` | C | C | L | C | C |
| Yorch Blanco | `[username]` | C | C | C | C | L |
| Johan Saravia | `[username]` | C | C | C | L | C |
| Guior | `[username]` | C | L | C | C | C |

#### 5.2.1.3. Sprint Backlog 1
Durante el Sprint 1, las actividades estuvieron orientadas principalmente a implementar la primera versión de la Landing Page de BodeGo.
La implementación comprende la estructura general de navegación y las diferentes secciones que presentan las características y beneficios del producto.

| User Story ID | Story Title | Task ID | Task Title | Description | Estimation (Hours) | Assigned To | Status |
| --- | --- | --- | --- | --- | ---: | --- | --- |
| — | Landing Page | TSK001 | Create Landing Page structure | Crear la estructura principal y los archivos HTML/CSS de la Landing Page. | 2 | Dany | Hecho |
| — | Landing Page | TSK002 | Implement navigation bar | Implementar el logo, enlaces de navegación y botón de registro. | 2 | Dany | Hecho |
| — | Landing Page | TSK003 | Implement hero section | Implementar título, subtítulo, descripción, imagen principal y CTA. | 3 | Dany | Hecho |
| — | Landing Page | TSK004 | Implement value proposition section | Implementar las tarjetas de Control de Lotes, Alertas y Doble Rol. | 4 | Mateo | Hecho |
| — | Landing Page | TSK005 | Implement solutions section | Implementar las tarjetas de Gestión Centralizada, Reportes Analíticos, Ofertas Estratégicas y Auditoría y Seguridad. | 3 | Yorch | Hecho |
| — | Landing Page | TSK006 | Implement impact section | Implementar los beneficios de Reducción de Mermas y Ahorro de Tiempo. | 2 | Yorch | Hecho |
| — | Landing Page | TSK007 | Implement contact section | Implementar el formulario de contacto para potenciales usuarios de BodeGo. | 3 | Johan | Hecho |
| — | Landing Page | TSK008 | Implement footer | Implementar el logo, enlaces, información de contacto y datos de BodeGo en el footer. | 2 | Johan | Hecho |
| — | Landing Page | TSK009 | Implement responsive design | Adaptar la Landing Page para computadoras, tablets y dispositivos móviles, además de realizar ajustes generales de estilos. | 5 | Guior | Hecho |

#### 5.2.1.4. Development Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
Se ha omitido la sección de la aplicación web debido a que solo se ha desarrollado la Landing Page. Se ofrecerá más información sobre la aplicación en
una etapa posterior del desarrollo.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review
Se ha omitido la sección de la aplicación web debido a que solo se ha desarrollado la Landing Page. Se ofrecerá más información sobre la aplicación en
una etapa posterior del desarrollo.

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
